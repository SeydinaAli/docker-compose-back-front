# Application Spring Boot et React CRUD

Ce référentiel contient une application CRUD (Create, Read, Search) créée avec Spring Boot pour l'API REST backend et React pour l'interface utilisateur frontend.

## Mise en route

### Prérequis
Pour exécuter cette application, vous devez disposer des prérequis suivants :

- Java Development Kit (JDK) 17
- Node.js et npm (Node Package Manager)
- Base de données MySQL (avec un schéma nommé `hostbuddy_restapi`)

### Configuration

1. Clonez le référentiel sur votre machine locale.
<<<<<<< HEAD
`git clone https://github.com/SeydinaAli/docker-compose-back-front.git
=======
`git clone https://github.com/Millstack/springboot-react.git`
>>>>>>> 823407298ab5ec09d971a319bbe7816648b5a924

2. Configurez la base de données MySQL :
- Créez une base de données MySQL avec le nom `hostbuddy_restapi`
- Mettez à jour les propriétés de connexion à la base de données dans le fichier application.properties situé dans le dossier springboot-backend. Définissez les valeurs correctes pour spring.datasource.url, spring.datasource.username et spring.datasource.password

3. Créez et exécutez le backend Spring Boot :
- Ouvrez un terminal et accédez au dossier springboot-backend
- Créez l'application backend à l'aide de Maven : `./mvnw clean package`
- Exécutez l'application backend : `./mvnw spring-boot:run`

4. Installez les dépendances et exécutez le frontend React :
- Ouvrez un autre terminal et accédez au dossier react-frontend
- Installez les dépendances à l'aide de npm : `npm install`
- Démarrez le serveur de développement React : `npm start`

5. Accédez à l'application :
- Ouvrez un navigateur Web et accédez à http://localhost:3000 pour accéder au frontend React

# Structure de l'application

Le référentiel est structuré comme suit :
- `springboot-backend` : contient l'application backend Spring Boot
- `react-frontend` : contient le React application frontend

- Le backend Spring Boot suit une structure standard avec des packages pour différents composants :
- `com.hostbuddy` : package de base
- `com.hostbuddy.dto` : contient les objets de transfert de données (DTO) ou les classes d'entités
- `com.hostbuddy.repository` : contient les interfaces de référentiel pour interagir avec la base de données
- `com.hostbuddy.service` : contient les interfaces et implémentations de service
- `com.hostbuddy.controller` : contient les contrôleurs d'API REST

Le code du frontend React se trouve dans le dossier react-frontend

# Comment utiliser

- Le frontend React fournit une interface utilisateur pour interagir avec l'API REST du backend
- Vous pouvez ajouter, afficher tous les éléments et rechercher par nom via le frontend
- Le backend stocke les éléments dans la base de données MySQL
- Mettez à jour le fichier application.properties avec vos propres détails de connexion à la base de données si nécessaire

# Application React

<<<<<<< HEAD
- Clonez le référentiel : https://github.com/SeydinaAli/docker-compose-back-front.git
=======
- Clonez le référentiel : https://github.com/SeydinaAli/docker-compose-back-front.git
>>>>>>> 823407298ab5ec09d971a319bbe7816648b5a924
- Accédez au répertoire du projet : cd react-app
- Installez les dépendances : npm install
- Démarrez le serveur de développement : npm start
- Ouvrez votre navigateur et visitez `http://localhost:3000` pour voir l'application

## Utilisation
- La page d'accueil affiche une liste de tous les éléments récupérés de la base de données
- Cliquez sur le lien « Ajouter » dans la barre de navigation pour ajouter un nouvel élément
- Cliquez sur le lien « Rechercher » dans la barre de navigation pour rechercher un élément par son nom

<<<<<<< HEAD
Vous pouvez copier et coller ce contenu dans le fichier `README.md` de votre référentiel
=======
Vous pouvez copier et coller ce contenu dans le fichier `README.md` de votre référentiel
>>>>>>> 823407298ab5ec09d971a319bbe7816648b5a924
