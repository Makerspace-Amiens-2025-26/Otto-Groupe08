---
layout: default
nav_order: 2
title: Objectifs du projet
---

# Introduction

Le projet repose sur le robot **Otto**, un petit robot humanoïde open-source conçu pour enseigner les bases de la robotique, de l'électronique et de la programmation. Dans le cadre de notre formation, nous développons l'**Otto-MKS**, une version personnalisée et améliorée conçue sur mesure au MakerSpace d'**UniLaSalle Amiens**. Ce robot intègre des fonctionnalités avancées, notamment une connectivité sans fil (Bluetooth ou WiFi) permettant un contrôle à distance via un smartphone.

## Contexte du Projet

Ce projet s'inscrit dans le cadre de notre première année d'études à UniLaSalle Amiens, en collaboration avec le MakerSpace. Réalisé par équipe de 3 étudiants, l'objectif est de concevoir, fabriquer, programmer et personnaliser notre propre robot Otto-MKS en exploitant les ressources et tutoriels mis à notre disposition. 

Le point culminant de ce projet est la participation aux **Ottolympiades**, un grand tournoi de fin d'année organisé lors de la journée des projets. Nos robots y affronteront ceux des autres équipes à travers plusieurs épreuves compétitives :
* **Chrono challenge :** Suivre une ligne droite le plus rapidement possible.
* **Course d'obstacle :** Traverser un parcours semé d'embûches en un temps record.
* **Otto Sumo :** Un duel entre deux robots où un seul doit rester debout.
* **Tir à la corde :** Deux équipes de 3 robots s'affrontent en force.

## Objectifs du Projet

Pour valider ce projet de première année, plusieurs attendus académiques et livrables précis doivent être réalisés :
* **Un robot fonctionnel :** Entièrement assemblé, programmé et capable de se déplacer de manière autonome ou pilotée.
* **Le fichier OnShape modifié :** Fournir la modélisation CAO 3D de notre version modifiée de l'Otto-MKS sur OnShape.
* **Une vidéo de présentation :** Un clip d'une minute au format portrait présentant le projet de manière professionnelle.
* **Un support de documentation :** La rédaction d'un rapport de projet complet OU la création d'un site web dédié à la documentation de notre travail.
* **Participation aux Ottolympiades :** Présenter et faire concourir notre robot lors des épreuves du tournoi.

---

# Existant

Le projet s'appuie sur la plateforme internationale open-source Otto, caractérisée par 4 points clés :
1. **Open-source :** Le projet est disponible gratuitement en ligne avec l'accès aux plans, aux fichiers de conception 3D et aux guides d'assemblage.
2. **Modulaire :** Otto peut être personnalisé à l'infini en ajoutant des éléments mécaniques ou différents capteurs (modules de son, LED, bras, etc.).
3. **Programmable :** Le robot peut être programmé avec l'IDE Arduino ou d'autres plateformes de programmation visuelle (blocs).
4. **Impression 3D :** Les composants du robot peuvent être imprimés en 3D, ce qui permet aux utilisateurs de fabriquer leur propre exemplaire et d'en modifier le design.

---

# Cahier des Charges

### 1. Composants Électroniques et Matériel (Fourni)
* **Carte électronique Otto-MKS :** Conçue sur mesure au MakerSpace, elle intègre un microcontrôleur **ESP32**, une LED, un interrupteur, des sorties pour servomoteurs ainsi qu'un emplacement pour le capteur ultrason et d'éventuels connecteurs additionnels (gyroscope, écran...).
* **Servomoteurs :** 4 servomoteurs indispensables pour assurer les mouvements de marche du robot.
* **Capteur ultrason (HC-SR04) :** Permet au robot d'acquérir des informations sur son environnement proche (détection de présence, mesure de distance, mouvements).
* **Batterie 9V rechargeable :** Une batterie aux dimensions standard d'une pile 9V, simplifiant la connexion et rechargeable directement en USB-C.

### 2. Règles de Conception et d'Homologation
Chaque robot doit obligatoirement passer un contrôle de conformité (homologation) avant le tournoi :
* **Dimensions maximales :** Le robot, actionneurs déployés au maximum, doit tenir dans une boîte de **150 mm (L) x 150 mm (l) x 200 mm (H)**.
* **Mode de déplacement :** Le robot doit impérativement se déplacer en **marchant**. Les roues sont interdites.
* **Fabrication et Programmation :** Réalisées par les étudiants du groupe (interdiction d'utiliser un kit commercial prêt à l'emploi).
* **Sécurité & Arrêt d'urgence :** L'interrupteur d'alimentation doit rester **accessible en tout temps par l'arbitre** afin de pouvoir couper le robot immédiatement en cas de danger pour lui-même, les autres robots ou le décor.
* **Modifications autorisées :** La personnalisation esthétique et l'ajout de bras/mains sont encouragés, mais aucun élément ne doit présenter de danger (interdiction des lasers, lames ou flammes).

### 3. Comportement et Modes de Contrôle
Selon l'épreuve des Ottolympiades, le robot devra être capable d'opérer sous deux configurations distinctes :
* **Mode autonome :** Le robot réalise l'épreuve seul, sans aucune aide extérieure. Il doit être programmé à l'avance et démarrer via un signal spécifique à l'épreuve.
* **Mode télécommandé :** L'équipe doit programmer et déployer une solution de contrôle à distance (par exemple, via l'application **RemoteXY**).

### 4. Directives de Programmation & Arbitrage
* **Code et Logique :** Aucun langage de programmation spécifique n'est imposé. Cependant, chaque membre de l'équipe doit être capable d'**expliquer en détail la logique du programme** déployé.
* **Utilisation de l'IA :** L'usage de l'Intelligence Artificielle est **autorisé**, mais strictement en tant qu'**aide à l'apprentissage** et à la compréhension.
* **Arbitrage :** L'arbitre assure le bon déroulement et le respect du règlement. Ses décisions ainsi que sa position sur la piste durant les matchs doivent être rigoureusement respectées.
