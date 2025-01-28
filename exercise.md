# Exercise
## Introduction
Enregistrez vous dans google colab et ajoutez le scripts ucl_course.ipynb. 

[Google colab](https://colab.research.google.com/) vous permettra de faire du python sans rien installer sur votre pc.
Le contexte est l'analyse des écureuils dans les parcs de new york.

Vous avez un datalake sur Azure à votre disposition avec 3 étages de données **bronze, silver, gold**

Les trois fichiers initiaux se trouvent dans le container **Bronze** :
- squirrel/park-data_.parquet
- squirrel/squirrel-data.parquet
- squirrel/stories.parquet


## Etapes
1. Compter le nombre de parc area
2. Garder 3 catégories de liter 
3. Pour un écureuil ne garder que la première couleur des "highlights" de fourrure.
4. Créer une table unique qui contient toutes ses informations et écrivez la dans le datastage **Gold** sous la forme d'une table unique. Il faut également que l'histoire associée à chaque "area" soit présente. Spécifiez votre nom pour le path : *"gautierRader/reporting_squirrel.parquet"*

## Commandes pratiques
- df.show()
- df.printSchema()
- df.count()
- df.select()
- df.distinct()

## Documentation pratique
- Le site web [Spark By Example](https://sparkbyexamples.com/pyspark-tutorial/) contient enormément de ressources avec des exemples
- [Documentation officiel PySpark](https://spark.apache.org/docs/latest/api/python/getting_started/quickstart_df.html)