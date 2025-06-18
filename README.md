# 🧠 Régression en Machine Learning : Du Classique à l’Avancé

Ce projet Jupyter Notebook explore de manière progressive et pédagogique les **algorithmes de régression**, allant des plus simples (comme la régression linéaire) aux modèles avancés et automatisés. 
Il sert à la fois de **preuve de maîtrise des outils de data science** et de **ressource d’apprentissage synthétique** pour ceux qui souhaitent renforcer leurs connaissances en régression.

---

## 📌 Objectifs

- Explorer une large gamme de **modèles de régression supervisée**
- Comprendre les **avantages, limites et cas d’usage** de chaque méthode
- Illustrer les étapes complètes d’un pipeline machine learning :
  - Analyse exploratoire (EDA)
  - Prétraitement & Feature Engineering
  - Entraînement des modèles
  - Évaluation des performances
- Comparer les modèles sur un **jeu de données réel**

---

## 🏡 Jeu de données utilisé

Le dataset utilisé est celui de **[House Prices - Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)**. 
Données de compétition

- 1 460 maisons résidentielles
- 80+ variables (catégorielles, numériques, ordinales)
- Objectif : prédire la variable `SalePrice`

---

## ⚙️ Algorithmes abordés

| Type                        | Modèles utilisés |
|-----------------------------|------------------|
| 🔹 **Régressions linéaires**      | `LinearRegression`, `Ridge`, `Lasso` |
| 🌳 **Arbres & Forêts**           | `DecisionTreeRegressor`, `RandomForestRegressor` |
| 🌀 **Méthodes à noyau**         | `SVR` |
| 🔧 **Boosting & Ensembles**     | `GradientBoostingRegressor`, `XGBRegressor`, `LGBMRegressor`, `CatBoostRegressor` |
| 🧠 **Réseaux de neurones**      | `MLPRegressor` |
| 🤖 **AutoML**                   | `AutoGluon Tabular Predictor` |

---

## 🧪 Évaluation

Les modèles sont évalués à l’aide de plusieurs métriques :
- **RMSLE**
- **RMSE**
- **R² Score**
- **Cross-validation**
- **Visualisations des erreurs**

---

## 📂 Arborescence du projet 

├── notebook.ipynb # Notebook principal (EDA, modèles, résultats)  
├── README.md # Présentation du projet  
├── data/ # Dossier des données (train/test)  
└── requirements.txt #  Dépendances Python  
