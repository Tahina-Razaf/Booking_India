# ✈️ Projet : Prix des réservations des vols en Inde (**Booking_India**)

## 🧩 Contexte et objectif
L'objectif de ce projet est de **comprendre les facteurs qui influencent les prix des vols entre plusieurs villes indiennes** et de **mettre en place un modèle de prédiction des prix**.  
Ce projet permet d’explorer les tendances du marché aérien indien et de créer un modèle prédictif fiable basé sur les données historiques de réservation.

---

## 👤 Mon rôle
Projet **100% personnel**.  
J’ai pris en charge **toutes les étapes du projet**, de l’importation des données à la validation du modèle final.  
Les détails des étapes et analyses sont présentés dans la section suivante : **Analyse et notebook**.

---

## 📊 Sources de données
Le jeu de données analysé provient de **Kaggle** et contient des informations relatives aux réservations de vols opérant entre plusieurs villes indiennes.  
Les observations concernent des vols enregistrés à un certain nombre de jours avant la date de départ. Les données sont structurées et proviennent d’une source en ligne fiable.

### Variables principales du dataset :
- `index` : identifiant unique de chaque observation (entier)  
- `airline` : compagnie aérienne (catégorielle)  
- `flight` : numéro de vol (catégorielle)  
- `source_city` : ville de départ (catégorielle)  
- `departure_time` : période de la journée du départ (catégorielle, 6 modalités)  
- `stops` : nombre d’escales ("one", "two", "three"), converti en entier pour l’analyse  
- `arrival_time` : période de la journée de l’arrivée (catégorielle)  
- `destination_city` : ville de destination (catégorielle)  
- `class` : classe de réservation (Business / Economy)  
- `duration` : durée du vol en heures (float)  
- `days_left` : nombre de jours avant le départ (entier)  
- `price` : prix du vol (float)  

Le dataset est globalement propre et cohérent, mais des vérifications de qualité standard ont été réalisées pour garantir la fiabilité des analyses.

---

## ⚙️ Outils et technologies
- **Python**  
- **Pandas** pour la manipulation et le nettoyage des données  
- **Matplotlib** et **Seaborn** pour la visualisation  
- **Machine Learning** pour la création et l’évaluation des modèles  
- **Jupyter Notebook** comme environnement de travail  

---

## 📝 Analyse et notebook
Le projet est contenu dans un unique **notebook**, regroupant toutes les étapes d’un workflow complet de création de modèle :  
1. Importation des données  
2. Compréhension de base des données (description et exploration initiale)  
3. Nettoyage des données  
4. Analyse exploratoire des données  
5. Ingénierie des variables  
6. Entraînement des modèles (modèle de base et modèle de comparaison)  
7. Optimisation du modèle  
8. Évaluation des modèles  
9. Validation du modèle choisi  

---

## 🔑 Résultats clés
- Modèle final utilisé : **Lasso Regression**  
- Visualisations des insights principaux dans la section suivante

---

## 📈 Visualisations clés

### 1. Différence de prix entre classes de réservation
![Différence de prix entre classes](Visualisations%20clés/Boxplot_prix_class.jpg)

### 2. Différence de prix entre compagnies aériennes
![Différence de prix entre compagnies](Visualisations%20clés/Boxplot_prix_compagnies.jpg)

### 3. Coefficients du modèle Lasso
![Coefficients du modèle Lasso](Visualisations%20clés/Coeff_Lasso.jpg)

### 3. Précision du modèle Lasso
![Précision du modèle Lasso](Visualisations%20clés/Model_precision.jpg)

---

## 🔗 Lien vers le projet
[Accéder au notebook sur GitHub](https://github.com/Tahina-Razaf/Booking_India)
