# To Do List Web Application

- **Frontend** - React et Vite
- **Backend** - NodeJs et Express
- **Base de donnée** - MongoDB

## **Les étapes pour créer le projet**
Tout d'abord, j'ai fait les téléchargements et les installations de NodeJs et MongoDB

1. J'ai commencé avec le Frontend et j'ai créé un project de React et Vite dans un dossier (/client) en utilisant les commandes de ligne:
    ```bash
    npm create vite@latest client --template react
    cd client
    npm install
    npm run dev
    ```

2. Puis j'ai créé le dossier pour le backend (/server) et je suis y naviguée en utilisant le commande de ligne:
    ```bash
    cd server
    ```

3. J'ai créé un package.json en utilisant le command:
    ```bash
    npm init -y
    ```

4. J'ai modifié le fichier package.json pour modifier le fichier d'entrée de 'index.js' à 'server.js' et j'ai ajouté le script "start" pour créér un façon plus court pour exécuter le commande 'node server.js' pour servir ce fichier.

5. J'ai installé le framework 'Express':
    ```bash
    npm install express
    ```

6. J'ai créé mon fichier 'server.js' et importé le module 'express':
    ```javascript
    const express = require('express');
    ```

7. Puis je l'ai initié un instance de cet express objet en faisant:
    ```javascript
    const app = express();
    ```

8. J'ai rajouté un console.log pour me montrer les propriétés de cet objet.
9. J'ai commencé à écouter à ce port en rajoutant le code:
    ```javascript
    app.listen(8080, () => {
        console.log('Server is running on Port ' + PORT);
    });
    ```

10. J'ai lancé mon script pour voir ce que ça donne:
    ```bash
    npm start
    ```
    et j'ai vu que mon server du backend a commencé.

11. Je suis retourné à mon dossier frontend (/client) et j'ai nettoyé/vidé les fichiers.

12. J'ai installé 'axios' dans mon frontend pour faire une communication entre le frontend et le backend.
