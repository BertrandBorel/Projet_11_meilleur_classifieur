# Projet_11_meilleur_classifieur

## Contexte du projet
Cet atelier a pour objectif de manipuler les différentes techniques de classification supervisée sous Python, comme KNN, SVM, Foret Aléatoire, XGBoos et autre.

Dans cet atelier, nous appliquons apprentissage supervisé pour reconnaitre les Digits à partir d’un enregistrement audio.

​

## Challenges

###  Collection d’une base de données.
Analyse, prétraitement et visualisation des données.
Préparation des données pour l’apprentissage.
Préparation de Pipeline en utilisant « sklearn.pipeline.Pipeline ».
Choix de meilleur modèle.
Vérification de l’efficacité de ce modèle à des nouvelles données.
Intégration de ce modèle dans une application pour test temps réel.
​

## Phases de l'Atelir

​

## Partie 1 : Base de données, Analyse, Prétraitement et Préparation

​

Pour aborder cette problématique de la reconnaissance des Digits, il est primordial d’avoir ou de collecter une DataSet. Pour cela, la fonction « collection » dans Tools/tools.py vous permettra de collecter votre propre DataSet.

​

NB. La description de votre DataSet et le processus de collection doivent être notés dans le compte rendu final).

Par la suite, il faut Appliquer les traitements nécessaires pour préparer la DataSet en utilisant Numpy et Pandas. Les étapes de ce processus de traitement doivent être bien enchainer, claire, commenter et fonctionnelle dans le Notebook.

​

## Partie 2 : Pipeline Apprentissage/Classification Supervisée

​

Cette deuxième partie est réservée pour lancer une série d’expérimentation en préparant un Pipeline de plusieurs techniques de classification supervisé, notamment : KNN, SVM, Arbre de décision, Forêt Aléatoire et XGBoost.

​

Pour une étude expérimentale bien complète, il est recommandé de varier les paramètres de chaque technique utilisée, pour cela, il est préférable d’utiliser les outils proposés par Sklearn comme : Pipeline et GridSearchCV.

​

## Partie 3 : Mettre en place la solution dans une application Test Temps Réel

​

Utilisez la fonction « joblib » pour enregistrer votre modèle, cela une fois vous avez préparé votre meilleur modèle de classification.

​

Faites intégrer cette solution dans une Application en utilisant la fonction « rec » qui est dans Tools/tools.py.

​

## Modalités pédagogiques
Le deadline pour rendre ce travail est fixé pour le XX mars.

Le projet est réalisé en groupe de 2-3 personnes.

## Critères de performance
Une base de données bien préparée.
Le bon choix du modèle de classification supervisée.
Le bon fonctionnement de l'Application demandée.

## Modalités d'évaluation
L’évaluation de ce projet sera partagée entre :
- DataSet.
- La réalisation des différentes étapes décrite dans le contexte.
- Les Notebooks demandés.
- Le compte rendu demandé.
