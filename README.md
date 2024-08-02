# Titre du projet
Clara-Jira-AI
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)  [![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)

Une petite description du projet

## Pour commencer

Entrez ici les instructions pour bien débuter avec votre projet...

### Pré-requis

Ce qu'il est requis pour commencer avec votre projet...

- Rancher deskop
- Node:19:bullseye
- 

### Installation
``docker pull node:19-bullseye``


## Démarrage
Remplir le fichier ``credential.json`` & ``atlassian-connect-json``

``docker compose -f docker-compose.yml -p clarai up --build -d --pull always --force-recreate``

``docker exec -it clarai-node-1 sh``

``cd clara-ai``

``npm run build``

``npm start``




## Auteurs
Lilian Allio




