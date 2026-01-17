# 🎬 projet_progWeb – Plateforme de Présentation de Films

## 🔐 Informations d’accès (environnement de démonstration)

Pour accéder à l’interface d’administration et gérer les contenus du site, veuillez utiliser les identifiants suivants :

* **Adresse e-mail** : `admin@gmail.com`
* **Mot de passe** : `AsdfZxcv`

---

## 📝 Présentation du projet

Ce projet web a été réalisé dans le cadre du module **PROGRAMMATION_WEB2_FILM_PRESENTATION**, en utilisant l’IDE **Visual Studio Code (VS Code)**.
Il s’agit d’une plateforme web bilingue (français / anglais) dédiée à la présentation de films, conçue pour offrir une navigation claire, intuitive et interactive.

---

## 🌐 Fonctionnalités principales

Le site est organisé autour de plusieurs sections fonctionnelles :

### **Page d’accueil**

* Présente une sélection de films disponibles sur la plateforme.
* Affiche pour chaque film son **titre** ainsi qu’une **description concise**.

### **Page de détails**

* Fournit des informations détaillées sur chaque film, notamment :

  * Année de production
  * Réalisateur
  * Langue du film

### **Page “À propos”**

* Contient une présentation succincte du propriétaire ou de l’auteur du site.

### **Interface Administrateur**

* Espace sécurisé réservé à la gestion des contenus.
* Permet l’ajout, la modification et la suppression de films via une interface dédiée.

---

## 🛠️ Spécifications techniques

* **Base de données** : SQLite
* **Backend** : PHP

  * Utilisation de requêtes **AJAX** pour le chargement dynamique des données
* **Interface utilisateur** :

  * Développée en PHP
  * Design **responsive**, compatible avec ordinateurs, tablettes et smartphones
* **Sécurité** :

  * Validation des champs de saisie afin d’empêcher l’injection de caractères non autorisés
  * Protection contre les **injections SQL** lors des opérations administrateur

---

## 📦 Déploiement et utilisation

1. Cloner le projet sur un serveur local (ex. : XAMPP, WAMP).
2. Vérifier l’accessibilité de la base de données SQLite.
3. Lancer le site via un navigateur en accédant au fichier `index.php`.
4. Se connecter en tant qu’administrateur pour gérer les films et les contenus dynamiques.

---

Ce projet met en avant une approche structurée du développement web, combinant bonnes pratiques de sécurité, architecture claire et expérience utilisateur soignée.
