# Machine Learning Projects

Classical ML examples for classification, regression, clustering, dimensionality reduction, text classification, and model tuning.

- `src/` — Python scripts
- `datasets/` — CSV files used by scripts

## Setup
```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```
Run scripts from this folder (the parent of `src/`) so `datasets/...` paths resolve. Some examples use built-in scikit-learn datasets or fetch data online.