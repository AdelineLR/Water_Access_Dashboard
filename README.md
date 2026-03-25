# Tableau de bord mondial sur l’accès à l’eau potable – Projet d’aide à la décision

![Tableau](https://img.shields.io/badge/Tableau-3498db?style=flat&logo=tableau&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoft%20sql%20server&logoColor=white)
 
## Contexte 
L'association Drinking Water For All (DWFA), une ONG fictive, a besoin d'un tableau de bord présentant une vue globale de l’accès à l’eau potable dans le monde. Celui-ci permettra de choisir le pays à cibler en fonction de 3 domaines d’expertise :
  1. Création de services d’accès à l’eau potable ;
  2. Modernisation de services d’accès à l’eau déjà existants ;
  3. Consulting auprès d’administrations/gouvernements à propos des politiques d’accès à l’eau.

Pour ce projet, l'outil de data visualisation utilisé est Tableau Software. Le pré-traitement des données a été réalisé avec MySQL Workbench et la base de données MySQL a été connectée à Tableau via MySQL server.
[Lien vers l'histoire sur Tableau Public](https://public.tableau.com/shared/ZP8PSK492?:display_count=n&:origin=viz_share_link)

## Mission
Concevoir un **tableau de bord interactif et actionnable** permettant de :  
* Identifier les pays prioritaires selon chaque domaine d’intervention  
* Structurer des jeux de données complexes provenant de multiples sources  
* Aider les décideurs à explorer les données et prendre des décisions éclairées

## Actions
* Sélection des **indicateurs clés** liés à l’accès à l’eau potable, la mortalité, la stabilité politique, la population et la région  
* Création d’un **blueprint et de mockups** correspondant aux trois domaines de financement et vues mondiale, région et pays 
* Nettoyage et prétraitement des données avec **MySQL**  
* Connexion des différentes sources via MySQL Server pour constituer une base relationnelle unique, permettant d’actualiser les données en temps quasi réel et d’assurer la fiabilité des analyses pour la prise de décision  
* Développement d’un **tableau de bord interactif Tableau**, structuré pour être clair et utilisable  
* Mise en avant des **insights actionnables** pour des parties prenantes non techniques

## Résultat
* Livraison d’un **tableau de bord synthétique et facile à utiliser**, permettant de prioriser les pays selon les objectifs stratégiques  
* Le tableau de bord facilite l’**identification rapide des pays** nécessitant création, modernisation ou conseil  
* Amélioration de l’**efficacité de la prise de décision** et méthode structurée pour une stratégie de financement **basée sur les données**

### Introduction
<img width="1431" height="892" alt="Vue_introduction" src="https://github.com/user-attachments/assets/32cfde36-3253-49de-bb67-b8b728bcf5f8" />

### Contexte
<img width="1412" height="891" alt="Vue_Contexte" src="https://github.com/user-attachments/assets/73da08b6-fcd2-4412-9e6c-c1eeb163178b" />

### Drinking Water For All
Présentation de l'ONG et des différentes vues
<img width="1427" height="896" alt="Vue_DrinkingWaterForAll" src="https://github.com/user-attachments/assets/a07cb3fc-77e4-4a72-8d0d-2a1edc5f9e07" />

### Vue mondiale
Vision globale des indicateurs à l'échelle monde
<img width="1417" height="896" alt="Vue Mondiale" src="https://github.com/user-attachments/assets/5fcc8471-b628-4295-b770-ea27996497a1" />

### Vue par Région OMS
Cette vue est dynamique et dépend du domaine d'expertise sélectionné. Les indicateurs sont présentés à l'échelle de la région OMS.
1. Création de service d'accès à l'eau
<img width="1412" height="895" alt="Vue Region" src="https://github.com/user-attachments/assets/07ba0a7d-7e70-4047-9f10-86fc9802ad64" />

2.  Modernisation des services d'accès à l'eau
<img width="1403" height="886" alt="Vue Region 2" src="https://github.com/user-attachments/assets/52768cb3-3617-4b4b-b802-4ee7ef27225e" />

3. Consulting à propose des politiques d'accès à l'eau
<img width="1407" height="883" alt="Vue Region 3" src="https://github.com/user-attachments/assets/f13f67eb-df28-4843-a93b-a1b5ede440b6" />

### Vue par Pays
Cette vue est dynamique et dépend du domaine d'expertise sélectionné. Les indicateurs sont présentés à l'échelle du pays.
1. Création de service d'accès à l'eau
<img width="1407" height="888" alt="image" src="https://github.com/user-attachments/assets/c85335df-fc5b-48d1-b526-af4cd758a2f4" />

2. Modernisation des services d'accès à l'eau
<img width="1407" height="882" alt="image" src="https://github.com/user-attachments/assets/9456e3e8-9a4f-42b2-ac65-b18354f9b064" />

3. Consulting à propose des politiques d'accès à l'eau
<img width="1406" height="888" alt="image" src="https://github.com/user-attachments/assets/94308687-150a-425d-9dd9-dd997d3fb913" />

## Données
* BasicAndSafelyManagedDrinkingWaterServices.csv : Données sur l'accès et la qualité des services à l'eau potable par pays [Source WHO](https://apps.who.int/gho/data/node.main.WSHWATER?lang=en)
* MortalityRateAttributedToWater.csv : Données sur le taux de mortalité due à l'eau insalubre par pays [Source WHO](https://apps.who.int/gho/data/view.main.SDGWSHBOD392v?lang=en)
* PoliticalStability.csv : Données sur l'indicateur de stabilité politique par pays [Source WHO](http://www.fao.org/faostat/en/#data/FS)
* Population.csv : Données sur la population par pays [Source FAO](http://www.fao.org/faostat/en/#data/FS)
* RegionCountry.csv : Données sur les pays par régions OMS
* Surface_area.csv : Données sur la superficie par pays [Source World Bank](https://databank.worldbank.org/reports.aspx?source=2&series=AG.SRF.TOTL.K2&country=#)

## Fichiers
* LeRay_Adeline_1_Blueprint_022023.pdf : Blueprint du tableau de bord
* LeRay_Adeline_2_Mockup_022023.pdf : Mockup du tableau de bord
* LeRay_Adeline_3_Présentation_022023.pdf : Présentation du contexte, du pré-traitement des données et de la démarche de création du tableau de bord
* P8_Create_Table.sql : Script MySQL pour la création des tables, le chargement et le pré-traitement des données
* P8_Table_Country.sql : Script MySQL pour la création d'une liste exhaustive des pays pour les jointures (UNION DISTINCT) 
* P8_Jointure.sql : Script MySQL pour les jointures des tables
* P8_Eau_potable.twbx : Tableaux de bord et Histoire sous Tableau

 _Projet réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms (Projet n°8 - Févr. 2023)_
