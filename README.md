# Vote pondéré de Golub — WDBC

Comparaison du vote pondéré et de la régression logistique sur 569 patients. Seed : **23**.

## Exécution

Prérequis : `uv` installé ; conserver `pyproject.toml`, `uv.lock` et le dossier `data` à côté de `notebook.ipynb`.

```bash
uv run jupyter nbconvert --to notebook --execute --inplace notebook.ipynb
```

La commande exécute toute l'analyse et met à jour les sorties du notebook. Cette version exporte aussi les tableaux et figures dans `results/`.

Pour ouvrir le notebook :

```bash
uv run jupyter lab notebook.ipynb
```

## Références

- Golub et al. (1999) : [10.1126/science.286.5439.531](https://doi.org/10.1126/science.286.5439.531).
- Données WDBC, UCI : [10.24432/C5DW2B](https://doi.org/10.24432/C5DW2B).

Code préparé avec l'assistance de ChatGPT.
