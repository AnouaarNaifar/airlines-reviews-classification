# 🛫 Classification des Avis d'Aériens - Analyse ML

## 📖 Description
Ce projet implémente une analyse complète et une classification des avis clients de compagnies aériennes. Il couvre l'ensemble du pipeline de Machine Learning : exploration des données, prétraitement, visualisation, feature engineering, et comparaison de plusieurs modèles de classification.

## 🎯 Objectif
Prédire le sentiment des avis clients (positif/négatif) en utilisant différents algorithmes de Machine Learning et techniques de traitement du langage naturel (NLP).

## 📊 Dataset
- **Fichier** : `airlines_reviews_dynamic.csv`
- **Contenu** : Avis clients de compagnies aériennes avec métadonnées (dates, notes, commentaires, etc.)

## 🚀 Structure du Projet

### Phase 1 : Exploration des Données
- Chargement et compréhension du dataset
- Analyse des métadonnées et types de données
- Qualité des données (valeurs manquantes, duplicatas)

### Phase 2 : Analyse Exploratoire (EDA)
- Distribution des variables
- Corrélations et relations entre features
- Visualisations détaillées (distribution des notes, analyse temporelle, etc.)

### Phase 3 : Prétraitement
- Nettoyage des données textuelles
- Traitement des valeurs manquantes
- Encodage des variables catégorielles
- Normalisation/standardisation

### Phase 4 : Feature Engineering
- Extraction de features depuis le texte
- Création de nouvelles variables
- Sélection de features

### Phase 5 : Modélisation
Comparaison de plusieurs modèles :
- **Logistic Regression**
- **Random Forest**
- **XGBoost**
- **Support Vector Machine (SVM)**

### Phase 6 : Évaluation
- Métriques de performance (Accuracy, Precision, Recall, F1-Score)
- Matrices de confusion
- Comparaison des modèles
- Visualisations des résultats

## 📦 Installation

### Prérequis
- Python 3.8+
- Jupyter Notebook ou VS Code avec extension Python

### Dépendances
Installez les packages requis :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

Ou avec le fichier requirements.txt :

```bash
pip install -r requirements.txt
```

## 💻 Utilisation

1. **Cloner le repository**
```bash
git clone <https://github.com/AnouaarNaifar/airlines-reviews-classification>
cd <airlines-reviews-classification>
```

2. **Installer les dépendances**
```bash
pip install -r requirements.txt
```

3. **Ouvrir le notebook**
```bash
jupyter notebook ML_airlines_reviews_classification.ipynb
```
ou avec VS Code

4. **Exécuter les cellules séquentiellement**

## 📈 Résultats Attendus
Le notebook génère :
- Visualisations détaillées des données
- Matrices de confusion pour chaque modèle
- Tableau comparatif des performances
- Recommandations sur le meilleur modèle

## 🛠️ Technologies Utilisées
- **Python** : Langage principal
- **Pandas & NumPy** : Manipulation de données
- **Matplotlib & Seaborn** : Visualisation
- **Scikit-learn** : Machine Learning
- **XGBoost** : Gradient Boosting

## 📝 Notes
- Le notebook est en français pour faciliter la compréhension
- Toutes les cellules contiennent des commentaires explicatifs
- Les sections sont clairement séparées par phases

## 👥 Auteur
[Anouaar Naifar] & [Mariem Kchaou] - ENETCOM 2IDSD2

## 📄 Licence
Ce projet est à usage éducatif.

---
*Projet réalisé dans le cadre du cours de Machine Learning - ENETCOM*