# Système de révision — 3e année de médecine (2026-2027)

> **Principe directeur : QUALITY > QUANTITY.**
> Hôpital = renforcement · Étude personnelle = avance · Vu ≠ étudié ≠ mémorisé ≠ maîtrisé.

Document construit le **jeudi 01/10/2026**. Le programme démarre **demain, vendredi 02/10/2026**.

> **Version 2 (01/10/2026)** · **Recouchage de l'unité sur 14 jours** (J-14 = jeu 26/11 → mer 09/12) · **Arrêt total des modules à partir du milieu de S7** (dernières séances sam 14/11 et dim 15/11 ; stop du lun 16/11 à l'examen du 10/12) · **Parcours thématique des modules** (Partie 6) · **Pack d'import Notion** (dossier `notion/`).

> **Version 3 (07/10/2026) — reprise après maladie et chirurgie.** Départ réel **mercredi 07/10** en mode convalescence (2 jours très légers), **S2 à ~75 %** sans modules, **modules démarrés en S3**. Les 14 jours de recouchage (26/11 → 09/12) et l'arrêt des modules à mi-S7 sont **conservés** : le retard est absorbé par S5 et S8 (cours légers regroupés) et, en dernier recours, par une réserve de 2 jours (recouchage à J-12).

**Sources analysées (5 documents) :**

| Code | Document | Ce qu'il apporte |
|---|---|---|
| [PROG] | *Programme de l'année 2026-2027* (Faculté, daté du 20/09/2026) | Calendrier officiel des unités, révisions, examens, jours fériés, emplois du temps des amphis et de la sémiologie |
| [CARDIO] | *Suivi de UEI1 et modules de S1* (fiche Medjelfa) | Liste exacte des 50 cours de l'UEI 1, **chiffres de tombabilité Medspace 2019-2025**, système de couches C1–C5 + Q |
| [MICRO] | *Suivi de cours microbiologie* (EduSaviours) | 29 cours (10 virologie + 19 bactériologie), 19 semaines |
| [PARA] | *Suivi de cours parasitologie* (EduSaviours) | 25 cours, 19 semaines |
| [PHARMA] | *Suivi de cours pharmacologie* (EduSaviours) | 19 cours, 19 semaines |

**Ce que les sources ne contiennent PAS** (donc je ne l'invente pas) : nombre de pages des cours, difficulté des cours (sauf la Parasitologie, que tu m'as déclarée difficile), tombabilité des modules (Micro/Para/Pharma), dates des stages, dates de vacances, ta section (A/B/C/D), ton service de sémiologie, l'ordre réel de présentation des cours à l'hôpital, la liste des cours de l'UEI 2.

**Fichiers associés — dossier `notion/` (pack d'import Notion, aussi en `notion_S1_import.zip`) :**
- `00 🏠 Tableau de bord S1.md` — page d'accueil (compte à rebours, priorités, routines)
- `01 🫀 UEI1 …csv` — base **Contrôle & progression** des 50 cours de l'UEI 1
- `02 🧠 UEI2 …csv` — même base pour l'UEI 2 (modèle : liste des cours non fournie)
- `03 🦠 Modules S1 …csv` — base **Contrôle & progression** des 73 cours de modules
- `04 🧩 Parcours thématique des modules.csv` — les 21 thèmes
- `05 📅 Tableau de bord hebdomadaire.csv` — S1 → examens de février
- `06 🔁 Recouchage J-14 UEI1.csv` — les 14 jours de recouchage
- `10/11/12 Tracker Microbiologie / Parasitologie / Pharmacologie.md` — objectifs, règles, parcours, couches, fin de semestre
- `99 ⚙️ Guide d'installation Notion.md` — import, types de propriétés, formules, vues

---

## PARTIE 1 — DIAGNOSTIC ACADÉMIQUE

### 1.1 Où tu en es exactement

| Élément | Situation au 01/10/2026 | Source |
|---|---|---|
| Unité en cours | **UEI 1 : Cardio-respiratoire** | [PROG] |
| Enseignement UEI 1 | du dim 27/09/2026 au jeu 03/12/2026 → **la semaine 1 d'enseignement est terminée** | [PROG] |
| Révision officielle | du 03/12 au 09/12/2026 | [PROG] |
| **Examen UEI 1** | **jeudi 10/12/2026** → **J-64** au mercredi 07/10 (reprise) | [PROG] |
| Cours vus à l'hôpital / en amphi | **1 seul** : SEM01 Introduction à la sémiologie (cours d'introduction) | toi (confirmé le 07/10) |
| Cours réellement étudiés | **0** | toi |
| **Santé** | Maladie + chirurgie jusqu'au 07/10 → **reprise progressive à partir du mer 07/10** ; cours manqués pendant l'absence = ⬜ *non vus* | toi |
| Modules en parallèle | Microbiologie, Parasitologie, Pharmacologie (examens en février 2027) | [PROG] |

**Statut de départ (confirmé le 07/10) :** tu pars de **zéro dans toutes les matières et tous les modules**. Seul **SEM01 Introduction + anamnèse** a été vu en amphi → 🟡 *Vu mais non étudié*. Tous les autres cours, y compris ceux présentés pendant ton absence, sont ⬜ *non commencés / non vus*.

### 1.2 ⚠️ Incohérences détectées dans les sources

1. La fiche [CARDIO] indique *« Date de l'examen UEI 1 : Jeudi 11/12/2025 »* → c'est la date de **l'an dernier** (fiche réutilisée). **Date retenue : jeudi 10/12/2026** (programme officiel [PROG]).
2. La fiche dit « Radiologie », le programme dit « Imagerie » → c'est la même matière.
3. Les chiffres de tombabilité de [CARDIO] **n'ont pas d'unité** (pas de « % ») et sont accompagnés de « Toutes les statistiques proviennent du site Medspace (2019-2025) ». Je les interprète comme **le nombre de QCM recensés par cours sur 2019-2025**. Je les affiche **tels quels** et je calcule à partir d'eux la **part de chaque cours dans l'UEI** (sur un total de **894**). Le pourcentage est donc **un calcul, pas une donnée de la source**.
4. Cinq paires de cours de Sémiologie partagent **un seul chiffre** (ex. « 43 » pour Sémiologie pondérale + Fièvre). La répartition entre les deux cours est **inconnue**.
5. Trois cours de Sémiologie n'ont **aucun chiffre** : SEM01 (Introduction + anamnèse), SEM04 (Topographie du thorax), SEM11 (Hémodynamique intracardiaque) → « Tombabilité : non indiquée dans les sources ».
6. [PROG] (hors S1) : les dates d'UEI 3/UEI 4 diffèrent légèrement entre le tableau principal et le tableau des jours fériés (ex. 21/02 vs 22/02). Sans impact sur le S1.

### 1.3 Les 4 constats qui structurent tout le plan

1. **La Sémiologie pèse 41,7 % des QCM de l'UEI 1** (373/894) + 25 QCS de cas cliniques. C'est la matière qui décide de ta note.
2. **Le rythme de l'hôpital est d'environ 5 cours de Cardio par semaine** (50 cours en 10 semaines) **+ ~3,9 cours de modules par semaine** (73 cours en 19 semaines). Total ≈ 9 nouveaux cours/semaine. **Être en avance sur TOUT en même temps, avec qualité, n'est pas tenable** en partant de zéro. → Il faut une **avance ciblée** (voir Partie 3).
3. **Le vrai danger du semestre est en février, pas en décembre** : examens Micro (dim 14/02), Pharma (mar 16/02), Para (jeu 18/02) tombent **3, 5 et 7 jours après l'examen de l'UEI 2** (jeu 11/02). Il n'y aura **pas le temps** de découvrir les modules à ce moment-là. Ils doivent être en couche 3 avant.
4. **Estimation déduite du programme** : l'Aïd el-Fitr est estimé au 10/03/2027 [PROG], donc le Ramadan commencerait vers début février 2027 → les examens des modules tomberaient probablement **pendant la première semaine de Ramadan**. Raison de plus pour être en avance (c'est une déduction, pas une donnée explicite).

### 1.4 Hypothèses de travail (à corriger dès que tu as l'info)

| Hypothèse | Pourquoi | Comment la corriger |
|---|---|---|
| L'hôpital/amphi présente les cours **dans l'ordre de numérotation** des fiches | Seul ordre disponible | Dis-moi l'ordre réel → je réordonne la file d'attente, pas le planning |
| Ta journée type (dim–jeu) : sémiologie/stage le matin, amphis 13h–16h | [PROG] : sémio 8h–12h, amphis 13h–16h | Donne-moi ta section et ton service |
| Tu peux travailler ~2 blocs le soir après 16h, et une vraie journée le samedi | Semaine algérienne (week-end ven–sam) | Ajuste la capacité si besoin |
| 1 **bloc** = ~1h15 de travail concentré (avec micro-pause) | Unité de mesure du planning | — |

---

## PARTIE 2 — CARTE DE L'ANNÉE

### 2.1 Calendrier officiel 2026-2027 [PROG]

| Période | Enseignement | Révision | Examens |
|---|---|---|---|
| **S1 — UEI 1 Cardio-respiratoire** + Micro, Para, Pharma | 27/09/2026 → 03/12/2026 | 03/12 → 09/12/2026 | **UEI 1 : jeu 10/12/2026** |
| **S1 — UEI 2 Appareil neurologique, locomoteur et cutané** + Micro, Para, Pharma | 14/12/2026 → 05/02/2027 | 05/02 → 11/02/2027 | **UEI 2 : jeu 11/02/2027** · **Micro : dim 14/02/2027** · **Pharma : mar 16/02/2027** · **Para : jeu 18/02/2027** |
| **S2 — UEI 3 Endocrinien, reproduction, urinaire** + ACP, Immunologie | 21/02/2027 → 22/04/2027 | 22/04 → 28/04/2027 | **UEI 3 : jeu 29/04/2027** |
| **S2 — UEI 4 Appareil digestif** + ACP, Immunologie | 02/05/2027 → 10/06/2027 | 10/06 → 16/06/2027 | **UEI 4 : dim 20/06/2027** · **ACP : mar 22/06/2027** · **Immuno : jeu 24/06/2027** |

### 2.2 Ligne du temps du S1 (le seul semestre détaillé dans tes sources)

```
27/09 ──── UEI 1 (10 sem.) ──── 03/12 ─ Révision ─ 10/12 EXAM UEI 1
                                                     │ 11–13/12 : seuls jours "libres" du S1
14/12 ──── UEI 2 (~8 sem.) ──── 05/02 ─ Révision ─ 11/02 EXAM UEI 2
                                                     14/02 MICRO · 16/02 PHARMA · 18/02 PARA
Modules Micro / Para / Pharma : enseignés sur les 19 semaines (27/09 → 05/02)
```

### 2.3 Jours fériés [PROG]

| Date | Jour | Fête | Impact |
|---|---|---|---|
| 01/11/2026 | Dimanche | Fête nationale | Pendant UEI 1 → **dimanche transformé en « jour fort »** (S5) |
| 01/01/2027 | Vendredi | Nouvel An | Pendant UEI 2 |
| 12/01/2027 | Mardi | Yennayer | Pendant UEI 2 |
| 10–12/03/2027 (estimé) | Mer–Ven | Aïd el-Fitr | Pendant UEI 3 |
| 01/05/2027 | Samedi | Fête du Travail | Début UEI 4 |
| 17–19/05/2027 (estimé) | Lun–Mer | Aïd el-Adha | Pendant UEI 4 |
| 06/06/2027 (estimé) | Dimanche | Nouvel An hégirien | Fin UEI 4 |
| 15/06/2027 (estimé) | Mardi | Achoura | Révision UEI 4 |

**Vacances : aucune période de vacances n'apparaît dans le programme fourni.** Le *Mode vacances* (Partie 6) est donc prêt mais **non daté** ; tu l'actives dès que l'administration annonce des dates.

### 2.4 Emploi du temps hebdomadaire S1 [PROG]

**Amphis (13h–16h, Ziania)** — dépend de ta section :

| Jour | Sections A / B | Sections C / D |
|---|---|---|
| Dimanche | Parasitologie (13h) · Microbiologie (14h30) | — |
| Lundi | Physiopathologie (13h) · Psychologie (14h30) | Pharmacologie (14h30) |
| Mardi | Biochimie (13h) · Imagerie (14h30) | Biochimie (13h) · Imagerie (14h30) |
| Mercredi | — | Microbiologie (13h) · Parasitologie (14h30) |
| Jeudi | Pharmacologie (13h) | Psychologie (13h) · Physiopathologie (14h30) |

**Sémiologie (8h–12h, Département Maharzi)** : chaque service enseigne **2 jours/semaine** (Zemirli, Mustapha, Birtraria, Bologhine : dim + mar ; Kouba, BEO, Rouiba : lun + mer) → c'est cohérent avec **2 cours de sémio par semaine**.

→ **Dis-moi ta section et ton service** : je pourrai caler la règle « étudier le cours AVANT son amphi » au jour près.

### 2.5 Contenu des unités disponibles dans les sources

| Unité / module | Matières / parties | Nb de cours | Détail disponible ? |
|---|---|---:|---|
| UEI 1 Cardio-respiratoire | Sémiologie 18 · Radiologie 10 · Physiopathologie 9 · Psychologie 7 · Biochimie 6 | **50** | ✅ liste + tombabilité |
| Microbiologie | Virologie 10 · Bactériologie 19 | **29** | ✅ liste, ❌ tombabilité |
| Parasitologie | Général · Protozoaires · Helminthes · Entomologie · Mycologie | **25** | ✅ liste, ❌ tombabilité |
| Pharmacologie | Fondements · Toxicologie & vigilance · Système nerveux · Classes thérapeutiques | **19** | ✅ liste, ❌ tombabilité |
| UEI 2, UEI 3, UEI 4, ACP, Immunologie | — | ? | ❌ **aucune liste de cours fournie** |

---

## PARTIE 3 — PRIORITÉS

### Hiérarchie

