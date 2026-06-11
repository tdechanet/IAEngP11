# Projet 11: Réalisez un traitement dans un environnement Big Data sur le Cloud

## Synopsis

Ce projet est réalisé dans le cadre de la formation AI Engineer de OpenClassrooms. Il a pour but le déploiement d'un cluster via AWS pour featuriser des images et appliqué une réduction de dimension.

## Données

Les [données](https://www.kaggle.com/datasets/moltean/fruits) sont des images représentants des fruits. Nous allons utiliser un dossier contenant prêt de 20 000 images.

## Arborescense

- **data/** : Ce dossier contient les données que nous utiliserons pour le projet.

- **notebooks/** : Ce dossier contient le notebook utilisé pour tester nos solutions en local avant de faire appel à AWS. Il contient aussi les données de test.

- **bootstrap-emr** : Ce fichier est déployé sur notre S3 et il sert à la mise en place de l'EMR. Il contient des imports nécessaire au fonctionnement du projet.

- **JupyterHub.ipynb** : Ce notebook est celui qui est exécuté sur l'EC2 maître via JupyterHub.