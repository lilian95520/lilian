# Clara-Jira-AI

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)  [![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)

## Introduction
Clara-Jira-AI is a project designed to enhance Jira functionalities using AI capabilities. This README will guide you through the setup, installation, and usage of the project.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Starting the Project](#starting-the-project)
- [Authors](#authors)

## Getting Started
These instructions will help you set up and run the Clara-Jira-AI project on your local machine.

### Prerequisites
Make sure you have the following installed:
- [Rancher Desktop](https://rancherdesktop.io/)
- [Node.js 19 (Bullseye)](https://hub.docker.com/_/node)

### Installation
To install the necessary Docker image, run the following command:
```sh
docker pull node:19-bullseye
```
## Usage
### Starting the Project
1. Fill in the `credential.json` and `atlassian-connect.json` files with the necessary information.
2. Run the following commands to build and start the project:
    ```sh
    docker compose -f docker-compose.yml -p clarai up --build -d --pull always --force-recreate
    ```
3. Access the container shell:
    ```sh
    docker exec -it clarai-node-1 sh
    ```
4. Navigate to the project directory:
    ```sh
    cd clara-ai
    ```
5. Build the project:
    ```sh
    npm run build
    ```
6. Start the project:
    ```sh
    npm start
    ```

## Authors
- Lilian Allio
