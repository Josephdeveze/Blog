# Blog PHP

Un blog simple développé en PHP avec une base de données MySQL et Bootstrap pour le style.

## Fonctionnalités

- 👤 **Authentification**
  - Inscription des utilisateurs
  - Connexion/Déconnexion 
  - Gestion des sessions

- 📝 **Articles**
  - Affichage de tous les articles sur la page d'accueil
  - Vue détaillée d'un article
  - CRUD complet pour les articles (admin)
  - Extrait des articles sur la page d'accueil

- 💬 **Commentaires** 
  - Ajout de commentaires sur les articles
  - Affichage des commentaires sous chaque article

- 👨‍💼 **Administration**
  - Interface d'administration des articles
  - Modification et suppression des articles

## Technologies utilisées

- PHP 
- MySQL
- PDO pour la connexion à la base de données
- Bootstrap 5 pour le style
- HTML/CSS

## Installation 

1. Cloner le projet dans votre répertoire web (ex: htdocs pour XAMPP)
2. Créer une base de données MySQL nommée `blog`
3. Importer la structure de la base de données (tables users, articles, comments)
4. Configurer les accès à la base dans `functions.php`:
```php
$host = '127.0.0.1';
$db   = 'blog';
$user = 'root'; 
$pass = '';