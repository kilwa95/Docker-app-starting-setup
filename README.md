# Projet Node.js avec Docker

Ce projet contient une configuration Docker pour exécuter une application Node.js.

## Prérequis

- Docker doit être installé sur votre machine.

## Instructions

Suivez ces étapes pour exécuter l'application dans un conteneur Docker.

### Étape 1: Cloner le dépôt

Clonez ce dépôt sur votre machine locale:

```bash
git clone https://github.com/kilwa95/nodejs-app-starting-setup
cd <NOM_DU_RÉPÔT>
```
### Étape 2: Construire l'image Docker
```bash
docker build .
```

### Étape 2: Exécuter le conteneur Docker
```bash
docker run -p 3000:80 nom-de-votre-image
```

