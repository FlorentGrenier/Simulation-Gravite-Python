# Simulation de gravité en Python
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) 
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Sommaire
1. [Description du projet](#description-du-projet)
2. [Contraintes](#contraintes)
3. [Objectif du projet](#objectif-du-projet)
4. [Formule mathématique](#formule-mathématique)
5. [Bibliothèque utilisée](#bibliothèque-utilisée)
6. [Liens utile](#liens-utile)

## Description du projet
Projet réalisé dans le cadre de la fin du module de mathématique en B3.

## Contraintes
- Utilisation de GitHub
- Creation d'une BDD
- Faire une IHM 
- Logs pertinent
- Readme complet

## Objectif du projet
- [x] Simulation d'une orbite
- [x] Utilisation de Pygame pour l'affichage de la simulation
- [ ] Faire une IHM pour permmetre le choix de planet au début de la simulation
- [x] Ajouter 1 force attractive
- [ ] Ajouter 2 forces attractives
- [x] Enregistrer dans un fichier les planètes avec toutes ces informations
- [ ] Réalisation d'un nuage de points 2D (ou 3D) avec la position des planètes

## Formule mathématique 
La formule $`k = -\frac{G \cdot M}{(x^2 + y^2)^{3/2}}`$​ est la formule utilisée pour calculer l'accélération gravitationnelle $`k`$ exercée sur un objet de masse $`M`$ situé à une position donnée $`(x,y)`$ dans un champ gravitationnel.

Cette formule est dérivée de la loi de la gravitation universelle de Newton, qui décrit l'attraction gravitationnelle entre deux objets massifs. En utilisant cette formule, on peut calculer l'accélération gravitationnelle subie par un objet en raison de la présence d'un autre objet massif, en tenant compte de la distance entre les deux objets.

## Bibliothèque utilisée
- pygame
- random
- json
- numpy
- matplotlib.pyplot

## Liens utile
- https://stackoverflow.com/questions/12038674/x-y-direction-to-degree
