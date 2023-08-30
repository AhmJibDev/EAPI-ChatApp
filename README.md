# Projet MuleSoft : Formulaire de Connexion & Chat App 🚀

👉 Cette application permet aux utilisateurs de se connecter via un formulaire et de communiquer en temps réel. Elle est construite avec Mule 4, HTML/CSS/JS et Websocket Connector. 🎉

## Architecture de l'Application 🏗️

L'application comporte les flux suivants :

### GetLoginPageFlow 📄
Gère la réception et la réponse aux requêtes des utilisateurs pour la page de connexion.

### DoLoginFlow 🔑
Effectue la validation du nom d'utilisateur et du mot de passe.

### GetStaticResourceFlow 🖼️
Gère et sert les ressources statiques comme les images, les fichiers CSS et JavaScript.

### BroadcastWebSocketFlow 📡
Gère la réception des messages entrants via WebSockets et les diffuse à tous les clients connectés.

### GetChatPageFlow 💬
Gère la page de chat de l'application et vérifie la validité de la session utilisateur.

## Prérequis 🧰
- Mule 4 ou version supérieure
- MySQL (ou modifiez la configuration de la base de données selon vos besoins)

## Configuration ⚙️
- **Base de Données** : Configurez la base de données en utilisant le fichier de configuration approprié.
- **Fichiers HTML/CSS/JS** : Placez vos fichiers HTML, CSS et JavaScript dans les répertoires appropriés.

## Installation 🖥️

### Base de données MySQL
Voici un exemple de script SQL pour créer une table stockant les informations d'authentification des utilisateurs :
`
CREATE TABLE demodb.users (
  id int NOT NULL AUTO_INCREMENT,
  username varchar(45) NOT NULL,
  password varchar(255) NOT NULL, -- stocker le mot de passe sous forme hachée
  PRIMARY KEY (id),
  UNIQUE KEY username_UNIQUE (username)
);`

## Clonez le dépôt et importez le projet dans votre environnement Mule.
`git clone https://github.com/AhmJibDev/EAPI-ChatApp.git`

## Utilisation 🎮
Démarrez l'application dans Mule ou déployez-la sur un serveur Mule. L'application sera accessible à `http://localhost:8091/login`.

Contact 📧
Pour toute question, n'hésitez pas à me contacter à ahmjib.developer@gmail.com.

