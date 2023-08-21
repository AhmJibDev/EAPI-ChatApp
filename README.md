# Nom du Projet 🚀
👉 Une application innovante qui permet aux utilisateurs de communiquer en temps réel, partager des idées et collaborer sur des projets. Construite avec Mule 4 et MySQL, cette application offre une expérience utilisateur fluide et réactive. 🎉

## Architecture de l'Application 🏗️
L'application se compose des flux suivants :

## GetLoginPageFlow 📄
Ce flux gère la réception et la réponse aux requêtes des utilisateurs pour la page de connexion.

## DoLoginFlow 🔑
Ce flux effectue la validation du nom d'utilisateur et du mot de passe.

## GetStaticResource 🖼️
Ce flux gère et sert les ressources statiques comme les images, les fichiers CSS et JavaScript.

## BroadcastWebSocketFlow 📡
Ce flux gère la réception des messages entrants via WebSockets et les diffuse à tous les clients connectés.

## GetChatPageFlow 💬
Ce flux gère la page de chat de l'application et vérifie la validité de la session de l'utilisateur.

## Prérequis 🧰
- Mule 4 ou version supérieure
- MySQL (ou modifiez la configuration de la base de données selon vos besoins)
- Configuration ⚙️
- Base de Données: Configurez la base de données en utilisant le fichier de configuration approprié.
- Fichiers HTML/CSS/JS: Placez vos fichiers HTML, CSS et JavaScript dans les répertoires appropriés.
- Installation 🖥️

## Clonez le dépôt et importez le projet dans votre environnement Mule.
Copy code
`git clone url_du_depot.git`

## Utilisation 🎮
Démarrez l'application dans Mule ou déployez-la sur un serveur Mule. L'application sera accessible à `http://localhost:8091`.

Contact 📧
Pour toute question, n'hésitez pas à me contacter à aitouaret.ahmed@gmail.com.

