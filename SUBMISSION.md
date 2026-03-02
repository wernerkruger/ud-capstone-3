# Submission Checklist

## Deliverables

1. **modeling.ipynb** — Run the notebook top-to-bottom (e.g. in Jupyter or VS Code). Ensure the dataset CSV is in the same folder or Kaggle credentials are set for kagglehub.
2. **Machine_Learning_Analysis_Report.pdf** — Export the report to PDF:
   - From `Machine_Learning_Analysis_Report.md`: use **pandoc** (`pandoc Machine_Learning_Analysis_Report.md -o Machine_Learning_Analysis_Report.pdf`) or your editor’s “Print to PDF” / “Export to PDF”.
   - If your rubric asks for `module_summary.pdf`, use that filename when exporting.
3. **requirements.txt** — For submission, regenerate with: `pip freeze > requirements.txt` so it matches your environment.
4. **Dataset** — The file `global_placement.csv` is included in the project folder.

## Quick start

```bash
pip install -r requirements.txt
jupyter notebook modeling.ipynb
```

Place `global_placement.csv` in the same directory as the notebook, or configure Kaggle API and the notebook will download it via kagglehub.
