# Netflix Titles — Exploratory Data Analysis

**Project 01 — Pluto Academy AI & ML Internship Program**

## Overview
This project performs an end-to-end exploratory data analysis (EDA) on the
Netflix Titles dataset (`netflix_titles.csv`), covering data loading,
cleaning, analysis, visualization, and insight generation.

## Dataset
- **File:** `netflix_titles.csv`
- **Rows:** 8,807 titles
- **Columns:** 12 (show_id, type, title, director, cast, country, date_added,
  release_year, rating, duration, listed_in, description)
- **Source:** Netflix Movies and TV Shows catalogue

## What's in this repo
| File | Description |
|---|---|
| `netflix_eda.ipynb` | Main notebook — full analysis, all code, all outputs |
| `netflix_titles.csv` | Raw dataset used in the notebook |
| `README.md` | This file |

## Project Structure (inside the notebook)
1. **Load & Inspect the Data** — shape, dtypes, missing values, duplicates, 5-line data summary
2. **Clean the Data** — documented handling of missing values, type fixes, irrelevant column removal
3. **Exploratory Data Analysis** — 5 specific questions answered with Pandas (groupby, value_counts, describe)
4. **Visualizations** — 6 chart types: bar, line, histogram, scatter, pie, heatmap (all titled/labeled)
5. **Insights Report** — 5 numbered, data-backed insights, plus a short note on the most surprising finding

## How to run
### Option A — Jupyter locally
```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook netflix_eda.ipynb
```
Run all cells (Kernel → Restart & Run All).

### Option B — Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `netflix_eda.ipynb` (File → Upload notebook).
3. Upload `netflix_titles.csv` to the Colab session's file storage (folder icon on the left → upload), so the `pd.read_csv('netflix_titles.csv')` cell can find it.
4. Run all cells (Runtime → Run all).

## Key Tools Used
- Python, Pandas, NumPy, Matplotlib

## Author
[Your Name Here]