**1. CARDIO (UEI 1)** — objectif : *maîtrise progressive et profonde* avant le 10/12.
**2. PARASITOLOGIE / MICROBIOLOGIE / PHARMACOLOGIE** — objectif : *suivre le rythme sans jamais décrocher jusqu'à mi-S7*, puis **arrêt total du lun 16/11 au 10/12** (Cardio seul), puis **sprint thématique** dès le 12/12 (et pendant d'éventuelles vacances).
**3. Le reste selon le calendrier** — UEI 2 à partir du 14/12 ; S2 (UEI 3, UEI 4, ACP, Immuno) plus tard.

### Ce que « prendre de l'avance » veut dire concrètement (avance ciblée)

| Matière | Objectif d'avance réaliste pendant UEI 1 | Pourquoi |
|---|---|---|
| **Sémiologie** | Rattrapage S2–S3 (après la convalescence), synchronisée en S4, **1 cours d'avance en S6**, terminée en S8 | 41,7 % des QCM → c'est là que l'avance rapporte le plus |
| **Physiopathologie** | Synchronisée en S1–S3, **1 cours d'avance dès S4**, terminée en S7 | 20,7 % des QCM, cours qui donnent le « pourquoi » des signes |
| **Biochimie** | Avance automatique dès S3 | 6 cours seulement pour 10 semaines d'amphi |
| **Psychologie** | Avance automatique dès S5 | 7 cours pour 10 semaines ; faible poids → C1 ciblée |
| **Radiologie** | Synchronisée (léger retard possible S2–S3, rattrapé S4) | 10 cours en 10 semaines, poids moyen |
| **Pharmacologie** | Au rythme de l'amphi (19 cours/19 sem.) | Module le plus léger en nombre de cours |
| **Microbiologie** | Au rythme ±2 cours jusqu'à mi-S7, puis arrêt ; avance pendant le sprint post-examen | 29 cours/19 sem. = 1,5/sem. → impossible d'être en avance sans sacrifier Cardio |
| **Parasitologie** | Au rythme ±3 cours (module difficile → petites doses), **avance pendant les jours libres** | 25 cours/19 sem. = 1,3/sem. |

> **Décision de directeur pédagogique :** pendant l'UEI 1, l'avance sur les modules n'est réaliste que pour la Pharmacologie. Pour la Micro et la Para, l'objectif est *« ne jamais décrocher »* ; l'avance se construit pendant les périodes où Cardio s'allège. Je préfère te le dire maintenant plutôt que te donner un planning qui paraît beau sur papier.

---

## PARTIE 4 — POIDS DE CHAQUE MODULE (carte du poids académique)

### 4.1 Les trois variables qu'on ne mélange jamais

| Variable | Ce que ça mesure | Ce que ça décide dans le planning | Données disponibles |
|---|---|---|---|
| **Volume** | Quantité de contenu (pages, densité) | **Temps de la couche 1** (nombre de blocs) | ❌ Pages : non fournies → **à mesurer vendredi 02/10**. Seul indicateur disponible : nombre de cours |
| **Tombabilité** | Fréquence aux examens (QCM Medspace 2019-25) | **Profondeur** : nombre de couches, intervalles, QCM | ✅ Cardio · ❌ modules |
| **Difficulté** | Effort pour comprendre/retenir | **Découpage** (C1 en 2 jours), C2 bis, révisions rapprochées | ❌ (sauf Para : élevée, déclarée par toi) → **auto-évaluation après chaque C1** (1 facile · 2 moyen · 3 difficile) |

**Grille de volume** (à appliquer quand tu auras relevé les pages — seuils proposés, ajustables) : faible ≤ 10 p. → ½ bloc · moyen 10–25 p. → 1 bloc · élevé > 25 p. → 2 blocs sur 2 jours.

### 4.2 UEI 1 — poids réel de chaque matière

| Matière | Nb de cours | Part des cours | QCM recensés 2019-25 [CARDIO] | **Part des QCM** | QCM / cours (moyenne) | Difficulté | **Part du temps Cardio recommandée** | Fréquence de révision |
|---|---:|---:|---:|---:|---:|---|---:|---|
| **Sémiologie** | 18 | 36 % | **373** + 25 QCS (6 cas cliniques) | **41,7 %** | 20,7 | non indiquée | **~39 %** | Élevée : C2 à J+1/2, C3 à J+7/10, C4 obligatoire, cas cliniques |
| **Physiopathologie** | 9 | 18 % | 185 | 20,7 % | 20,6 | non indiquée | **~19 %** | Élevée |
| **Radiologie** | 10 | 20 % | 153 | 17,1 % | 15,3 | non indiquée | **~19 %** | Moyenne |
| **Biochimie** | 6 | 12 % | 115 | 12,9 % | **19,2** | non indiquée | **~12 %** | Moyenne-élevée (bon rendement par cours) |
| **Psychologie** | 7 | 14 % | 68 | 7,6 % | 9,7 | non indiquée | **~11 %** | Faible : C1 ciblée, flashcards |
| **Total** | **50** | | **894** | | | | | |

*Part du temps recommandée = moyenne (part des cours + part des QCM). C'est une formule transparente qui mélange volume (approché par le nombre de cours) et rendement. Quand tu auras les pages, on remplace « nombre de cours » par « nombre de pages ».*

**Carte du poids académique — UEI 1 (confirmée par les sources) :**
- **Sémiologie = poids TRÈS ÉLEVÉ** (le plus de cours ET le plus de QCM) → 2 nouveaux cours/sem. + révisions supplémentaires + cas cliniques.
- **Physiopathologie = poids ÉLEVÉ** (peu de cours, mais 20,6 QCM/cours).
- **Radiologie = poids MOYEN** (10 cours, rendement plus faible : 15,3/cours ; 2 cours quasi absents des examens : RAD04 = 3, RAD10 = 8).
- **Biochimie = poids MOYEN mais RENTABLE** (6 cours seulement, 19,2 QCM/cours ; BIO04 = 35).
- **Psychologie = poids FAIBLE** (7 cours, 9,7 QCM/cours ; 3 cours ≤ 4 QCM en 7 ans).

**Les 5 cours les plus « tombables » de l'UEI 1 :** SEM10 Étude synthétique respiratoire (**73**) · SEM16 Sémio artérielle et veineuse (**39**) · SEM18 Étude synthétique CV (**37**) · PHY07 Troubles hydro-sodés (**36**) · BIO04 Dyslipidémies et athérosclérose (**35**). Thèmes de sémio les plus lourds : SP cardiaques I/II (**48**), SF respiratoires I/II (**46**), Pondérale + Fièvre (**43**).

### 4.3 Niveaux de priorité (calcul transparent)

Pas de score décimal (les sources ne le permettent pas). Un niveau P1–P4 basé sur le **chiffre réel** de tombabilité par cours (pour une paire au chiffre commun : chiffre ÷ 2, faute de mieux).

| Niveau | Règle | Cours concernés | Traitement |
|---|---|---|---|
| **P1** | ≥ 30 QCM | SEM10, SEM16, SEM18, PHY07, BIO04 | C1 en 1,5–2 blocs (parfois sur 2 jours) · 4 couches · cas cliniques |
| **P2** | 20–29 | SEM02, 03, 05, 06, 09, 14, 15 · PHY02, 04, 05 · RAD05, 08 · BIO02, 05 · PSY01 | 4 couches |
| **P3** | 10–19 | SEM07, 08, 12, 13 · PHY01, 03, 06, 08, 09 · RAD01, 02, 03, 06, 07, 09 · BIO01, 06 · PSY02, 04 | 3 couches + C4 rapide (flash + QCM) |
| **P4** | < 10 | SEM17 · RAD04, RAD10 · BIO03 · PSY03, 05, 06, 07 | **C1 ciblée** (½ bloc : titres, points-clés, QCM) · C2 groupée · C3 flash · pas de C4 |
| **n.i.** | aucun chiffre | SEM01, SEM04, SEM11 | Traités comme **P2 par défaut** (cours fondateurs) |

