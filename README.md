# Planify

Cette application combine un carnet d'adresses et un agenda interactif afin d'offrir une solution complète de gestion des contacts et des événements personnels.

---

## 📒 Carnet d'Adresses & Agenda Web

### 📌 Description du projet

Ce projet est une application web qui combine un carnet d'adresses et un agenda personnel dans une seule plateforme intuitive.

L'objectif est de permettre à l'utilisateur de :

1. Gérer ses contacts (amis, famille, collègues, etc.)
2. Organiser ses événements (rendez-vous, réunions, rappels)
3. Centraliser toutes ses informations personnelles au même endroit

---

## 🚀 Fonctionnalités principales

### 👤 Gestion des contacts

- Ajouter un contact (nom, prénom, téléphone, email, adresse…)
- Modifier les informations d'un contact
- Supprimer un contact
- Rechercher un contact rapidement
- Classer les contacts (groupes ou catégories)

### 📅 Gestion de l'agenda

- Ajouter un événement (titre, date, heure, description)
- Modifier ou supprimer un événement
- Afficher les événements sous forme de calendrier
- Ajouter des rappels (notifications)

### 🔐 Authentification

- Inscription et connexion utilisateur
- Sécurisation des données personnelles
- Accès privé à ses propres contacts et événements

---

## 🛠️ Technologies utilisées

- **Frontend** : HTML, CSS, JavaScript
- **Backend** : Laravel (PHP)
- **Base de données** : MySQL
- **Outils** : Git, Laragon (environnement local)

---

## 📂 Structure du projet (exemple)

```
/app
/resources
    /views
        /contacts
        /agenda
        /auth
/public
/routes
/database
```

---

## ⚙️ Installation

1. Cloner le projet : `git clone https://github.com/ton-repo/carnet-agenda.git`
2. Installer les dépendances :
   ```
   composer install
   npm install
   ```
3. Configurer le fichier `.env` :
   - Base de données
   - Nom de l'application
4. Lancer les migrations : `php artisan migrate`
5. Démarrer le serveur : `php artisan serve`

---

## 📸 Aperçu (optionnel)

- Page d'accueil
- Liste des contacts
- Vue calendrier

---

## 🎯 Objectif pédagogique

Ce projet permet de pratiquer :

- La programmation web avec Laravel
- La gestion des bases de données
- La création d'interfaces utilisateur
- La mise en place d'un système d'authentification

---

## 📌 Améliorations possibles

- Synchronisation avec Google Calendar
- Import/export de contacts (CSV)
- Notifications en temps réel
- Version mobile (responsive design)

---

## 👨‍💻 Auteur

Projet réalisé par Arthur Kouamen
