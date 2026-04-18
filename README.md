# Prédiction des prix immobiliers – Projet Big Data

## Description
Ce projet met en place une pipeline complète de traitement de données appliquée au marché immobilier français.  
Il couvre les étapes de collecte, nettoyage, fusion, modélisation et exploitation des données.

L’objectif est de produire une estimation du prix au m² et un système de scoring permettant d’identifier des biens sous-évalués ou surévalués.


## Données

Les données proviennent de plusieurs plateformes immobilières collectées par web scraping.

Les scripts de collecte sont fournis dans le dépôt.  
Des fichiers intermédiaires sont conservés afin de pouvoir relancer le pipeline à différentes étapes.


## Modélisation

Trois modèles de machine learning sont utilisés pour estimer le prix au m² :

- Régression linéaire  
- Random Forest  
- Gradient Boosted Trees  


## Résultats

Le projet permet de produire :

- Une estimation du prix au m²  
- Un score par annonce :
  - Sous-évalué  
  - Prix du marché  
  - Surévalué  
- Des indicateurs agrégés pour analyser les tendances du marché immobilier


## Auteurs

- Yacin BEN BELGACEM  
- Juline DUBOIS  
- Leticia KERTOUS  
- Zeynep SORGUT  
