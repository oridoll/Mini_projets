### Idées générales

- choix de l'utilisation de torch ou tensorflow
- faire des codes généraux dans un package utils.py que l'on peut réutiliser d'un mini projet à un autre
- classification fine, faire un choix de réseau d'utilisation de fine tuning ou de transfert learning
- évaluer la qualité du modèle
- prendre en compte le cas out of distribution


### Utils

Une classe utils avec comme premiers arguments (en self) les dimensions et charactéristiques propres au mini-projet qui sont ainsi fixées au début,
on utilise ensuite des méthodes qui utilisent ces dimensions mais pas besoin de les renseigner à chaque fois

## Preparation des images
- une fonction pour reshape les images
- une fonction pour dégrader la résolution
- normaliser (voir TP chat et chien)

## Fonctions d'affichage
- affichage d'images
- affichage des courbes loss et accuracy


### PLAN

1. Analyse exploratoire

2. Classification binaire

3. Classification fine

4. Segmentation des animaux

5. Analyse comparative
