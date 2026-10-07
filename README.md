# ft_irc

Projet réalisé dans le cadre du cursus **42**.

L'objectif est de développer un **serveur IRC** permettant à plusieurs clients
de se connecter et de communiquer entre eux via le protocole IRC.

## 🖥️ Fonctionnalités

Le serveur permet notamment :

- La connexion de plusieurs clients
- L'authentification des utilisateurs
- La gestion des salons (channels)
- La création et la gestion des salons
- L'envoi de messages entre utilisateurs
- La gestion des opérateurs
- La gestion des permissions sur les channels
- La gestion des commandes IRC

## 🌐 Réseau

Le serveur communique avec les clients grâce à des **sockets TCP**.

Le projet nécessite notamment de gérer :

- Les connexions et déconnexions des clients
- La réception et l'envoi de données
- Plusieurs clients simultanément
- Le parsing des commandes IRC
- La gestion des événements réseau

## 🛠️ Technologies

- **C++98**
- **TCP/IP**
- **Sockets**
- **Makefile**

## 🎯 Objectifs

Ce projet m'a permis de travailler sur :

- La programmation réseau
- Les sockets TCP
- La communication client/serveur
- Le parsing de protocoles
- La gestion de plusieurs connexions
- La programmation orientée objet
- La gestion d'états et de permissions
