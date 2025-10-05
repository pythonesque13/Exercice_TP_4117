# Exercices de Fouille de Données (UE 4117)


Ce dépôt contient l'ensemble des exercices pratiques de l'**Unité d'Enseignement (UE) 4117 : Fouille de Données**.

Il a été réalisé dans le cadre de notre formation en Informatique, option **Science des Données**, à l'Université de Yaoundé I.

-----

## Installation et Lancement (Prérequis)

Pour tester et exécuter les differents exercices, veuillez suivre les étapes ci-dessous.

### Prérequis

Vous devez avoir installé sur votre machine :

  * **Python 3.8 ou +**
  * Un gestionnaire de paquets (**pip**)

### 1\. Cloner le Dépôt

Ouvrez votre terminal et clonez le projet :

```bash
git clone https://github.com/pythonesque13/Exercice_TP_4117.git
cd Exercice_TP_4117
```

### 2\. Configuration de l'Environnement Virtuel

Il est fortement recommandé d'utiliser un **environnement virtuel** pour isoler les dépendances du projet.

#### A. Création de l'Environnement

Créer l'environnement virtuel nommé `.env` :

```bash
python3 -m venv .env
```

#### B. Activation de l'Environnement

Activez l'environnement virtuel. Les commandes varient selon votre système d'exploitation :

| Système d'exploitation | Commande d'activation |
| :--- | :--- |
| **Linux / macOS** | `source .env/bin/activate` |
| **Windows (PowerShell)** | `.env\Scripts\Activate.ps1` |


### 3\. Installation des Dépendances

Installer tous les paquets Python nécessaires à partir du fichier `requirements.txt` :

```bash
pip install -r requirements.txt
```

### 4\. Exécuter un Exercice

#### EDA WINE

Pour le premier exercice celui de l'exploration des donnees sur le jeu de donnees **wine**, il faut:
-- Naviguer dans le dossier notebooks
```bash
cd notebooks
```

-- Une fois dans le dossier notebooks il faut lancer le serveur jupyther dans votre terminal avec la commande
```bash
jupyter lab
```
-- Ouvrir le notebook **1_EDA_wines.ipynb**

-----

#### EDA WINE

Pour le second exercice celui de l'application des approches de discretisation sur une variable au choix(dans notre cas **alcohol** ) du jeu de donnees **wine**, il faut:
-- Naviguer dans le dossier notebooks
```bash
cd notebooks
```

-- Une fois dans le dossier notebooks il faut lancer le serveur jupyther dans votre terminal avec la commande
```bash
jupyter lab
```
-- Ouvrir le notebook **2_Methode-discretisation.ipynb**

##  Désactivation de l'Environnement

Lorsque vous avez fini de travailler sur le projet, vous pouvez désactiver l'environnement virtuel en utilisant la commande :

```bash
deactivate
```
