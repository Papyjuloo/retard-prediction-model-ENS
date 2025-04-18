[French version below]

# retard-prediction-model-ENS
Analysis of Transilien train delays as part of an ENS challenge. Data exploration, visualizations, and modeling to identify the causes of delays.

# Transilien Train Delay Analysis 🚆

This project was developed as part of a data science challenge organized by ENS.  
The goal was to explore train delay data from the Transilien network and build a predictive model to determine whether a train would be delayed.

---

## 📊 Project Objective

- Analyze Transilien train data (routes, delays, disruptions, weather, etc.)
- Identify key factors contributing to delays
- Build a machine learning model to predict train delays

---

## 🧰 Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- XGBoost

---

## 📁 Project Structure

- `Challenge machine learning - Rendu final.ipynb`: Main notebook containing all steps from data cleaning and visualization to modeling.
- `README.md`: Project overview

---

## 📈 Modeling

The notebook includes:
- Data preprocessing (cleaning, encoding, feature engineering)
- Feature selection
- Model training using XGBoost
- Performance evaluation (accuracy, confusion matrix…)

---

## ✅ Results

The final model achieved solid performance in predicting train delays, with good class balance.  
Key features included type of disruption, train line, and weather conditions could be added to improve our model.


## 👤 Author

Project by Jules Le Beguec & Mathieu Lahoud
Contact: jules.le_beguec@mines-albi.fr mathiue.lahoud@mines-albi.fr
ENS Data Challenge – 2025


-----------------------------------------------------------------------------------------------------------------------------------------
# Analyse des retards des trains Transilien 🚆

Projet réalisé dans le cadre d’un challenge de data science organisé par l’ENS.  
L’objectif était d’explorer les données de ponctualité du réseau Transilien et de développer un modèle capable de prédire les retards de trains.

---

## 📊 Objectif du projet

- Analyser les données des trains Transilien (trajets, retards, perturbations, météo…)
- Identifier les variables influentes sur les retards
- Construire un modèle de machine learning pour prédire si un train sera en retard

---

## 🧰 Outils & Librairies

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- XGBoost

---

## 📁 Structure du projet

- `Challenge machine learning - Rendu final.ipynb` : Notebook principal contenant l’ensemble de l’analyse, des visualisations et de la modélisation.
- `README.md` : Présentation du projet

---

## 📈 Modélisation

Le notebook inclut :
- Prétraitement des données (nettoyage, encodage, features)
- Sélection de variables
- Entraînement d’un modèle XGBoost
- Évaluation des performances (précision, matrice de confusion…)

---

## ✅ Résultats

Le modèle obtient des performances satisfaisantes dans la détection des trains en retard, avec une précision équilibrée entre classes.  
Des variables comme le type de perturbation, la ligne ou les conditions météo pourraient être ajoutées au modèle afin de l'améliorer.

## 👤 Auteur

Projet réalisé par Jules Le Beguec & Mathieu Lahoud
Contact: jules.le_beguec@mines-albi.fr mathiue.lahoud@mines-albi.fr
Challenge ENS – 2025
