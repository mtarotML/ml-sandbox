# ML From Scratch

Ce projet a pour objectif de **recréer des algorithmes de Machine Learning à partir de zéro**, en utilisant **Python et Numpy**, afin de comprendre leur fonctionnement interne et développer des compétences solides en ML.

## Objectifs
- Implémenter des algorithmes classiques (régression linéaire, régression logistique, perceptron, réseaux de neurones) sans utiliser de librairies ML comme scikit-learn ou TensorFlow.
- Expérimenter et visualiser les résultats à l’aide de notebooks.
- Structurer le code proprement pour faciliter l’évolution vers des projets plus complexes.

## Structure du projet
ml-from-scratch/
├── README.md # Présentation du projet
├── notebooks/ # Notebooks pour prototypage et exploration
├── src/ # Code Python “propre”
│ ├── init.py
│ ├── linear_regression.py
│ ├── logistic_regression.py
│ └── neural_network.py
├── tests/ # Tests unitaires
└── requirements.txt # Librairies nécessaires

bash
Copier le code

## Installation
1. Cloner le repo :
```bash
git clone https://github.com/mtarotML/ml-sandbox.git
cd ml-from-scratch
Créer un environnement virtuel et installer les dépendances :

bash
Copier le code
python -m venv venv
source venv/bin/activate      # Linux / Mac
venv\Scripts\activate         # Windows
pip install -r requirements.txt