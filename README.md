# Ohmyfood

## Description

Ohmyfood est un site web mobile-first qui permet aux utilisateurs de découvrir et de réserver des menus dans divers restaurants sélectionnés. Ce projet met l'accent sur l'accessibilité, le responsive design, et une expérience utilisateur optimale sur mobile.

La page principale inclut :

- Un header avec le logo du site et la localisation de l'utilisateur.
- Un bandeau principal avec un appel à l'action pour explorer les restaurants.
- Une section expliquant le fonctionnement du service en trois étapes.
- Une présentation des restaurants avec des cartes contenant des images, des descriptions et des badges.
- Un footer avec des liens vers des pages d'informations (mentions légales, contact, etc.).

## Structure des fichiers

Le projet est organisé de manière modulaire pour faciliter la maintenance et l'évolution :

```sh
/.
├── .vscode/              # Configuration pour l'éditeur Visual Studio Code
├── css/
│   └── main.css          # Fichier CSS compilé à partir des fichiers SCSS
├── images/
│   ├── logo/             # Images du logo du site
│   └── restaurants/      # Images des restaurants
├── pages/
│   ├── délice.html       # Détails du restaurant "Le Délice des Sens"
│   ├── la_française.html # Détails du restaurant "À La Française"
│   ├── note_enchantée.html # Détails du restaurant "La Note Enchantée"
│   └── palette.html      # Détails du restaurant "La Palette du Goût"
├── scss/                 # Fichiers source SCSS pour les styles
│   ├── _base.scss        # Styles de base
│   ├── _mixins.scss      # Mixins utilisés pour les media queries et autres
│   ├── _variables.scss   # Variables globales (couleurs, tailles, etc.)
│   └── main.scss         # Fichier SCSS principal qui importe les partiels
├── index.html            # Page principale du site
└── README.md             # Documentation du projet
