# Formulaire de Contact Sécurisé avec Symfony 7

Ce projet consiste en la conception et le développement d'un formulaire de contact sécurisé utilisant Symfony 7, une plateforme de développement PHP moderne et robuste.

## Fonctionnalités

- Permet aux utilisateurs de soumettre leurs informations de contact de manière sécurisée.
- Utilise des bonnes pratiques de sécurité pour protéger contre les attaques courantes telles que l'injection SQL, XSS, CSRF, etc.
- Stocke les informations soumises dans une base de données.

## Installation

1. Clonez le dépôt GitHub : `git clone https://github.com/Munderstand101/PC-EPSI-SBD-SecureContactForm.git`
2. Installez les dépendances avec Composer : `composer install`
3. Configurez votre base de données dans le fichier `.env`.
4. Créez la base de données et exécutez les migrations :
5. Lancez le serveur Symfony : `symfony serve -d`
6. Accédez à l'application dans votre navigateur à l'adresse `http://localhost:8000/contact`.

## Utilisation

- Remplissez le formulaire de contact avec votre nom, votre adresse e-mail et votre message.
- Appuyez sur le bouton "Envoyer" pour soumettre vos informations.
- Vos informations seront stockées en toute sécurité dans la base de données.
