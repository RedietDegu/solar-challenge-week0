# Notebooks

- `benin_eda.ipynb`: Week 0 Task 2 exploratory data analysis for the Benin dataset. Activate the `.venv` environment, select the `Python (solar-week0)` kernel, and point `raw_path` to `data/benin_raw.csv` (kept out of Git).
- `compare_countries.ipynb`: Week 0 Task 3 cross-country comparison. Expects cleaned CSVs in `data/<country>_clean.csv`. The notebook creates placeholder data if files are missing—replace them with the official cleaned outputs before drawing conclusions.

General tips:
- Keep raw CSVs in `../data/` (they are ignored by Git).
- Clear noisy outputs before committing (`Kernel → Restart & Clear Outputs`).
- Promote reusable functions to `src/` or `scripts/` so notebooks stay focused on analysis.
