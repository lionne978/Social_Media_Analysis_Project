# 🌐 Analyse de Réseaux Sociaux : Facebook  
**Projet académique | UNCHK | 2024**

## 📚 Objectif
Analyser un réseau social à partir du dataset **facebook_combined.txt** disponible sur le site **Stanford Network Analysis Project (SNAP)**, en appliquant des méthodes d’analyse de graphes et de réseaux sociaux.

## 🛠️ Outils et Technologies
- **Python** (via **Jupyter Notebook**)
- **NetworkX** pour la manipulation de graphes
- **Pandas**, **NumPy** pour le traitement des données
- **Matplotlib** pour la visualisation
- **community** (python-louvain) pour la détection de communautés

## 📂 Étapes principales
1. **Importation des bibliothèques**
   - `networkx`, `pandas`, `numpy`, `matplotlib`, `community`

2. **Chargement des données**
   - Lecture du fichier `facebook_combined.txt`
   - Affichage du nombre de nœuds et d’arêtes
   - Première visualisation du graphe

3. **Analyse des métriques topologiques globales**
   - Calcul de la densité
   - Calcul du diamètre
   - Calcul du coefficient de clustering moyen

4. **Analyse des métriques de centralité**
   - Degré
   - Centralité de proximité
   - Centralité d'intermédiarité
   - Centralité de vecteur propre
   - Visualisation des distributions et identification des nœuds influents

5. **Détection de communautés**
   - Utilisation de l'algorithme de Louvain
   - Visualisation des communautés
   - Affichage du nombre de communautés détectées

6. **Simulation de diffusion d'information**
   - Simulation de la propagation de contenu à partir des nœuds les plus influents
   - Comparaison de la diffusion selon différentes mesures de centralité

## 🧠 Concepts abordés
- **Métriques topologiques globales** : densité, diamètre, coefficient de clustering
- **Centralités** : degré, proximité, intermédiaire, vecteur propre
- **Analyse structurale** : composantes connexes, sous-graphes
- **Détection de communautés** : Louvain, Girvan-Newman
- **Diffusion de contenu** sur un réseau social
- **Campagnes de marketing viral** via ciblage des influenceurs