**Modificateurs** (montent d'un niveau) : difficulté auto-évaluée = 3 · statut 🔥 · cours « carrefour » relié à ≥ 3 autres cours · examen à moins de 3 semaines.

### 4.4 Modules — poids réel

| Module | Nb de cours | Part du volume modules | Cours/semaine au rythme de l'amphi (cours ÷ 19 sem.) | Tombabilité | Difficulté | **Part du temps modules recommandée** | Révision |
|---|---:|---:|---:|---|---|---:|---|
| **Microbiologie** | 29 (10 viro + 19 bactério) | **39,7 %** | **1,5** | non indiquée dans les sources | non indiquée | **~40 %** | Standard |
| **Parasitologie** | 25 | **34,2 %** | **1,3** | non indiquée dans les sources | **élevée (déclarée par toi)** | **~34 %** (dont la moitié en reprises courtes) | **Rapprochée** : micro-reprises 2×/sem. |
| **Pharmacologie** | 19 | **26,0 %** | **1,0** | non indiquée dans les sources | non indiquée | **~26 %** | Standard, bloc léger possible |

**Conséquence directe :** ta cadence de base « 1 cours/semaine/module » est **insuffisante** pour la Micro (il faut 1,5) et la Para (1,3) : à 1/semaine, au 05/02 tu aurais ~10 cours de retard en Micro et ~6 en Para. Les sources justifient donc une autre cadence (voir Partie 6).

👉 Si tu as des statistiques Medspace pour les modules (comme pour Cardio), envoie-les : je calculerai les priorités internes de chaque module.

---

## PARTIE 5 — STRATÉGIE CARDIO (de zéro à l'examen)

### 5.1 Les 5 phases

| Phase | Semaines (ven → jeu) | Objectif | Nouveaux cours Cardio/sem. |
|---|---|---|---:|
| **A. Convalescence** | **S1** : mer 07/10 → jeu 08/10 | Mise en place + SEM01 (déjà vu) + PHY01, séances courtes | 2 |
| **A'. Reprise progressive** | **S2** : 09/10 → 15/10 | ~75 % de la capacité, **Cardio seul** | 5 (+1 bonus) |
| **B. Montée** | **S3–S4** : 16/10 → 29/10 | Démarrage des modules · synchronisation avec l'hôpital en S4 | 6–7 |
| **C. Croisière + avance** | **S5–S6** : 30/10 → 12/11 | 1 cours d'avance en sémio ; C3 des premiers cours | 6–8 |
| **C'. Arrêt des modules** | **S7** : 13/11 → 19/11 | Modules jusqu'au dim 15/11, puis **Cardio seul** : le temps libéré va aux **C3 anticipées** | 6 |
| **C'. Fin des C1** | **S8** : ven 20/11 → mer 25/11 | 8 dernières C1 (dont 4 légères) **avant mer 25/11** + C3 · 0 module · réserve : recouchage à J-12 | 8 |
| **D. Recouchage — passage 1 (C3)** | **jeu 26/11 (J-14) → jeu 03/12 (J-7)** | Repasser **toute** l'unité en C3 + 6 cas cliniques (25 QCS) | 0 |
| **E. Recouchage — passage 2 (C4)** | **ven 04/12 (J-6) → mer 09/12 (J-1)** | C4 de toute l'unité · passage éclair P1 la veille | 0 |
| **EXAMEN** | **jeu 10/12/2026** | | |

### 5.2 Plan de référence semaine par semaine (couche 1)

*Ordre = numérotation de la fiche (hypothèse). Les cours d'une même ligne sont répartis sur plusieurs jours (Partie 7), jamais tous le même jour. Charge = blocs de couche 1 (synthèse 2 · P1 1,5 · P4 ½ · autres 1).*

| Sem. | Dates | Sémiologie | Physio | Radio | Biochimie | Psycho | Thèmes intégrés | Nouveaux | Charge C1 |
|---|---|---|---|---|---|---|---|---:|---:|
| **S1** | 07/10–08/10 | 01 | 01 | — | — | — | Rencontre avec le patient · Volume, eau & sodium | 2 | 2 |
| **S2** | 09/10–15/10 | 02, 03, 04 | 02, 03 | — | — | 01 (bonus) | Volume, eau & sodium · Fièvre & infection · Respiratoire clinique · Chocs & cœur aigu · Rencontre avec le patient | 6 | 6 |
| **S3** | 16/10–22/10 | 05, 06, 07 | 04 | 01 | 01, 02 | — | Respiratoire clinique · Chocs & cœur aigu · Imagerie : bases & techniques · Volume, eau & sodium | 7 | 7 |
| **S4** | 23/10–29/10 | 08, 09, 10 (P1) | 05, 06 | 02 | — | — | Respiratoire clinique · Fièvre & infection · Imagerie : bases & techniques | 6 | 7 |
| **S5** | 30/10–05/11 *(01/11 férié)* | 11, 12, 13 | 07 (P1) | 03, 04 (P4) | 03 (P4) | 02 | Chocs & cœur aigu · Cœur clinique · Volume, eau & sodium · Imagerie : bases & techniques · Biologie : interprétation · Rencontre avec le patient | 8 | 7,5 |
| **S6** | 06/11–12/11 | 14, 15 | 08 | 05 | 04 (P1) | 03 (P4) | Cœur clinique · Vaisseaux & athérosclérose · Imagerie : bases & techniques · Rencontre avec le patient | 6 | 6 |
| **S7** | 13/11–19/11 | 16 (P1), 17 (P4) | 09 | 06, 07 | 05 | 04 | Vaisseaux & athérosclérose · Cœur clinique · Thorax : imagerie, plèvre & épanchements · Rencontre avec le patient | 7 | 7 |
| **S8** | 20/11–25/11 | 18 (P1) | — | 08, 09, 10 (P4) | 06 | 05 (P4), 06 (P4), 07 (P4) | Cœur clinique · Thorax : imagerie, plèvre & épanchements · Prescription & douleur · Rencontre avec le patient | 8 | 7 |
| **S9** | 26/11–03/12 | — | — | — | — | — | **Recouchage passage 1 (C3)** dès jeu 26/11 + cas cliniques | 0 | — |
| **S10** | 04/12–09/12 | — | — | — | — | — | **Recouchage passage 2 (C4)** + passage éclair | 0 | — |

S5 et S8 sont les semaines Cardio les plus denses : elles portent le retard de la convalescence. Elles restent tenables parce qu'elles contiennent beaucoup de cours P4 (½ bloc) et, pour S8, aucun module.

### 5.3 Position par rapport à l'hôpital (si l'hôpital suit la numérotation)

| Fin de semaine | Sémio (toi / hôpital) | Physio | Radio | Bio | Psy |
|---|---|---|---|---|---|
| S2 | 4 / 6 (−2) | 3 / 3 (=) | 0 / 3 (−3) | 0 / 3 (−3) | 1 / 3 (−2) |
| S4 | 10 / 10 (=) | 6 / 5 (**+1**) | 2 / 5 (−3) | 2 / 5 (−3) | 1 / 5 (−4) |
| S6 | 15 / 14 (**+1**) | 8 / 7 (**+1**) | 5 / 7 (−2) | 4 / 6 (−2) | 3 / 7 (−4) |
| S8 | 18 / 18 (=) | 9 / 9 (=) | 10 / 9 (**+1**) | 6 / 6 (=) | 7 / 7 (=) |

*Bio et Psy : l'amphi ne peut pas tenir 1 cours/sem. pendant 10 semaines (6 et 7 cours) → le retard affiché est surestimé. Après ta convalescence, le retard sur l'hôpital est normal jusqu'en S4 : pendant cette période, l'hôpital sert de **première lecture** (🟡), pas de renforcement.*

**Règle :** dès que la vraie position est connue, la priorité de la semaine va à la matière **la plus en retard pondérée par son poids** (un retard d'1 cours de Sémio est plus grave qu'un retard d'1 cours de Psycho).

### 5.4 Recouchage de l'unité : 14 jours (J-14 → J-1)

Règles : **aucun nouveau cours** à partir du jeu 26/11 · **aucun module** · deux passages complets sur les 50 cours (C3 puis C4) · la Sémiologie reçoit ~40 % du temps · repos réduit à **½ journée/semaine** (vendredis matin 27/11 et 04/12).

| J- | Jour | Type | Passage | Contenu | Cours | Objectif | Charge |
|---|---|---|---|---|---|---|---|
| J-14 | Jeu 26/11 | SOIR | Passage 1 · C3 | Physiopathologie : les chocs | PHY01–PHY05 | Restituer les 4 chocs en 1 tableau comparatif | Normale |
| J-13 | Ven 27/11 | FAIBLE (matin repos) | Passage 1 · C3 | Psychologie complète + Biochimie (bases) | PSY01–07 · BIO01–03 | C3 rapide, P4 en flashcards | Légère |
| J-12 | Sam 28/11 | FORT | Passage 1 · C3 | Sémiologie respiratoire | SEM01–SEM09 | Page blanche par cours + QCM | Élevée |
| J-11 | Dim 29/11 | SOIR | Passage 1 · C3 | Synthèse respiratoire + imagerie thoracique | SEM10 · RAD05–RAD08 | SEM10 = 73 QCM : priorité absolue | Normale |
| J-10 | Lun 30/11 | SOIR | Passage 1 · C3 | Physiopathologie (suite) | PHY06–PHY09 | PHY07 (P1) en premier | Normale |
| J-9 | Mar 01/12 | SOIR | Passage 1 · C3 | Biochimie + imagerie (techniques) | BIO04–06 · RAD01–RAD04 | BIO04 (P1) en premier | Normale |
| J-8 | Mer 02/12 | SOIR | Passage 1 · C3 | Sémiologie cardiaque | SEM11–SEM15 | SP cardiaques (48) + SF cardiaques (36) | Normale |
| J-7 | Jeu 03/12 | SOUPLE → début révision officielle | Passage 1 · C3 | Fin du passage 1 + cas cliniques | SEM16–18 · RAD09–10 · 6 cas cliniques (25 QCS) | Plus aucun cours nouveau | Élevée |
| J-6 | Ven 04/12 | FAIBLE (matin repos) | Passage 2 · C4 | Psychologie + tous les P4 (flash) | PSY01–07 · SEM17 · RAD04 · RAD10 · BIO03 | Flash + QCM | Légère |
| J-5 | Sam 05/12 | FORT (journée) | Passage 2 · C4 | Sémiologie respiratoire | SEM01–SEM10 | QCM chronométrés + carnet d'erreurs | Élevée |
| J-4 | Dim 06/12 | FORT (journée) | Passage 2 · C4 | Sémiologie cardio-vasculaire + cas cliniques | SEM11–SEM18 | SEM14–15, 16, 18 en priorité | Élevée |
| J-3 | Lun 07/12 | FORT (journée) | Passage 2 · C4 | Physiopathologie complète + cas cliniques | PHY01–PHY09 | Mécanismes → signes | Normale |
| J-2 | Mar 08/12 | FORT (journée) | Passage 2 · C4 | Radiologie + Biochimie | RAD01–10 · BIO01–06 | BIO04, RAD05, RAD08 en priorité | Normale |
| J-1 | Mer 09/12 | LÉGER | Passage éclair | P1 + carnet d'erreurs + QCM mixtes (matin) · après-midi léger · coucher tôt | SEM10 · SEM16 · SEM18 · PHY07 · BIO04 | Confiance, pas de nouveauté | Légère |
| J0 | Jeu 10/12 | EXAMEN | — | EXAMEN UEI 1 | — | — | — |

Du 26/11 au 03/12, l'hôpital et les amphis continuent : ce sont des soirs à 2 blocs (samedi = 4–5 blocs). Du 04/12 au 09/12 (révision officielle), journées complètes. Les C3 déjà faites en S4–S8 rendent le passage 1 plus rapide pour les premiers cours.

---

## PARTIE 6 — PLAN DES MODULES

### 6.1 Cadence et règle d'arrêt

| Période | Pharmacologie | Microbiologie | Parasitologie | Total/sem. |
|---|---|---|---|---:|
| S1–S2 (convalescence + reprise) | — | — | — | **0** |
| S3–S6 (mode semestre) | 1/sem. | 1/sem. | 1/sem. dès S4 (séance courte) + 2 micro-reprises | 2–3 |
| **S7 : sam 14/11 + dim 15/11** | — | BAC03 | PAR04 | 2 |
| **⛔ lun 16/11 → jeu 10/12** | **0** | **0** | **0** | **0** — Cardio seul |
| 12/12 → 04/02 (sprint + UEI 2) | ~2/sem. | ~2–3/sem. | ~2–3/sem. | **6 + 1 le vendredi** |
| 28/01 → 11/02 (recouchage UEI 2) | C3 | C3 | C3 (prioritaire) | 1 bloc/jour |
| 12/02 → 18/02 | C4 → examen 16/02 | C4 → examen 14/02 | C4 → examen 18/02 | modules seuls |

Pendant l'arrêt, **aucune séance de module** (pas même des flashcards) : c'est ta règle. Les cartes de modules sont simplement **suspendues** dans Anki et réactivées le 12/12.

### 6.2 Plan des modules pendant l'UEI 1 (parcours thématique)

| Sem. | Pharmacologie | Microbiologie | Parasitologie | Total |
|---|---|---|---|---:|
| S1–S2 | — (convalescence) | — | — | 0 |
| S3 | PHA01 | BAC01 | — | 2 |
| S4 | PHA02 | BAC02 | PAR01 | 3 |
| S5 | PHA03 | BAC05 | PAR02 | 3 |
| S6 | PHA04 | BAC06 | PAR03 | 3 |
| S7 (sam 14/11 · dim 15/11) | — | BAC03 (sam) | PAR04 (dim) | 2 |
| S7 (dès lun 16/11) → S10 | ⛔ | ⛔ | ⛔ | 0 |
| **12–13/12** (après l'examen) | PHA08, PHA09 | BAC04 | — | 3 |
| **Au 13/12** | **6 / 19** | **6 / 29** | **4 / 25** | **16 / 73** |

### 6.2 bis Parcours thématique complet (programme proposé)

Les modules sont étudiés **par thème** : les cours qui se ressemblent (même mécanisme, même famille, même organe) sont placés à quelques jours d'intervalle, souvent **entre deux modules différents** (ex. Antibiotiques en Micro + Pharma la même semaine), et alignés quand c'est possible sur l'unité en cours (Cardio-respiratoire jusqu'en novembre, Neuro-locomoteur-cutané ensuite). Les fondations passent toujours en premier. Si l'amphi présente un cours plus tôt, il passe 🟡 et garde sa place dans le parcours (ou avance si tu préfères). **Confirmé le 07/10 :** l'amphi de Micro a commencé par BAC01 *Introduction au monde microbien* → la Micro démarre bien par la bactériologie (T02), la virologie vient ensuite.

| Thème | Cours | Fenêtre | Lien avec l'unité | À produire |
|---|---|---|---|---|
| **T01 · Fondations pharmaco** | PHA01, PHA02, PHA03, PHA04 | S3 / S4 / S5 / S6 | Prérequis de toute la pharmaco | Schéma ADME + courbe concentration/temps + tableau agoniste/antagoniste |
| **T02 · Bases bactériennes** | BAC01, BAC02, BAC05, BAC06 | S3 / S4 / S5 / S6 | Prépare les antibiotiques (T08) | Tableau Gram+ / Gram− (paroi, coloration, exemples) |
| **T03 · Hôte ↔ microbes** | PAR01, BAC03, BAC04 | S4 / S7 (sam 14/11) / 12/12 | PHY05 Choc septique · SEM03 Fièvre | Schéma « microbiote → conflit → sepsis » |
| **T04 · Protozoaires intestinaux** | PAR02, PAR03, PAR04 | S5 / S6 / S7 (dim 15/11) | — | Tableau comparatif Para (agent · transmission · cycle · clinique · diagnostic · traitement) |
| **T05 · SNA I — cœur & vaisseaux** | PHA08, PHA09, PHA10 | 13/12 / S11 | PHY02–05 Chocs · PHY04 Anaphylaxie (adrénaline) · PHY08 HTA | Tableau récepteurs α/β → effets → médicaments |
| **T06 · Virus : bases** | VIR01, VIR02, VIR03 | S11 | SEM03 Fièvre · PHY05 | Schéma du cycle viral |
| **T07 · Fièvre & paludisme** | PAR07 | S11 | SEM03 Fièvre · PHY06 Thermorégulation (S4) | Schéma du cycle + tableau des espèces |
| **T08 · Antibiotiques (Micro + Pharma)** | BAC07, PHA14, PHA15, BAC08, BAC09 | S12 | PHY05 Choc septique | UN SEUL tableau commun Micro + Pharma |
| **T09 · Toxicité & vigilance** | PHA05, PHA06, PHA07 | S12 / S13 | PSY05 Psychologie de la prescription | Arbre « effet indésirable → que faire » |
| **T10 · Peau & muqueuses** | BAC15, VIR04, PAR17, PAR18, PAR20, PAR22, VIR05 | S13 / S14 | UEI 2 (cutané) | Tableau « lésion → agents possibles → diagnostic » |
| **T11 · SNA II — neuro & muscle** | PHA11, PHA12, PHA13 | S14 | UEI 2 (neurologique, locomoteur) | Tableau muscarinique/nicotinique → effets → médicaments |
| **T12 · Vecteurs & protozoaires sanguins/tissulaires** | PAR16, PAR05, PAR06, PAR08 | S15 | UEI 2 (neuro : toxo, trypano · cutané : leishmaniose) · rappel PAR07 | Tableau vecteur/parasite (avec PAR07) |
| **T13 · Virus respiratoires & éruptifs** | VIR08 | S15 | UEI 1 respiratoire · UEI 2 cutané | Tableau virus → clinique → prévention |
| **T14 · Inflammation, allergie & hormones** | PHA16, PHA17, PHA18, PHA19 | S15 / S16 | PHY04 Anaphylaxie · PSY06 Douleur · UEI 2 locomoteur | Tableau AINS vs corticoïdes + antihistaminiques |
| **T15 · Plathelminthes (cestodes & trématodes)** | PAR09, PAR10, PAR11, PAR12 | S16 / S17 | UEI 1 thorax (kyste hydatique) · UEI 2 neuro (cysticercose) | Tableau comparatif des plathelminthes |
| **T16 · Bactéries pathogènes (agents)** | BAC16, BAC17, BAC18, BAC11 | S17 | UEI 1 respiratoire (mycobactéries, légionelles) · UEI 2 neuro (Listeria, anaérobies) | Fiche par famille bactérienne |
| **T17 · Nématodes** | PAR13, PAR14, PAR15 | S17 / S18 | UEI 2 cutané (larva migrans, onchocercose) | Tableau comparatif des nématodes |
| **T18 · Virus à ARN & hépatites** | VIR06, VIR07 | S18 | UEI 4 digestif (plus tard) · T21 | Tableau des hépatites A–E |
| **T19 · Mycoses profondes** | PAR19, PAR21, PAR23, PAR24 | ⚠️ Sans créneau | UEI 1 respiratoire (pneumocystose, aspergillose) | Tableau des mycoses profondes |
| **T20 · Prévention, hygiène & diagnostic** | BAC10, BAC12, BAC13, BAC14, VIR10, BAC19, VIR09 | Ven S12 / Ven S13 / Ven S14 / Ven S15 / Ven S16 / Ven S17 / ⚠️ Sans créneau | BIO03 Pièges · BIO06 Liquides d'épanchement | Fiche « du prélèvement au résultat » |
| **T21 · Immunodéprimé (synthèse)** | PAR25 | ⚠️ Sans créneau | Rappels VIR07, PAR04, PAR08, PAR18, PAR19 | Tableau « déficit → agents » |

**Bilan honnête :** avec la convalescence (modules démarrés en S3) et l'arrêt à mi-S7, seuls **16 cours de modules sur 73** sont faits au 13/12. Il en reste **57** pour la période de l'UEI 2 : à **6 par semaine + 1 le vendredi**, il reste **6 cours sans créneau** (PAR19, PAR21, PAR23, PAR24, VIR09, PAR25). C'est le **risque n°1 du semestre**. Leviers, dans l'ordre :
1. **Vacances d'hiver** si l'administration en annonce → Mode vacances (~12 cours de modules/semaine) → problème réglé.
2. **Statistiques Medspace des modules** → on passe les cours peu tombables en couche 1 ciblée (½ bloc) et on libère des créneaux.
3. À défaut : ces cours sans créneau se font en **C1 ciblée** dans le bloc modules quotidien du 28/01 → 11/02 (au détriment d'une partie des C3).
4. La liste des cours de l'UEI 2 → j'équilibre semaine par semaine.

### 6.2 ter Fin de semestre des modules (proposition)

| Dates | Microbiologie | Pharmacologie | Parasitologie |
|---|---|---|---|
| 28/01 → 11/02 (recouchage UEI 2) | C3 · 1 bloc tous les 2 jours | C3 rapide · 1 bloc tous les 3 jours | **C3 prioritaire** chaque jour |
| Ven 12/02 · Sam 13/02 | **C4** (bases + virologie, puis bactériologie + antibiotiques) | — | — |
| **Dim 14/02** | **EXAMEN** | C4 l'après-midi (fondements + SNA) | — |
| Lun 15/02 | — | **C4** (classes thérapeutiques + QCM) | — |
| **Mar 16/02** | — | **EXAMEN** | C4 l'après-midi (protozoaires + entomologie) |
| Mer 17/02 | — | — | **C4** (helminthes + mycologie + QCM) |
| **Jeu 18/02** | — | — | **EXAMEN** |

Pour l'UEI 2, un arrêt total des modules pendant le recouchage est **impossible** : leurs examens tombent 3 à 7 jours après. D'où le bloc modules quotidien entre le 28/01 et le 11/02.

### 6.3 Stratégie par module

**Parasitologie (difficile → petites doses, beaucoup de rappels)**
- Jamais plus d'**1 nouveau cours de Para par jour**, et jamais le même jour qu'un P1 de Cardio.
- Séance nouvelle = **45–60 min max**. Le cours se termine par un **tableau comparatif** à remplir : *Agent · Réservoir/transmission · Cycle · Clinique · Diagnostic · Traitement/prévention*.
- **Micro-reprises de 15 min** 2×/sem. (mercredi et vendredi) : flashcards + reconstruire le tableau de mémoire.
- Familles à comparer dans un même tableau : Amibes/Flagellés/Cryptosporidies (PAR02–04) · Leishmanies/Trypanosomes (PAR05–06) · Paludisme/Toxoplasmose (PAR07–08) · Cestodes adultes/larvaires (PAR09–10) · Douves/Schistosomes (PAR11–12) · Nématodes per-os/transcutanés/Filaires (PAR13–15) · Levures/Filamenteux (PAR17–24).

**Microbiologie (le plus gros volume des modules)**
- Le samedi (jour fort) porte le cours principal ; le 2e cours de la semaine (semaines paires) le mercredi.
- Les cours « généralités » (structure, physiologie, génétique, multiplication virale) sont des **fondations** : C2 rapide (J+2).
- Les cours « agents » (BAC15–18, VIR04–08) se révisent en **tableaux** : agent · pouvoir pathogène · diagnostic · traitement.

**Pharmacologie (module plus léger, utilisable après un cours lourd)**
- Placée le **lundi soir après la Sémio B** (bloc plus léger) ou le **vendredi**.
- PHA01–04 (bases : ADME, PK, PD) : à bien comprendre, tout le reste en dépend.

### 6.4 Liens entre modules et Cardio (proposés à partir des intitulés des cours)

| Cours Cardio | Cours de modules liés | Utilisation |
|---|---|---|
| PHY05 Choc septique | BAC04 Conflit hôte–bactérie · VIR03 Physiopathologie des infections virales · BAC07–08 / PHA14–15 Antibiotiques | Rappel croisé quand le 2e cours est étudié |
| PHY04 Choc anaphylactique | PHA09 Sympathomimétiques (adrénaline) · PHA19 Antihistaminiques · PHA17 Corticoïdes | Quand PHA09 arrive (~S9) → mini-rappel PHY04 |
| PHY08 HTA · PHY02/03 | PHA08–12 SNA | Idem |
| SEM03 Fièvre · PHY06 Thermorégulation | PAR07 Paludisme · PHA16 AINS | Rappel croisé |
| Sémio respiratoire · Radio thorax | PAR10 Cestodes larvaires · PAR19 Pneumocystose · PAR21 Aspergillose · BAC18 Mycobactéries | Rappel croisé |
| PSY05 Psychologie de la prescription | PHA06 Effets secondaires · PHA07 Pharmacovigilance | Rappel croisé |
| PSY06 Psychologie de la douleur | PHA16 AINS | Rappel croisé |

### 6.5 Mode VACANCES (à activer dès que des dates sont connues)

Semaine type vacances : **5 jours de travail + 1,5 jour de repos**, **3 blocs + 1 bloc de révision par jour**, maximum **3 nouveaux cours par jour**.

| Jour | Bloc 1 (matin, lourd) | Bloc 2 | Bloc 3 | Bloc 4 (court) |
|---|---|---|---|---|
| J1 | Micro nouveau | Para nouveau (court) | Pharma nouveau | C2 de la veille + flashcards |
| J2 | Micro nouveau | Micro nouveau | Para reprise (tableau) | C2 + flashcards |
| J3 | Micro nouveau | Para nouveau (court) | Pharma nouveau | C2 + flashcards |
| J4 | Micro nouveau | Pharma nouveau | Para reprise + QCM | C2 + flashcards |
| J5 *(faible)* | Para nouveau (court) | Micro C2/C3 | QCM mixtes | Bilan + préparation de l'unité suivante |
| J6–J7 | **Repos** (½ journée de flashcards possible) | | | |

Total/semaine ≈ **Micro 6 · Para 3 + 2 reprises · Pharma 3–4 ≈ 12 nouveaux** (≈ 40/34/26 % du temps, proportionnel au volume). **Préparation de l'unité suivante** : 1 bloc tous les 2 jours dès que j'ai la liste des cours de l'UEI 2.

**Mini-mode vacances 11–13/12** (après l'examen UEI 1) : ven 11/12 **repos complet** · sam 12/12 : BAC04 (fin de *Hôte ↔ microbes*) + réactivation des flashcards de modules · dim 13/12 : PHA08 + PHA09 (SNA I, en lien direct avec les chocs et l'HTA que tu viens de réviser). L'UEI 2 démarre lun 14/12.

---

## PARTIE 7 — SEMAINE TYPE (mode semestre, sans stage)

### 7.1 Les types de journée (la base du système dynamique)

Les jours ne portent **pas** de matière fixe : ils portent un **type** et des **créneaux**. Tu remplis chaque créneau avec **le prochain cours de la file d'attente** de la matière.

| Type de jour | Jour par défaut | Capacité | Rôle |
|---|---|---|---|
| **FAIBLE** | Vendredi | Matin repos · après-midi 2 blocs légers | Révisions, QCM, flashcards, petit cours, rattrapage léger, **bilan + plan de la semaine** |
| **FORT** | Samedi (+ jours fériés) | 4 blocs (2 matin + 2 après-midi) · **soirée libre** | Cours lourds, P1, liens Physio→Sémio |
| **SOIR** | Dimanche → mercredi | 2 blocs après 16h | 1 nouveau cours + 1 révision (ou 1 lourd + 1 léger) |
| **SOUPLE** | Jeudi | Matin = **TAMPON** (si libre) · soir **repos** | Absorber les retards ; si tu es à jour → repos ou reprise Para |
| **STAGE** | Le jour du stage | 1 bloc max | Révision/flashcards (Partie 8) |

**Repos protégé : jeudi soir + vendredi matin + samedi soir (+ jeudi matin si tu es à jour) ≈ 1 à 1,5 jour/semaine.**

### 7.2 Semaine type

| Créneau | Bloc 1 | Bloc 2 | Bloc 3 | Flashcards (15–20 min) | Nb de cours |
|---|---|---|---|---|---:|
| **VEN — FAIBLE** | Cours léger (Psy, P4) ou rattrapage | **Rappel intégré** du thème de la semaine passée (QCM + restitution) + C3 | Bilan 20 min + plan de la semaine | ☐ réviser | 2 |
| **SAM — FORT** | **Physiopathologie** (thème de la semaine) | **Sémiologie A** (même thème) | **Microbiologie** | ☐ créer ×3 | 3 |
| **DIM — SOIR** | **Biochimie** ou **Psycho** (standard) | Révisions C2 (J+1/J+2 du samedi) | — | ☐ créer + réviser | 2 |
| **LUN — SOIR** | **Sémiologie B** | **Pharmacologie** (plus léger après le lourd) | — | ☐ créer ×2 | 2 |
| **MAR — SOIR** | **Radiologie** (même thème si possible) | **Parasitologie** (séance courte 45–60 min) | — | ☐ créer ×2 | 2 |
| **MER — SOIR** | **Rappel intégré** du thème : Physio → Bio → Sémio → Radio (QCM mixte) | Micro n°2 (semaines à 2 cours) **ou** C2 modules + micro-reprise Para 15 min | — | ☐ réviser | 2 (+ petits cours en révision) |
| **JEU — SOUPLE** | Matin : **TAMPON** (rattrapage) | — | — | (optionnel) | 0–1 |

**Bilan d'une semaine normale :** nouveaux cours = Sémio 2 · Physio 1 · Radio 1 · Bio/Psy 1–2 · Micro 1–2 · Para 1 · Pharma 1 ≈ **8–9** · révisions ≈ 3–4 blocs · **~14 blocs ≈ 17–18 h + ~2 h de flashcards**.

### 7.3 La séquence intégrée (ta 2e stratégie)

Même thème clinique, **réparti sur plusieurs jours** :
**SAM** Physiopathologie → **DIM** Biochimie → **LUN** Sémiologie → **MAR** Radiologie → **MER** Rappel intégré.
Exemple « Cœur aigu » (S2 → S3) : PHY02 + PHY03 (sam 10 et lun 12/10) → BIO02 Biomarqueurs cardiaques (dim 18/10) → SEM05 dyspnée (sam 17/10) → **mer 21/10 : rappel intégré** choc cardiogénique + IC aiguë + biomarqueurs + dyspnée.
Quand la numérotation empêche un lien de tomber la même semaine (ex. SEM03 Fièvre en S1, PHY06 Thermorégulation en S4), le lien se fait par la **révision** : un rappel de SEM03 (flashcards + QCM) est placé la semaine de PHY06.

---

## PARTIE 8 — SEMAINE AVEC STAGE

Stage ≈ ½ journée toutes les 2 semaines, dates inconnues → **bloc « STAGE » déplaçable**.

### 8.1 Règles

1. Le jour du stage devient **jour STAGE** : **1 bloc max** (révision C2/C3 ou cours P4) + flashcards 15 min.
2. Le nouveau cours prévu ce jour-là va au **TAMPON du jeudi matin**.
3. Si le stage tombe **le jeudi** → plus de tampon : le cours déplacé va au **vendredi** (seulement s'il est léger), sinon on remplace la Para nouvelle de la semaine par une reprise Para.
4. Si le stage tombe **le samedi** (peu probable) → samedi = 2 blocs (Physio + Sémio A) ; la Micro passe au mercredi.
5. **On ne supprime jamais** : la Sémio, les flashcards, le repos du jeudi soir.

### 8.2 Exemple : stage le mardi

| Créneau | Semaine normale | **Semaine avec stage (mardi)** |
|---|---|---|
| VEN | Cours léger + rappel intégré + bilan | identique |
| SAM | Physio + Sémio A + Micro | identique |
| DIM | Bio/Psy + C2 | identique |
| LUN | Sémio B + Pharma | identique |
| **MAR** | Radio + Para | **STAGE** → soir : **flashcards + C2 courte** (1 bloc max) |
| MER | Rappel intégré + Micro 2/C2 | **Radio** + rappel intégré **court** (Micro n°2 reportée à la semaine suivante) |
| **JEU** | Tampon / repos | **Para (séance courte)** le matin · soir repos |

Nouveaux cours : 8 au lieu de 9. **C'est voulu.**

---

## PARTIE 9 — SYSTÈME DE RÉVISION EN COUCHES

### 9.1 Correspondance avec tes fiches Medjelfa / EduSaviours

Tes fiches imprimées ont 5 cases (C1–C5) + Q. Voici comment les cocher avec ton système à 4 couches :

| Ton système | Case de la fiche | Contenu |
|---|---|---|
| **État 🟡 « Vu »** (ne compte pas comme appris) | **C1** — lecture préliminaire (amphi ou YouTube) | Écoute/lecture passive |
| **Couche 1 — Apprentissage** | **C2** — titres + informations de base | Première vraie étude |
| **Couche 2 — Consolidation** | **C3** — informations secondaires | Rappel actif + QCM |
| **Couche 3 — Maîtrise** | **C4** — détails | Pièges, tableaux, forte tombabilité |
| **Couche 4 — Pré-examen** | **C5** — révision finale | Ultra-rapide, cas cliniques |
| **QCM** | **Q** — « avec chaque couche » | Coche Q à chaque couche faite avec QCM |

### 9.2 Contenu de chaque couche

| Couche | Objectifs | Méthode | Durée indicative |
|---|---|---|---|
| **1 — Apprentissage** | Comprendre, structurer, relier, produire des notes utiles | Lecture active → plan du cours en 1 page → mécanismes expliqués « à voix haute » → **création des flashcards** → 5–10 QCM pour vérifier | Selon le volume (½ à 2 blocs) |
| **2 — Consolidation** | Rappel actif, corriger les lacunes | **Page blanche** (restituer le plan sans regarder) → corriger → 10–20 QCM → compléter les flashcards | ~40 % du temps de C1 |
| **3 — Maîtrise** | Rapidité, pièges, tableaux, points très tombables | QCM d'annales du cours → noter chaque erreur dans le **carnet d'erreurs** → tableaux comparatifs | ~30 % du temps de C1 |
| **4 — Pré-examen** | Ultra-rapide, intégration | Fiche 1 page + carnet d'erreurs + cas cliniques + QCM chronométrés | 15–30 min/cours |

### 9.3 Intervalles selon la priorité (calculés à partir de la date de C1)

| Niveau | C2 | C3 | Rappel intermédiaire | C4 |
|---|---|---|---|---|
| **P1** | J+1 / J+2 | J+7 | Flashcards J+14 et J+21 | **Obligatoire** + cas cliniques |
| **P2** (et n.i.) | J+2 / J+3 | J+10 | Flashcards J+21 | **Obligatoire** |
| **P3** | J+3 / J+5 | J+14 ou S9 | Flashcards | Rapide (flash + QCM) |
| **P4** | J+5 / J+7 (groupée avec d'autres) | S9 (flash) | — | Non (sauf 🔥) |
| **Parasitologie** | J+2 | J+7 | Micro-reprises 2×/sem. | Obligatoire avant le 18/02 |

**Ajustement par la maîtrise (après chaque couche) :**
- QCM ≥ 85 % **et** page blanche complète → l'intervalle suivant **× 1,5** (le cours s'espace).
- QCM 60–85 % → intervalle normal.
- QCM < 60 % **ou** page blanche < 50 % → statut **🔥** : **C2 bis à J+2**, le cours monte d'un niveau.

**Ajustement par le volume :** un cours au volume « élevé » (> 25 p.) reçoit un **rappel intermédiaire de plus** (flashcards ciblées entre C2 et C3).

**Ajustement par l'examen :** dès le lun 16/11, plus aucun module : le temps libéré va aux C3 de Cardio. À J-14 (jeu 26/11), plus aucun nouveau cours : recouchage (Partie 5.4).

---

## PARTIE 10 — FLASHCARDS + QCM

### 10.1 Flashcards

| Moment | Action | Quantité indicative |
|---|---|---|
| Fin de la **couche 1** | ☐ **Créer** les flashcards du cours | P1 : 20–25 · P2 : 15 · P3 : 10 · P4 : 5–8 · Para : 10–15 |
| **Couche 2** | ☐ **Compléter** avec les erreurs du rappel actif | +3 à 5 |
| **Chaque jour** | ☐ **Réviser** les cartes dues | **15–20 min max** |
| Vendredi | Revue des cartes ratées de la semaine | 15 min |
| Couche 4 | Uniquement les cartes ratées + P1 | — |

Règles : une carte = une idée ; question → réponse courte ; privilégier les **mécanismes, valeurs-clés, signes, pièges**. **Jamais plus de 25 nouvelles cartes par jour.** Outil : celui que tu préfères (Anki, cartes papier en boîtes de Leitner…).

### 10.2 QCM

| Couche | QCM | Objectif |
|---|---|---|
| C1 | 5–10 | Vérifier la compréhension |
| C2 | 10–20 | Repérer les lacunes |
| C3 | Toutes les annales du cours | Pièges, formulations |
| C4 | Mixtes, chronométrés + **25 QCS de cas cliniques** (6 cas) | Conditions d'examen |
| Mercredi (rappel intégré) | QCM mixtes du thème | Intégration entre matières |

**Carnet d'erreurs** (indispensable) : chaque QCM raté → 1 ligne : *cours · piège · bonne réponse · pourquoi je me suis trompé*. Il devient ta révision des 48 dernières heures.

---

## PARTIE 11 — PLANNING À PARTIR D'AUJOURD'HUI (reprise après chirurgie : mer 07/10 → jeu 15/10)

L'ancienne semaine 1 (02/10 → 08/10) n'a pas pu être faite (maladie + chirurgie). Le programme repart **aujourd'hui, mercredi 07/10**, en **mode convalescence**.

### Règles de reprise (prioritaires sur tout le reste)

1. **Les consignes de ton chirurgien ou de ton médecin passent avant ce planning** (position, temps assis, traitement, contrôles). Le planning s'adapte à elles, pas l'inverse.
2. **Mer 07/10 et jeu 08/10** : 1 à 1,5 bloc par jour maximum, en **séances de 30–45 min** avec 10 min de pause.
3. **S2 (09/10 → 15/10)** : environ **75 % de la capacité normale**, **Cardio seul**, aucun module.
4. **Signal d'arrêt** : douleur, fièvre ou grosse fatigue → **mode minimum** (10 min de flashcards) et repos. On ne rattrape jamais en allongeant les soirées.
5. **Sommeil prioritaire** : pas de travail tard le soir pendant la reprise.
6. **Cours manqués pendant ton absence** : ils sont ⬜ *non vus* (pas 🟡). Récupère les supports (polycopiés, notes d'un camarade, vidéos) ; la case **C1 de ta fiche** (« lecture préliminaire, amphi ou YouTube ») sert exactement à ça.
7. **Le retard (~1 semaine) est absorbé sans toucher aux 14 jours de recouchage** : S5 et S8 plus denses (cours légers regroupés), modules démarrés en S3, et **réserve** : démarrer le recouchage le sam 28/11 (J-12) au lieu du jeu 26/11 si besoin.

### Mercredi 07/10 — CONVALESCENCE

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 (30–45 min) | **Mise en place** : importer le pack Notion · rassembler les supports de l'UEI 1, y compris les cours manqués · relever les pages des cours que tu as sous la main | Organisation | Élevée | — | Préparer sans se fatiguer |
| 2 (30–45 min, si ça va) | **SEM01** Introduction à la sémiologie + anamnèse | Nouveau (C1) | n.i. → P2 | à mesurer | Comprendre la démarche clinique |
| 3 (10 min) | Flashcards SEM01 (5–10 cartes) | Création | — | Faible | Mémoire |

**Cours 1 : SEM01** · Type : Couche 1 (déjà 🟡 vu) · Module : Sémiologie · Volume : à mesurer · Difficulté : à auto-évaluer · **Tombabilité : non indiquée dans les sources** · *Pourquoi aujourd'hui ?* Déjà vu, conceptuel, idéal pour reprendre doucement, et il ouvre toute la sémiologie.
**Flashcards :** ☑ À créer ☐ À compléter ☐ À réviser · **QCM :** ☐ Non (pas aujourd'hui) · **Charge : très légère**

### Jeudi 08/10 — CONVALESCENCE

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 (2 × 30–40 min) | **PHY01** Choc hypovolémique | Nouveau (C1) | P3 | à mesurer | Comprendre le mécanisme du choc |
| 2 (10 min) | Flashcards : créer PHY01 · réviser SEM01 | Création + révision | — | Faible | Mémoire |
| Soir | **REPOS** | | | | |

**Cours 1 : PHY01** · C1 (non vu : première découverte) · Physiopathologie · Volume : à mesurer · Difficulté : à auto-évaluer · **Tombabilité : 13** (1,5 %) · *Pourquoi aujourd'hui ?* Cours peu tombable donc sans pression un jour de convalescence, et c'est la base de tous les chocs (PHY02, 04, 05). Commence par une vidéo ou une lecture rapide du poly (= case C1 de ta fiche), puis étudie-le.
**Flashcards :** ☑ À créer ☐ À compléter ☑ À réviser · **QCM :** ☑ Oui (5 QCM) · **Charge : très légère**

### Vendredi 09/10 — JOUR FAIBLE (reprise)

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| Matin | Repos | | | | |
| 1 | **SEM01 + PHY01** : page blanche + QCM | Couche 2 | P2 / P3 | — | Rappel actif |
| 2 (20 min) | **Bilan + organisation** : finir le relevé des pages, régler Notion, lister les cours manqués à récupérer | Organisation | — | — | Préparer S2 |
| 3 | Flashcards | Révision | — | Faible | Mémoire |

**Flashcards :** ☐ À créer ☐ À compléter ☑ À réviser · **QCM :** ☑ Oui · **Charge : légère** · 0 nouveau cours (voulu)

### Samedi 10/10 — JOUR FORT allégé (3 blocs, soirée libre)

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 | **PHY02** Choc cardiogénique | Nouveau (C1) | P2 | à mesurer | Comparer avec PHY01 |
| 2 | **SEM02** Sémiologie pondérale | Nouveau (C1) | P2 | à mesurer | Relier à la volémie (hypovolémie ↔ poids) |
| 3 (court) | Flashcards : créer PHY02 + SEM02 | Création | — | Faible | Mémoire |

- **Cours 1 : PHY02** · C1 · Physiopathologie · **Tombabilité : 22** (2,5 %) · *Pourquoi ?* Thème « chocs » avec PHY01 (étudié jeudi) ; prépare PHY03 de lundi.
- **Cours 2 : SEM02** · C1 · Sémiologie · **Tombabilité : 43 (commun avec SEM03)** · *Pourquoi ?* Thème « volume » avec PHY01 ; ouvre la paire SEM02-03.
- **Flashcards :** ☑ À créer ×2 · **QCM :** ☑ Oui · **Charge : normale (allégée)**

### Dimanche 11/10 — SOIR

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 | **SEM03** Fièvre | Nouveau (C1) | P2 | à mesurer | Compréhension |
| 2 | **SEM02** | Couche 2 (J+1) | P2 | — | Page blanche + QCM |
| 3 | Flashcards : créer SEM03 · réviser | Consolidation | — | Faible | Mémoire |

- **Cours 1 : SEM03** · C1 · Sémiologie · **Tombabilité : 43 (commun avec SEM02)** · *Pourquoi ?* Paire avec SEM02 → 1 jour d'écart.
- **Flashcards :** ☑ créer ☑ réviser · **QCM :** ☑ Oui · **Charge : normale**

### Lundi 12/10 — SOIR

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 | **PHY03** Insuffisance cardiaque aiguë | Nouveau (C1) | P3 | à mesurer | Du choc cardiogénique à l'IC aiguë |
| 2 | **PHY02** (+ PHY01) — session « chocs » | Couche 2 (J+2) | P2 | — | Tableau comparatif des chocs + QCM |
| 3 | Flashcards : créer PHY03 · réviser | Consolidation | — | Faible | Mémoire |

- **Cours 1 : PHY03** · C1 · Physiopathologie · **Tombabilité : 18** (2,0 %) · *Pourquoi ?* Suite logique de PHY02 (thème « Chocs & cœur aigu »).
- **Flashcards :** ☑ créer ☑ réviser · **QCM :** ☑ Oui · **Charge : normale**

### Mardi 13/10 — SOIR

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 | **SEM04** Topographie du thorax | Nouveau (C1) | n.i. → P2 | à mesurer | Repères du thorax (préparent SEM05–08 et la radio) |
| 2 | **SEM03** | Couche 2 (J+2) | P2 | — | Page blanche + QCM |
| 3 | Flashcards | Consolidation | — | Faible | Mémoire |

- **Cours 1 : SEM04** · C1 · Sémiologie · **Tombabilité : non indiquée dans les sources** · *Pourquoi ?* Prépare toute la sémiologie respiratoire de S3.
- **Flashcards :** ☑ créer ☑ réviser · **QCM :** ☑ Oui · **Charge : normale**

### Mercredi 14/10 — SOIR

| Bloc | Contenu | Type | Priorité | Volume | Objectif |
|---|---|---|---|---|---|
| 1 | **Rappel intégré « Volume & chocs »** : PHY01 · PHY02 · PHY03 (C2) · SEM02 · SEM03 | Consolidation groupée | Élevée | — | Relier physio ↔ sémio (QCM mixte + schéma de mémoire) |
| 2 (bonus, seulement si tu te sens bien) | **PSY01** Aspects communicationnels + examen mental | Nouveau (C1) | P2 | à mesurer | Relier à l'anamnèse (SEM01) |
| 3 | Flashcards | Révision | — | Faible | Mémoire |

- **Bonus : PSY01** · C1 · Psychologie · **Tombabilité : 24** (2,7 %) · *Pourquoi ?* Thème « rencontre avec le patient » avec SEM01. **Si tu es fatigué → il passe en S3**, sans culpabilité.
- **Flashcards :** ☑ réviser · **QCM :** ☑ Oui · **Charge : normale**

### Jeudi 15/10 — SOUPLE

| Bloc | Contenu | Type |
|---|---|---|
| Matin (si libre) | **TAMPON** : ce qui n'a pas été fait cette semaine. Si tout est fait → repos. | Rattrapage |
| Soir | **REPOS** | |

### Vérification automatique (07/10 → 15/10)

| Contrôle | Résultat | Correction appliquée |
|---|---|---|
| Charge compatible avec une convalescence | ✅ 2 jours à ≤ 1,5 bloc, puis ~75 % | Séances courtes, soirées libres |
| Max 3 cours/jour | ✅ (mercredi 14 = révision groupée) | — |
| Vendredi léger | ✅ 0 nouveau cours | — |
| C2 de chaque cours | ✅ SEM01, PHY01 (09/10) · SEM02 (11/10) · PHY02 (12/10) · SEM03 (13/10) · PHY03 (14/10) · SEM04 (ven 16/10) | — |
| Flashcards chaque jour | ✅ | — |
| Modules | ⚠️ absents | **Volontaire** : démarrage en S3 (PHA01, BAC01) |
| Repos | ✅ jeudi soir, vendredi matin, samedi soir | — |
| Nouveaux cours | 7 (+1 bonus) en 9 jours | — |

### Semaine 3 en aperçu (ven 16/10 → jeu 22/10)

| Créneau | Contenu |
|---|---|
| VEN 16 *(faible)* | **BIO01** Biochimie de l'homme sain (léger) · C2 SEM04 (+ PSY01 si fait) · bilan |
| SAM 17 | **PHY04** Choc anaphylactique · **SEM05** SF respiratoires I · **BAC01** Introduction au monde microbien |
| DIM 18 | **BIO02** Biomarqueurs cardiaques · C2 SEM05 · C3 SEM01 / PHY01 |
| LUN 19 | **SEM06** SF respiratoires II · **PHA01** Introduction à la pharmacologie |
| MAR 20 | **RAD01** Tube à rayons X · C2 PHY04 + SEM06 |
| MER 21 | **SEM07** Examen physique respiratoire I · rappel intégré « Cœur aigu » (PHY02-03 + BIO02) |
| JEU 22 | Tampon (PSY01 si pas encore fait) · soir repos |

## PARTIE 12 — TABLEAUX DE SUIVI

Tous ces tableaux existent en **bases de données Notion** dans le dossier `notion/` (avec vues, formules et calendriers : voir le guide). Ci-dessous, leur version lisible.

Légende des états : ⬜ Non commencé (ou non vu : absent) · 🟡 Vu à l'hôpital mais non étudié · 🔵 Couche 1 · 🟢 Couche 2 · 🟣 Couche 3 · ✅ Couche 4 / pré-examen · 🔥 À revoir rapidement
Maîtrise : 1 = fragile · 2 = correct · 3 = solide (auto-évaluation après QCM).

### 12.1 Tableau central de contrôle — UEI 1 Cardio-respiratoire

*Tombabilité = chiffre brut de la fiche [CARDIO] (Medspace 2019-25). Part UEI 1 = chiffre ÷ 894 (calcul). Volume (pages) et difficulté : non fournis par les sources → à remplir. P1/P2 = dates de recouchage.*

| ID | Cours | Matière | Thème intégré | Volume | Difficulté | Tombabilité | Part UEI 1 | Priorité | C1 prévue | Dernière révision | Prochaine révision | Couche actuelle | Recouchage P1 · P2 |
|---|---|---|---|---|---|---:|---:|---|---|---|---|---|---|
| SEM01 | Introduction à la sémiologie médicale + anamnèse | Sémiologie | Rencontre avec le patient | ? p. · 1 bloc | à évaluer | non indiquée | — | P2 (défaut) | S1 · 07/10 | — | C2 09/10 | 🟡 Vu | 28/11 · 05/12 |
| SEM02 | Sémiologie pondérale | Sémiologie | Volume, eau & sodium | ? p. · 1 bloc | à évaluer | 43 (commun 02+03) | 4,8 % | P2 | S2 · 10/10 | — | C2 11/10 | ⬜ | 28/11 · 05/12 |
| SEM03 | Fièvre | Sémiologie | Fièvre & infection | ? p. · 1 bloc | à évaluer | 43 (commun 02+03) | 4,8 % | P2 | S2 · 11/10 | — | C2 13/10 | ⬜ | 28/11 · 05/12 |
| SEM04 | Topographie du thorax | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | non indiquée | — | P2 (défaut) | S2 · 13/10 | — | C2 16/10 | ⬜ | 28/11 · 05/12 |
| SEM05 | SF respiratoires I : dyspnée, douleurs thoraciques | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | 46 (commun 05+06) | 5,1 % | P2 | S3 | — | selon date de C1 | ⬜ | 28/11 · 05/12 |
| SEM06 | SF respiratoires II : toux, expectoration, vomique, hémoptysie, troubles de la voix | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | 46 (commun 05+06) | 5,1 % | P2 | S3 | — | selon date de C1 | ⬜ | 28/11 · 05/12 |
| SEM07 | Examen physique de l'appareil respiratoire I | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | 27 (commun 07+08) | 3,0 % | P3 | S3 | — | selon date de C1 | ⬜ | 28/11 · 05/12 |
| SEM08 | Examen physique de l'appareil respiratoire II | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | 27 (commun 07+08) | 3,0 % | P3 | S4 | — | selon date de C1 | ⬜ | 28/11 · 05/12 |
| SEM09 | Explorations respiratoires | Sémiologie | Respiratoire clinique | ? p. · 1 bloc | à évaluer | 22 | 2,5 % | P2 | S4 | — | selon date de C1 | ⬜ | 28/11 · 05/12 |
| SEM10 | Étude synthétique de l'appareil respiratoire | Sémiologie | Respiratoire clinique | ? p. · 2 blocs (synthèse) | à évaluer | 73 | 8,2 % | P1 | S4 | — | selon date de C1 | ⬜ | 29/11 · 05/12 |
| SEM11 | Hémodynamique intracardiaque | Sémiologie | Chocs & cœur aigu | ? p. · 1 bloc | à évaluer | non indiquée | — | P2 (défaut) | S5 | — | selon date de C1 | ⬜ | 02/12 · 06/12 |
| SEM12 | SF cardiaques I : dyspnée, précordialgies | Sémiologie | Cœur clinique | ? p. · 1 bloc | à évaluer | 36 (commun 12+13) | 4,0 % | P3 | S5 | — | selon date de C1 | ⬜ | 02/12 · 06/12 |
| SEM13 | SF cardiaques II : palpitations, syncopes, lipothymies | Sémiologie | Cœur clinique | ? p. · 1 bloc | à évaluer | 36 (commun 12+13) | 4,0 % | P3 | S5 | — | selon date de C1 | ⬜ | 02/12 · 06/12 |
| SEM14 | Signes physiques cardiaques I : palpation, inspection | Sémiologie | Cœur clinique | ? p. · 1 bloc | à évaluer | 48 (commun 14+15) | 5,4 % | P2 | S6 | — | selon date de C1 | ⬜ | 02/12 · 06/12 |
| SEM15 | Signes physiques cardiaques II : percussion, auscultation | Sémiologie | Cœur clinique | ? p. · 1 bloc | à évaluer | 48 (commun 14+15) | 5,4 % | P2 | S6 | — | selon date de C1 | ⬜ | 02/12 · 06/12 |
| SEM16 | Sémiologie artérielle et veineuse | Sémiologie | Vaisseaux & athérosclérose | ? p. · 1,5–2 blocs | à évaluer | 39 | 4,4 % | P1 | S7 | — | selon date de C1 | ⬜ | 03/12 · 06/12 |
| SEM17 | Exploration cardiaque | Sémiologie | Cœur clinique | ? p. · ½ bloc (C1 ciblée) | à évaluer | 2 | 0,2 % | P4 | S7 | — | selon date de C1 | ⬜ | 03/12 · 06/12 |
| SEM18 | Étude synthétique de l'appareil cardio-vasculaire | Sémiologie | Cœur clinique | ? p. · 2 blocs (synthèse) | à évaluer | 37 | 4,1 % | P1 | S8 | — | selon date de C1 | ⬜ | 03/12 · 06/12 |
| PHY01 | Choc hypovolémique | Physiopathologie | Volume, eau & sodium | ? p. · 1 bloc | à évaluer | 13 | 1,5 % | P3 | S1 · 08/10 | — | C2 09/10 | ⬜ | 26/11 · 07/12 |
| PHY02 | Choc cardiogénique | Physiopathologie | Chocs & cœur aigu | ? p. · 1 bloc | à évaluer | 22 | 2,5 % | P2 | S2 · 10/10 | — | C2 12/10 | ⬜ | 26/11 · 07/12 |
| PHY03 | Insuffisance cardiaque aiguë | Physiopathologie | Chocs & cœur aigu | ? p. · 1 bloc | à évaluer | 18 | 2,0 % | P3 | S2 · 12/10 | — | C2 14/10 | ⬜ | 26/11 · 07/12 |
| PHY04 | Choc anaphylactique | Physiopathologie | Chocs & cœur aigu | ? p. · 1 bloc | à évaluer | 20 | 2,2 % | P2 | S3 | — | selon date de C1 | ⬜ | 26/11 · 07/12 |
| PHY05 | Choc septique | Physiopathologie | Fièvre & infection | ? p. · 1 bloc | à évaluer | 23 | 2,6 % | P2 | S4 | — | selon date de C1 | ⬜ | 26/11 · 07/12 |
| PHY06 | Thermorégulation | Physiopathologie | Fièvre & infection | ? p. · 1 bloc | à évaluer | 18 | 2,0 % | P3 | S4 | — | selon date de C1 | ⬜ | 30/11 · 07/12 |
| PHY07 | Troubles hydro-sodés | Physiopathologie | Volume, eau & sodium | ? p. · 1,5–2 blocs | à évaluer | 36 | 4,0 % | P1 | S5 | — | selon date de C1 | ⬜ | 30/11 · 07/12 |
| PHY08 | Hypertension artérielle | Physiopathologie | Vaisseaux & athérosclérose | ? p. · 1 bloc | à évaluer | 17 | 1,9 % | P3 | S6 | — | selon date de C1 | ⬜ | 30/11 · 07/12 |
| PHY09 | Maladie thromboembolique | Physiopathologie | Vaisseaux & athérosclérose | ? p. · 1 bloc | à évaluer | 18 | 2,0 % | P3 | S7 | — | selon date de C1 | ⬜ | 30/11 · 07/12 |
| RAD01 | Tube à rayons X, formation de l'image radiologique | Radiologie | Imagerie : bases & techniques | ? p. · 1 bloc | à évaluer | 19 | 2,1 % | P3 | S3 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| RAD02 | Initiation à l'imagerie en coupe : TDM et IRM | Radiologie | Imagerie : bases & techniques | ? p. · 1 bloc | à évaluer | 15 | 1,7 % | P3 | S4 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| RAD03 | Échographie | Radiologie | Imagerie : bases & techniques | ? p. · 1 bloc | à évaluer | 15 | 1,7 % | P3 | S5 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| RAD04 | Exploration du cœur et des gros vaisseaux | Radiologie | Imagerie : bases & techniques | ? p. · ½ bloc (C1 ciblée) | à évaluer | 3 | 0,3 % | P4 | S5 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| RAD05 | Techniques d'examens radiologiques du thorax | Radiologie | Imagerie : bases & techniques | ? p. · 1 bloc | à évaluer | 26 | 2,9 % | P2 | S6 | — | selon date de C1 | ⬜ | 29/11 · 08/12 |
| RAD06 | Anatomie lobaire et segmentaire | Radiologie | Thorax : imagerie, plèvre & épanchements | ? p. · 1 bloc | à évaluer | 15 | 1,7 % | P3 | S7 | — | selon date de C1 | ⬜ | 29/11 · 08/12 |
| RAD07 | Signe du bronchogramme aérique | Radiologie | Thorax : imagerie, plèvre & épanchements | ? p. · 1 bloc | à évaluer | 12 | 1,3 % | P3 | S7 | — | selon date de C1 | ⬜ | 29/11 · 08/12 |
| RAD08 | Signe de la silhouette | Radiologie | Thorax : imagerie, plèvre & épanchements | ? p. · 1 bloc | à évaluer | 21 | 2,3 % | P2 | S8 | — | selon date de C1 | ⬜ | 29/11 · 08/12 |
| RAD09 | Atélectasie lobaire et segmentaire | Radiologie | Thorax : imagerie, plèvre & épanchements | ? p. · 1 bloc | à évaluer | 19 | 2,1 % | P3 | S8 | — | selon date de C1 | ⬜ | 03/12 · 08/12 |
| RAD10 | Pathologie pleurale et extra-pleurale | Radiologie | Thorax : imagerie, plèvre & épanchements | ? p. · ½ bloc (C1 ciblée) | à évaluer | 8 | 0,9 % | P4 | S8 | — | selon date de C1 | ⬜ | 03/12 · 08/12 |
| BIO01 | Biochimie de l'homme sain | Biochimie | Volume, eau & sodium | ? p. · 1 bloc | à évaluer | 13 | 1,5 % | P3 | S3 | — | selon date de C1 | ⬜ | 27/11 · 08/12 |
| BIO02 | Biomarqueurs cardiaques | Biochimie | Chocs & cœur aigu | ? p. · 1 bloc | à évaluer | 24 | 2,7 % | P2 | S3 | — | selon date de C1 | ⬜ | 27/11 · 08/12 |
| BIO03 | L'acte biochimique et pièges d'interprétation | Biochimie | Biologie : interprétation | ? p. · ½ bloc (C1 ciblée) | à évaluer | 9 | 1,0 % | P4 | S5 | — | selon date de C1 | ⬜ | 27/11 · 08/12 |
| BIO04 | Dyslipidémies et athérosclérose | Biochimie | Vaisseaux & athérosclérose | ? p. · 1,5–2 blocs | à évaluer | 35 | 3,9 % | P1 | S6 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| BIO05 | Stress oxydant | Biochimie | Vaisseaux & athérosclérose | ? p. · 1 bloc | à évaluer | 21 | 2,3 % | P2 | S7 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| BIO06 | Liquides d'épanchement | Biochimie | Thorax : imagerie, plèvre & épanchements | ? p. · 1 bloc | à évaluer | 13 | 1,5 % | P3 | S8 | — | selon date de C1 | ⬜ | 01/12 · 08/12 |
| PSY01 | Aspects communicationnels de la rencontre avec le malade et sa famille, examen mental | Psychologie | Rencontre avec le patient | ? p. · 1 bloc | à évaluer | 24 | 2,7 % | P2 | S2 (bonus) · 14/10 | — | C2 16/10 | ⬜ | 27/11 · 04/12 |
| PSY02 | Problèmes particuliers de l'entrevue | Psychologie | Rencontre avec le patient | ? p. · 1 bloc | à évaluer | 11 | 1,2 % | P3 | S5 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |
| PSY03 | Stress et maladies psychosomatiques | Psychologie | Rencontre avec le patient | ? p. · ½ bloc (C1 ciblée) | à évaluer | 7 | 0,8 % | P4 | S6 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |
| PSY04 | Fonctionnement de la personnalité | Psychologie | Rencontre avec le patient | ? p. · 1 bloc | à évaluer | 11 | 1,2 % | P3 | S7 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |
| PSY05 | Psychologie de la prescription | Psychologie | Prescription & douleur | ? p. · ½ bloc (C1 ciblée) | à évaluer | 4 | 0,4 % | P4 | S8 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |
| PSY06 | Psychologie de la douleur | Psychologie | Prescription & douleur | ? p. · ½ bloc (C1 ciblée) | à évaluer | 7 | 0,8 % | P4 | S8 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |
| PSY07 | L'annonce d'une maladie grave | Psychologie | Rencontre avec le patient | ? p. · ½ bloc (C1 ciblée) | à évaluer | 4 | 0,4 % | P4 | S8 | — | selon date de C1 | ⬜ | 27/11 · 04/12 |

### 12.2 Tableau de progression — UEI 1

| Matière | Cours | État | Volume | Couche 1 | Couche 2 | Couche 3 | Couche 4 | Flashcards | QCM | Maîtrise |
|---|---|---|---|---|---|---|---|---|---|---|
| Sémiologie | SEM01 Introduction à la sémiologie médicale + anamnèse | 🟡 | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM02 Sémiologie pondérale | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM03 Fièvre | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM04 Topographie du thorax | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM05 SF respiratoires I : dyspnée, douleurs thoraciques | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM06 SF respiratoires II : toux, expectoration, vomique, hémoptysie, troubles de la voix | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM07 Examen physique de l'appareil respiratoire I | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM08 Examen physique de l'appareil respiratoire II | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM09 Explorations respiratoires | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM10 Étude synthétique de l'appareil respiratoire | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM11 Hémodynamique intracardiaque | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM12 SF cardiaques I : dyspnée, précordialgies | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM13 SF cardiaques II : palpitations, syncopes, lipothymies | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM14 Signes physiques cardiaques I : palpation, inspection | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM15 Signes physiques cardiaques II : percussion, auscultation | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM16 Sémiologie artérielle et veineuse | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Sémiologie | SEM17 Exploration cardiaque | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Sémiologie | SEM18 Étude synthétique de l'appareil cardio-vasculaire | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY01 Choc hypovolémique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY02 Choc cardiogénique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY03 Insuffisance cardiaque aiguë | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY04 Choc anaphylactique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY05 Choc septique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY06 Thermorégulation | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY07 Troubles hydro-sodés | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY08 Hypertension artérielle | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Physiopathologie | PHY09 Maladie thromboembolique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD01 Tube à rayons X, formation de l'image radiologique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD02 Initiation à l'imagerie en coupe : TDM et IRM | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD03 Échographie | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD04 Exploration du cœur et des gros vaisseaux | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Radiologie | RAD05 Techniques d'examens radiologiques du thorax | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD06 Anatomie lobaire et segmentaire | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD07 Signe du bronchogramme aérique | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD08 Signe de la silhouette | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD09 Atélectasie lobaire et segmentaire | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Radiologie | RAD10 Pathologie pleurale et extra-pleurale | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Biochimie | BIO01 Biochimie de l'homme sain | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Biochimie | BIO02 Biomarqueurs cardiaques | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Biochimie | BIO03 L'acte biochimique et pièges d'interprétation | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Biochimie | BIO04 Dyslipidémies et athérosclérose | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Biochimie | BIO05 Stress oxydant | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Biochimie | BIO06 Liquides d'épanchement | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Psychologie | PSY01 Aspects communicationnels de la rencontre avec le malade et sa famille, examen mental | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Psychologie | PSY02 Problèmes particuliers de l'entrevue | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Psychologie | PSY03 Stress et maladies psychosomatiques | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Psychologie | PSY04 Fonctionnement de la personnalité | ⬜ | ? p. | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| Psychologie | PSY05 Psychologie de la prescription | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Psychologie | PSY06 Psychologie de la douleur | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |
| Psychologie | PSY07 L'annonce d'une maladie grave | ⬜ | ? p. | ☐ | ☐ | ☐ | — (flash) | ☐ | ☐ | –/3 |

### 12.3 Tableau central + progression — UEI 2 Neuro-locomoteur-cutané

*Enseignement 14/12/2026 → 05/02/2027 · révision 05/02 → 11/02 · **examen jeu 11/02/2027** · recouchage J-14 dès **jeu 28/01/2027**. **La liste des cours de l'UEI 2 n'est pas dans tes sources** : la structure est prête (même colonnes que l'UEI 1), envoie la fiche et je la remplis.*

| ID | Cours | Matière | Volume | Difficulté | Tombabilité | Priorité | État | C1 | C2 | C3 | C4 | Flashcards | QCM | Maîtrise | Prochaine révision |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| UEI2-01 | *à compléter* |  |  |  |  |  | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |  |
| UEI2-02 | *à compléter* |  |  |  |  |  | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |  |

### 12.4 Tableau central + progression — Modules (ordre du parcours thématique)

*Tombabilité : non indiquée dans les sources pour les trois modules. VIR = Virologie, BAC = Bactériologie.*

| # | Cours | Module | Thème | Semaine | État | C1 | C2 | C3 | C4 | Flashcards | QCM | Maîtrise |
|---:|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | PHA01 Introduction à la pharmacologie | Pharmacologie | T01 Fondations pharmaco | S3 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 2 | PHA02 ADME | Pharmacologie | T01 Fondations pharmaco | S4 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 3 | PHA03 Pharmacocinétique | Pharmacologie | T01 Fondations pharmaco | S5 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 4 | PHA04 Pharmacodynamie | Pharmacologie | T01 Fondations pharmaco | S6 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 5 | BAC01 Introduction au monde microbien | Microbiologie | T02 Bases bactériennes | S3 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 6 | BAC02 Structure bactérienne | Microbiologie | T02 Bases bactériennes | S4 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 7 | BAC05 Physiologie bactérienne | Microbiologie | T02 Bases bactériennes | S5 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 8 | BAC06 Génétique bactérienne | Microbiologie | T02 Bases bactériennes | S6 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 9 | PAR01 Introduction à la parasitologie | Parasitologie | T03 Hôte ↔ microbes | S4 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 10 | BAC03 Microbiote humain | Microbiologie | T03 Hôte ↔ microbes | S7 (sam 14/11) | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 11 | BAC04 Manifestation du conflit hôte–bactérie | Microbiologie | T03 Hôte ↔ microbes | 12/12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 12 | PAR02 Amibes, amoebose, amibes libres | Parasitologie | T04 Protozoaires intestinaux | S5 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 13 | PAR03 Flagellés intestinaux et urogénitaux, ciliés | Parasitologie | T04 Protozoaires intestinaux | S6 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 14 | PAR04 Cryptosporidiose, isosporose, sarcocystose, cyclosporose, blastocytose | Parasitologie | T04 Protozoaires intestinaux | S7 (dim 15/11) | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 15 | PHA08 Présentation du SNA | Pharmacologie | T05 SNA I — cœur & vaisseaux | 13/12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 16 | PHA09 Sympathomimétiques | Pharmacologie | T05 SNA I — cœur & vaisseaux | 13/12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 17 | PHA10 Sympatholytiques | Pharmacologie | T05 SNA I — cœur & vaisseaux | S11 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 18 | VIR01 Virus : définition, structure et classification | Microbiologie | T06 Virus : bases | S11 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 19 | VIR02 Multiplication des virus dans l'organisme | Microbiologie | T06 Virus : bases | S11 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 20 | VIR03 Physiopathologie des infections virales | Microbiologie | T06 Virus : bases | S11 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 21 | PAR07 Plasmodiums – paludisme | Parasitologie | T07 Fièvre & paludisme | S11 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 22 | BAC07 Les antibiotiques : classification | Microbiologie | T08 Antibiotiques (Micro + Pharma) | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 23 | PHA14 Introduction à l'étude des antibiotiques | Pharmacologie | T08 Antibiotiques (Micro + Pharma) | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 24 | PHA15 Les antibiotiques | Pharmacologie | T08 Antibiotiques (Micro + Pharma) | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 25 | BAC08 Les antibiotiques : résistance | Microbiologie | T08 Antibiotiques (Micro + Pharma) | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 26 | BAC09 Rôle du laboratoire dans le suivi du traitement antibiotique | Microbiologie | T08 Antibiotiques (Micro + Pharma) | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 27 | PHA05 Toxicologie générale | Pharmacologie | T09 Toxicité & vigilance | S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 28 | PHA06 Effets secondaires et médicaments | Pharmacologie | T09 Toxicité & vigilance | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 29 | PHA07 Pharmacovigilance | Pharmacologie | T09 Toxicité & vigilance | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 30 | BAC15 Cocci à Gram (+) et Gram (–) | Microbiologie | T10 Peau & muqueuses | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 31 | VIR04 Virus à ADN (I) : herpesviridae | Microbiologie | T10 Peau & muqueuses | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 32 | PAR17 Introduction à la mycologie | Parasitologie | T10 Peau & muqueuses | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 33 | PAR18 Candida – candidoses, malasseziose | Parasitologie | T10 Peau & muqueuses | S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 34 | PAR20 Dermatophytes – dermatophyties | Parasitologie | T10 Peau & muqueuses | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 35 | PAR22 Mycétomes, sporotrichose | Parasitologie | T10 Peau & muqueuses | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 36 | VIR05 Virus à ADN (II) : adénovirus, papillomavirus, hepadnavirus | Microbiologie | T10 Peau & muqueuses | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 37 | PHA11 Parasympathomimétiques | Pharmacologie | T11 SNA II — neuro & muscle | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 38 | PHA12 Parasympatholytiques | Pharmacologie | T11 SNA II — neuro & muscle | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 39 | PHA13 Myorelaxants | Pharmacologie | T11 SNA II — neuro & muscle | S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 40 | PAR16 Notion d'entomologie médicale | Parasitologie | T12 Vecteurs & protozoaires sanguins/tissulaires | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 41 | PAR05 Flagellés sanguicoles et tissulaires I : leishmanies et leishmanioses | Parasitologie | T12 Vecteurs & protozoaires sanguins/tissulaires | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 42 | PAR06 Flagellés sanguicoles et tissulaires II : trypanosomes – trypanosomoses | Parasitologie | T12 Vecteurs & protozoaires sanguins/tissulaires | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 43 | PAR08 Toxoplasme – toxoplasmose | Parasitologie | T12 Vecteurs & protozoaires sanguins/tissulaires | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 44 | VIR08 Virus à ARN (III) : orthomyxoviridae, paramyxoviridae | Microbiologie | T13 Virus respiratoires & éruptifs | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 45 | PHA16 Les anti-inflammatoires non stéroïdiens | Pharmacologie | T14 Inflammation, allergie & hormones | S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 46 | PHA17 Les corticoïdes | Pharmacologie | T14 Inflammation, allergie & hormones | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 47 | PHA18 Les antidiabétiques | Pharmacologie | T14 Inflammation, allergie & hormones | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 48 | PHA19 Les antihistaminiques | Pharmacologie | T14 Inflammation, allergie & hormones | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 49 | PAR09 Généralités sur les helminthes, cestodes adultes | Parasitologie | T15 Plathelminthes (cestodes & trématodes) | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 50 | PAR10 Cestodes à l'état larvaire | Parasitologie | T15 Plathelminthes (cestodes & trématodes) | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 51 | PAR11 Douves – distomatoses | Parasitologie | T15 Plathelminthes (cestodes & trématodes) | S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 52 | PAR12 Schistosomes – schistosomoses | Parasitologie | T15 Plathelminthes (cestodes & trématodes) | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 53 | BAC16 Bacilles à Gram (–) I : entérobactéries, Pseudomonas, vibrionaceae | Microbiologie | T16 Bactéries pathogènes (agents) | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 54 | BAC17 Bacilles à Gram (–) II : Haemophilus, Bordetella, Brucella, Campylobacter, Helicobacter, légionelles | Microbiologie | T16 Bactéries pathogènes (agents) | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 55 | BAC18 Bacilles à Gram (+) : Listeria, Corynebacterium, Bacillus, mycobactéries | Microbiologie | T16 Bactéries pathogènes (agents) | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 56 | BAC11 Les bactéries anaérobies | Microbiologie | T16 Bactéries pathogènes (agents) | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 57 | PAR13 Nématodes à transmission per-os | Parasitologie | T17 Nématodes | S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 58 | PAR14 Nématodes à transmission transcutanée | Parasitologie | T17 Nématodes | S18 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 59 | PAR15 Filaires – filarioses | Parasitologie | T17 Nématodes | S18 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 60 | VIR06 Virus à ARN (I) : virus des hépatites C, A, D et E | Microbiologie | T18 Virus à ARN & hépatites | S18 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 61 | VIR07 Virus à ARN (II) : picornaviridae, rétroviridae | Microbiologie | T18 Virus à ARN & hépatites | S18 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 62 | PAR19 Cryptococcose, pneumocystose, microsporidioses | Parasitologie | T19 Mycoses profondes | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 63 | PAR21 Aspergillus – aspergilloses | Parasitologie | T19 Mycoses profondes | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 64 | PAR23 Histoplasmoses, blastomycoses, coccidioïdomycose, paracoccidioïdomycose | Parasitologie | T19 Mycoses profondes | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 65 | PAR24 Mucormycoses, fusarioses, zygomycoses | Parasitologie | T19 Mycoses profondes | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 66 | BAC10 Antiseptiques, désinfectants et stérilisation | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S12 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 67 | BAC12 Les vaccins bactériens | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S13 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 68 | BAC13 Hygiène hospitalière | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S14 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 69 | BAC14 Biosécurité et biosûreté dans un laboratoire de microbiologie | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S15 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 70 | VIR10 Traitement et prévention des infections virales | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S16 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 71 | BAC19 Diagnostic bactériologique | Microbiologie | T20 Prévention, hygiène & diagnostic | Ven S17 | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 72 | VIR09 Diagnostic virologique | Microbiologie | T20 Prévention, hygiène & diagnostic | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |
| 73 | PAR25 SIDA et parasitoses, SIDA et mycoses | Parasitologie | T21 Immunodéprimé (synthèse) | ⚠️ Sans créneau | ⬜ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | –/3 |

### 12.5 Tableau de bord hebdomadaire (à remplir chaque vendredi)

| Semaine | Dates | Phase | Objectif principal | Unité (nouveaux) | Modules (nouveaux) | Faits | C2 | C3 | Flashcards /7 | QCM % | 🔥 | Repos | Énergie | Décision |
|---|---|---|---|---:|---:|---|---|---|---|---|---|---|---|---|
| **S1** | 07/10 → 08/10 (reprise après chirurgie) | A · Convalescence | Mise en place + SEM01 + PHY01 · séances de 30–45 min | 2 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **S2** | 09/10 → 15/10 | A' · Reprise progressive (~75 %) | 5 cours (+ PSY01 en bonus) · pas encore de modules | 6 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **S3** | 16/10 → 22/10 | B · Montée | 7 cours Cardio · démarrage des modules (PHA01, BAC01) | 7 | 2 |  |  |  |  |  |  | ☐ |  |  |
| **S4** | 23/10 → 29/10 | B · Montée | SEM10 (P1, 73) en 2 blocs · Infection & température · synchro avec l'hôpital | 6 | 3 |  |  |  |  |  |  | ☐ |  |  |
| **S5** | 30/10 → 05/11 | C · Croisière + avance | Dim 01/11 férié = jour fort → PHY07 (P1) · semaine Cardio la plus dense (8 cours dont 3 légers) | 8 | 3 |  |  |  |  |  |  | ☐ |  |  |
| **S6** | 06/11 → 12/11 | C · Croisière + avance | BIO04 (P1) · examen physique du cœur · HTA | 6 | 3 |  |  |  |  |  |  | ☐ |  |  |
| **S7** | 13/11 → 19/11 | C' · Arrêt des modules mi-S7 | Modules jusqu'au dim 15/11 puis STOP · temps libéré → C3 anticipées | 7 | 2 |  |  |  |  |  |  | ☐ |  |  |
| **S8** | 20/11 → 26/11 | C' · Fin des C1 + C3 | 8 dernières C1 (dont 4 légères) avant mer 25/11 · jeu 26/11 = J-14 : début du recouchage · réserve : démarrer le recouchage sam 28/11 (J-12) | 8 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **S9** | 27/11 → 03/12 | D · Recouchage passage 1 (C3) | Repasser TOUTE l'unité en C3 + 6 cas cliniques | 0 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **S10** | 04/12 → 09/12 · EXAMEN jeu 10/12 | E · Recouchage passage 2 (C4) | C4 complète + passage éclair P1 · examen jeu 10/12 | 0 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **S11** | 11/12 → 17/12 | Repos + sprint modules + début UEI2 (lun 14/12) | Ven 11/12 repos · 12–13/12 : fin Hôte ↔ microbes + SNA I · puis virus (bases) + paludisme | ? | 8 |  |  |  |  |  |  | ☐ |  |  |
| **S12** | 18/12 → 24/12 | UEI2 + modules | Antibiotiques (Micro + Pharma) · Toxicité & vigilance · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S13** | 25/12 → 31/12 | UEI2 + modules | Toxicité & vigilance · Peau & muqueuses · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S14** | 01/01 → 07/01 (01/01 férié) | UEI2 + modules | Peau & muqueuses · SNA II — neuro & muscle · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S15** | 08/01 → 14/01 (12/01 férié) | UEI2 + modules | Vecteurs & protozoaires sanguins/tissulaires · Virus respiratoires & éruptifs · Inflammation, allergie & hormones · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S16** | 15/01 → 21/01 | UEI2 + modules | Inflammation, allergie & hormones · Plathelminthes (cestodes & trématodes) · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S17** | 22/01 → 28/01 | UEI2 + modules · J-14 UEI2 jeu 28/01 | Plathelminthes (cestodes & trématodes) · Bactéries pathogènes (agents) · Nématodes · Prévention, hygiène & diagnostic | ? | 7 |  |  |  |  |  |  | ☐ |  |  |
| **S18** | 29/01 → 04/02 | Recouchage UEI2 + modules 1 bloc/j | Nématodes · Virus à ARN & hépatites | 0 | 4 |  |  |  |  |  |  | ☐ |  |  |
| **⚠️ À placer** | — | Sans créneau | Vacances · stats Medspace des modules · allègement (C1 ciblée) | 0 | 6 |  |  |  |  |  |  | ☐ |  |  |
| **S19** | 05/02 → 11/02 · EXAMEN UEI2 jeu 11/02 | Révision UEI2 + modules 1 bloc/j | C4 UEI2 · modules C3 courtes | 0 | 0 |  |  |  |  |  |  | ☐ |  |  |
| **Examens modules** | 12/02 → 18/02 | C4 modules | Micro dim 14/02 · Pharma mar 16/02 · Para jeu 18/02 | 0 | 0 |  |  |  |  |  |  | ☐ |  |  |

### 12.6 Trackers des modules

Chaque module a sa page dans `notion/` : **objectifs chiffrés par jalon**, règles du module, **parcours thématique en cases à cocher**, suivi par couches, plan de fin de semestre, tableaux comparatifs à produire.

| Module | Au 15/11 (arrêt) | Au 13/12 | Au 31/12 | Au 14/01 | Au 27/01 | Au 04/02 | Sans créneau | Examen |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| Microbiologie | 5/29 | 6/29 | 16/29 | 20/29 | 26/29 | 28/29 | 1 | **dim 14/02** |
| Pharmacologie | 4/19 | 6/19 | 12/19 | 16/19 | 19/19 | 19/19 | 0 | **mar 16/02** |
| Parasitologie | 4/25 | 4/25 | 7/25 | 13/25 | 18/25 | 20/25 | 5 | **jeu 18/02** |

### 12.7 Journal quotidien (modèle)

```
Date :            Type de jour : FAIBLE / FORT / SOIR / SOUPLE / STAGE
Vu à l'hôpital :  ...
Étudié (C1) :     ...            Difficulté ressentie (1–3) :
Révisé (C2/C3) :  ...            QCM : ..../.... (...%)
Flashcards :      ☐ créées  ☐ complétées  ☐ révisées
Non fait :        ...  → envoyé au tampon / vendredi
Énergie (1–3) :
```

---

## PARTIE 13 — RÈGLES DYNAMIQUES

### 13.1 Le moteur du système

1. **Files d'attente par matière** : chaque matière a sa liste ordonnée (Parties 5–6). Si l'hôpital change l'ordre → on **réordonne la file**, pas la semaine.
2. **Créneaux typés** (Partie 7) : chaque créneau prend le **prochain cours de la file** de sa matière.
3. **Révisions calculées depuis la date de C1** (Partie 9) : elles se placent dans le créneau de révision le plus proche de la date cible (±1 jour accepté).
4. **Capacité fixe** : 14 blocs/semaine en mode semestre. Si un ajout dépasse la capacité → il remplace l'élément **le moins prioritaire** (P4, puis Psy, puis C2 de module hors Para), jamais la Sémio, jamais les flashcards, jamais le repos.

### 13.2 Que faire quand…

| Événement | Règle |
|---|---|
| **« Aujourd'hui, j'ai vu le cours X à l'hôpital »** | Si X est déjà en C1+ → l'hôpital compte comme **renforcement** : note les points nouveaux, le C2 suivant peut être repoussé de 2 jours si tout était connu. Si X n'est pas encore étudié → statut **🟡**, X passe **en tête de file** et prend le prochain créneau de sa matière (dans les 48 h). |
| **« Je n'ai pas fait le cours prévu »** | Pas de décalage global. Ordre : ① tampon du jeudi matin ② vendredi (si le cours est léger) ③ remplace l'élément le moins prioritaire des 3 jours suivants. Après 2 reports → réévaluer la charge de la semaine. |
| **Cours d'une autre matière fait plus tôt** | On échange les deux créneaux. Les révisions suivent la nouvelle date de C1. |
| **Stage annoncé** | Appliquer la Partie 8. |
| **Journée peu productive** | **Mode minimum** : 1 bloc de révision (ou 1 cours P4) + flashcards. Le nouveau cours → tampon. Ce n'est pas un échec, c'est prévu. |
| **Cours très bien maîtrisé** (QCM ≥ 85 % deux fois) | Retiré temporairement des révisions ; seulement flashcards jusqu'à la C4. |
| **Cours difficile** (difficulté 3 ou 🔥) | C1 coupée en 2 jours · C2 bis à J+2 · monte d'un niveau de priorité. |
| **Pages relevées** | Volume faible → ½ bloc ; élevé → 2 blocs sur 2 jours ; je recalcule les semaines. |
| **Retard > 1 semaine dans une matière** | Le créneau Bio/Psy du dimanche passe à la matière en retard (pondérée par son poids) jusqu'au rattrapage. |
| **Vacances annoncées** | Mode vacances (Partie 6.5). |
| **Mi-S7** (lun 16/11) | **Arrêt total des modules** jusqu'au 10/12. Créneaux modules → C3 Cardio. |
| **J-14** (jeu 26/11) | Plus aucun nouveau cours ; recouchage en 2 passages (C3 puis C4). Si une C1 n'est pas finie le 25/11 : C1 ciblée le 26/11 au lieu de sa C3. |

### 13.3 Contrôle automatique de chaque semaine (avant de la valider)

☐ ≤ 3 cours par jour (4 seulement si révision de petits cours) · ☐ pas 2 P1 nouveaux le même soir · ☐ vendredi sans cours P1 · ☐ C2 de chaque cours de la semaine placée · ☐ flashcards chaque jour · ☐ aucune matière/module oublié(e) depuis plus de 7 jours (Para : plus de 4 jours) · ☐ jour de stage ≤ 1 bloc · ☐ révisions ni trop proches (< J+1) ni trop éloignées (> J+14 sans flashcards) · ☐ ≤ 10 nouveaux cours · ☐ repos ≥ 1 jour · ☐ temps Sémio ≈ 39 % du temps Cardio, Psycho ≈ 11 %.

### 13.4 Comment me redonner la main

Envoie-moi simplement, par exemple :

> « S2 — vu à l'hôpital : SEM05, PHY03, Micro : Introduction au monde microbien. Étudié : PHY03 (C1, QCM 70 %, difficulté 2), SEM04 (C1). Pas fait : RAD01. Stage jeudi prochain matin. Pages : PHY03 = 18 p., SEM05 = 30 p. »

→ je recalcule les files, les révisions et la semaine suivante.

---

## VÉRIFICATION CRITIQUE FINALE

> **« Est-ce que ce planning est réellement tenable pour un étudiant de médecine, ou est-ce simplement un planning qui paraît beau sur le papier ? »**

**Charge réelle :** ~14 blocs ≈ 17–18 h + ~2 h de flashcards ≈ **20 h/semaine d'étude personnelle**, en plus de ~30 h d'hôpital et d'amphis. C'est **exigeant mais tenable**, à trois conditions : (1) les soirs restent à 2 blocs maximum, (2) le samedi est une vraie journée de travail, (3) le repos (jeudi soir, vendredi matin, samedi soir) n'est jamais sacrifié deux semaines de suite.

**Ce que j'ai simplifié parce que c'était trop chargé :**
1. **Abandon de l'avance totale.** Être en avance sur les 8 matières en partant de zéro = ~10 nouveaux cours/semaine + révisions → non tenable avec qualité. Avance ciblée : Sémio et Physio d'abord ; Bio/Psy naturellement ; modules au rythme.
2. **Cours P4 en couche 1 ciblée** (½ bloc) : 8 cours de l'UEI qui ont 2 à 9 QCM en 7 ans ne méritent pas le même temps que SEM10 (73).
3. **Le tampon du jeudi n'est jamais pré-rempli** (sauf l'option SEM04 en S1) : sinon il ne peut plus absorber les retards.
4. **Para en séances courtes** plutôt qu'en gros blocs.
5. **Pas de nouveau cours de Cardio en S9–S10** : sans ça, les couches 3–4 n'auraient pas eu de place.

**Points faibles assumés :**
- **S5 et S8 sont les semaines les plus denses** (8 cours de Cardio chacune, dont 3–4 légers) : elles portent le retard de la convalescence. Soupapes : PSY02 → S6 ; en S8, la réserve du recouchage (démarrage à J-12).
- **Les modules ne seront pas en avance au 10/12** (≈ 16/73 au 13/12, à cause de la convalescence et de l'arrêt à mi-S7 ; 6 cours sans créneau). C'est le risque n°1 du semestre : ~6–7 cours de modules/semaine pendant l'UEI 2, examens de février juste après l'UEI 2, probable début de Ramadan. Il faudra des vacances, les stats Medspace des modules, ou la liste de l'UEI 2 pour équilibrer.
- **Convalescence** : le planning de reprise (07/10 → 15/10) est volontairement léger. Si la récupération est plus lente, on étale S2 sur S3 et on utilise la réserve du recouchage (J-12), **jamais** des soirées plus longues.
- **Le gain** : 14 jours pleins de recouchage + ~1,5 semaine de C3 anticipées → chaque cours de Cardio passe au moins 4 fois (C1, C2, C3, C4), les P1 5 fois (+ passage éclair).
- **Le volume réel (pages) est inconnu** : le temps par cours est provisoire jusqu'à ton relevé de vendredi.

**Version de survie** (semaine malade / imprévu) : Sémio ×2 + Physio ×1 + 1 module (priorité Para) + flashcards chaque jour. On coupe dans cet ordre : Psycho → P4 → C2 des modules (sauf Para) → Radio P3. **On ne coupe jamais : Sémio, flashcards, repos.**

---

### Ce qu'il me faut de ta part pour affiner

1. Ta **section** (A/B/C/D) et ton **service de sémiologie** → jours exacts des amphis/sémio.
2. ~~Les cours vus~~ ✅ confirmé : seul SEM01. ~~Premier cours de Micro~~ ✅ : *Introduction au monde microbien* (BAC01) → l'amphi commence par la **bactériologie**, comme le parcours thématique (BAC01 en S3, virologie plus tard).
3. **Le nombre de pages** de chaque cours (relevé de vendredi).
4. Les **dates de stage** et d'éventuelles **vacances** dès qu'elles sont annoncées.
5. Si possible : les **statistiques Medspace des modules** et la **liste des cours de l'UEI 2**.
