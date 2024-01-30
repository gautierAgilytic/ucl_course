# Exercise
## Introduction
Enregistrez vous dans google colab et ajoutez le scripts ucl_course.ipynb. 

Google colab vous permettra de faire du python sans rien installer sur votre pc.
Le contexte est l'annalyse des écureuils dans les parcs de new york.

Vous avez un datalake sur Azure à votre disposition avec 3 étage de données **bronze, silver, gold**

Les trois fichiers initiaux se trouvent dans le container **Bronze** :
- squirrel/park-data_.parquet
- squirrel/squirrel-data.parquet
- squirrel/stories.parquet


## Etape 
1. Compter le nombre de catégorie de parc
2. Garder 3 catégories de liter 
3. Pour un écureuil ne garder que la première couleur de la fourrure principales.
4. Créer une table unique qui contient toutes ses informations et écrivez la dans le datastage **Gold** sous la forme d'une table unique. Spécifiez votre nom pour le path : *"gautierRader/reporting_squirrel.parquet"*

## Commandes pratique 
- df.show()
- df.printSchema()
- df.count()
- df.select()
- df.distinct()
