# Data Science Project: Supermarket Sales Analysis with Machine Learning

## Description
Ce projet vise à analyser les ventes d'un supermarché à travers un jeu de données détaillant les achats effectués par des clients dans trois branches différentes. L'objectif est d'analyser les facteurs influençant la satisfaction client (évaluée à travers une note) en utilisant des techniques de Machine Learning et de Data Science. Nous utilisons des modèles prédictifs pour estimer cette satisfaction, en tenant compte de différentes caractéristiques comme le montant total des achats, la méthode de paiement, et d'autres informations liées aux transactions.

### Objectifs
- Analyser les données de ventes d'un supermarché
- Utiliser un modèle de régression pour prédire la satisfaction des clients (rating)
- Identifier les variables les plus influentes dans cette prédiction

## Dataset
Le jeu de données utilisé dans ce projet provient du fichier `supermarket_sales - Sheet1.csv`. Il contient des informations sur les ventes dans plusieurs branches d'un supermarché, notamment les produits achetés, les méthodes de paiement, les données démographiques des clients, ainsi que le montant des achats.

### Variables principales :
- Branch : Branche du supermarché (A, B, C)
- City : Ville où se trouve le supermarché
- Customer type : Type de client (Membre ou Non-membre)
- Gender : Sexe du client
- Product line : Catégorie du produit
- Unit price : Prix unitaire du produit
- Quantity : Quantité de produits achetés
- Tax 5% : Taxe de 5% appliquée sur la commande
- Total : Montant total de l'achat, incluant la taxe
- Payment : Méthode de paiement (Cash, Credit card, Ewallet)
- COGS : Coût des biens vendus
- Gross margin percentage : Pourcentage de marge brute
- Gross income : Revenu brut
- Rating : Note de satisfaction client (sur une échelle de 1 à 10)

## Méthodologie
1. Préparation des données : Nettoyage des données, transformation des variables catégorielles, gestion des valeurs manquantes.
2. Analyse exploratoire des données (EDA) : Visualisation des distributions des variables et identification des relations entre les caractéristiques.
3. Sélection des caractéristiques : Identification des variables les plus pertinentes pour prédire la satisfaction client.
4. Modélisation : Utilisation de modèles de régression pour prédire la variable `Rating`.
   - Modèle de régression linéaire
   - Random Forest Regressor
5. Évaluation du modèle : Utilisation des métriques d'évaluation comme le RMSE (Root Mean Squared Error) et le R² pour analyser la performance des modèles.

## Résultats
- Modèle de régression linéaire : RMSE : X, R² : Y
- Random Forest Regressor : RMSE : 1.88, R² : -0.15

Les résultats ont montré que certaines variables, comme le prix unitaire (Unit price), ont une influence significative sur la satisfaction client, tandis que d'autres, comme le type de produit, ont peu d'impact.

## Installation

### Prérequis
- Python 3.x
- Bibliothèques : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Installation des dépendances
1. Clonez ce repository
   git clone https://github.com/votre-utilisateur/nom-du-repo.git

2. Installez les bibliothèques nécessaires
   pip install -r requirements.txt

### Fichiers inclus
- supermarket_sales - Sheet1.csv : Jeu de données utilisé pour l’analyse
- supermarket_sales_analysis.py : Code Python pour l’analyse et la modélisation
- README.md : Documentation du projet

## Auteurs
- Nom : DJAHA YANKEP CHARLY WILLIAM

## License
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus d'informations.
