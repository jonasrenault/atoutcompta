# Compta Atoutprises

Script pour générer les écritures comptables pour la saisie des salaires d'Atoutprises.

## Installation

Il faut installer ghostscript en local. Suivre les instructions [ici](https://camelot-py.readthedocs.io/en/master/user/install-deps.html).

## Utilisation

### Utilisation en ligne avec Google Colab

<a target="_blank" href="https://colab.research.google.com/github/jonasrenault/atoutcompta/blob/main/ComptaColab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### Utilisation en local

Installer le projet avec [uv](https://github.com/astral-sh/uv) :

```bash
uv sync
```

Lancer le server jupyter-lab

```bash
$ uv run jupyter lab
```

S'assurer que le fichier avec les dépenses simplifiées est dans le répertoire courant.
