# Optimisation des Régimes Alimentaires

## Description du projet

Ce projet de recherche opérationnelle se concentre sur la **gestion des régimes alimentaires** dans les environnements hôteliers et autres lieux à forte fréquentation.
L’objectif est de proposer une **solution efficace et inclusive** pour :

* Répondre aux besoins alimentaires variés des clients,
* **Minimiser** le nombre de plats proposés,
* Assurer une **diversité suffisante** pour satisfaire toutes les contraintes.

Nous considérons **8 régimes alimentaires différents**, chacun présentant des **incompatibilités spécifiques**. Ces restrictions sont prises en compte lors de la planification des repas, afin de garantir que chaque client trouve un menu adapté.

## Méthodologie

Pour résoudre ce problème, nous avons :

* Modélisé les **incompatibilités entre régimes** sous forme de graphe,
* Utilisé la **coloration des graphes** pour minimiser le nombre de plats nécessaires,
* Visualisé les résultats grâce à **NetworkX** et **Matplotlib**,
* Implémenté l’ensemble dans un **notebook Jupyter** pour une meilleure interactivité.

## Technologies utilisées

* **Python 3**
* **NetworkX** → Modélisation et traitement des graphes
* **Matplotlib** → Visualisation des graphes et des solutions
* **Jupyter Notebook** → Développement et exécution du projet

## Résultats attendus

* Nombre minimal de plats nécessaires pour couvrir tous les régimes,
* Visualisation d’un graphe coloré représentant les incompatibilités et leur résolution,
* Preuve de faisabilité pour une planification alimentaire inclusive et optimisée.

## Perspectives

Ce projet fournit une **première approche opérationnelle** pour la gestion des régimes alimentaires. Des extensions possibles incluent :

* La prise en compte de **nouvelles contraintes** (budget, disponibilité des ingrédients, saisonnalité),
* L’intégration dans une **application de gestion hôtelière** complète,
* L’exploration d’algorithmes plus avancés (programmation linéaire, heuristiques).

