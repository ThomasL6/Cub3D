# Cub3D

![cub3d](https://raw.githubusercontent.com/ayogun/42-project-badges/main/badges/cub3dm.png)

## Description
Cub3D est un projet graphique de l'École 42 visant à créer un jeu de type "raycaster" inspiré de Wolfenstein 3D.

## Objectif
Développer un moteur de rendu 3D basé sur la technique du raycasting, capable d'afficher un environnement 3D à partir d'une carte 2D.

## Fonctionnalités

- Rendu 3D en temps réel utilisant la technique du raycasting
- Déplacement du joueur dans un environnement 3D
- Chargement de cartes à partir de fichiers .cub
- Textures pour les murs
- Gestion des collisions

## Compilation et Exécution

make
./cub3D map.cub

## Contrôles

- Flèches directionnelles : Se déplacer
- Touches A, S, D, W : Se déplacer (alternative)
- ESC : Quitter le jeu

## Structure du projet

- `src/` : fichiers source
- `includes/` : fichiers d'en-tête
- `maps/` : fichiers de cartes .cub
- `textures/` : images pour les textures des murs

## Dépendances

- MinilibX : Bibliothèque graphique simplifiée
