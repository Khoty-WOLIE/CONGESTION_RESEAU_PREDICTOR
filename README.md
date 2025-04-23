# CONGESTION_RESEAU_PREDICTOR
Modélisation de la congestion réseau via des algorithmes de machine learning et deep learning, avec ingénierie des variables et optimisation des hyperparamètres.

# 📡 Network Congestion Predictor

Un projet de data science pour prédire les types de congestion réseau à partir de données de consommation et de protocole.

## 🔍 Objectif
Prédire le type de congestion réseau à partir des données d’usage collectées sur les cellules mobiles.

## 🧠 Modèles utilisés
- Régression Logistique
- Arbre de Décision
- Forêt Aléatoire
- XGBoost
- MLP (Perceptron Multicouche)
- Réseau de Neurones (ANN)

## 🛠️ Feature Engineering
- Regroupement TCP/UDP
- Transformation logarithmique
- Ratios, regroupements par période

## 📊 Évaluation
Métriques utilisées : `accuracy`, `matrice de confusion`, `MCC` (Matthews Correlation Coefficient).

## 🚀 Résultats finaux
Le modèle XGBoost optimisé atteint une précision de 86% avec un MCC de 81.
