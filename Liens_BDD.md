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
| Prévalence diabète |par département : https://odisse.santepubliquefrance.fr/explore/assets/diabete-prevalence-departement/ <br> https://odisse.santepubliquefrance.fr/explore/assets/diabete-prevalence-france/ <br> https://odisse.santepubliquefrance.fr/explore/assets/diabete-prevalence-region/| 🟢 | premier lien : par département; deuxième lien : pour la france; troisième lien : par région |
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
| Nombre médecins généralistes | https://data.drees.solidarites-sante.gouv.fr/explore/dataset/la-demographie-des-professionnels-de-sante-depuis-2012/information/| |🟢 | |
| Densité médicale (auto-calc) | — | ⚙️ | Calculée : médecins / population |
| Ratio besoin/offre (auto-calc) | — | ⚙️ | Calculée à partir des scores |
| Ratio besoin/offre  |https://defis.data.gouv.fr/datasets/62263314072c63d4d53e0c50 | 🟢 | Télécharger APL médecin généraliste. Indicateur d'accessibilité à la population pour chaque commune en fonction de l'offre et de la demande de soin de premier recours et de l'âge des médecins, prend en compte l'âge de la population et le niveau d’activité des professionnels en exercice  |
| Présence centre de santé |https://defis.data.gouv.fr/datasets/67e43007cd5e91b9fdcbc7b3 | 🟢 | Télécharger l'excel établissement |
| Présence pharmacie | https://defis.data.gouv.fr/datasets/67e43007cd5e91b9fdcbc7b3| 🟢 | Télécharger l'excel établissement|
|nb des centres deja implementes|  https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=e0b99aac-98d0-4626-80bf-a1e95796ea93,https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=7b8218bc-faf9-4660-a8d8-1027e5679f08,https://www.data.gouv.fr/datasets/finess-structures-1?resource_id=cd493959-fb03-41e5-9347-0edd14dfbc22|🟡 | j ai pas encore bien verifie si ces bd contiennent des donnees vraiment utiles
---

# Score Attractivité — Variables

## A. VIABILITÉ ÉCONOMIQUE (20%) — 4 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Budget municipal |https://www.impots.gouv.fr/cll/zf1/cll/zf1/accueil/flux.ex?_flowId=accueilcclloc-flow | 🟢 | lien donnant les données de la région, du département, ou de la commune|
| Revenu moyen ménage | https://www.insee.fr/fr/statistiques/8984752 ,,,https://www.insee.fr/fr/statistiques/8229323| 🟢 | |
| Taux chômage | https://www.insee.fr/fr/statistiques/4805248| 🟢 | |
| Prix logement (EUR/m²) | https://www.data.gouv.fr/datasets/prix-immobilier-par-commune-ventes-2014-a-2025-dvf-millesime-2026| 🟢 | |

## C. QUALITÉ DE VIE - ÉQUIPEMENTS (15%) — 6 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Nombre écoles primaires, maternelles, collèges, lycées | https://www.data.gouv.fr/datasets/adresse-et-geolocalisation-des-etablissements-denseignement-des-premier-et-second-degres| 🟢 | |
| Score équipements culturels (cinéma, musée, théâtre, galerie) | https://www.data.gouv.fr/datasets/base-des-lieux-et-equipements-culturels-basilic | 🟢 | |
| Score commerces essentiels (super, boulangerie, boucherie, pharmacie, restaurant) |https://www.data.gouv.fr/datasets/base-nationale-des-commerces-ouverte | 🟢 | |
| Score santé locale (pharmacies, médecins proches) | | 🔴 | |

## D. ENVIRONNEMENT & LOISIRS (15%) — 5 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Distance mer | | 🔴 | |
| Distance montagne/forêt | https://www.data.gouv.fr/datasets/forets-publiques-diffusion-publique . https://www.data.gouv.fr/datasets/perimetre-de-massif-30382878| 🟢 | premier lien : forêt, deuxième lien : montagne|
| Score loisirs/sports (piscine, foot, tennis, gym, rando, kayak, etc.) | https://equipements.sports.gouv.fr/explore/assets/data-es-equipement/| 🟢 | |
| Fréquence événements (marchés, fêtes, concerts) | | 🔴 | |
| Score environnement (pollution air, eau, nature) | | 🔴 | |

## E. ACCESSIBILITÉ & MOBILITÉ (12%) — 4 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Distance ville importante (réseau professionnel) | | 🔴 | |
| Score transport (gare, bus, aéroport) | https://www.data.gouv.fr/datasets/nombre-de-stations-de-transports-en-commun-selon-le-type-de-reseau | 🟢 | |
| Population rayon 15km (bassin de patients) | https://www.data.gouv.fr/datasets/population-municipale-des-communes-france-entiere | 🟢 | nb de pop pour chaque ville et commune |
| Distance hôpital urgent | | 🔴 | |

## F. LOGEMENT & IMMOBILIER (10%) — 2 variables

| Variable | Lien(s) source | Statut | Notes |
|---|---|---|---|
| Disponibilité logements (% en vente/location) | | 🔴 | |
| | | 🔴 | |
