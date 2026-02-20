# ProjetS4PEIP2
# PolyPonts Racing
## Description générale

Ce projet a été réalisé en tant que projet de fin d'année de PEIP2.
Il consiste en un petit jeu permettant d'illustrer un problème d'ordonnancement : le flow-shop à deux machines.

Concrètement, vous allez devoir aider des personnages à traverser des ponts le plus rapidement possible, en les triant dans l'ordre de votre choix.
Vos personnages affronteront d'autres personnages triés par une IA très perfectionnée. Mais attention ! Les ponts sont fragiles, et seulement une seule personne peut monter sur un pont à la fois.

De plus, chaque personne met un temps différent à traverser chaque pont ! Il vous faudra donc trier les personnes afin d'optimiser le temps de passage de chaque personne, et ainsi, de battre le tri de l'IA.

Ce jeu est disponible en version Web à cette adresse : https://spishewi.github.io/Projet-Polyponts-Racing-PEIP2S4-2024-2025/

## Technologies utilisées

Ce projet a été réalisé avec [Python 3](https://www.python.org/), en utilisant la bibliothèque graphique [Pygame](https://pyga.me/).


Nous avons ensuite utilisé l'outil [PygBag](https://github.com/pygame-web/pygbag) pour porter ce jeu Python en version Web.

## Installation depuis les sources

1. Installez Python 3.12+ depuis [le site officiel](https://www.python.org/). (note: faites attention à installer `pip` et ajouter Python au `path`).
2. Installez les dépendances avec la commande :
```bash
pip install -r requirements.txt
```
3. Vous pouvez ensuite naviguer dans le dossier source (`src/`) et lancer le programme avec la commande `python main.py`.

## Crédits
- font: Daniel Linssen
- Dessin du personnage: Segel2D
- Icônes: Lucide Contributors 2022 (voir LUCIDE-LICENSE)

## License

Ce projet est distribué sous licence MIT.


Vous êtes libre d’utiliser, copier, modifier et distribuer ce code, y compris dans des projets commerciaux, à condition de conserver la mention de copyright et le texte de la licence d’origine.
Le logiciel est fourni « tel quel », sans aucune garantie d’aucune sorte.
Pour plus d’informations, consultez le fichier LICENSE inclus dans ce dépôt.