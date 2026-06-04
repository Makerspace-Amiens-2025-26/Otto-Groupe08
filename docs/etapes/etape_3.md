---
layout: default
title: 3. Programmation & Étalonnage
parent: Étapes de fabrication
nav_order: 3
description: Réglage des moteurs et application RemoteXY.
---

# 3. Programmation & Étalonnage

Ici, on s'occupe du code et du réglage des moteurs via l'IDE Arduino.

## 📐 Le centrage des moteurs (À faire en premier)
1. On téléverse un code simple pour bloquer les **6 moteurs à 90°** (leur position centrale).
2. Une fois les moteurs bloqués, on aligne les jambes et les bras bien droits.
3. On met les vis pour bloquer le tout mécaniquement.

## 🎮 Pilotage 100% Manuel
Notre robot n'est pas automatique, il se pilote entièrement au smartphone avec l'application **RemoteXY** en Bluetooth/Wi-Fi.

* **Le Joystick :** Sert à faire marcher le robot (avancer, reculer, tourner).
* **Les Boutons :** Servent à actionner les bras pour pousser les adversaires au Sumo.

*(Note : Nous avons utilisé l'IA comme un assistant pour nous aider à comprendre le code de RemoteXY et optimiser les mouvements).*