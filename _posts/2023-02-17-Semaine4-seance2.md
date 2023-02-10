---
layout: post
title:  "Rencontre 8"
author: "Emulie Chhor"
tags: Rencontre
excerpt_separator: <!--more-->
comments: false
sticky: false
hidden: false
---

On introduit quelques notions pour nettoyer les données
<!--more-->

Les données se trouvent [ici]

Un exemple de notebook est à venir

# Plan de la séance

1. Introduction aux techniques de nettoyage de données
2. Que faire lorsque notre jeu de données a des données manquantes?
3. Que faire avec les données aberrantes?
4. Introduction au challenge 1

## Introduction aux techniques de nettoyage de données



## Que faire lorsque notre jeu de données a des données manquantes?

Plusieurs méthodes d'offrent à nous lorque certaines données sont manquantes
dans notre jeu de données. On pourrait naivement enlever toutes les lignes 
avec des données manquantes. Cependant, la simplicité de cette méthode 
s'accompagne avec un problème majeur: les données qu'on ignore peuvent contenir
de l'information importante. En général, on préfère utiliser des méthodes
alternatives d'`imputation`:
- Imputation de moyenne: on remplace par la moyenne ou la médiane
- Interpolation ou extrapolation: on remplace par la moyenne des points les plus proches
- Utilisation un algorithme alternatif pour prédire la valeur des données manquantes


- [Méthodes d'imputation en sklearn]


## Que faire avec les données aberrantes?

Plusieurs stratégies s'offrent à nous pour trouver les données aberrantes:
- z-score
- IQR
- Local Outlier Factor (LOF)
- Distance de Mahalanobis 

Que faire lorsque avec ces données aberrantes? On peut:
- Méthode du `clipping`: si une valeur dépasse un certain seuil, on initialize 
  la valeur à ce seuil
- Imputation
- Transformation


