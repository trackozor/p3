# Ohmyfood

## Description

Ohmyfood est un site web mobile-first conçu pour permettre aux utilisateurs de découvrir et de réserver des menus dans une sélection de restaurants de qualité. Ce projet se distingue par :

Accessibilité : Utilisation de balises HTML sémantiques pour améliorer l'expérience des lecteurs d'écran.
Responsive design : Approche mobile-first pour une compatibilité sur smartphone, tablette et ordinateur.
Animations CSS : Amélioration de l'interactivité et de l'esthétique avec des transitions fluides.

## Fonctionnalités principales

Voici les fonctionnalités principales offertes par Ohmyfood :

Page d'accueil :

Présentation des restaurants sous forme de cartes interactives.
Bandeau principal contenant un appel à l’action.
Section explicative décrivant le fonctionnement du service.
Pages spécifiques aux restaurants :

Présentation du restaurant (image, description, emplacement).
Liste des menus avec descriptions et prix.
Boutons pour réserver directement un menu.
Animations CSS :

Chargement interactif avec effets visuels.
Transitions fluides pour améliorer l'expérience utilisateur.
Accessibilité :

Balises ARIA pour les lecteurs d'écran.

## Prérequis

## Technologie utilisées

## Installation

## Structure des fichiers

Le projet est organisé de manière modulaire pour faciliter la maintenance et l'évolution :

```sh
ohmyfood/
├── .vscode/                # Configuration pour Visual Studio Code (facultatif)
│
├── css/
│   └── main.css            # Fichier CSS compilé depuis SCSS
│
├── images/
│   ├── logo/               # Images du logo
│   └── restaurants/        # Images des restaurants
│
├── pages/
│   ├── délice.html         # Page dédiée au restaurant "Le Délice des Sens"
│   ├── la_française.html   # Page dédiée au restaurant "À La Française"
│   ├── note_enchantée.html # Page dédiée au restaurant "La Note Enchantée"
│   └── palette.html        # Page dédiée au restaurant "La Palette du Goût"
│
├── scss/                   # Fichiers SCSS pour les styles
│   ├── components/         # Boutons, cartes, etc.
│   │   ├──  _button.scss   
│   │   ├──  _card.scss 
│   ├── layout/             # Header, footer, structures principales
│   │   ├──  _common.css     
│   │   ├──  _footer.scss
│   │   ├──  _header.scss
│   │   ├──  _loader.scss
│   │   ├──  _reset.scss
│   ├── pages/              # Styles spécifiques pour chaque page
│   │   ├──  _accueil.scss
│   │   ├──  _menu.scss
│   ├── util/               # Variables, mixins, animations
│   │   ├── _variables.scss # Couleurs, typographie, etc.
│   │   ├── _mixins.scss    # Media queries, styles réutilisables
│   │   └── _animations.scss # Animations CSS
│   └── main.scss           # Point d'entrée SCSS
│
├── index.html              # Page principale
│
├── package.json            # Configuration pour npm
│
└── README.md               # Documentation du projet


