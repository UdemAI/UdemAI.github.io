---
layout: post
title:  "Rencontre 5"
author: "Emulie Chhor"
tags: Rencontre
excerpt_separator: <!--more-->
comments: false
sticky: false
hidden: false
---


On introduit la méthodologie à la science de données et quelques algorithmes de dimension
de dimensionalité: PCA, SVD, t-SNE
<!--more-->

Les données se trouvent [ici]

Un exemple de notebook est à venir

# Plan de la séance

1. Étapes d'un problème en apprentissage machine
2. Introduction aux hyperparamètres
3. Introduction à la réduction de dimensionalité

## Les étapes d'un problème en apprentissage machine



## Introduction aux hyperparamètres et à la méthode du coude

Précédemment, nous avons vu l'algorithme du KNN qui fait essentiellement un vote
pondéré de ses K plus proche voisins. Mais comment trouve-t-on ce K optimal? 
Une méthode naive serait de tester plusieurs valeurs d'hyperparamètre et choisir
celui minimisant l'erreur. Cependant, cette méthode ne généralise pas toujours
bien le modèle. On introduit donc la méthode du coude pour trouver le 
meilleur hyperparamètre.

- [Vidéo explicative de la méthode du coude (elbow)]
- [Documentation Sklearn]

## Introduction à la réduction de dimensionalité

Lorsqu'on a des données de grande dimension, il est parfois pratique de réduire
leur dimensionalité. Quelques algorithmes de réduction de dimensionalité:
- PCA
- SVD
- t-SNE

**PCA**

Le PCA réduit les données en trouvant les valeurs et vecteurs propres de 
la matrice de cofacteur.

- [Vidéo explicative du PCA]
- [Documentation Sklearn]

**SVD**

Le SVD se base sur la décomposition SVD en algèbre linéaire pour réduire la 
dimensionalité du jeu de données.

- [Vidéo explicative du SVD]
- [Documentation Sklearn]

**t-SNE**

- [Vidéo explicative du t-SNE]
- [Documentation Sklearn]


## Papiers à lire

On vous propose quelques papiers à lire. Nous en discuterons durant les séances
subséquentes.



