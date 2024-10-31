# Flask To-Do List App

## Description
 Une application web simple de liste de tâches créée avec Flask et SQLAlchemy.
 Elle permet d'ajouter, de compléter et de supprimer des tâches, avec les données 
 stockées dans une base de données SQLite.

## Fonctionnalités :
- Ajouter une tâche
- Marquer une tâche comme terminée
- Supprimer une tâche
- Persistance de données avec SQLite

## Prérequis
 - Python 3.x
 - Environnement virtuel (optionnel mais recommandé)

## Installation

### 1. Cloner le dépôt
git clone [https://github.com/adnan-khadija/todo-flask.git](https://github.com/adnan-khadija/todo_flask.git)
cd todo-flask

### 2. Créer un environnement virtuel
python3 -m venv venv
source venv/bin/activate  # Sur Windows : venv\Scripts\activate

### 3. Installer les dépendances
pip install -r requirements.txt

## Initialisation de la Base de Données

La base de données SQLite (todo.db) sera automatiquement créée lors du premier lancement de l'application.
Vous pouvez également l'initialiser avec la commande suivante :
python -c "from app import db; db.create_all()"

## Lancer l'Application

### 1. Exécuter l'application Flask
python app.py

### 2. Accéder à l'application
 Ouvrir votre navigateur et aller sur http://127.0.0.1:5000

## Utilisation

 - Ajouter une tâche : Saisir un titre et cliquer sur "Add".
 - Marquer une tâche comme terminée : Cliquer sur la tâche pour changer son statut.
 - Supprimer une tâche : Cliquer sur le bouton "delete" pour supprimer une tâche.

## Structure des Fichiers
 - app.py : Fichier principal avec les routes et le modèle de tâche.
 - templates/index.html : Template HTML pour la page principale.
 - todo.db : Fichier de base de données SQLite créé lors du premier lancement de l'application.

## Dépendances
 - Flask : Framework web léger pour Python.
 - Flask-SQLAlchemy : Support SQLAlchemy pour les applications Flask.


