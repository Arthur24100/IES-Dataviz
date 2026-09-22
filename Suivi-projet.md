# Suivi de projet — [Nom du projet]

> Document de suivi : comptes-rendus de réunion + avancement individuel des membres.
> Dernière mise à jour : JJ/MM/AAAA

## Informations générales

| Champ | Détail |
|---|---|
| Nom du projet | |
| Client / Commanditaire | |
| Encadrant(s) | |
| Date de début | |
| Date de fin estimée | |
| Dépôt / outil de gestion | |

## Équipe

| Membre | Rôle | Contact |
|---|---|---|
| Membre 1 | | |
| Membre 2 | | |
| Membre 3 | | |
| Membre 4 | | |
| Membre 5 | | |

## Sommaire des réunions

| # | Date | Sujet principal | Compte-rendu |
|---|---|---|---|
| 1 | 22/09/2026 | Cours 2 Mise au point Sujet | [Aller au CR](#reunion-1) |

---

## Comptes-rendus de réunion

### Réunion 1 — JJ/MM/AAAA {#reunion-1}

#### Ordre du jour
1.
2.
3.

#### Points discutés
- Optimisation spatiale prédictive pour santé publique départementale  
    Où un conseiller régional doit-il placer 2 maisons médicales dans son département pour avoir le plus grand impact sanitaire avec le budget disponible ?

#### Décisions prises
- Choix de 3 départements de Nouvelle-aquitaine

- Faire deux models pour prédire deux score par ville:
    - Score Medicale
        Suivant plusieurs entrées faire un score par ville pour en déduire un score sur 100, les entrés possible sont les suivante :
        Variables d'entrée (catégories) :
        A. MORTALITÉ (30%) - 5 variables
            Taux de mortalité générale
            Taux de mortalité prématurée (<75 ans)
            Surmortalité cardiovasculaire
            Surmortalité cancers
            Surmortalité respiratoire
        B. MORBIDITÉ (30%) 
            Prévalence diabète
            Prévalence hypertension
            Prévalence surpoids/obésité
            Prévalence BPCO/asthme
        % Population avec au moins 1 maladie chronique
        C. DÉMOGRAPHIE (20%) - 6 variables
            % Population 65+
            % Population 75+
            % Population 85+
            Taux natalité
            % Population 15-30 ans
            % Population 50+
        D. ACCÈS AUX SOINS (10%) - 2 variables
            Consultations urgence par habitant/an
            Délai moyen attente consultation généraliste
        E. VULNÉRABILITÉ SOCIALE (7%) - 1 variable
            % Population migrants/étrangers
        F. OFFRE (6 variables) ← NOUVEAU
            Population totale
            Nombre médecins généralistes
            Densité médicale (auto-calc)
            Ratio besoin/offre (auto-calc)
            Présence centre santé
            Présence pharmacie


    - Score Attractivité 
        Suivant plusieurs entrées faire un score par ville pour en déduire un score sur 100, les entrés possible sont les suivante :

            A. VIABILITÉ ÉCONOMIQUE (20%) - 4 variables
                Budget municipal
                Revenu moyen ménage
                Taux chômage
                Prix logement (EUR/m²)
            C. QUALITÉ DE VIE - ÉQUIPEMENTS (15%) - 6 variables
                Nombre écoles primaires
                Nombre collèges-lycées
                Score équipements culturels (cinéma, musée, théâtre, galerie)
                Score commerces essentiels (super, boulangerie, boucherie, pharmacie)
                Nombre restaurants
                Score santé locale (pharmacies, médecins proches)
            D. ENVIRONNEMENT & LOISIRS (15%) - 5 variables
                Distance MER 
                Distance montagne/forêt
                Score loisirs/sports (piscine, foot, tennis, gym, rando, kayak, etc.)
                Fréquence événements (marchés, fêtes, concerts)
                Score environnement (pollution air, eau, nature)
            E. ACCESSIBILITÉ & MOBILITÉ (12%) - 4 variables
                Distance ville importante (réseau professionnel)
                Score transport (gare, bus, aéroport)
                Population rayon 15km (bassin de patients)
                Distance hôpital urgent
            F. LOGEMENT & IMMOBILIER (10%) - 2 variables
                Disponibilité logements (% en vente/location)

- Visualisation
    - Cartes des 3 régions avec pour chaque ville le score médical
    - Cartes des 3 régions avec pour chaque ville le score d'attractivité


#### Actions à réaliser

| Action | Responsable | Échéance | Statut |
|---|---|---|---|
| | | | À faire |


---
