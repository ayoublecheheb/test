# ⚙️ Guide d'installation Notion

Temps nécessaire : environ 20 minutes, une seule fois.

## 1. Importer

1. Dans Notion, crée une page vide **« 🩺 3e année — S1 »**.
2. Dans la barre latérale, ouvre **Paramètres → Importer → « Texte et Markdown »**, puis choisis `notion_S1_import.zip`. Si le zip est refusé, importe les fichiers **un par un** : les `.md` deviennent des pages, les `.csv` deviennent des bases de données (« CSV »).
3. Déplace toutes les pages importées dans **« 🩺 3e année — S1 »**.
4. Dans la page 🏠 *Tableau de bord S1*, remplace la liste « Bases de données et pages » par des **liens** (`@` + nom de la base) ou par des **vues liées** (`/vue liée`).

## 2. Corriger les types de propriétés

Notion importe tout en texte. Clique sur le nom de chaque colonne → **Type de propriété**.

### 🫀 UEI1 Cardio et 🧠 UEI2 — Contrôle & progression

| Propriété | Type | Options / remarque |
|---|---|---|
| Cours | Titre | — |
| Matière | Sélection | Sémiologie · Physiopathologie · Radiologie · Biochimie · Psychologie |
| Thème intégré | Sélection | — |
| Semaine C1 | Sélection | S1 … S8 |
| Priorité | Sélection | 🔴 P1 · 🟠 P2 · 🟡 P3 · ⚪ P4 |
| Tombabilité (QCM 2019-25) | Nombre | vide = non indiquée dans les sources |
| Part UEI1 (%) | Nombre | — |
| Pages | Nombre | à remplir (volume réel) |
| Difficulté | Sélection | 1 · 2 · 3 |
| État | Sélection | ⬜ Non commencé · 🟡 Vu (non étudié) · 🔵 Couche 1 · 🟢 Couche 2 · 🟣 Couche 3 · ✅ Couche 4 · 🔥 À revoir |
| Vu à l'hôpital, C1, C2, C3, C4 | Case à cocher | « Yes/No » devient coché/décoché |
| Flashcards | Sélection | À créer · Créées · Complétées · En révision |
| QCM (%) | Nombre | — |
| Maîtrise | Sélection | 1 · fragile · 2 · correct · 3 · solide |
| Date C1 (date réelle), Prochaine révision, C1 prévue, C2 prévue, C3 prévue (recouchage), C4 prévue (recouchage) | Date | Les dates « prévue » viennent du plan ; « Date C1 » = le jour où tu l'as vraiment faite |

### 🦠 Modules S1

Mêmes types que ci-dessus (dont **C1 prévue → C4 prévue** en Date), plus : **Module** (Sélection), **Partie** (Sélection), **Thème** (Sélection), **Ordre thématique** (Nombre), **Semaine prévue** (Sélection), **Vu en amphi** (Case à cocher).

### 📅 Tableau de bord hebdomadaire

**Semaine** (Titre), **Phase** et **Mode** (Sélection), **Unité — nb nouveaux**, **Modules — nb nouveaux**, **Nouveaux faits**, **C2 faites**, **C3 faites**, **Flashcards (jours /7)**, **QCM moyen (%)**, **🔥 ouverts** (Nombre), **Stage cette semaine** et **Repos pris** (Case à cocher), **Énergie (1-3)** (Sélection).

### 🔁 Recouchage J-14 et 🧩 Parcours thématique

**Date** (Date), **Passage** (Sélection), **Fait** (Case à cocher) · **Statut** (Sélection : ⬜ À faire · 🔵 En cours · ✅ Fait).

## 3. Ajouter les formules (propriété « Formule »)

### Dans 🫀 UEI1 et 🦠 Modules — `Progression`

```
(if(prop("C1"),1,0) + if(prop("C2"),1,0) + if(prop("C3"),1,0) + if(prop("C4"),1,0)) / 4
```
Affichage : **Barre** · format **Pourcentage**.

### Dans 🫀 UEI1 — `Score priorité`

```
ifs(prop("Priorité") == "P1", 4, prop("Priorité") == "P2", 3, prop("Priorité") == "P3", 2, 1)
+ if(prop("État") == "🔥 À revoir", 2, 0)
+ if(prop("Difficulté") == "3", 1, 0)
+ if(prop("Maîtrise") == "1 · fragile", 1, 0)
+ if(prop("C1") and not prop("C3") and dateBetween(parseDate("2026-12-10"), now(), "days") < 21, 1, 0)
```
Plus le score est haut, plus le cours passe tôt. (Si tu renommes les options P1–P4 avec des emojis, adapte le texte entre guillemets.)

### Dans 🫀 UEI1 — `Révision conseillée` (rappel des couches)

Pendant le semestre : C1 + C2. Les C3 et C4 se font au recouchage.

