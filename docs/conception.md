---
layout: default
nav_order: 4
title: Conception et prototypage
---

# Conception et Prototypage

Cette partie explique nos choix de conception et comment nous avons préparé le prototype virtuel de l'**OTTO-JÄGER** au MakerSpace d'UniLaSalle Amiens.

---

## 💡 Nos Choix de Conception

Pour fabriquer un robot redoutable pour les épreuves (et surtout pour le Sumo), nous avons modifié le modèle classique avec deux grands choix stratégiques :

* **Le passage à 6 moteurs :** Au lieu des 4 moteurs habituels pour les jambes, nous avons ajouté **2 moteurs pour les bras**. Cela permet au robot de donner des coups et de déstabiliser ses adversaires sur le ring.
* **Le pilotage 100% Manuel :** Nous avons supprimé le mode automatique. Le robot est entièrement contrôlé par nous via un smartphone. C'est beaucoup plus efficace pour adapter sa stratégie en plein combat.
* **Le look bicolore :** Un style contrasté avec un corps Noir et des membres Blancs pour un rendu propre et agressif.

---

## 💻 Le Prototypage Virtuel (OnShape)

Avant de lancer les imprimantes 3D, tout a été planifié et assemblé virtuellement sur le logiciel **OnShape** pour éviter les erreurs de taille.

### Les défis de la modélisation :
1. **Intégrer les bras :** Il a fallu modifier le haut du corps pour créer des fixations solides pour les deux moteurs de bras supplémentaires.
2. **Gérer les câbles :** Faire entrer 6 moteurs (au lieu de 4), la carte ESP32 et la grosse pile 9V dans un si petit espace a demandé de bien calculer notre coup pour que tout rentre sans forcer.

{: .note }
> **Le saviez-vous ?** Toutes nos pièces ont été vérifiées sur ordinateur pour être certains de respecter la taille maximale autorisée par le règlement des Ottolympiades (**150 x 150 x 200 mm**). 

---
➡️ *Une fois la conception validée sur OnShape, nous sommes passés à la pratique : [1. Modélisation & Impression 3D](etape_1).*