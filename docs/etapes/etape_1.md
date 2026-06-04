---
layout: default
title: 1. Modélisation & Impression 3D
parent: Étapes de fabrication
nav_order: 1
description: Configuration sur OnShape et choix du design bicolore Noir et Blanc pour l'OTTO-JÄGER.
---

# 1. Modélisation & Impression 3D

Cette première étape pose les bases de la structure et de l'identité visuelle de l'**OTTO-JÄGER**. Elle combine le travail de CAO (Conception Assistée par Ordinateur) et la fabrication additive au MakerSpace d'UniLaSalle Amiens.

## 🛠️ Modifications CAO sur OnShape

En partant du modèle open-source, nous avons ajusté les volumes sur **OnShape** pour adapter le châssis à nos composants :
* **Tolérances et volumes :** Optimisation de l'espace interne pour fixer solidement la carte ESP32, guider proprement les nappes des 4 servomoteurs et loger la batterie 9V rechargeable.
* **Esthétique :** Intégration des détails de notre thématique Jägermeister tout en épurant les lignes pour préparer l'habillage graphique.

## 🖨️ Paramètres et Code Couleur d'Impression 3D

Pour nous démarquer dans l'arène, nous avons opté pour un design contrasté **Noir et Blanc** qui donne un look agressif et moderne à notre OTTO-JÄGER.

### Répartition des Couleurs
* **Tête et Corps principal :** Filament PLA Noir profond (pour un aspect robuste et compact).
* **Jambes, Pieds et Bras :** Filament PLA Blanc éclatant (mettant en valeur la cinématique de marche et les mouvements).

### Configuration du Slicer (Trancheur)
Pour garantir une excellente solidité lors des impacts (notamment pour l'épreuve du Sumo) tout en maîtrisant le poids, nous avons appliqué les paramètres suivants :

| Paramètre | Valeur Sélectionnée | Raison Technique |
| :--- | :--- | :--- |
| **Hauteur de couche** | 0.2 mm | Excellent compromis entre précision d'assemblage et vitesse d'impression. |
| **Remplissage (Infill)** | 20% en Gyroïde | Structure interne optimisée pour dissiper les chocs multidirectionnels. |
| **Nombre de parois (Walls)** | 3 lignes | Renforcement obligatoire autour des puits de vissage des servomoteurs. |
| **Supports** | Activés à 50° | Uniquement requis sous la cavité des yeux pour le capteur ultrason. |

---
➡️ *Une fois vos pièces imprimées, nettoyées et prêtes, passez à la suite : [2. Assemblage Mécanique](etape_2).*