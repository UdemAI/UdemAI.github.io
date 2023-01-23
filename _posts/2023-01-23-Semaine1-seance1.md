---
layout: post
title:  "Rencontre 1"
author: "Emulie Chhor"
tags: Rencontre
excerpt_separator: <!--more-->
comments: false
sticky: false
hidden: false
---

On introduit le problème de régression avec le dataset `shampoo.csv`
<!--more-->

Les données se trouvent [ici](https://github.com/UdemAI/Code/blob/main/Datasets/shampoo.csv)

Un exemple de notebook peut se trouver [ici](https://github.com/UdemAI/Code/blob/main/Notebooks/Week1.ipynb)

# Plan de la séance

1. Introduction à Google Colab 
2. Exploration du dataset `shampoo.csv`
3. Introduction aux méthodes de régression

## Introduction à Google Colab

On explique comment rouler un fichier `.ipynb` dans un Google Colab

## Exploration du dataset `shampoo.csv`

On utilise les libraries `pandas` et `matplotlib` pour visualiser les 
données

- Lecture du jeu de données avec `pandas.read_csv()`
- Obtention de statistiques descriptive avec `pandas.DataFrame.describe()`
- Visualisation du jeu de données avec `matplotlib.plot()`

## Introduction aux méthodes de régression

On voudrait répondre à la question suivante: Prédire la valeur des ventes
au 50e mois à l'aide d'une régression linéaire

On remarque qu'on peut obtenir la régression linéaire de plusieurs façons: 
1. avec la librairie `sklearn`
2. avec un calcul matriciel
3. en minimisant l'erreur MSE
4. avec une descente de gradient

Nous avons déjà commencé à discuter de la 3e méthode, mais on s'attardera 
davantage à ces méthodes pour les prochaines séances.

