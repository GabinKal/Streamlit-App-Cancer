# CancerDetectApp: Streamlit ML Diagnostic Tool 🩺📊

## 📌 Description du projet

CancerDetectApp est une application interactive développée avec Streamlit qui permet de prédire la présence d’une tumeur bénigne ou maligne à partir de données médicales.
Le projet illustre l’utilisation d’un modèle de Machine Learning supervisé appliqué au domaine médical, tout en mettant l’accent sur :

la simplicité d’utilisation via une interface web intuitive,

la transparence des prédictions grâce à des visualisations interactives,

la reproductibilité à travers un code clair et structuré.

## ⚙️ Fonctionnalités principales

-🧬 Prédiction de cancer : le modèle de classification (par ex. Random Forest, Logistic Regression ou SVM selon ton entraînement) indique si la tumeur est bénigne ou maligne.

-📊 Interface utilisateur Streamlit : formulaire pour entrer les caractéristiques des cellules (features du dataset), bouton de prédiction en temps réel.

-📈 Visualisations interactives : graphiques explicatifs pour comprendre la répartition des données et la performance du modèle.

-💾 Gestion des dépendances : fichier requirements.txt généré automatiquement pour faciliter l’installation.

## 🛠️ Technologies utilisées

Python 3.11

Streamlit (interface web)

scikit-learn (machine learning)

pandas / numpy (traitement des données)

matplotlib / seaborn / plotly (visualisations, selon ce que tu as utilisé)

## 📂 Structure du projet

Streamlit-App-Cancer/
│── app/
│ └── main.py # Script principal Streamlit
│
│── asset/
│ └── style.css # Feuille de style personnalisée
│
│── data/
│ └── data.csv # Jeu de données utilisé pour l’entraînement/test
│
│── model/
│ ├── model.pkl # Modèle ML sauvegardé
│ └── scaler.pkl # Scaler sauvegardé (normalisation des features)
│
│── README.md # Documentation du projet
│── main.py # Script racine (point d’entrée alternatif)
│── requirements.txt # Dépendances Python

## 🎯 Objectif pédagogique

Ce projet est à vocation éducative et démonstrative.
Il ne constitue pas un outil médical officiel et ne doit pas être utilisé pour des diagnostics réels.
