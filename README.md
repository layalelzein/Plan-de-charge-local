# Plan de Charge

## Description
Ce dépôt contient un projet Python utilisant Flask pour créer une page web nommée "Plan de Charge". Cette page affiche un formulaire dont les données sont mises à jour dans un fichier Excel situé dans le dépôt.

## Prérequis
Avant de commencer, assurez-vous que vous avez Python 3 installé sur votre machine.

## Installation

### Étapes de base
1. Clonez ce dépôt sur votre machine locale :
    ```sh
    git clone https://github.com/votre-utilisateur/plan_de_charge.git
    cd plan_de_charge
    ```

2. Installez les dépendances nécessaires :
    ```sh
    pip3 install flask pandas openpyxl
    ```

3. Démarrez le projet :
    ```sh
    python3 app.py
    ```

4. Ouvrez votre navigateur (Google Chrome, Safari, etc.) et accédez à l'URL suivante :
    ```
    http://127.0.0.1:5002
    ```

### Si cela ne fonctionne pas

#### 1. Créer un environnement virtuel
   ```sh
   python3 -m venv plan_de_charge_env
   ```

#### 2. Activer l'environnement virtuel
   - Sur macOS et Linux :
     ```sh
     source plan_de_charge_env/bin/activate
     ```
   - Sur Windows :
     ```sh
     .\plan_de_charge_env\Scripts\activate
     ```

#### 3. Installer les dépendances dans l'environnement virtuel
   Avec l'environnement virtuel activé, installez Flask, Pandas et openpyxl :
   ```sh
   pip install flask pandas openpyxl
   ```

#### 4. Démarrer l'application avec l'environnement virtuel activé
   ```sh
   python app.py
   ```

## Utilisation
Après avoir démarré l'application, ouvrez votre navigateur et accédez à l'adresse suivante :
```
http://127.0.0.1:5002
```
Vous verrez un formulaire sur la page "Plan de Charge". Les données saisies dans ce formulaire seront mises à jour dans un fichier Excel situé dans le dépôt.

## Contribuer
Les contributions sont les bienvenues ! Pour des changements majeurs, veuillez d'abord ouvrir une issue pour discuter de ce que vous aimeriez changer.
