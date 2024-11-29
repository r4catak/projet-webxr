# Visualiseur de protéines (Projet Réalité augmentée)
![](https://cdn.discordapp.com/attachments/1243601633699430431/1312094175625482331/IMG_20241129_173339.jpg?ex=674b3e6d&is=6749eced&hm=3a7d3e81fa3c21c5469cefea270abd8a3f2856db0b850817f8448765fb775def&)

## Membres du groupe

Brossard Matthieu et Chen Cyril

## Introduction du projet

Ce projet est une application web de visualisation de protéines utilisant Three.js et WebXR. Il permet de charger et d'afficher des modèles 
de protéines en 3D à partir des fichiers fournis par AlphaFold en réalité augmentée. Ce visualiseur représente les atomes et les
liaisons des protéines de manière interactive avec la possibilité justement de manipuler la vue en 3D pour explorer la structure du molécule.
[Le projet est disponible ici.](https://matth-bross.github.io/projet-webxr/)

## Fonctionnalités

- Un chargement dynamique de protéines en entrant un identifiant de protéine pour charger un modèle 3D en direct depuis AlphaFold.
- On peut visualiser les atomes et les liaisons directement en 3D avec des couleurs distinctes pour chaque 
type d'élément chimique (carbone, oxygène, azote, etc.).
- On peut contrôler la vue pour explorer la structure de la protéine sous différents angles (rotation uniquement).

## Technologies utilisées

Nous avons utilisé Three.js et WebXR pour effectuer ce projet. Cette outils nous a permis de modéliser des objets en 3D directement sur le Web.

## Détails 

- Chaque atome est représenté par une sphère colorée selon son type chimique :
> Carbone (C) : Vert |
> Oxygène (O) : Rouge |
> Azote (N) : Bleu |
> Autres : Blanc

- Les liaisons covalentes sont représentées par des cylindres entre les atomes.

## Ressource

Les modèles de protéines sont téléchargés à partir d'AlphaFold, une base de données de structures de protéines.

## License
[License MIT](https://fr.wikipedia.org/wiki/Licence_MIT)

