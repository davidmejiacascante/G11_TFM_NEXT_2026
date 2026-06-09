HEALTHCARE WORKER BURNOUT ANALYSIS
=================================

See README.md for full documentation.

Setup:
  python -m venv .venv
  .venv\Scripts\activate
  pip install -r requirements.txt

Commands:
  black .
  ruff check .
  pytest -v

Data:
  data/raw/      # raw study datasets
  data/processed/ # cleaned datasets with CBI scores

Outputs:
  reports/       # generated visualizations
  notebooks/     # analysis notebooks
