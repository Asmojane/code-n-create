# Introduction

Bienvenue dans mon dépôt de challenges Kaggle ! Tous les projets ici sont développés en **Python** et utilisent diverses bibliothèques de science des données et de machine learning telles que **Pandas**, **NumPy**, **Scikit-learn**, **TensorFlow** et **Keras**. Chaque notebook se concentre sur l'application de techniques de machine learning à différents jeux de données et défis, avec des étapes détaillées pour le prétraitement des données, la création de fonctionnalités, la construction de modèles et l'évaluation.

Vous pouvez consulter mon profil Kaggle et découvrir plus de mes travaux ici : [Kaggle - JaneMathieuASMO](https://www.kaggle.com/janemathieuasmo).

# Résumé des Challenges Kaggle

## Titanic - Machine Learning from Disaster
Le challenge Titanic est un classique en machine learning. L'objectif est de prédire si les passagers ont survécu au naufrage du Titanic en se basant sur des variables telles que l'âge, le sexe, la classe du billet, et plus encore.

Dans mes trois notebooks pour ce challenge :

- J'ai commencé par explorer le jeu de données, traiter les valeurs manquantes, et créer de nouvelles fonctionnalités comme la taille de la famille et l'extraction de titres à partir des noms.
- J'ai prétraité les données catégorielles, y compris l'encodage du genre et du lieu d'embarquement.
- J'ai entraîné plusieurs modèles (par exemple, Régression Logistique, Arbres de Décision) et ajusté les hyperparamètres. Le modèle final a obtenu un score de **0.76555** sur le tableau public.

---

## Digit Recognizer - Computer Vision
Le challenge Digit Recognizer se concentre sur la vision par ordinateur, avec pour objectif d'identifier correctement des chiffres manuscrits provenant du jeu de données MNIST. Ce défi introduit des techniques telles que le traitement d'image et les réseaux de neurones.

Dans ce notebook :

1. J'ai effectué une visualisation des données pour comprendre le jeu de données MNIST, affichant des exemples de chiffres manuscrits et reformant les données de pixels pour les préparer à la modélisation.
2. J'ai utilisé **K-Nearest Neighbors (KNN)** pour classer les chiffres après avoir normalisé les valeurs des pixels.
3. J'ai utilisé un **Réseau de Neurones Convolutif (CNN)** pour classer les chiffres. Le modèle se compose de plusieurs couches de convolution et de pooling pour capturer les caractéristiques spatiales des images.

### L'architecture du CNN comprend :
- Deux couches de convolution avec des filtres de taille 32 et 64.
- Des couches de MaxPooling pour réduire les dimensions spatiales.
- Une couche Dropout pour éviter le surapprentissage.

Le modèle a atteint une précision élevée de **0.98867** sur l'ensemble de validation.
