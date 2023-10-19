# Application Web de gestionnaire de tâches

Une application de gestion de tâches inspirée de JIRA qui vous permet de gérer vos tâches quotidiennes.

**Description du Projet :**

Notre projet consiste en une application full stack basée sur une architecture de microservices, déployée à l'aide de conteneurs Docker. L'objectif principal est de créer une application de gestion de tâches, offrant des fonctionnalités de création, de mise à jour et de suppression de tâches, avec un frontend en React et un backend en Flask. La base de données MySQL stocke les informations sur les tâches.

**Architecture du Projet :**

- **Frontend en React** : Le frontend est développé en React, fournissant une interface utilisateur réactive avec une page d'accueil pour la liste des tâches et une route générique pour la gestion individuelle des tâches.

- **Backend en Flask** : Le backend est implémenté en utilisant Flask, un framework web Python, offrant des API endpoints pour les opérations CRUD. L'authentification est assurée à l'aide de jetons JWT pour la sécurité.

- **Base de Données MySQL** : La base de données MySQL stocke les informations sur les tâches, avec une table et un schéma explicite.

- **Docker et Docker Compose** : Les composants du projet sont conteneurisés avec Docker, et Docker Compose est utilisé pour orchestrer ces conteneurs, facilitant ainsi le déploiement et la gestion.

**Technologies Prévues :**

- **Frontend :** React
- **Backend :** JavaScript
- **Base de Données :** MongoDB
- **Conteneurs :** Docker
- **Orchestration :** Docker Compose
- **Tests :** Fichiers de tests pour la santé des conteneurs, les fonctionnalités de l'application, et les tests de base de données.

Ce projet permet d'illustrer une approche complète de développement et de déploiement d'une application full stack moderne en utilisant une architecture de microservices et des technologies contemporaines.

**SCHÉMA DE L'APPLICATION :**

![image](./Screenshots/SCHEMA.png "Schéma de l'application")

## Configuration de l'environnement de développement
1. **Prérequis**
   - Vous devez avoir [node.js](https://nodejs.org/en/) installé sur votre machine.
2. **Installation des dépendances**
   - Ce projet est partagé sans le dossier node_modules, vous devez donc installer toutes les dépendances vous-même.
   - Pour installer les dépendances :
      Ouvrez votre ligne de commande.
      Accédez aux répertoires suivants : `/frontend/task-manager-app/` et `/backend`.
      Exécutez `npm install` ou `npm i` pour installer toutes les dépendances.
3. Après avoir installé toutes les dépendances, vous êtes prêt à lancer l'application :
   - Pour démarrer l'application, exécutez `npm start` dans les deux répertoires.

## Fonctionnalités
### 1. Vues multiples
   <p> Il existe 3 façons de voir et de gérer vos tâches : </p>

1. **Vue en liste** :

   ![Liste](./Screenshots/1.png "Vue en liste" )

   - Vous pouvez faire glisser le texte pour changer son état ou cliquer sur la case à cocher.
   - Cliquez sur l'icône de menu déroulant pour afficher les informations que vous avez saisies sur la tâche :

   ![Information](./Screenshots/2.png "Information sur la tâche")

2. **Vue calendrier** :
   - Vous pouvez naviguer pour voir vos projets avec un calendrier personnalisé :

   ![Vue](./Screenshots/3.png "Vue calendrier")

   - Les jours qui ont une ou plusieurs tâches sont mis en évidence :
   
   ![Jours avec tâches](https://user-images.githubusercontent.com/97839369/221428621-67ad5d24-c7ab-4e46-9344-71276222f6c4.png)

   - Les tâches terminées ont une bordure verte :

   ![Tâches](./Screenshots/4.png "Tâches terminées")

   - Tandis que les tâches non terminées ont une bordure rouge :

   ![Tâches](./Screenshots/5.png "Tâches non terminées")

   - Cliquez sur l'icône de menu déroulant pour afficher les informations que vous avez saisies sur la tâche :

   ![Information](./Screenshots/6.png "Information sur la tâche")

3. **Vue en tableau** :
      ![Vue](./Screenshots/7.png "Vue en tableau")

   - Vous pouvez faire glisser le texte pour changer son état :

   ![Changement](./Screenshots/8.png "Changement d'état")

   - Cliquez sur l'icône de menu déroulant pour afficher les informations que vous avez saisies sur la tâche :

   ![Information](./Screenshots/9.png "Information sur la tâche")

### 2. Notifications
<p> Vous êtes notifié pour chaque action que vous effectuez </p>

   ![Notifications](https://user-images.githubusercontent.com/97839369/221429251-af13e90e-e49b-497c-8b51-c8447ddd841a.png)
   ![Notifications](https://user-images.githubusercontent.com/97839369/221429277-e72093ca-3064-4c08-a35d-c23728c4b8d5.png)

### 3. Responsive
L'application est entièrement responsive :

   ![Responsive](./Screenshots/10.png "Responsive")

