<h1>Prédiction du Diabète</h1>

<h2>Objectifs</h2>
- Identifier les individus présentant un risque de diabète à partir de données médicales.
- Utiliser des techniques de prétraitement des données et d'extraction des caractéristiques pour améliorer les performances des modèles.
- Comparer plusieurs algorithmes afin de sélectionner le modèle offrant la meilleure précision et fiabilité.
Contenu du projet
Le projet suit une méthodologie structurée en plusieurs étapes :
1. **Analyse des données** : Compréhension et exploration des données médicales.
2. **Prétraitement des données** : Nettoyage, gestion des valeurs manquantes et normalisation des données.
3. **Extraction des caractéristiques** : Sélection des attributs les plus significatifs pour la prédiction.
4. **Construction des modèles** : Utilisation d'algorithmes d'apprentissage supervisé, tels que :
   - Régression logistique (LR)
   - Arbre de décision (DT)
   - Support Vector Machines (SVM)
   - K-Nearest Neighbors (KNN)
   - Forêt aléatoire (RF)
   - Gradient Boosted Decision Trees (GBDT)
5. **Évaluation des performances** : Comparaison des modèles à l'aide des métriques comme l'accuracy et le score ROC-AUC.
Visualisation des performances
Les performances des modèles sont représentées par un graphique comparant les taux d'accuracy et de ROC-AUC pour chaque algorithme. Les barres orange clair et orange foncé permettent une lecture claire et intuitive.
Résultats attendus
Les modèles développés permettent de fournir des prédictions fiables pour la détection précoce du diabète. Cela contribue à mieux cibler les individus à risque et à optimiser les efforts de prévention et de traitement.
Utilisation
1. **Prérequis** :
   - Python 3.8 ou supérieur
   - Librairies nécessaires : `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

2. **Exécution** :
   - Exécuter le fichier Jupyter Notebook fourni (`Diabete.ipynb`) pour reproduire les étapes du projet.

3. **Visualisation** :
   - Les résultats des performances des modèles sont sauvegardés dans un fichier image (`PE_diabetes.jpeg`).
