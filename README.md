# OC_Projet8 : Déployer un modèle sur le cloud
## Créé par Agnès Regaud

## Sujet
Je suis Data Scientist dans une jeune start-up de l'AgriTech nommée Fruits qui cherche à proposer des solutions innovantes pour la récolte des fruits.
Leur objectif est de préserver la biodiversité des fruits en développant des robots cueilleurs intelligents qui permettraient un traitement spécifique de chaque espèce de fruits.
Cette start-up veut commencer à se faire connaître tout d'abord en mettant à disposition du grand public une application mobile permettant aux utilisateurs de prendre en photo un fruit afin d'obtenir des informations sur ce fruit.

Et c'est donc l'objet de la mission :
Dans un contexte de gros volume de données et donc d'environnement Big Data, il s'agissait ici de développer les 1ères briques de cette application mobile en se servant d'un notebook réalisé par un alternant qui vient de quitter l'entreprise. Ce travail a servi de point de départ pour la chaîne de traitement de données, et je l'ai complété avec une étape de réduction de dimensions des features.

Le projet a été réalisé en 2 temps, dans deux environnements différents.
J'ai, dans un premier temps, développé et exécuté le code en local, en travaillant sur un nombre limité d'images à traiter.
Une fois les choix techniques validés, j'ai déployé la solution dans un environnement Big Data en mode distribué.

Le script a été développé en PySpark et déposé sur le cloud d'AWS avec des serveurs situés sur le territoire européen afin de respecter les contraintes du RGPD et ne pas engendrer de coût trop élevé.

## Objectifs du projet
- Hadoop en local
- scripts en Pyspark : préprocessing et PCA
- architecture Big Data : Utiliser le cloud AWS (EMR, S3, IAM)
- Démonstration en direct de la mise en place d'une instance AWS
- Respect des contraintes du RGPD, et de coût à limiter en paramétrant correctement l'installation afin d’utiliser des serveurs situés sur le territoire européen 

## Compétences évaluées
- Utiliser les outils du cloud pour manipuler des données dans un environnement Big Data
- Identifier les outils du cloud permettant de mettre en place un environnement Big Data
- Paralléliser des opérations de calcul avec Pyspark
