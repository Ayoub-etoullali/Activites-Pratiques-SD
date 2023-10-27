# Atelier de Régression 

# Problème 1

## Partie 1 : Régression Linéaire Simple

Ceci est la première partie d'un atelier de Data Mining portant sur la régression linéaire simple en utilisant l'ensemble de données "Advertising". Cette partie vous guidera à travers les étapes de préparation des données, d'exploration, d'ajustement du modèle de régression linéaire simple, et d'évaluation de la performance du modèle.

#### Objectifs
- Charger les données à partir du fichier "advertising.csv".
- Visualiser les données à l'aide de graphiques.
- Diviser les données en ensembles d'apprentissage et de test.
- Ajuster un modèle de régression linéaire simple en utilisant la descente de gradient en lot.
- Mesurer la performance du modèle en calculant l'erreur quadratique moyenne (MSE).

#### Prérequis
Python (3.x recommandé) et les bibliothèques suivantes :
  - Pandas
  - NumPy
  - Matplotlib
  - scikit-learn (pour la division des données)
  
#### Instructions
1. Clonez ou téléchargez ce référentiel sur votre ordinateur.
2. Assurez-vous d'avoir les bibliothèques Python requises installées. Vous pouvez les installer à l'aide de pip :
`pip install pandas numpy matplotlib scikit-learn`
3. Exécutez le code Python présenté dans le fichier Jupyter Notebook ou un environnement de développement Python de votre choix.
4. Suivez les commentaires dans le code pour comprendre chaque étape de l'atelier.

#### Structure des fichiers

- `Problème 1 - Régression Linéaire.ipynb` : Le fichier Jupyter Notebook contenant le code Python pour la partie 1 de l'atelier.

#### Ressources supplémentaires
Pour en savoir plus sur la régression linéaire et la descente de gradient, consultez des ressources telles que des tutoriels en ligne et des cours d'apprentissage automatique.

# Documentation sur la Régression Logistique, la Matrice de Confusion et la Métrique d'Accuracy

Ce README fournit une documentation sur l'utilisation de modèles de régression logistique, de matrices de confusion et de la métrique d'accuracy en Python. Le document couvre à la fois l'implémentation manuelle et l'utilisation de scikit-learn pour la régression logistique.

## Partie 2 :
- Load the data from the CSV file.
- Split the data into training and testing sets (80% for training and 20% for testing).
- Implement batch gradient descent to find the best-fitting linear regression model.
- Visualize the evolution of the Mean Squared Error (MSE) during training.
- Print the model's error on the test data.
  
Interpret the Results:

- The script will output the error of the model on the test set. A lower error indicates a better fit.
- You can use the model parameters to make predictions on new data.
- Implementation Details
- The linear_regression.py script loads data, implements gradient descent, and visualizes the training process.
- The implementation uses the Mean Squared Error (MSE) as the cost function.
- The script offers flexibility to configure learning rate, epsilon, and the number of iterations to suit your needs.

# Problème 2
## Implémentation Manuelle de la Régression Logistique

### a) Création du Modèle
- Importez les bibliothèques nécessaires, comme NumPy.
- Initialisez les paramètres du modèle, tels que le vecteur de poids et le biais.
- Définissez la fonction sigmoïde pour la régression logistique.
- Définissez la fonction d'hypothèse et la fonction de coût (perte logistique).
- Calculez le gradient de la fonction de coût et mettez à jour les paramètres à l'aide de la descente de gradient.

### b) Entraînement du Modèle
- Utilisez vos données d'entraînement pour ajuster les paramètres du modèle.

### c) Affichage des Coefficients
- Après l'entraînement, vous pouvez afficher les coefficients du modèle.

### d) Tracé de la Fonction Logit
- Utilisez Matplotlib pour visualiser la fonction sigmoïde.

### e) Tracé de la Fonction Sigmoid
- Visualisez la fonction sigmoïde à l'aide de Matplotlib.

### f) Faire des Prédictions
- Utilisez le modèle appris pour faire des prédictions pour des points de données individuels, par exemple, pour une personne ayant un taux de glucose de 197.

### g) Faire des Prédictions pour Plusieurs Points de Données
- Étendez le modèle pour prédire les résultats pour un ensemble de personnes ayant différents taux de glucose.

## Tâche 4 : Matrice de Confusion

### a) Fonction Personnalisée pour Créer une Matrice de Confusion
- Créez une fonction Python qui génère une matrice de confusion à partir des vecteurs `y_real` et `y_predicted`.

### b) Tester la Fonction Personnalisée
- Testez la fonction personnalisée avec les vecteurs fournis.

### c) Matrice de Confusion pour le Modèle de Régression Logistique Manuelle
- Utilisez la fonction `confusion_matrix` de scikit-learn pour générer la matrice de confusion pour le modèle de régression logistique manuelle.

### d) Calcul de l'Accuracy
- Expliquez la métrique d'accuracy et fournissez la formule de l'accuracy.
- Calculez l'accuracy pour le modèle de régression logistique manuelle en utilisant la matrice de confusion.

### e) Calcul de l'Accuracy en Utilisant scikit-learn
- Calculez l'accuracy en utilisant la fonction `accuracy_score` de scikit-learn.

## Conclusion de la Documentation

Ce README fournit un guide étape par étape pour travailler avec des modèles de régression logistique, des matrices de confusion et des métriques d'accuracy en Python. Il inclut à la fois l'implémentation manuelle et l'utilisation de scikit-learn pour la régression logistique. Utilisez cette documentation pour comprendre, mettre en œuvre et évaluer des modèles de régression logistique en Python.

## Auteur
<kbd>Ayoub ETOULLALI</kbd> 👨‍💻
