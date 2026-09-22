# Liens des bases de données — Variables du modèle

> Un ou plusieurs liens par variable. Pour ajouter plusieurs sources sur une même ligne, les séparer par `<br>` (saut de ligne dans la cellule) ou par ` · `.
> Statuts possibles : 🟢 Trouvé · 🟡 À vérifier · 🔴 Manquant

## A. MORTALITÉ (30%) — 5 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Taux de mortalité générale | https://www.data.gouv.fr/datasets/causes-de-deces| 🟢 | |
| Taux de mortalité prématurée (<75 ans) | | 🔴 | |
| Surmortalité cardiovasculaire | | 🔴 | |
| Surmortalité cancers | | 🔴 | |
| Surmortalité respiratoire | | 🔴 | |

## B. MORBIDITÉ (30%)

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Prévalence diabète | | 🔴 | |
| Prévalence hypertension | | 🔴 | |
| Prévalence surpoids/obésité | | 🔴 | |
| Prévalence BPCO/asthme | | 🔴 | |
| % Population avec au moins 1 maladie chronique | | 🔴 | |

## C. DÉMOGRAPHIE (20%) — 6 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| % Population 65+ | | 🔴 | |
| % Population 75+ | | 🔴 | |
| % Population 85+ | | 🔴 | |
| Taux natalité | | 🔴 | |
| % Population 15-30 ans | | 🔴 | |
| % Population 50+ | | 🔴 | |
| % Population slon l'age| https://www.insee.fr/fr/statistiques/8581696|🟢|cette bd traite la population selon l'age et le sexe |
## D. ACCÈS AUX SOINS (10%) — 2 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Consultations urgence par habitant/an | | 🔴 | |
| Délai moyen attente consultation généraliste | | 🔴 | |

## E. VULNÉRABILITÉ SOCIALE (7%) — 1 variable

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| % Population migrants/étrangers | | 🔴 | |

## F. OFFRE — 6 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Population totale | | 🔴 | |
| Nombre médecins généralistes | | 🔴 | |
| Densité médicale (auto-calc) | — | ⚙️ | Calculée : médecins / population |
| Ratio besoin/offre (auto-calc) | — | ⚙️ | Calculée à partir des scores |
| Ratio besoin/offre  | | 🟢 | indicateur d'accessibilité à la population pour chaque commune en fonction de l'offre et de la demande de soin de premier recours et de l'âge des médecins, prend en compte l'âge de la population et le niveau d’activité des professionnels en exercice  |
| Présence centre de santé |https://defis.data.gouv.fr/datasets/67e43007cd5e91b9fdcbc7b3 | 🟢 | Télécharger l'excel établissement |
| Présence pharmacie | https://defis.data.gouv.fr/datasets/67e43007cd5e91b9fdcbc7b3| 🟢 | Télécharger l'excel établissement|
|nb des centres deja implementes|  https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=e0b99aac-98d0-4626-80bf-a1e95796ea93,https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=7b8218bc-faf9-4660-a8d8-1027e5679f08,https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=cd493959-fb03-41e5-9347-0edd14dfbc22|🟡 | j ai pas encore bien verifie si ces bd contiennent des donnees vraiment utiles
---

# Score Attractivité — Variables

## A. VIABILITÉ ÉCONOMIQUE (20%) — 4 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Budget municipal | | 🔴 | |
| Revenu moyen ménage | https://www.insee.fr/fr/statistiques/8984752 ,,,https://www.insee.fr/fr/statistiques/8229323| 🟢 | |
| Taux chômage | | 🔴 | |
| Prix logement (EUR/m²) | | 🔴 | |

## C. QUALITÉ DE VIE - ÉQUIPEMENTS (15%) — 6 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Nombre écoles primaires | | 🔴 | |
| Nombre collèges-lycées | | 🔴 | |
| Score équipements culturels (cinéma, musée, théâtre, galerie) | | 🔴 | |
| Score commerces essentiels (super, boulangerie, boucherie, pharmacie) | | 🔴 | |
| Nombre restaurants | | 🔴 | |
| Score santé locale (pharmacies, médecins proches) | | 🔴 | |

## D. ENVIRONNEMENT & LOISIRS (15%) — 5 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Distance mer | | 🔴 | |
| Distance montagne/forêt | | 🔴 | |
| Score loisirs/sports (piscine, foot, tennis, gym, rando, kayak, etc.) | | 🔴 | |
| Fréquence événements (marchés, fêtes, concerts) | | 🔴 | |
| Score environnement (pollution air, eau, nature) | | 🔴 | |

## E. ACCESSIBILITÉ & MOBILITÉ (12%) — 4 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Distance ville importante (réseau professionnel) | | 🔴 | |
| Score transport (gare, bus, aéroport) | | 🔴 | |
| Population rayon 15km (bassin de patients) | | 🔴 | |
| Distance hôpital urgent | | 🔴 | |

## F. LOGEMENT & IMMOBILIER (10%) — 2 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Disponibilité logements (% en vente/location) | | 🔴 | |
| | | 🔴 | |
