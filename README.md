# TP_Git_Python - Mon assistant de révision

## Présentation
* **Module :** Outils Collaboratifs (Git / GitHub) - Licence 1
* **Objectif du programme :** Créer un assistant de révision en Python (`main.py`) qui interagit avec l'utilisateur pour collecter son prénom, la matière à réviser et la durée de la session.
* **Rôle du fichier main.py :** Fichier unique qui évolue à travers quatre versions successives.

## Évolution du programme (Versions V1 à V4)
* **V1 :** Création locale du message initial de bienvenue (`git init`, `add`, `commit`).
* **V2 :** Ajout de la saisie du prénom de l'utilisateur, puis premier envoi (`push`) vers le dépôt GitHub.
* **V3 :** Ajout de la matière à réviser directement à distance sur GitHub, puis récupération en local avec `git pull`.
* **V4 :** Ajout local de la durée de révision sur le PC, suivi d'un nouveau `git push`.

## Comment exécuter le programme
1. Ouvrir le dossier `TP_Git_Python` dans Visual Studio Code, puis cliquer sur `main.py`.
2. Cliquer sur le bouton ▶ **Run Python File** en haut à droite de l'éditeur (et sélectionner l'interpréteur Python si nécessaire).
3. Dans le terminal intégré qui s'ouvre, saisir le prénom, la matière et la durée en minutes en validant chaque réponse avec la touche **Entrée**.

## Commandes Git utilisées
* `git init` : Initialise le dépôt Git dans le dossier local.
* `git add` : Ajoute les modifications du fichier dans la zone de préparation.
* `git commit` : Enregistre officiellement les modifications localement avec un message.
* `git push` : Envoie les commits locaux vers le dépôt distant GitHub.
* `git pull` : Récupère et fusionne les commits distants depuis GitHub vers l'ordinateur.