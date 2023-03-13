# Analyse de la clientèle d'un concessionnaire 

Contactés par un concessionaire, il nous est confié la mission de mieux cibler les véhicules susceptibles d'intéresser les clients. Pour cela, le concessionnaire met à disposition plusieurs fichiers contenants différentes informations, notamment la liste des véhicules et leurs caractéristiques, la liste des véhicules achetés durant l'année. 

# L'objectif 
L'objectif étant ainsi d’évaluer en temps réel le type de véhicule le plus susceptible d'intéresser des clients qui se présentent dans la concession 

# Mise en oeuvre
Pour ce faire, nous construisons un data lake après avoir chargé les données des différents fichiers dans différentes sources

# Contenu des fichiers
- Le fichier rapport.pdf décrit les différentes étapes suivies afin de réaliser le data lake
- Le notebook analyse-avec-spark.ipynb est un exemple de traitement (avec Spark) sur les données récupérés du data lake
- Le fichier java ImportCatalogue.java est un programme permettant de charger les données d'un fichier .csv dans une table OracleNoSQL