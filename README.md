# **Node.js Ping API**

Une API simple construite avec **Node.js**, **TypeScript**, et **Express**, permettant de retourner les headers de la requête sur la route `/ping`. La documentation de l'API est disponible via **Swagger**.

## **Table des matières**

- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Lancer le projet](#lancer-le-projet)
- [Endpoints](#endpoints)
- [Documentation Swagger](#documentation-swagger)
- [Scripts npm](#scripts-npm)
- [Contribuer](#contribuer)
- [Licence](#licence)

## **Fonctionnalités**

- Route `/ping` qui retourne les headers de la requête au format JSON.
- Documentation Swagger générée automatiquement.
- Middleware pour définir correctement le header `Content-Length`.
- Support des variables d'environnement via `.env`.

## **Prérequis**

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **Node.js** (version 16 ou supérieure) : [Téléchargez Node.js ici](https://nodejs.org/)
- **npm** (inclus avec Node.js)

## **Installation**

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/votre-utilisateur/nodejs-ping-api.git
   cd nodejs-ping-api

2. **Installer les dépendances :
```bash
npm install
```

## **Configuration**
Créer un fichier .env : À la racine du projet, créez un fichier .env avec les variables d'environnement nécessaires :

```bash
PING_LISTEN_PORT=3000
```
`PING_LISTEN_PORT` : Définit le port sur lequel le serveur écoutera (par défaut : 3000).


## **Lancer le projet**
**En mode développement :**
Pour démarrer le projet avec recompilation automatique :

```bash
npm run dev
```
