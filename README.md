# Titre du projet
Nettoyage de données – Projet Factures Clients (Online Retail II)

# Description du projet
Ce projet consiste à analyser et nettoyer un dataset de facturation client issu du e-commerce,
basé sur le fichier "Online Retail II" disponible sur Kaggle. L'objectif est d'identifier et
corriger les anomalies les plus courantes (valeurs manquantes, doublons, retours produits, fautes de frappe),
et de rendre les données exploitables pour des analyses commerciales futures.

# 📂 Fichiers inclus
- `data/` : dossier contenant le fichier brut (non publié sur GitHub)
- `Nettoyage_de_données Kaggle.ipynb` : notebook principal de nettoyage utilisable sur google collab
- `outputs/` : dataset nettoyé (data_Nettoyées.xlsx)

# ⚙️ Technologies utilisées
- Python 3.x
- Pandas
- Wordninja
- Pyspellchecker
- Jupyter Notebook

# 📊 Étapes réalisées
1. Chargement des données brutes (fichier Excel)
2. Analyse des valeurs manquantes
3. Suppression ou traitement des doublons
4. Nettoyage des textes collés dans les colonnes produits
5. Suppression des tokens aberrants ("t", "s", etc.)
6. Export du dataset nettoyé

🚀 Résultat final

Un fichier CSV/xlsx prêt à l’analyse, avec :
- 0 doublons
- 0 valeur manquante critique
- Textes produits lisibles
