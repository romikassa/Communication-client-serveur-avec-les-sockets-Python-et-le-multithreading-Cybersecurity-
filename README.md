# TP Cybersécurité — Communication client/serveur avec sockets Python

## Description
Implémentation d'un serveur et de plusieurs clients en Python (sockets TCP),
capables d'échanger des messages en temps réel et simultanément grâce au
multithreading.

## Fonctionnalités
- Communication bidirectionnelle client ↔ serveur (envoi et réception en parallèle)
- Gestion de plusieurs clients en même temps (un thread par client)
- Identification de chaque client (nom ou adresse IP)
- Gestion des exceptions pour éviter qu'une déconnexion brutale ne plante le serveur

## Prérequis
- Python 3
- Un réseau local commun entre les machines (Wi-Fi ou Ethernet)

## Utilisation
1. Sur la machine serveur : `python server.py`
2. Sur chaque machine cliente : `python client.py` (après avoir renseigné l'IP du serveur)

## Technologies
`socket`, `threading`

## Analyse sécurité
Ce TP met en évidence des failles d'une communication réseau basique
(messages en clair, absence d'authentification) et les mesures de protection
possibles (TLS, authentification, limitation des connexions).

## Auteur
Romaissa — Module Cybersécurité
