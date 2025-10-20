# Netflix Streaming Platform Analysis

Analytical project exploring Netflix content and trends using a public dataset and an interactive Jupyter Notebook. The analysis focuses on content metadata, ratings, genres and temporal trends to inform decisions for product/market strategy.

## Contents
- [Notebook with analysis and visualizations](netflix_analysis.ipynb)
- [Raw dataset (CSV)](netflix_dataset.csv)

## Overview
This repository contains:
- netflix_analysis.ipynb — interactive Jupyter Notebook with data cleaning, exploration and visualizations (Plotly, Matplotlib/Seaborn).
- netflix_dataset.csv — source dataset with show IDs, titles, type (MOVIE/SHOW), descriptions, release year, rating/duration, genres, country, and external scores (IMDb/TMDb).

Example data columns included in the CSV: show id, title, type, description, release_year, rating, duration, listed genres, country, imdb_id, imdb_score, tmdb_score (see the dataset file for full schema).

Files:
- [netflix_analysis.ipynb](netflix_analysis.ipynb)
- [netflix_dataset.csv](netflix_dataset.csv)

## Quickstart

1. Clone or download the repository.
2. Create a Python environment (recommended Python 3.8+):
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .venv\Scripts\activate      # Windows

3. Install common dependencies used in the notebook:
   pip install pandas plotly jupyterlab matplotlib seaborn numpy

4. Launch the notebook:
   jupyter notebook netflix_analysis.ipynb
   or
   jupyter lab netflix_analysis.ipynb

Open and run the notebook cells to reproduce the analysis and interactive charts.

## Notes & Recommendations
- The notebook uses Plotly for interactive visualizations (client-side). For reproducible static outputs consider exporting figures or saving as images.
- Review the dataset for missing or malformed values before extending analysis.
- If you plan to publish visualizations online, remove or mask any sensitive information if present.

## License
MIT License — include a LICENSE file if you want to make this explicit.

## Author / Contact
Marko Vučković

If you want improvements (packaged scripts, requirements.txt, Dockerfile, or automated report export), open an issue or create a PR.
