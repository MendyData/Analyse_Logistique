# Projet Smart City - Analyse des arbres de la ville de Paris

## Description

Ce projet fait partie d'un challenge organisé par la ville de Paris dans le cadre du programme “Végétalisons la ville”. Le but de ce projet est d'effectuer une analyse exploratoire des données sur les arbres de la ville de Paris, afin d'optimiser les tournées pour l'entretien des arbres.

## Objectifs

- Explorer les données des arbres de Paris
- Identifier les variables pertinentes pour l'analyse
- Réaliser des visualisations descriptives et géospatiales
- Apporter des insights sur l'entretien des arbres et proposer des améliorations
- Optimiser les trajets des équipes d'entretien pour une meilleure efficacité

## Jeu de données

Le jeu de données utilisé dans ce projet est disponible sur [OpenData Paris](https://opendata.paris.fr/explore/dataset/les-arbres/). Il contient des informations détaillées sur les arbres de la ville, incluant :
- L'espèce des arbres
- Leur localisation géographique (latitude, longitude)
- Leur stade de développement
- Leur caractère remarquable ou non

## Contenu du dépôt

- `notebooks/`: Contient les notebooks Jupyter utilisés pour l'analyse
  - `Smart_City.ipynb`: Notebook principal contenant toute l'analyse des données
- `data/`: Répertoire contenant les jeux de données utilisés pour l'analyse (non inclus dans le dépôt pour des raisons de taille)
- `README.md`: Ce fichier de présentation du projet



## Résultats attendus

- Une vue globale de l'état des arbres de Paris
- Une optimisation des tournées d'entretien des arbres
- Une analyse des espèces d'arbres, des stades de développement, et de la répartition géographique
- Des insights sur les arbres remarquables et la biodiversité

## Contributions

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet ou ajouter des fonctionnalités, n'hésitez pas à ouvrir une issue ou à proposer une pull request.

---

**Auteur :** Angèle MENDY
**Date :** Octobre 2024



## Installation

Pour reproduire ce projet sur votre machine, suivez les étapes ci-dessous :

1. Cloner ce dépôt GitHub :
    ```bash
    git clone https://github.com/votre-utilisateur/Projet_2_Smart_City.git
    ```

2. Créer et activer un environnement virtuel Python :
    ```bash
    python -m venv venv
    source venv/bin/activate  # Sur Windows : venv\Scripts\activate
    ```

3. Installer les librairies nécessaires :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Ouvrir le notebook Jupyter :
    ```bash
    jupyter notebook notebooks/Smart_City.ipynb
    ```

2. Explorer et exécuter les cellules pour reproduire l'analyse.

