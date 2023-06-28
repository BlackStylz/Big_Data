# Big_Data
Traitement de données massives via instance EMR de AWS
 
Mettre en place les premières briques de traitement pour un passage à l’échelle en termes de volumes de données. En vue de réaliser un modèle de classification automatique
Contraintes:
- Diffusion des poids du modèle Tensorflow
- Réduction de dimensions de type PCA en PySpark

## Jeu de données:
Type de données images
131 fruits différents
Entre 297 et 984 fichiers par fruits 
(~68 000 fichiers au total)


## Script PySpark
Le script est exécuté via l'application JupyterHub d'une instance EMR
![image](https://github.com/BlackStylz/Big_Data/assets/92699143/6970e99c-8d99-4f94-b21e-aeeb825efef4)

## Visualistion 
Visualisation des fruits sur les 2 premières composantes ACP
