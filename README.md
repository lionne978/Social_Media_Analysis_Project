🎬 Analyse des Sentiments de Critiques de Films (IMDB)
Projet académique | UNCHK | Octobre - Novembre 2024

📚 Contexte
Ce projet s'inscrit dans le cadre d'un travail académique visant à explorer des techniques de traitement du langage naturel (NLP) et de Machine Learning. L'objectif est de construire un modèle performant capable de prédire le sentiment (positif ou négatif) à partir de critiques de films issues d'IMDB.

📂 Dataset
Source : Plateforme Kaggle (IMDB Dataset of 50K Movie Reviews)

Taille : 50 000 critiques de films équilibrées entre classes positives et négatives.

🛠️ Outils et Technologies
Python (via Jupyter Notebook)

Bibliothèques principales :

pandas, numpy pour la manipulation des données

nltk, re pour le traitement du texte

scikit-learn pour la modélisation machine learning

matplotlib, seaborn pour la visualisation des données

🧹 Processus
Nettoyage des données : suppression des caractères spéciaux, mise en minuscules, retrait des stopwords.

Analyse exploratoire :

Identification des mots les plus fréquents dans les critiques positives et négatives.

Visualisation via nuages de mots.

Modélisation :

Vectorisation des textes avec TF-IDF.

Application de plusieurs algorithmes de classification :

Régression Logistique

Random Forest

Support Vector Machine (SVM)

Sélection du meilleur modèle basé sur la précision et le lift.

Résultats :

Précision finale : 90%

Lift : 34%

📈 Résultats
Le modèle final offre une capacité robuste de prédiction du sentiment avec un équilibre entre précision et rappel, démontrant l'efficacité de la préparation de données et du choix des algorithmes.
