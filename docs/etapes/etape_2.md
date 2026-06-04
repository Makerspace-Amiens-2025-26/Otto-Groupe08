---
layout: default
title: 2. Assemblage Mécanique
parent: Étapes de fabrication
nav_order: 2
description: Montage de la structure bicolore, intégration des servomoteurs et du bouton de sécurité.
---

# 2. Assemblage Mécanique

L'assemblage mécanique consiste à interconnecter les membres imprimés en Noir et Blanc de l'**OTTO-JÄGER** avec ses moteurs et sa carte de commande.

## 📦 Liste du Matériel

Vérifiez que vous disposez des éléments suivants sur votre établi au MakerSpace :
* Vos pièces 3D (Tête et Corps noirs ; Jambes et Pieds blancs).
* 4 Servomoteurs avec leurs sachets de palonniers et vis.
* 1 Capteur ultrason HC-SR04.
* 1 Carte électronique personnalisée Otto-MKS (ESP32).
* 1 Batterie 9V rechargeable en USB-C.
* L'interrupteur d'arrêt d'urgence et un tournevis de précision.

---

## 🔧 Étapes de Montage Pas à Pas

### Étape 2.1 : Les Pieds et les Chevilles
1. Glissez le premier servomoteur dans le logement prévu à l'intérieur du pied blanc gauche.
2. Fixez-le fermement à l'aide des vis à bois fournies.
3. Répétez l'opération pour le pied blanc droit.

### Étape 2.2 : Liaison des Jambes et du Corps
1. Montez les deux servomoteurs de hanche à l'intérieur du châssis noir de l'OTTO-JÄGER.
2. Faites remonter tous les câbles d'alimentation des moteurs vers la section supérieure du corps.
3. Emboîtez les jambes blanches sur les axes des servomoteurs.

> ⚠️ **ATTENTION :** Ne fixez pas encore les vis sur les axes des moteurs ! Les servomoteurs doivent d'abord être alignés électroniquement à 90° à l'étape suivante avant d'être bloqués mécaniquement.

### Étape 2.3 : Intégration de l'Électronique et Sécurité
1. Insérez le capteur ultrason HC-SR04 dans les yeux de la tête noire.
2. Positionnez la carte ESP32 dans ses glissières à l'intérieur du corps.
3. **Sécurité Obligatoire :** Installez l'interrupteur d'arrêt d'urgence sur l'emplacement extérieur prévu. Il doit être parfaitement accessible pour permettre aux arbitres de couper instantanément le robot sur la piste en cas de problème.
4. Raccordez la batterie 9V.

---
➡️ *La structure est prête mais les articulations ne sont pas alignées. Passez à l'étape logicielle : [3. Programmation & Étalonnage](etape_3).*