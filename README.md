La lecture du notebook se fait de façon chronologique, du notebook 1 au 12:

- Notebook "Partie 1" : Extraction et séléection des données depuis les bases de données CEREMA (DVF) et BDNB + Création de la variable "Etaban" qui servira de clé de fusion ente les datasets.

- Notebook "Partie 2" : Identification des lots qui correspondent aux appartements pour obtenir une ligne par mutation d'appartement + Création de la variable cible qui déterminera si un bien a été revendu au moins une fois sur la période 2014-2021.

- Notebook "Partie 3" : Feature engenering sur la première sélection de variable.

- Notebook "Partie 4" : Recherche des variables les plus significatives à présenter en visualisation.

- Notebook "Partie 5" : Premières data visualisation.

- Notebook "Partie 6" : Sélection des features pour modélisation par régression - Target = qty_of_mut (Utilisation de Lasso , Variance Treshold, SelectKBest)

- Notebook "Partie 7" : Sélection de features pour modélisation par classification - Target = Revente (Utilisation de RFE, SelectFromModel, SelectKBest)

- Notebook "Partie 8" : Tentative de réduction de dimension par PCA / LDA.

- Notebook "Partie 9" : Feature engenering sur le deuxième sélection de variable.

- Notebook "Partie 10" : Data visualisation de cette deuxième sélection de variables.

- Notebook "Partie 11" : Modélisation à partir des variables explictives exclusivement liées au bâtiment + Optimisation du meilleur modèle obtenu.

- Notebook "Partie 12" : Modélisation à partir de 2 variables créées à partir des variables issues de DVF: "durée_de_détention" et "evol_val" + Optimisation du meilleur modèle obtenu.
