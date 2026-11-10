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

   ```