```
if(empty(prop("Date C1")), "C1 prévue le " + formatDate(prop("C1 prévue"), "DD/MM"),
 if(not prop("C2"), "C2 le " + formatDate(dateAdd(prop("Date C1"), ifs(prop("Priorité") == "P1", 1, prop("Priorité") == "P2", 2, prop("Priorité") == "P3", 3, 5), "days"), "DD/MM"),
 if(not prop("C3"), "C3 au recouchage : " + formatDate(prop("C3 prévue (recouchage)"), "DD/MM"),
 if(not prop("C4"), "C4 au recouchage : " + formatDate(prop("C4 prévue (recouchage)"), "DD/MM"), "✅ Couches terminées"))))
```
Recopie la date de C2 proposée dans **Prochaine révision** si ton C1 a glissé.

### Dans 🦠 Modules — `Révision conseillée`

```
if(empty(prop("Date C1")), "C1 prévue le " + formatDate(prop("C1 prévue"), "DD/MM"),
 if(not prop("C2"), "C2 le " + formatDate(dateAdd(prop("Date C1"), if(prop("Module") == "Parasitologie", 2, 3), "days"), "DD/MM"),
 if(not prop("C3"), "C3 le " + formatDate(prop("C3 prévue"), "DD/MM"),
 if(not prop("C4"), "C4 le " + formatDate(prop("C4 prévue"), "DD/MM"), "✅ Couches terminées"))))
```

### Dans 🫀 UEI1 — `J avant examen`

```
dateBetween(parseDate("2026-12-10"), now(), "days")
```

### Dans 📅 Tableau de bord hebdomadaire — `Taux de réalisation`

```
if(toNumber(prop("Unité — nb nouveaux")) + toNumber(prop("Modules — nb nouveaux")) > 0,
 round(prop("Nouveaux faits") / (toNumber(prop("Unité — nb nouveaux")) + toNumber(prop("Modules — nb nouveaux"))) * 100), 0)
```

### Dans 📅 Tableau de bord hebdomadaire — `Alertes`

```
(if(not prop("Repos pris"), "⚠️ Repos non pris · ", "")) +
(if(prop("Flashcards (jours /7)") < 5, "⚠️ Flashcards irrégulières · ", "")) +
(if(prop("🔥 ouverts") >= 3, "🔥 Trop de cours à revoir · ", "")) +
(if(prop("QCM moyen (%)") < 60, "⚠️ QCM < 60 %", ""))
```

## 4. Créer les vues

### 🫀 UEI1 Cardio

| Vue | Type | Réglages |
|---|---|---|
| 🎯 **Contrôle central** | Tableau | Tri : Score priorité ↓ · Colonnes : Cours, Matière, Priorité, Tombabilité, Pages, Difficulté, État, Progression, Prochaine révision |
| 📈 **Progression** | Tableau | Groupé par **Matière** · Colonnes : État, C1–C4, Flashcards, QCM, Maîtrise |
| 🧱 **Kanban des couches** | Tableau Kanban | Groupé par **État** |
| 📅 **Révisions** | Calendrier | Par **Prochaine révision** |
| 🗓 **Par semaine** | Tableau Kanban | Groupé par **Semaine C1** |
| 🗓 **Plan C1 / C2 / C3 / C4** | Calendrier | 4 vues : par **C1 prévue**, **C2 prévue**, **C3 prévue (recouchage)**, **C4 prévue (recouchage)** |
| 🔥 **À revoir** | Tableau | Filtre : État = 🔥 À revoir **ou** Maîtrise = 1 · fragile |
| 🧩 **Par thème** | Tableau | Groupé par **Thème intégré** |

### 🦠 Modules

| Vue | Type | Réglages |
|---|---|---|
| 🧩 **Parcours thématique** | Tableau | Groupé par **Thème** · Tri : Ordre thématique ↑ |
| 🦠 / 🪱 / 💊 **Par module** | Tableau | Groupé par **Module** (ou 3 vues filtrées) |
| 🗓 **Cette semaine** | Tableau | Filtre : Semaine prévue = semaine en cours |
| 🧱 **Kanban des couches** | Tableau Kanban | Groupé par **État** |
| 📅 **Révisions** | Calendrier | Par **Prochaine révision** |
| 🗓 **Plan C1 / C2 / C3 / C4** | Calendrier | 4 vues : par **C1 prévue**, **C2 prévue**, **C3 prévue**, **C4 prévue** |

### 📅 Tableau de bord hebdomadaire

Vue **Tableau** (toutes les semaines) + vue **Galerie** (carte = Semaine, Objectif principal, Taux de réalisation, Alertes).

## 5. Bonus (facultatif)

- **Relation** entre 📅 *Semaines* et 🫀 *UEI1* / 🦠 *Modules* (propriété Relation) → un **Rollup** « % C1 faites » par semaine.
- Dans chaque tracker de module : insère une **vue liée** de la base 🦠 *Modules* filtrée sur ce module.
- **Modèle de page** pour un cours : sections *Plan en 1 page · Mécanismes · Pièges · Carnet d'erreurs · Liens avec les autres matières*.
