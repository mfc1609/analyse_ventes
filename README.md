# 📊 Analyse des Ventes - Retail Électronique

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📝 Description du Projet

Ce projet est une analyse exploratoire de données (EDA) simulant les ventes d'une chaîne de magasins d'électronique en France. 

L'objectif est de transformer des données brutes en **insights business** exploitables pour aider à la prise de décision (gestion des stocks, stratégie commerciale par ville).

Pour démontrer la robustesse du code et simuler un volume réaliste, ce projet intègre un **module de génération de données synthétiques** créant un historique de 1000 transactions sur l'année 2024.

## 🎯 Objectifs de l'analyse

1.  **Nettoyage & Préparation :** Conversion des types, gestion des dates, création de nouvelles métriques (Chiffre d'affaires, Mois).
2.  **Analyse Temporelle :** Identifier les tendances de ventes mensuelles et la saisonnalité.
3.  **Performance Produits :** Distinguer les produits générateurs de volume vs générateurs de revenus.
4.  **Analyse Géographique :** Comparer la performance des magasins (Paris, Lyon, Marseille, etc.).

## 🛠️ Technologies Utilisées

* **Python** : Langage principal.
* **Pandas** : Manipulation et agrégation de données (`groupby`, `pivot_table`).
* **Matplotlib / Seaborn** : Visualisation de données.
* **NumPy / Random** : Génération de données aléatoires pour la simulation.

## 📂 Structure du Notebook

Le notebook `analysis.ipynb` suit une approche structurée :
1.  **Génération de Données :** Création d'un dataset fictif de 1000 lignes (Date, Produit, Prix, Ville).
2.  **Data Cleaning :** Vérification des types et calcul du CA (`Quantité * Prix`).
3.  **Exploration (EDA) :**
    * *KPIs globaux* : CA total, Panier moyen.
    * *Top Produits* : Les "Portables" dominent le CA, tandis que les accessoires dominent le volume.
    * *Top Villes* : Répartition du CA par zone géographique.
4.  **Visualisation :** Graphiques temporels et Heatmaps de corrélation (Produit/Ville).
