---
title: Prédiction probabiliste avec Python
summary: Prédiction probabiliste de séries temporelles multivariées de mobilité avec des modèles basés sur l'apprentissage profond
date: 2023-05-08
type: docs
math: false
tags:
  - Python
image:
  caption: 'Modèle de prédiction probabiliste pour séries temporelles'
---

Dans cette présentation, nous explorons un projet de prédiction probabiliste de séries temporelles multivariées en utilisant des modèles d'apprentissage profond. Le projet se concentre sur les données de mobilité pour prédire les mouvements futurs avec des incertitudes. Les modèles introduits utilisent une structure de type RNN qui projettent en sortie les paramètres de modèles de distributions (lois normales). Le cours associé au projet est disponible [ici](https://github.com/pdenailly/Atelier-Summer-School/blob/main/Pr%C3%A9sentation_prediction_probabiliste.pdf).

## Projet Google Colab

Le projet est disponible sur Google Colab et peut être consulté via le lien suivant :

[Accéder au projet Colab](https://colab.research.google.com/github/pdenailly/Atelier-Summer-School/blob/main/Pr%C3%A9dictions_V%C3%A9los.ipynb#scrollTo=jkgfEYHLmokT)

Un code python disponible [ici](https://github.com/pdenailly/Atelier-Summer-School/blob/main/rolling_dataset.py) est nécessaire au projet.

## Description du projet

L'objectif de ce projet est de démontrer comment utiliser les réseaux neuronaux récurrents (RNN) et d'autres modèles avancés pour la prédiction de séries temporelles. Voici les principales étapes couvertes :

1. **Préparation des données** : Traitement des séries temporelles multivariées.
2. **Modélisation** : Mise en œuvre des modèles probabilistes basés sur l'apprentissage profond.
3. **Évaluation** : Analyse des performances des prédictions, y compris l'incertitude probabiliste.

## Données 

Les données utilisées dans ce projet sont des comptages de traffic de vélos dans la ville de Paris, en plusieurs localisations. 

[Télécharger le csv des comptages de vélos](https://github.com/pdenailly/Atelier-Summer-School/blob/main/bike_data.csv)


