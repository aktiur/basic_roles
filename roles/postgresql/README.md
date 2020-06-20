# PostgreSQL

Installe un serveur PostgreSQL, le configure, et met en place utilisateurs et
base de données.

## Résumé

Ce rôle vise à installer PostgreSQL en utilisant le système de cluster de Debian.
Il réalise les opérations suivantes :
- Installe PostgreSQL et ses dépendances, ainsi que les potentielles extensions demandées
- Crée et active le cluster
- Crée les utilisateurs
- Crée les bases de données et donne les permissions aux utilisateurs

## Variables

Les variables sont documentées directement dans [le fichier des variables par
défaut](defaults/main.yml)
