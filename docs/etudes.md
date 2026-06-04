---
layout: default
nav_order: 3
title: Études et choix techniques
---

# Études et Choix Techniques

Cette page détaille les choix techniques majeurs que nous avons faits pour rendre l'**OTTO-JÄGER** le plus efficace possible lors des épreuves au MakerSpace d'UniLaSalle Amiens.

---

## 🦾 Les Bras : Le Système de Glissement

Le grand point fort de notre robot pour l'épreuve du Sumo repose sur la conception et l'utilisation de ses deux bras articulés :

* **Mécanisme de glissement :** Comme on peut le voir sur les vidéos de nos matchs, les bras utilisent un système horizontal qui vient glisser et racler le sol de l'arène.
* **Avantage stratégique :** Ce mouvement de glissement permet de passer efficacement sous le châssis du robot adverse pour le soulever et l'éjecter, tout en maintenant notre propre robot bien stable sur ses pieds.
* **Force d'impact :** Deux servomoteurs puissants sont directement dédiés à ce système pour appliquer une force de poussée maximale au moment du contact.

---

## ⚙️ Choix de la Motorisation : Passer à 6 Moteurs

Alors que le modèle d'origine utilise seulement 4 moteurs, nous avons pris la décision technique d'en installer **6** :
* **4 moteurs pour la base :** Ils gèrent la marche et les déplacements (hanches et chevilles).
* **2 moteurs pour les bras :** Ils activent de manière indépendante notre système de glissement pour le combat.

Ce choix a demandé une étude précise de l'espace interne de notre coque noire pour réussir à passer l'intégralité des 6 nappes de câbles sans bloquer les articulations.

---

## 🎮 Pilotage : Le Choix du 100% Manuel

Nous avons délibérément choisi de supprimer la marche automatique pour ce tournoi :
* **Contrôle total via RemoteXY :** Le robot est piloté en temps réel par Bluetooth/Wi-Fi depuis notre smartphone.
* **Adaptabilité :** Le pilotage manuel s'est avéré indispensable pour feinter nos adversaires, corriger notre placement sur le baril de Sumo et déclencher l'attaque des bras au timing parfait.

---

## ⚡ L'Alimentation

Pour faire fonctionner cet ensemble de 6 moteurs, nous avons opté pour une **batterie 9V rechargeable en USB-C**. 

*Note technique (Retour d'expérience) :* Si ce choix offre une excellente tension pour la puissance des bras, la consommation simultanée des 6 moteurs poussés au maximum a rapidement vidé l'énergie disponible, ce qui a causé notre panne en finale. Une gestion plus économique de la batterie sera à étudier pour les prochaines versions.