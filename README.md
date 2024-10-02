"# Titanic" 
Ce projet constitue un exercice complet de traitement et d'analyse de données, incluant la préparation, la visualisation et l'application d'algorithmes de Machine Learning supervisé sur le jeu de données du Titanic. Il s'agit d'un processus itératif visant à explorer les données, les préparer pour la modélisation, et entraîner différents modèles de classification afin de prédire la survie des passagers.

Technologies Utilisées
Python : Langage de programmation pour le traitement et l'analyse des données.
Pandas : Bibliothèque pour manipuler les DataFrames et analyser les données.
Numpy : Manipulation de matrices numériques et calculs statistiques.
Matplotlib et Seaborn : Outils de visualisation pour créer des graphiques.
Scikit-learn : Bibliothèque de Machine Learning pour l'entraînement et l'évaluation de modèles.
Grid Search : Technique d'optimisation hyperparamétrique pour trouver les meilleurs paramètres des modèles.
Phases du Projet
Phase 1 : Importation des Bibliothèques

Importation des bibliothèques Python, y compris Pandas, Numpy, Matplotlib, Seaborn, et Scikit-learn pour le traitement des données et la modélisation.
Phase 2 : Chargement des Données

Chargement des données Titanic à partir d'un fichier CSV, affichage des premières lignes, et vérification de la structure des données.
Nettoyage et traitement des données, notamment la suppression des valeurs manquantes, et conversion des données catégorielles en variables numériques.
Phase 3 : Exploration et Visualisation des Données

Création de graphiques pour analyser les corrélations entre différentes variables comme le sexe, la classe des passagers, et leur survie.
Exploration des distributions de données et identification des patterns visuels à partir des graphiques produits avec Seaborn et Matplotlib.
Phase 4 : Préparation des Données pour la Modélisation

Séparation des données en variables d'entrée (features) et variable cible (survie).
Normalisation des données pour améliorer la performance des algorithmes de Machine Learning.
Division des données en ensembles d'entraînement et de test (train-test split) pour valider les modèles.
Phase 5 : Modélisation avec Algorithmes de Machine Learning Supervisé

K-Nearest Neighbors (KNN) : Entraînement d'un modèle KNN pour prédire la survie des passagers en fonction des caractéristiques comme l'âge, le sexe, la classe, etc.
Decision Tree : Entraînement d'un arbre de décision pour mieux comprendre les relations entre les variables et leur impact sur la survie.
Random Forest : Application d'une forêt d'arbres décisionnels pour améliorer la robustesse et la précision des prédictions.
Phase 6 : Optimisation des Modèles avec Grid Search

Utilisation de Grid Search pour effectuer une recherche systématique des meilleurs hyperparamètres (comme le nombre de voisins pour KNN ou la profondeur maximale des arbres pour Decision Tree) en testant différentes combinaisons afin d'optimiser la performance des modèles.
Comparaison des scores de précision des modèles après optimisation.
Phase 7 : Évaluation des Modèles

Mesures de la performance des modèles à l’aide de métriques comme l'exactitude (accuracy), la précision, le rappel (recall) et le F1-score.
Comparaison des performances entre les modèles KNN, Decision Tree et Random Forest pour identifier le meilleur modèle prédictif pour la survie des passagers du Titanic.
Résultats et Conclusion
Le notebook permet non seulement de comprendre la structure des données du Titanic, mais aussi d'appliquer des techniques avancées de Machine Learning pour faire des prédictions de survie. L'utilisation de Grid Search pour optimiser les hyperparamètres a permis d'améliorer la performance des modèles, et le modèle final a été sélectionné en fonction des meilleures performances sur l'ensemble de test.
