
# Pandas Data Analysis Practice

A collection of beginner-friendly Jupyter notebooks for learning pandas and practicing exploratory data analysis. The notebooks include short explanations, readable comments, and small examples.

## Contents

| Notebook | Topics |
|---|---|
| `01_pandas_series.ipynb` | Creating Series and using custom indexes |
| `02_pandas_dataframes.ipynb` | DataFrame creation, selecting rows/columns, filtering |
| `03_missing_data.ipynb` | Detecting, dropping, and filling missing values |
| `04_merge_concat_join.ipynb` | Merging, concatenating, and joining DataFrames |
| `05_groupby_aggregation.ipynb` | Grouping and summarizing data |
| `06_pivot_tables.ipynb` | Pivot tables and cross-tabulations |
| `07_dataframe_operations.ipynb` | Basic DataFrame operations and `apply` |
| `08_anime_feature_extraction.ipynb` | Extracting features from anime title strings |
| `09_country_data_analysis.ipynb` | Questions and exploration using country data |

## Datasets

- `data/anime.csv` — anime titles, ranks, and scores used in the feature-extraction notebook.
- `data/Countries.csv` — country-level data used in the country analysis notebook.

The country dataset may contain missing values and reflects the supplied source data; it should not be treated as a live or authoritative current-data feed.

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- pandas
- NumPy

## Setup

1. Clone or download this repository.
2. Open a terminal in the repository folder.
3. (Recommended) Create and activate a virtual environment.

   ```bash
   python -m venv .venv
   ```

   Windows PowerShell:
   ```powershell
   .venv\Scripts\Activate.ps1
   ```

   macOS/Linux:
   ```bash
   source .venv/bin/activate
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start Jupyter from the repository root so the relative paths to `data/` work:

   ```bash
   jupyter notebook
   ```

6. Open a notebook and run the cells from top to bottom.

## Notes

- Outputs are cleared so GitHub displays the notebooks cleanly and repository diffs remain readable.
- Some examples intentionally demonstrate pandas behavior; read each cell's comments before changing it.
- Generated sales values in the pivot-table notebook are reproducible because a random seed is set.


