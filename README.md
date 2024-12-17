# Résolution du problème TSPTW à l'aide de la recherche opérationnelle en Python
### Cesi A3
## Description du projet

Ce projet vise à résoudre le problème du TSPTW (Traveling Salesman Problem with Time Windows) en utilisant des techniques de recherche opérationnelle implémentées en Python.

Le problème TSPTW est une variante du problème classique du voyageur de commerce (TSP). Il consiste à trouver le chemin le plus court passant par un ensemble de nœuds (à visiter une seule fois), tout en respectant des contraintes de fenêtres de temps associées à chaque nœud.

Les principaux objectifs sont :

- Minimiser la distance totale parcourue par le voyageur.
- Respecter les plages horaires (fenêtres de temps) de chaque nœud.
- Assurer une solution optimale à l'aide d'algorithmes et de modèles mathématiques.

---

## Contexte et objectifs

La recherche opérationnelle offre des méthodes puissantes pour modéliser et résoudre des problèmes complexes impliquant des contraintes et des optimisations.

Le projet met en application des techniques telles que :

- Programmation linéaire et programmation linéaire en nombres entiers (PL/PLNE).
- Modélisation mathématique.
- Utilisation de solveurs d'optimisation tel que PuLP en Python.

Ce projet a été réalisé dans le cadre d'un module de recherche opérationnelle, avec pour but de résoudre un graphe représentant le TSPTW.

---

## Exemple de graphe

Voici un exemple de graphe simple avec contraintes de fenêtres de temps :

- **Nœuds** : A, B, C, D.
- **Fenêtres de temps** :
  - A : [0, 5]
  - B : [2, 8]
  - C : [4, 10]
  - D : [6, 12].
- **Distances** : A-B : 3, B-C : 4, C-D : 2, etc.

Le programme déterminera le chemin optimal en tenant compte des contraintes.

---

## Résultats attendus

- **Chemin optimal** respectant les fenêtres de temps.
- **Distance totale minimale** parcourue.
- Visualisation graphique de la solution.
- Comparaison avec Méta- Heuristique
---


