# ESILV-Python-for-data-analysis-project-2022

Projet par HANNA Marianne
# Release Prediction Year of Music Song Data


## Introduction

Le Million Song Dataset (MSD) est une collection librement accessible de caractéristiques audio et de métadonnées pour un million de morceaux de musique populaire contemporaine. Il s'agit d'un sous-ensemble du MSD qui contient des caractéristiques audio de chansons avec l'année de la chanson. 

L'objectif est de prédire l'année de sortie d'une chanson à partir des caractéristiques audio.

Vous pouvez récuperer le fichier : https://archive.ics.uci.edu/ml/datasets/YearPredictionMSD

## Description du jeu de données
Il y a 90 attributs :
- Date 
- TimbreAverage [1-12]
- TimbreCovariance[1-78] 

Ces caractéristiques ont été extraites des caractéristiques 'timbre' de l'API. 


## Modèles
Pour prédire la décennie de sortie d'une chanson à partir des caractéristiques audio, nous avons utilisé 6 modèles d'apprentissage automatique de regression différents, afin d'établir une référence et de comparer les résultats.
    
- Des algorithmes linéaire: Regression Lineaire et LASSO

- Des algorithmes non-linéaires: Arbre de décision et KNN

- Algorithme d'ensemble: Random Forest et eXtreme Gradient Boosting


## Vous retrouverez dans ce dépot : 

- le notebook .ipynb : qui montre le lien entre les variables et la cible. Utiliser la bibliothèque scikit-learn pour essayer plusieurs algorithmes, changer les hyper paramètres, faire une recherche sur grille, comparer les résultats des modèles à l'aide de graphiques.


- la présentation en pdf : expliquant les entrées et les sorties du problèmes, mes réflexions sur la question posée, les différentes variables que nous avons créées, comment le problème s'inscrit dans le contexte de l'étude.


Bonne lecture :) 
