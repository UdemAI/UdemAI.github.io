---
layout: post
title:  "Rencontre 2"
author: "Emulie Chhor"
tags: Rencontre
excerpt_separator: <!--more-->
comments: false
sticky: false
hidden: false
---

On se penche sur la méthodologie de base lors de l'exploration de données
<!--more-->

Les données se trouvent [ici](https://github.com/UdemAI/Code/blob/main/Datasets/shampoo.csv)

Un exemple de notebook est à venir

# Plan de la séance

1. Introduction à `pandas`
2. Techniques de visualisation de données 
3. Vérification des hypothèses d'une régression linéaire
4. Détection de point aberrant avec la méthode IQR

## Introduction à `pandas`

On introduit quelques fonction utiles de pandas: `moving_average`, `pivot_table`

## Introduction à l'analyse exploratoire des données avec `matplotlib` et `seaborn`

On montre comment constuire des `boxplot`, des `heatmap` et autres 
techniques de visualisation et comment les interpréter

## Vérification des hypothèses d'une régression linéaire

Avant de générer une régression linéaire, il faut vérifier certaines hypothèses:
- Indépendance des erreurs
- Uniformité de la variance (homoscédasticité) 

Nous allons vérifier ces hypothèses avec des `qqplot` et des `residual plot`

## Détection de point aberrant avec la méthode IQR

Il existe plusieurs méthodes pour détecter les points aberrants: 
- Méthode interquartiles (IQR)
- Distance de Cook
- Leverage
- DFFITS

On verra comment implémenter la méthode IQR sur python.


