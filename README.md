# Motivational Project

Ce projet est un site statique généré avec [MkDocs](https://www.mkdocs.org/) et déployé via GitHub Pages.

## Vue d'ensemble

Le **Projet Motivationnel** est conçu pour ma candidature au poste d'Administratrice système DevOps. Ce projet utilise le thème **Material pour MkDocs**.Le site est automatiquement déployé sur GitHub Pages à chaque mise à jour de la branche `main`.

> **Accès au fichier sur ce lien suivant : [Processus de recrutement](process.yml).**

## Fonctionnalités

- **MkDocs avec le thème Material** : Générateur de site statique simple d'utilisation avec un design élégant et responsive.
- **Déploiement continu** : Le site est automatiquement déployé à chaque push sur la branche `main` grâce à GitHub Actions.
- **Hébergement** : Hébergé gratuitement sur GitHub Pages.

## Installation

### Prérequis

- [Python 3.x](https://www.python.org/downloads/)
- [MkDocs](https://www.mkdocs.org/)
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

### Étapes d'installation

Clonez le dépôt :

```bash
git clone git@github.com:HeleneFnt/Motivational-Project.git
cd Motivational-Project
```

Installez les dépendances :

```bash
pip install mkdocs mkdocs-material
```

Lancez le site en local :

```bash

mkdocs serve
```

Ouvrez votre navigateur et accédez à [cette page](http://127.0.0.1:8000) pour voir le site en local.

Déploiement

Chaque push sur la branche main déclenche un déploiement automatique sur GitHub Pages via GitHub Actions. Le site est accessible à [cette adresse.](https://helenefnt.github.io/Motivational-Project/)

## Copyright

© 2024 Hélène Finot. All rights reserved.
