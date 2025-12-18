# GMAO v2.0 - Gestion Voitures

## A propos

Deuxième version d'une application GMAO destinée à gérer les véhicules et interventions associées et de determiner l'intervention a effectué apres un certains kimlométrage.
L'objectif est de fournir une interface simple pour enregister les véhicules, planifier et suivre les interventions ,et de créer automatiquement une intervention précise pour chaque véhicule apres un certains seuil de kilométrage,et deconserver un historique dans une base SQLite local.

## Table des matières

* 🪧 [À propos](#à-propos)
* 📦 [Prérequis](#prérequis)
* 🚀 [Installation](#installation)
* 🛠️ [Fonction principales](#fonction-principales)
* 🏗️ [Construit avec](#construit-avec)

## Prérequis

Avant d'installer et d'utiliser le projet, assurez-vous d'avoir :

* **Python 3.10+** — Télécharger et installer depuis [https://www.python.org/](https://www.python.org/). Python 3.10 ou supérieur est recommandé pour la compatibilité avec `customtkinter`.
* **pip** — inclus avec Python moderne. Utiliser `python -m pip install --upgrade pip` pour mettre à jour.

### Dépendances 

* `customtkinter` — composants UI modernes (voir la doc officielle).

> Les versions précises des dépendances sont indiquées dans `requirements.txt`.

## Installation

Exemples (Windows) :

```bash
# 1) Créer et activer un environnement virtuel
python -m venv .venv
.venv\Scripts\activate

# 2) Installer les dépendances
pip install -r requirements.txt

# 3) Lancer l'application
python main.py
```

## Fonction principales

- Gestion des véhicules : Ajout ,afficher liste véhicule, modification, suppression.
- Gestion des interventions : Ajout,afficher intervention, modification,suppression (une intervention doit etre liée à un véhicule).
- Gestion des règles de maintenance : creation règle, modification règle (Chaque règle est automatiquement assigné à un véhicule crée)


## Construit avec

### Langages & Frameworks

* **Python 3.10+** — langage principal.
* **tkinter** / **customtkinter** — interface graphique.
* **SQLite** — base de données embarquée (fichier local `.db`).

### Outils

* **IDE** : VS Code / PyCharm (au choix)


## Auteur / Contact

Ramanandraibe Kanto Andrianina — [andrianinakanto5@gmail.com](mailto:andrianinakanto5@gmail.com)
