# 6bis_arbre_decision_hyperparametres_botanique_part_2

Partie II : Arbres de Décision, Hyperparamètres et Botanique

Introduction :
Le précédent exposé nous a introduits à un modèle de Machine Learning innovant : les arbres de décision. Comme pour la majorité des modèles, divers hyperparamètres nécessitent un ajustement via la validation croisée. Notre attention se porte ici spécifiquement sur un hyperparamètre crucial : la profondeur de l'arbre. L'objectif de cette partie est d'explorer les différentes techniques de validation croisée, en se concentrant sur l'exemple concret de l'Iris Dataset.

Contexte du Projet :
Afin de maîtriser la validation croisée, une présentation dans un notebook est nécessaire. La présentation peut se limiter à trois cellules markdown, chacune détaillant une aspect particulier de la validation croisée :

La première diapositive expose la validation croisée "traditionnelle".
La deuxième diapositive décrit le principe de la "k-fold cross-validation".
La troisième diapositive présente la "leave-one-out cross-validation".
Jupyter Notebook 1 : Validation Croisée Traditionnelle

Importation des librairies.
Chargement des données.
Préparation des données.
Échantillonnage des données en utilisant la technique de validation croisée traditionnelle.
Affichage de la distribution des données.
Automatisation de l'apprentissage du modèle :
Poursuivez le Jupyter Notebook en implémentant une recherche par grille de la valeur optimale de l'hyperparamètre "max_depth". Il est impératif de ne pas utiliser les routines de scikit-learn à cette étape. Évaluez et affichez les performances sur les jeux d'apprentissage, de validation et de test.

Jupyter Notebook 2 : k-fold Cross-Validation (k=3)

Importation des librairies.
Chargement des données.
Préparation des données.
Echantillonnage des données en utilisant la technique de "k-fold cross-validation" avec k égal à 3.
Affichage de la distribution des données.
Automatisation de l'apprentissage du modèle :
Continuez en implémentant la recherche par grille de l'hyperparamètre "max_depth" selon un schéma de "3-fold cross-validation", sans utiliser les routines de scikit-learn. Évaluez et affichez les performances sur les différents jeux de données.

Exercice Subsidiaire :
Pour les plus audacieux, répétez l'exercice en mettant en œuvre une "leave-one-out cross-validation". Cette étape peut être réalisée en utilisant la fonction GridSearchCV() de scikit-learn.

Livrables :
Fournissez les Jupyter Notebooks résultants de chaque étape de l'analyse.
