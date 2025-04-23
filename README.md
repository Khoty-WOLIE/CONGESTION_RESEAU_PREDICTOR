# CONGESTION_RESEAU_PREDICTOR
Modélisation de la congestion réseau via des algorithmes de machine learning et deep learning, avec ingénierie des variables et optimisation des hyperparamètres.

# 📡 Network Congestion Predictor

Un projet de **data science** visant à prédire les **types de congestion réseau** à partir de données d’usage mobile et de protocoles réseau.

## 🔍 Objectif
Développer un modèle de machine learning capable de **prédire automatiquement le type de congestion** rencontré sur une cellule réseau mobile, à partir de données telles que le volume de trafic (bytes), les protocoles utilisés (TCP/UDP), l’heure, ou encore l’opérateur.

## 🧠 Modèles utilisés

Plusieurs modèles de classification ont été testés :
- **Régression Logistique** : modèle linéaire simple pour les problèmes de classification.
- **Arbre de Décision** : arbre de règles de décision.
- **Forêt Aléatoire** : ensemble d’arbres pour améliorer la robustesse.
- **XGBoost** : algorithme de boosting performant pour la classification.
- **MLP (Perceptron Multicouche)** : réseau de neurones simple à plusieurs couches.
- **ANN (Artificial Neural Network)** : architecture plus flexible et profonde de réseaux de neurones.

## 🛠️ Ingénierie des variables (Feature Engineering)
Création de nouvelles variables à partir des données brutes :
- **Regroupement TCP/UDP** : regroupement des types de trafic selon le protocole réseau.
- **Transformation logarithmique** : réduction de l’effet des valeurs extrêmes.
- **Création de ratios et regroupements horaires** : pour mieux capturer les tendances temporelles.

## 📊 Évaluation
Les modèles ont été évalués selon plusieurs métriques :
- **Accuracy** : pourcentage global de bonnes prédictions.
- **Matrice de confusion** : visualisation des erreurs de classification par classe.
- **MCC (Matthews Correlation Coefficient)** : indicateur robuste, même avec des classes déséquilibrées.

## 🚀 Résultats finaux
Le modèle **XGBoost optimisé** atteint :
- **Précision (accuracy)** : **86%**
- **MCC** : **81**

---

### 👨‍💻 Réalisé par [Khoty WOLIE](https://www.linkedin.com/in/khoty-wolie/)

Projet personnel de machine learning appliqué à la télécommunication, regroupant toutes les étapes d’un pipeline de data science complet : prétraitement, ingénierie des variables, modélisation, optimisation, évaluation et export final.
