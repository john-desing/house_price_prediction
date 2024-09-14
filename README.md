# Prédiction des Prix des Maisons et Détection de Fraudes

## Objectif
Ce projet a pour but de démontrer deux compétences avancées :
1. **Prédiction des prix des maisons** avec optimisation de modèles, sélection de caractéristiques, et interprétation des résultats avec SHAP.
2. **Détection des fraudes** dans les transactions financières avec des algorithmes optimisés et analyse SHAP.

## Structure du projet
- **data/** : Données brutes et traitées.
- **notebooks/** : Notebooks d'analyse exploratoire.
- **src/** : Scripts pour la génération des données, prétraitement, modélisation, optimisation, et interprétation.
- **results/** : Résultats des performances des modèles.
- **README.md** : Explication du projet.
- **requirements.txt** : Liste des dépendances.

## Fonctionnalités Avancées
- Optimisation des hyperparamètres avec GridSearchCV.
- Sélection des caractéristiques importantes avec des modèles d'arbres.
- Interprétation des modèles avec SHAP pour comprendre les prédictions.

- **Visualisations interactives** avec Plotly pour l'analyse exploratoire.
- **Heatmaps de corrélation** pour comprendre les relations entre variables.
- **Courbes ROC et Precision-Recall** pour évaluer la performance des modèles de détection de fraudes.
- **Importance des caractéristiques** et **comparaison des prédictions** pour la prise de décision.

## Exécution des notebooks
Les notebooks contiennent des analyses visuelles et interactives pour explorer les données et évaluer les modèles. Exécutez-les en lançant Jupyter :

jupyter notebook notebooks/house_price_analysis.ipynb
jupyter notebook notebooks/fraud_detection_analysis.ipynb

## Exécution du Projet
Installez les dépendances :

```bash
pip install -r requirements.txt
