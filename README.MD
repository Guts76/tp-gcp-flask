# Cours CLI GCP
COurs sur GCP avec CI/CD

## Prérequis

1. Compte GCP
2. VSCode

## Description

Fichier doit contenir les ressources

Se placer à la racine du projet

``` shell

# Besoin d'initialisation si besoin
gcloud init

# Création d'une image
gcloud builds submit

```

L'image se trouve donc construite dans Google Build

On peut ensuite exécuter un conteneur avec Cloud Run > Créer un service et remplir les options demandées

Ici on peut le lier à un dossier GitHub pour pouvoir faire de la CI et du CD

## Notes

[GCP] : https://cloud.google.com/

[Cloud_Run] : https://console.cloud.google.com/run?project=cellular-axon-325108

