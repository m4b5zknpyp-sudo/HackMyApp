# HackMyApp

HackMyApp est une application web volontairement vulnérable développée dans le cadre du projet **ACG SecureHack**.

L'objectif de cette application est de servir de **laboratoire local de cybersécurité** afin de permettre l'identification, l'exploitation contrôlée et la correction de différentes vulnérabilités web.

## Fonctionnalités

L'application propose notamment :

- 🔐 Authentification des utilisateurs
- 📝 Inscription
- 👤 Gestion des profils utilisateurs
- 📰 Consultation d'articles
- 🔎 Recherche d'articles
- 💬 Commentaires
- 🛠️ Espace d'administration

L'application contient volontairement plusieurs vulnérabilités permettant de réaliser un audit de sécurité dans un environnement contrôlé.

## Vulnérabilités étudiées

Dans le cadre de l'audit, plusieurs vulnérabilités peuvent être étudiées, notamment :

- SQL Injection
- Reflected XSS
- Stored XSS
- IDOR / Broken Access Control

Les tests doivent être réalisés uniquement sur l'environnement local prévu à cet effet.

## Technologies utilisées

- PHP 8.2
- MySQL 8
- Apache
- Docker
- Docker Compose
- HTML / CSS
- JavaScript

## Prérequis

Pour lancer l'application, il faut installer :

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Git

## Installation

Cloner le dépôt :

```bash
git clone https://github.com/TON-PSEUDO/HackMyApp.git
