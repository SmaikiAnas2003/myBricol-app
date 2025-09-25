# myBricol - Plateforme de Services de Bricolage 🛠️

![Frontend](https://img.shields.io/badge/Frontend-Angular-dd0031)
![Backend](https://img.shields.io/badge/Backend-Spring_Boot-6db33f)
![Database](https://img.shields.io/badge/Database-MySQL-4479a1)

**myBricol** est une application web complète, fruit d'un projet d'équipe, conçue pour mettre en relation des professionnels du bricolage avec des clients à la recherche de services. La plateforme offre une expérience utilisateur fluide et intuitive pour la gestion des projets, l'authentification des utilisateurs et l'interaction, le tout construit sur une architecture robuste, modulaire et sécurisée.

Ce dépôt est un **monorepo**, contenant à la fois le **frontend en Angular** et le **backend en Spring Boot**.

---

## ✨ Un Projet d'Équipe

Ce projet a été entièrement réalisé dans un cadre de travail collaboratif, mettant en pratique les méthodologies modernes de gestion de projet telles qu'Agile et Scrum. Chaque membre de l'équipe a contribué activement aux différentes phases du projet, de l'analyse des besoins à la conception, au développement et à l'intégration, assurant ainsi la livraison d'un produit final cohérent et de qualité.

---

## 🎯 Fonctionnalités Clés

La plateforme est conçue avec un riche ensemble de fonctionnalités pour répondre aux besoins de tous les utilisateurs, des simples visiteurs aux administrateurs.

### Rôles des Utilisateurs
* **Visiteur :** Peut parcourir le catalogue de services, rechercher des prestations spécifiques et consulter leurs détails sans avoir besoin d'un compte.
* **Client :** Peut s'inscrire et se connecter pour demander des services, évaluer des professionnels et déposer des réclamations.
* **Professionnel :** Peut s'inscrire et se connecter pour proposer ses services, gérer ses disponibilités et répondre aux demandes des clients.
* **Admin :** Supervise l'ensemble des activités de la plateforme, y compris la gestion des professionnels, le traitement des réclamations et la supervision des transactions.

### Fonctionnalités Principales
* **Gestion des Utilisateurs :** Inscription, connexion et gestion des rôles sécurisées pour les différents types d'utilisateurs.
* **Gestion des Services :** Les professionnels peuvent créer, afficher et gérer les services qu'ils proposent.
* **Recherche et Découverte :** Les utilisateurs peuvent facilement rechercher et filtrer les services de bricolage.
* **Gestion des Commandes :** Un système complet pour la gestion du panier et des commandes.

---

## 🛠️ Stack Technique

Le projet a été construit à l'aide d'une stack technologique moderne et performante, choisie pour sa scalabilité et sa robustesse.

### Backend (`/backend`)
* **Framework :** **Spring Boot** - Utilisé pour le développement rapide d'API REST robustes et performantes.
* **Base de données :** **MySQL** - Une base de données relationnelle open-source fiable pour le stockage des données.
* **ORM :** **Spring Data JPA / Hibernate** - Pour une interaction transparente avec la base de données.
* **Sécurité :** **Spring Security avec JWT** - Pour sécuriser l'API, gérer les rôles (ADMIN, USER) et gérer l'authentification avec hachage des mots de passe (BCrypt).

### Frontend (`/frontend`)
* **Framework :** **Angular** - Un puissant framework développé par Google pour créer des interfaces utilisateur dynamiques et interactives.
* **Langage :** **TypeScript** - Pour un code plus structuré et une meilleure gestion des erreurs.
* **Bibliothèques UI :** **Angular Material / Bootstrap** pour des composants modernes et responsives.
* **Performance :** Optimisée avec des techniques comme le **Lazy Loading** et le cache API pour assurer une expérience utilisateur fluide.

### DevOps & Conception
* **Conteneurisation :** **Docker** - Utilisé pour créer des environnements de développement uniformes et simplifier le déploiement des applications.
* **Modélisation :** **StarUML** - Pour la conception des diagrammes UML, y compris les diagrammes de cas d'utilisation et de classes, afin de modéliser la structure de l'application.

---

## 🏗️ Architecture

L'application suit une architecture en couches pour assurer une séparation claire des responsabilités, facilitant ainsi la maintenance et l'évolutivité.

### Architecture Backend (`ma.ac.emi.bricool`)
* **Controllers :** Gèrent les requêtes HTTP entrantes.
* **Services :** Contiennent la logique métier principale.
* **Repositories :** Gèrent l'interaction avec la base de données via Spring Data JPA.
* **Entities :** Classes Java qui représentent les tables de la base de données.

### Architecture Frontend
* **Modules :** Les fonctionnalités sont séparées en modules distincts (ex: `AuthModule`, `ProjectModule`).
* **Composants :** Chaque vue de l'interface utilisateur est gérée par un composant dédié (ex: `HomeComponent`).
* **Services :** Gèrent la communication avec l'API backend via `HttpClient`.

---

## 🚀 Démarrage

Pour faire fonctionner ce projet sur votre machine locale, suivez ces étapes.

### Prérequis
* Java Development Kit (JDK)
* Node.js et npm
* Serveur MySQL
* Angular CLI

### Installation

1.  **Clonez le dépôt :**
    ```bash
    git clone [https://github.com/SmaikiAnas2003/myBricol-app.git](https://github.com/SmaikiAnas2003/myBricol-app.git)
    cd myBricol-app
    ```

2.  **Configurez le Backend :**
    * Naviguez vers le dossier backend : `cd backend`
    * Configurez votre connexion à la base de données MySQL dans le fichier `src/main/resources/application.properties`.
    * Lancez l'application Spring Boot à l'aide de votre IDE favori ou de Maven.

3.  **Configurez le Frontend :**
    * Naviguez vers le dossier frontend : `cd ../frontend`
    * Installez les dépendances : `npm install`
    * Lancez le serveur de développement : `ng serve`
    * Ouvrez votre navigateur à l'adresse `http://localhost:4200/`.

---

## 👥 Auteurs

* **SMAIKI Anas**
