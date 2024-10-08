# OpenMedic - Analyse des Ventes de Médicaments

Ce dossier contient des analyses basées sur les données fournies par Open Medic. L'objectif est de fournir des insights détaillés sur les ventes de divers médicaments en France et de rechercher des anomalies ou des tendances intéressantes.

## À Propos d'Open Medic

**Open Medic** est une base de données publique qui compile des informations détaillées sur les ventes de médicaments en France. Les données sont collectées à partir de diverses sources, notamment les pharmacies, les hôpitaux et les grossistes. Open Medic vise à fournir une transparence sur les tendances du marché pharmaceutique et à faciliter l'accès à des données de qualité pour les chercheurs, les analystes et les professionnels de santé.

### Ce que Comporte la Base de Données

La base de données Open Medic comprend plusieurs types d'informations :

- **Ventes par Médicament :** Quantités vendues, chiffre d'affaires généré et évolution des ventes.
- **Données Régionales :** Répartition des ventes par région ou département.
- **Périodes de Temps :** Données détaillées par mois et année.
- **Caractéristiques des Médicaments :** Nom du médicament, code ATC, forme galénique, etc.
- **Pharmacies et Grossistes :** Informations sur les points de vente et les canaux de distribution.

## Analyse de la Vente du Duphaston (2017-2023)

**Fichier :** `openmedic_duphaston.ipynb`

### Description

Ce notebook explore les ventes du médicament **Duphaston** en France entre 2017 et 2023, en utilisant les données d'Open Medic. Duphaston est un médicament à base de didrogesterone, souvent prescrit pour traiter les troubles hormonaux et les troubles menstruels.

### Contexte du Médicament

**Duphaston** est un progestatif utilisé principalement dans le traitement des troubles hormonaux tels que les irrégularités menstruelles, les douleurs menstruelles, et comme traitement de soutien pendant la grossesse. Il est également utilisé dans le cadre de thérapies hormonales substitutives.

### Objectifs de l'Analyse

1. **Comprendre les Tendances de Vente :** Analyser les tendances de vente de Duphaston pour identifier les variations saisonnières, les pics de consommation, et les tendances générales.
2. **Détecter des Anomalies :** Identifier des anomalies ou des variations inhabituelles dans les ventes qui pourraient indiquer des problèmes d'approvisionnement, des changements dans les prescriptions ou d'autres facteurs externes.
3. **Comparer avec d'autres Médicaments :** Étendre l'analyse à d'autres médicaments pour identifier des tendances similaires ou différentes, et détecter des anomalies potentielles dans un contexte plus large.

### Étapes de l'Analyse

1. **Chargement et Préparation des Données :** Importation des données spécifiques à Duphaston et nettoyage des données pour l'analyse.
2. **Analyse Exploratoire :** Exploration des données pour identifier les tendances de vente.
3. **Visualisation :** Création de graphiques et de tableaux pour illustrer les tendances et les anomalies.
4. **Interprétation des Résultats :** Analyse des résultats pour tirer des conclusions sur les tendances et anomalies détectées.


## Informations Complémentaires

### Spécialités Médicales

| PSP_SPE | Libellé Prescripteur                                      |
|---------|------------------------------------------------------------|
| 1       | MEDECINE GENERALE LIBERALE                                |
| 2       | ANESTHESIOLOGIE - REANIMATION LIBERALE                    |
| 3       | PATHOLOGIE CARDIO-VASCULAIRE LIBERALE                     |
| 4       | CHIRURGIE LIBERALE                                        |
| 5       | DERMATOLOGIE ET VENEROLOGIE LIBERALE                      |
| 6       | RADIOLOGIE LIBERALE                                       |
| 7       | GYNECOLOGIE OBSTETRIQUE LIBERALE                           |
| 8       | GASTRO-ENTEROLOGIE ET HEPATOLOGIE LIBERALE                 |
| 9       | MEDECINE INTERNE LIBERALE                                 |
| 11      | OTO RHINO-LARYNGOLOGIE LIBERALE                            |
| 12      | PEDIATRIE LIBERALE                                        |
| 13      | PNEUMOLOGIE LIBERALE                                      |
| 14      | RHUMATOLOGIE LIBERALE                                     |
| 15      | OPHTALMOLOGIE LIBERALE                                    |
| 17      | PSYCHIATRIE LIBERALE                                     |
| 18      | STOMATOLOGIE LIBERALE                                     |
| 19      | CHIRURGIE DENTAIRE                                       |
| 31      | MEDECINE PHYSIQUE ET DE READAPTATION LIBERALE              |
| 32      | NEUROLOGIE LIBERALE                                       |
| 35      | NEPHROLOGIE LIBERALE                                      |
| 36      | CHIRURGIE DENTAIRE (SPECIALISTE O.D.F.)                   |
| 37      | ANATOMIE-CYTOLOGIE-PATHOLOGIQUE LIBERALE                   |
| 38      | DIRECTEUR LABORATOIRE MEDECIN LIBERAL                      |
| 42      | ENDOCRINOLOGIE ET METABOLISMES LIBERAL                     |

### Régions et Départements d'Outre-mer

| Code | Libellé                                               |
|------|-------------------------------------------------------|
| 5    | Régions et Départements d'outre-mer                   |
| 11   | Ile-de-France                                         |
| 24   | Centre-Val de Loire                                   |
| 27   | Bourgogne-Franche-Comté                               |
| 28   | Normandie                                             |
| 32   | Nord-Pas-de-Calais-Picardie                           |
| 44   | Alsace-Champagne-Ardenne-Lorraine                     |
| 52   | Pays de la Loire                                     |
| 53   | Bretagne                                              |
| 75   | Aquitaine-Limousin-Poitou-Charentes                   |
| 76   | Languedoc-Roussillon-Midi-Pyrénées                    |
| 84   | Auvergne-Rhône-Alpes                                 |
| 93   | Provence-Alpes-Côte d'Azur et Corse                   |
| 0 et 99 | Inconnu                                             |
