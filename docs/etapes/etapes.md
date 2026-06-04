---
layout: default
title: Étapes de fabrication
nav_order: 5
has_children: true
---

# Étapes de Fabrication

Bienvenue dans la section dédiée aux étapes de fabrication de l'**OTTO-JÄGER**. Vous trouverez ici les guides détaillés et structurés pour accompagner pas à pas l'assemblage, la configuration et la personnalisation de notre robot au MakerSpace.

## Aperçu des Étapes

Voici les différentes étapes du processus de fabrication. Cliquez sur l'une d'elles pour accéder au guide détaillé :

<ul>
  {% for child in page.children %}
    <li>
      <strong><a href="{{ child.url | relative_url }}">{{ child.title }}</a></strong>
      {% if child.description %} — {{ child.description }}{% endif %}
    </li>
  {% endfor %}
</ul>

## Commencer

> **Avant de débuter :** Assurez-vous de disposer de l'ensemble des composants fournis par le MakerSpace (carte ESP32, capteur ultrason, servomoteurs, visserie) et d'avoir validé l'export de vos pièces thématiques imprimées en 3D. 

Suivez scrupuleusement l'ordre des étapes pour garantir la stabilité cinématique du robot et éviter tout problème lors des phases de tests préliminaires.

---

Pour toute question ou aide lors d'une manipulation au MakerSpace, n'hésitez pas à solliciter les membres de l'équipe du Groupe 08 ou les encadrants du laboratoire.