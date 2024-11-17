![Anticipation des besoins en consommation de bâtiment](https://github.com/Sengsathit/OCR_data_scientist_assets/blob/main/header_seattle.png?raw=true)

# PROJET : Anticipation des besoins en consommation de bâtiment

Ce projet à pour contexte la ville de **Seattle**, qui vise la neutralité carbone d'ici 2050. Ce projet se concentre sur l'analyse et la modélisation des données énergétiques des bâtiments non résidentiels. En s'appuyant sur les relevés réalisés en 2016, l'objectif est de prédire les émissions de CO2 et la consommation totale d'énergie pour les bâtiments dont les données ne sont pas disponibles, tout en évaluant la pertinence de l'indicateur ENERGY STAR Score pour ces prédictions.

## Structure du dépôt

- `notebook_exploratoire.ipynb` : Ce notebook contient les étapes d'importation et de préparation initiale des données, ainsi que des analyses exploratoires approfondies, des visualisations pour identifier les tendances, les anomalies, et les relations entre les variables.
- `notebook_modelisation_1.ipynb` et `notebook_modelisation_2.ipynb` : Ces notebooks se concentrent sur la mise en place et l'entraînement de plusieurs modèles prédictifs. Ils incluent la sélection des variables pertinentes, la normalisation des données, l'entraînement des modèles de base, et l'évaluation initiale des performances. Ils explorent également des outils d'explicabilité pour comprendre comment les variables influencent les prédictions.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter les notebooks.

---

## Prérequis

Pour exécuter ce projet, vous aurez besoin de Python (version 3.8 ou supérieure). Il est également recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.

### Étapes pour créer et activer un environnement virtuel :

1. Créez un environnement virtuel :
   ```bash
   python -m venv .venv
   source .venv/bin/activate

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
