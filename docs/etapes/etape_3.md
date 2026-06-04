---
layout: default
title: 3. Programmation & Étalonnage
parent: Étapes de fabrication
nav_order: 3
description: Alignement des servomoteurs à 90°, intégration du code ESP32 et liaison RemoteXY.
---

# 3. Programmation & Étalonnage

Cette étape permet de programmer le microcontrôleur ESP32 pour coordonner la marche de l'**OTTO-JÄGER** et configurer ses modes de fonctionnement.

## 💻 Environnement de Développement

Le code a été écrit et téléversé via l'**IDE Arduino** avec les bibliothèques suivantes :
* Gestionnaire de cartes **ESP32** (Espressif).
* Bibliothèque Servo adaptée aux timers de l'ESP32.
* Bibliothèque **RemoteXY** pour générer l'application de contrôle Bluetooth/Wi-Fi.

---

## 📐 Alignement et Calibration des Membres

Pour s'assurer que notre robot marche parfaitement droit :
1. Nous injectons un code "neutre" qui force les 4 moteurs à se positionner à exactement **90°**.
2. Les moteurs étant bloqués électroniquement au centre, nous emboîtons les jambes et les pieds blancs de l'OTTO-JÄGER pour qu'ils soient parfaitement verticaux et parallèles.
3. Nous vissons ensuite les palonniers sur les axes pour verrouiller définitivement cet alignement mécanique.

---

## 🎮 Logique des Modes de Jeu

L'OTTO-JÄGER est configuré pour basculer entre deux comportements stratégiques :

### 1. Mode Autonome (Capteur Ultrason)
Dédié aux épreuves de vitesse et d'évitement. Le capteur HC-SR04 mesure les distances en continu. Si un obstacle surgit à moins de 15 cm, l'ESP32 interrompt la marche rapide et exécute une routine de pivotement pour contourner le danger.

### 2. Mode Télécommandé (RemoteXY)
Conçu pour les duels. L'interface sur smartphone intègre un joystick virtuel réactif qui pilote les mouvements et les rotations en temps réel, indispensable pour ajuster notre trajectoire lors des combats.

{: .note }
> **Intelligence Artificielle :** Au cours de cette phase, l'IA a été utilisée comme un outil d'apprentissage pour optimiser la structure de nos fonctions de marche et fiabiliser la gestion des tâches en arrière-plan sur l'ESP32.

---
➡️ *Le robot est programmé et calibré. Passez à la dernière étape : [4. Tests & Homologation](etape_4).*