# Symfony API pour Gestion des Étudiants et Utilisateurs

## Description

Ce projet Symfony est une API simple pour gérer les entités "Étudiant" et "Utilisateur". Il utilise l'extension ApiResource de Symfony pour simplifier la création d'une API REST.

## Prérequis

- PHP 7.4 ou version ultérieure
- Composer
- Symfony CLI
- MySQL ou une autre base de données prise en charge

## Démarrage

1. Clonez le dépôt :
 - git clone https://github.com/Kinbachir/symfonyCRUD.git

2. Installez les dépendances :
 - composer install

3. Configurez votre base de données dans le fichier .env :
 - DATABASE_URL=mysql://user:password@127.0.0.1:3306/nom_de_votre_base

4. Créez la base de données et exécutez les migrations :
 - php bin/console doctrine:database:create
 - php bin/console doctrine:migrations:migrate

5. Lancez le serveur de développement Symfony :
 - symfony server:start

6. Votre application Symfony avec ApiResource est maintenant opérationnelle :
 - Visitez http://localhost:8000 dans votre navigateur pour voir l'API en action.

