# cmc-chatbot-avatar
# 🤖 CMC Chatbot Avatar Project 

<div align="center">
  <img src="https://img.shields.io/badge/Status-En%20développement-yellow" alt="Status">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue" alt="Version">
</div>

##  Bienvenue 
Projet de stage développé pour **CMC CS – Digital Factory** (Nouaceur Casablanca Settat) visant à créer un chatbot avec avatar pour l'accueil et l'assistance digitale des usagers.

##  Objectifs
- Créer une **interaction humaine** via un avatar animé
- Fournir une **assistance 24h/7**
- Répondre instantanément aux **questions fréquentes**
- **Orienter efficacement** vers les services appropriés

##  Stack Technique
| Composant       | Technologie                          |
|-----------------|--------------------------------------|
| **Frontend**    | JavaScript + HTML/CSS                |
| **Backend**     | Laravel (PHP Framework)             |
| **Chatbot**     | Dialogflow (API REST)               |
| **Avatar**      | Live2D ou Web3D                     |
| **Base de données** | MySQL (via Laravel Eloquent)      |
| **Hébergement** | Render/Vercel/Firebase              |

##  Structure du projet
```bash
cmc-chatbot-avatar/
├── frontend/               # Interface utilisateur
│   ├── chatbot.js         # Logique du chat
│   ├── avatar.html        # Intégration avatar
│   └── style.css          # Styles CSS
├── backend/                # API Laravel
│   ├── app/               # Modèles et contrôleurs
│   ├── routes/            # Routes API
│   ├── config/            # Configuration
│   └── public/            # Assets publics
├── chatbot/                # Configuration Dialogflow
├── avatar/                 # Ressources Live2D
│   ├── model.json         # Modèle 3D
│   └── textures/          # Textures avatar
├── docs/                   # Documentation
└── README.md               # Ce fichier
```
 Installation & Lancement
Prérequis
PHP 8.0+

Composer

Node.js

Compte Dialogflow

1.  Cloner le dépôt
bash
git clone https://github.com/votre-utilisateur/cmc-chatbot-avatar.git
cd cmc-chatbot-avatar
2.  Installer Laravel
bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
3.  Configurer MySQL
Editer le fichier .env :
ini
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=cmc_chatbot
DB_USERNAME=root
DB_PASSWORD=
Puis lancer les migrations :
bash
php artisan migrate
4.  Configurer Dialogflow
Ajouter dans .env :
ini
DIALOGFLOW_PROJECT_ID=votre-project-id
DIALOGFLOW_PRIVATE_KEY="---CLÉ PRIVÉE---"
DIALOGFLOW_CLIENT_EMAIL=votre-email@service-account.com
5.  Lancer le serveur
bash
php artisan serve
6.  Démarrer le frontend
Ouvrir dans le navigateur :
bash
open frontend/avatar.html
## Fonctionnalités clés
✅ Interface de chat responsive

✅ Intégration Dialogflow API

✅ Gestion des sessions utilisateur

✅ Avatar animé Live2D/Web3D

✅ Journalisation des interactions (MySQL)

##  Roadmap
Architecture de base

Intégration Dialogflow

Animation avatar Live2D

Tests utilisateurs

Déploiement production

##  Contributions
Projet réalisé par Pepe Marcel LOUA dans le cadre d'un stage à CMC CS – Digital Factory.

📧 Contact : pepemarcelloua@gmail.com

