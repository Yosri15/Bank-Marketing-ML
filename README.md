# 🏦 Bank Marketing Campaign Prediction - Machine Learning

Ce projet vise à prédire si un client souscrira à un dépôt bancaire (campagne marketing) en utilisant des algorithmes de Machine Learning.

## 📁 Données
- **Source** : [Bank Marketing Dataset](https://www.kaggle.com/code/bayunova/bank-marketing/data) (fichier `bank-additional-full.csv`).
- **Description** :
  - 41 188 exemples, 20 variables (âge, profession, statut matrimonial, etc.).
  - Cible binaire : `y` (oui=1, non=0).

## 🛠️ Fonctionnalités
- **Analyse exploratoire (EDA)** : Visualisation des distributions, corrélations, et statistiques.
- **Prétraitement** :
  - Normalisation des variables numériques (`StandardScaler`).
  - Encodage des variables catégorielles (`OneHotEncoder`).
  - Gestion du déséquilibre de classes avec **SMOTE**.
- **Modèles testés** :
  - Régression Logistique
  - Arbre de Décision
  - Random Forest
  - SVM
  - k-NN
- **Métriques d'évaluation** : Accuracy, ROC-AUC, F1-score, Matrice de confusion.

