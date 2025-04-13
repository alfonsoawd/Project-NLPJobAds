# 🔍 Beyond the Salary: Unpacking Job Attributes in French Ads with NLP

---

## Version Française

### Contexte du projet

Ce projet a pour objectif d'analyser les attributs des offres d'emploi en France, en distinguant les caractéristiques liées à la rémunération des avantages non salariaux, en s’appuyant sur des techniques de traitement automatique du langage naturel (NLP) et des méthodes d’apprentissage supervisé.  
Réalisé dans le cadre du cours **Applied Labour Economics** sous la direction de Roland Rathelot, le projet est mené par **Alfonso Awadalla** (alfonso.awadalla-carreno@polytechnique.edu) et **Sofia Vaca** (sofia.vaca@polytechnique.edu). L’analyse se focalise sur la manière dont les employeurs communiquent divers attributs dans leurs annonces, en explorant les différences sectorielles et géographiques pour fournir des informations pertinentes en économie du travail.

### Présentation du Projet

**Objectif :**  
Extraire et classifier systématiquement les attributs des annonces d'emploi afin de différencier les informations relatives à la rémunération de celles concernant les avantages non salariaux. Cette analyse permet d’identifier les variations par secteur d’activité et par localisation, afin d’éclairer le débat en matière de politiques publiques.

**Questions de recherche :**  
- Quels sont les attributs payants et non payants mis en avant dans les offres d’emploi ?  
- Dans quelle mesure ces différences s’expliquent-elles par le secteur d’activité et la localisation de l’annonce ?

### Structure du Projet
```
├── README.md                                      <- Documentation principale du projet
├── LICENSE                                        <- Licence du projet
├── app                                            <- Scripts pour exécuter l’outil de cartographie interactive
├── data                                           <- Toutes les données
│   ├── 1- Raw Data                                <- Données brutes
│   ├── 2- Formatted Data                          <- Données formatées
│   ├── 3- Final Data                              <- Données finales
│   ├── linking tables                             <- Tables de liaison
│   └── shapefiles                                 <- Shapefiles nécessaires à la cartographie
├── src                                            <- Code source pour le traitement et l’analyse des données.
│   ├── 00_explore_jocas_missing_values.ipynb      <- Exploration des valeurs manquantes de JOCAS
│   ├── 01_match_communes_with_shapefile.ipynb     <- Correspondance des communes avec le shapefile
│   ├── 02_clean_rome_fap_mapping.ipynb            <- Nettoyage de la table de correspondance ROME-FAP
│   ├── 03_process_stmt_demand.ipynb               <- Traitement des données STMT (demande)
│   ├── 04_process_jocas_supply.ipynb              <- Traitement des données JOCAS (offre)
│   └── 05_compute_labour_tightness_ratio.ipynb    <- Calcul du ratio de tension sur le marché du travail
├── docs                                           <- Références et documents utilisés lors du projet
├── reports                                        <- Note méthodologique + diaporama de présentation
```

### Exécution du Projet

Pour reproduire l’analyse :
1. Placez les données nécessaires dans le dossier `data`.
2. Exécutez les scripts ou notebooks présents dans le dossier `src` pour effectuer le nettoyage, le traitement et l’analyse des données.
3. Consultez le rapport détaillé dans le dossier `reports` pour une présentation complète des méthodes et des résultats obtenus.

### Contributions & Contact

Pour toute suggestion ou pour signaler une anomalie, veuillez contacter :  
- **Alfonso Awadalla** : [alfonso.awadalla-carreno@polytechnique.edu](mailto:alfonso.awadalla-carreno@polytechnique.edu)  
- **Sofia Vaca** : [sofia.vaca@polytechnique.edu](mailto:sofia.vaca@polytechnique.edu)

Les contributions et collaborations visant à améliorer ce projet sont les bienvenues.

---

## English Version

### Project Context

This project aims to analyze job advertisements in France by distinguishing between pay-related attributes and non-monetary benefits, using Natural Language Processing (NLP) techniques and supervised machine learning methods.  
Conducted as part of the **Applied Labour Economics** course under the guidance of Roland Rathelot, the project is carried out by **Alfonso Awadalla** (alfonso.awadalla-carreno@polytechnique.edu) and **Sofia Vaca** (sofia.vaca@polytechnique.edu). The analysis focuses on how employers communicate various attributes in job ads, exploring both sectoral and geographical differences to provide valuable insights into labour economics.

### Project Overview

**Objective:**  
Systematically extract and classify job ad attributes to differentiate between pay-related features and non-pay benefits. This analysis identifies variations by industry sector and geographic location to inform debates on public policies.

**Research Questions:**  
- What pay-related and non-pay-related attributes are highlighted in job ads?  
- To what extent can these differences be explained by the industry sector and the location of the ad?

### Project Structure
```
├── README.md                                       <- Main documentation of the project
├── LICENSE                                         <- Project license
├── app                                             <- Scripts to run the interactive mapping tool
├── data                                            <- All the data
│   ├── 1- Raw Data                                 <- Raw data
│   ├── 2- Formatted Data                           <- Formatted data
│   ├── 3- Final Data                               <- Final data
│   ├── linking tables                              <- Linking tables
│   └── shapefiles                                  <- Shapefiles required for mapping
├── src                                             <- Source code for data processing and analysis.
│   ├── 00_explore_jocas_missing_values.ipynb       <- Exploration of missing values in JOCAS
│   ├── 01_match_communes_with_shapefile.ipynb      <- Matching communes with shapefile
│   ├── 02_clean_rome_fap_mapping.ipynb             <- Cleaning the ROME-FAP mapping table
│   ├── 03_process_stmt_demand.ipynb                <- Processing STMT data (demand)
│   ├── 04_process_jocas_supply.ipynb               <- Processing JOCAS data (supply)
│   └── 05_compute_labour_tightness_ratio.ipynb     <- Calculating the labour market tightness ratio
├── docs                                            <- References and documents used during the project
├── reports                                         <- Methodological note + presentation slides
```


### Running the Project

To reproduce the analysis:
1. Place the required data into the `data` folder.
2. Run the scripts or notebooks located in the `src` folder to clean, process, and analyze the data.
3. Refer to the detailed report in the `reports` folder for a comprehensive presentation of methods and results.

### Contributions & Contact

For suggestions or to report issues, please contact:  
- **Alfonso Awadalla** : [alfonso.awadalla-carreno@polytechnique.edu](mailto:alfonso.awadalla-carreno@polytechnique.edu)  
- **Sofia Vaca** : [sofia.vaca@polytechnique.edu](mailto:sofia.vaca@polytechnique.edu)

Contributions and collaborations to improve the project are welcome.


