# TP Modèles génératifs avec PyTorch

**Auteure :** Aya Khalil, EMSI Casablanca, 5IAD G2

## Description

Ce TP porte sur les modèles génératifs avec PyTorch, appliqués au dataset MNIST (chiffres manuscrits). Le générateur entraîné est sauvegardé dans `generator_mnist.pt`.

## Contenu du dépôt

- `Modeles_generatifs_pytorch.ipynb` : notebook du TP (code, résultats)
- `main.py` : script Python du TP
- `generator_mnist.pt` : poids du générateur entraîné
- `pyproject.toml` et `uv.lock` : dépendances du projet
- `data/MNIST/raw` : fichiers du dataset MNIST

## Installation

Avec `uv` :

```bash
uv sync
```

Ou avec `pip` :

```bash
pip install torch torchvision matplotlib jupyter
```

## Exécution

Lancer le script :

```bash
python main.py
```

Ou ouvrir le notebook `Modeles_generatifs_pytorch.ipynb` avec Jupyter ou VS Code.

## Remarque

Le dataset MNIST est téléchargé automatiquement par `torchvision` s'il est absent.
