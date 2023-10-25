# Basic roles

Ce dépôt comprend des roles destinés à être installés comme une collection.

Ces rôles permettent la configuration de serveurs sous Ubuntu.

## Rôles génériques

- common: réalise la configuration de base (logiciels essentiels, préservation
  des logs, firewall, fail2ban, outils de diagnostic)

## Rôles web
- nginx: install nginx
- nginx_letsencrypt: crée un certificat pour nginx
- django: installe une application django
- matomo: un serveur d'analytiques web
- wordpress: une instance wordpress

## Rôles de base de données

- mariadb
- postgresql
- redis

## Rôles langage

- python
- php
- virtualenv
