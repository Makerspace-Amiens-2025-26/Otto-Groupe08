---
layout: default
title: Étapes de fabrication
nav_order: 5
has_children: true
---

# Étapes de Fabrication

Bienvenue dans la section dédiée aux étapes de fabrication de l'**OTTO-JÄGER**. Vous trouverez ici les guides détaillés et structurés pour accompagner pas à pas l'assemblage, la configuration et la personnalisation de notre robot au MakerSpace.

<img src="{{ '/images/IMG_1924.JPG' | relative_url }}" alt="Robot OTTO-JÄGER Noir et Blanc" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.3); margin: 20px 0;">

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

> **Avant de débuter :** Assurez-vous de disposer de l'ensemble des composants fournis par le MakerSpace (carte ESP32, servomoteurs, visserie) et d'avoir validé l'impression de vos pièces bicolores en 3D.

Suivez scrupuleusement l'ordre des étapes pour garantir la stabilité cinématique du robot et éviter tout problème lors des phases de tests préliminaires.

---

Pour toute question ou aide lors d'une manipulation au MakerSpace, n'hésitez pas à solliciter les membres de l'équipe du Groupe 08 ou les encadrants du laboratoire.