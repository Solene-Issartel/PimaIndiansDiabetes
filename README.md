# PimaIndiansDiabetes
Compte rendu du TP d'Econométrie : Regression Logistique

## Dataset : PimaIndiansDiabetes

Actuellement, le dataset est lu depuis son dépôt disponible à l'adresse [https://plmlab.math.cnrs.fr/gdurif_teaching/polytech_ig5_regression_tutorial/raw/master/data/PimaIndiansDiabetes.csv](https://plmlab.math.cnrs.fr/gdurif_teaching/polytech_ig5_regression_tutorial/raw/master/data/PimaIndiansDiabetes.csv).

Si cela ne fonctionne pas, j'ai ajouté le csv (PimaIndiansDiabetes.csv). 
Il suffira de modifier le code 
```R
pima <- read.table("https://plmlab.math.cnrs.fr/gdurif_teaching/polytech_ig5_regression_tutorial/raw/master/data/PimaIndiansDiabetes.csv", sep = ";", header=TRUE)
```

par 

```R
pima <- read.table("PimaIndiansDiabetes.csv", sep = ";", header=TRUE)
```

## Formats disponibles

Le compte rendu est disponible en **R Markdown** et en **HTML**.

La version **PDF** est uniquement là si vous n'arrivez pas à lire les deux autres formats (mise en page de moins bonne qualité).
