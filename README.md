# CatchMaster
*Déplacez un panier pour attraper des objets qui tombent et marquez des points.*

> ***Authors**: Ugo "BaKeMoN0" Courche, Hadrien "Vraus" Belleville*
>
> ***Date**: 30/06/2024*
>
> ***Engine & Version**: [Unreal Engine 5.3](https://www.unrealengine.com/en-US/download)*

# Table of Contents

- [Introduction](#introduction)
- [Concept](#concept)
- [Fonctionnalités Minimum](#fonctionnalités-minimum)
- [Tâches pour la semaine](#tâches-pour-la-semaine)
  - [Semaine 1](#semaine-1)
    - [Objectif](#objectif)
- [Organisation du travail](#organisation-du-travail)
  - [Création du projet](#création-du-projet)
  - [Gestion du projet](#gestion-du-projet)
    - [Organisation des tickets](#organisation-des-tickets)

Introduction
Bienvenue dans le projet CatchMaster! Ce document te guidera à travers le concept du jeu, les fonctionnalités prévues, et la façon d'organiser le travail. J'espère que ce projet te motivera à faire du Unreal et à développer d'autres jeux après !

## Concept

Dans ce jeu, tu contrôles un panier qui se déplace de gauche à droite en bas de l'écran. Des objets tombent du haut de l'écran à des vitesses variées, et le but est de positionner le panier sous ces objets pour les attraper. Chaque objet attrapé rapporte des points, avec des objets spéciaux offrant des bonus supplémentaires. La difficulté augmente progressivement avec la vitesse et la fréquence des chutes d'objets, mettant à l'épreuve tes réflexes et ta précision.

## Fonctionnalités Minimum

1. **Contrôle du Panier :**
   - Déplacement du panier de gauche à droite à l'aide des touches fléchées ou du glissement sur l'écran tactile.
1. **Objets Tombants :**
   - Génération aléatoire d'objets qui tombent du haut de l'écran.
1. **Système de Points :**
   - Attribution de points pour chaque objet attrapé.
1. **Niveaux de Difficulté Croissante :**
   - Augmentation progressive de la vitesse et de la fréquence des objets tombants.
1. **Écran de Score :**
   - Affichage du score actuel pendant le jeu.
1. **Écran de Fin de Partie :**
   - Affichage du score final et possibilité de redémarrer le jeu.
1. **Objets Spéciaux :**
   - Inclusion d'objets bonus avec des effets spéciaux (ex. : double points, ralentissement du temps).
1. **Effets Sonores :**
   - Effets sonores pour les objets attrapés et autres actions importantes.
1. **Interface Utilisateur Simple :**
   - Menu principal avec options de démarrage du jeu et d'accès aux réglages.
1. **Animations Fluides :**
    - Animations fluides pour les mouvements du panier et des objets tombants.

## Tâches pour la semaine

### Semaine 1

> *30 juin 2024 - 7 juillet 2024*
> 
> *Faut quand même aller voter!*

La première tâche à développer pour ce jeu serait de **implémenter les contrôles du panier**. Cela constitue la base de l'interaction du joueur avec le jeu et est essentiel pour tester et affiner les autres fonctionnalités.

Voici des idées pour se lancer (optionnelles):

1. **Créer l'objet panier :**
   - Dessiner ou importer un simple sprite représentant le panier.
1. **Implémenter le déplacement du panier :**
   - Ajouter des contrôles pour déplacer le panier de gauche à droite.
     - Pour clavier : utiliser les touches fléchées gauche et droite.
     - Pour écran tactile : implémenter le glissement horizontal.
1. **Définir les limites de déplacement :**
   - Empêcher le panier de sortir des limites de l'écran.

#### Objectif :
- Avoir un panier qui peut être déplacé par le joueur de manière fluide et réactive, respectant les limites de l'écran.

## Organisation du travail

### Création du projet

> **Important**

- Commencer par **cloner** ce dépo pour l'avoir localement.
- **Créer un dossier** `Game/` où tu mettras le projet Unreal.
- **Modifier** le fichier `.gitignore` pour y ajouter à toutes les lignes le chemin correct.
   - C'est à dire ajouter `Game/` pour retarget correctement le `.gitignore`.
- **Commit** / **Push** le nouveau `.gitignore`
- Lancer le moteur dans sa **version 5.3.2**.
- **Paramètres par défaut** du projet:
   - **C++**
   - Target Platform: **Desktop**
   - Quality Preset: **Scalable**
   - **No** Starter Content
   - **No** Raytracing
   - Ils peuvent être ajouter plus tard au besoin de toute façon.
- Créer le projet dans le dossier `Game/` créé préalablement.

### Gestion du projet

> Ce n'est pas obligatoire de faire comme ça mais c'est juste une bonne habitude à prendre je pense surtout pour préparer l'année prochaine.

Faire une gestion de projet classique avec l'outil de projet GitHub. 
Organisation des colonnes du Kanban:
+ Backlog
   + Contient la liste total de tous les tickets du projet qui ne sont pas lancés
+ A faire
   + Les tickets qui sont à faire en priorité pour une première version du projet
+ En cours
   + Les tickets en cours
+ Bloqué
   + Les tickets qui ne peuvent plus être avancé. Il faut finir un autre ticket ou en créer un pour débloquer celui-ci 
+ Validation
   + Les tickets qui sont vraisemblablement finis
+ Fini
   + Les tickets finis

#### Organisation des tickets

+ Créer un label de catégorie pour les tickets.
   + Pour différencier les tickets concernant le Gameplay, le 3C, les animations, l'UI, l'enviro etc...
+ Créer un label de ticket pour les bugs
   + Pour permettre de spécifier qu'un ticket est un bug trouvé dans le projet concernant un élément de Gemaplaye ou autre.
+ Utilisation des autres catégories préexistante pour se donner une idée de la quantité de travail et de la difficulté de la tâche.
