# Spring Ride Connect

Spring Ride Connect est une plateforme de covoiturage de type BlaBlaCar. Elle permet aux utilisateurs de proposer des trajets et de réserver des places pour voyager ensemble.

## 🚀 Fonctionnalités

- Authentification et gestion des utilisateurs
- Création et recherche de trajets
- Réservation de places
- Système de validation et messagerie (le cas échéant)

## 🛠️ Technologies Utilisées

- **Backend** : Java 21, Spring Boot 3
- **Base de données** : H2 (développement) / MySQL (production)
- **Frontend** : Thymeleaf
- **Sécurité** : Spring Security

## ⚙️ Installation et Exécution Locale

1. **Cloner le projet :**
   ```bash
   git clone https://github.com/medilyass37/Spiring-Ride.git
   cd springride_VF
   ```

2. **Configurer la base de données :**
   Par défaut, l'application utilise une base H2 en mémoire. Si vous utilisez MySQL, modifiez les accès dans `src/main/resources/application.properties`.

3. **Compiler et exécuter :**
   ```bash
   ./mvnw clean install
   ./mvnw spring-boot:run
   ```
   *Sur Windows, utilisez `.\mvnw.cmd` à la place de `./mvnw`.*

## 📦 Comment déposer ce projet sur GitHub

1. **Initialiser Git** (si ce n'est pas déjà fait) :
   ```bash
   git init
   ```

2. **Ajouter tous les fichiers au suivi Git** (le fichier `.gitignore` filtrera ce qui ne doit pas être envoyé) :
   ```bash
   git add .
   ```

3. **Créer un commit** avec un message descriptif :
   ```bash
   git commit -m "Initial commit : projet Spring Ride Connect"
   ```

4. **Créer un nouveau dépôt sur GitHub** en vous rendant sur [https://github.com/new](https://github.com/new) (ne cochez aucune option d'initialisation de README ou .gitignore).

5. **Lier votre projet local au dépôt distant** :
   ```bash
   git branch -M main
   git remote add origin https://github.com/VOTRE_NOM_UTILISATEUR/NOM_DU_DEPOT.git
   ```

6. **Pousser votre code vers GitHub** :
   ```bash
   git push -u origin main
   ```
