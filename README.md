# Serveur HTTP en Node.js

Ce projet est un serveur HTTP basique développé avec Node.js. Il écoute sur le port 4000 et répond à différentes requêtes en fonction de l'URL demandée.

## Fonctionnalités

- Affiche un message de bienvenue sur la page d'accueil (`/`).
- Fournit une page "À propos" (`/about`).
- Fournit une page de contact (`/contact`).
- Renvoie une erreur 404 pour les routes inconnues (`/autre`).

## Prérequis

Avant d'exécuter le serveur, assurez-vous d'avoir installé [Node.js](https://nodejs.org/) sur votre machine.

## Installation

1. **Clonez ce dépôt ou copiez le fichier du serveur**
   ```bash
   git clone <URL_DU_DÉPÔT>
   cd <NOM_DU_DOSSIER>
   ```

2. **Vérifiez que Node.js est installé**
   ```bash
   node -v
   ```
   Cela doit afficher la version installée de Node.js.

3. **Placez le fichier `server.js` dans un dossier dédié**

## Exécution du serveur

1. **Ouvrez un terminal et accédez au dossier contenant le fichier `server.js`**
   ```bash
   cd <NOM_DU_DOSSIER>
   ```

2. **Lancez le serveur avec la commande suivante**
   ```bash
   node server.js
   ```

3. **Le serveur démarrera et écoutera sur `http://localhost:4000`**
   
   Vous devriez voir le message suivant dans le terminal :
   ```bash
   Serveur démarré sur http://localhost:4000
   ```

## Routes disponibles

| Route                      | Réponse |
|----------------------------|-----------------------------------------------|
| `http://localhost:4000/`    | "Bienvenue sur notre serveur Node.js !"       |
| `http://localhost:4000/about` | "Voici la page à propos."                     |
| `http://localhost:4000/contact` | "Contactez-nous à contact@monserveur.com."   |
| `http://localhost:4000/autre` | "404 - Page non trouvée"                      |

## Améliorations possibles

- Ajouter d'autres routes dynamiques.
- Servir des fichiers HTML au lieu de simples messages texte.
- Implémenter un routeur plus avancé avec Express.js.
- Ajouter un système de logs pour enregistrer les requêtes entrantes.



**Félicitations pour votre premier serveur HTTP en Node.js !**

