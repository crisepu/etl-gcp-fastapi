# ETL GCP FastAPI

Learning project: dual profile Software Engineer + Data Engineer.
Built in 5 progressive phases covering Python, FastAPI, and Google Cloud Platform.

## Project Phases

| Phase | Topic | Status |
|-------|-------|--------|
| 1 | Python + Pandas + EDA | In progress |
| 2 | FastAPI | Pending |
| 3 | GCP (BigQuery, Cloud Storage) | Pending |
| 4 | ETL Pipeline | Pending |
| 5 | Orchestration (Airflow / Cloud Composer) | Pending |

## Phase 1 — NYC Taxi EDA

Exploratory Data Analysis on the NYC Yellow Taxi public dataset (January 2023).

**Stack:** Python 3.x · pandas · matplotlib · seaborn · Jupyter Notebook

**Notebook:** [notebooks/01_eda_nyc_taxi.ipynb](notebooks/01_eda_nyc_taxi.ipynb)

## Project Structure

```
etl-gcp-fastapi/
├── data/
│   ├── raw/          # Original files, never modified
│   └── processed/    # Clean data produced by notebooks
├── notebooks/        # Jupyter analysis notebooks
├── src/              # Reusable source code (Phases 2-5)
└── README.md
```

## Setup

```bash
pip install pandas matplotlib seaborn jupyter pyarrow
jupyter notebook
```
