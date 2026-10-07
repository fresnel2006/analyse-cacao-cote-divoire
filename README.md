# Analyse du cacao ivoirien et de la déforestation

Exploration du dataset **cote_divoire_cocoa** (Trase) sur les exportations de cacao de Côte d'Ivoire : départements de production, coopératives, exportateurs, pays de destination et déforestation liée au cacao.

## Ce que fait le notebook
- Lecture du CSV (environ 38 Mo) directement en SQL avec DuckDB
- Normalisation des colonnes texte (département, coopérative, exportateur, groupe de négoce, pays de destination, bloc économique...)
- Dédoublonnage des lignes
- Préparation des données pour l'analyse de la déforestation annuelle liée au cacao

## Lancer le projet
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

## Stack
Python, DuckDB, pandas, Jupyter

## Auteur
Ange Fresnel Traoré - ESATIC, Abidjan
