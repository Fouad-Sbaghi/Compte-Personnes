# Projet Compte-Personnes

Ce projet est un projet de **première année** réalisé en collaboration avec **Nicolas Digrande** et **Nassim Benchenni**.

## Description

Ce projet permet La solution mise en œuvre repose sur un système de comptage utilisant des capteurs infrarouges, reliés à une carte Arduino.
Lorsqu'une personne passe devant le capteur, une interruption du faisceau infrarouge est détectée et un comptage est effectué.
L'Arduino est également connecté à un module XBee, qui transmet sans fil les données vers un second module XBee connecté à un Raspberry Pi 3B.

Le Raspberry Pi reçoit les données de comptage, les traite et les enregistre dans une base de données. Un site web local, hébergé sur le Raspberry Pi, permet d'afficher en temps réel le nombre de personnes présentes dans la salle.
Ce site est accessible via un navigateur web sur le réseau local.

En complément, un écran est directement connecté à l'Arduino pour afficher instantanément le compteur sur le boîtier, offrant une visualisation rapide sur place.
Ce système permet donc à la fois un affichage physique et une consultation à distance via une interface web, tout en assurant la sauvegarde des données pour un usage statistique.

## Structure du projet

L’équipe est composée de trois membres, chacun ayant un rôle bien défini dans le développement du projet.
**Fouad** s’est chargé de la partie matérielle : l’installation des capteurs infrarouges, le codage sur la carte Arduino ainsi que la modélisation et l’impression 3D du boîtier.
**Nicolas** a pris en charge l’intégration du Raspberry Pi, la gestion de la base de données locale ainsi que la communication sans fil via les modules XBee.
**Nassim** s’est concentré sur l’affichage web : création du site local, liaison avec la base de données, et mise à jour dynamique du nombre de personnes.


