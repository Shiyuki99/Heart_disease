# Heart Disease Prediction (Study Project)

> **This is a study project** focused on practicing an end-to-end data science workflow for heart disease prediction.

## Project Goal
Build a machine learning pipeline that predicts the presence of heart disease (binary classification) from clinical features, using a combined dataset from four different countries: Cleveland, Hungary, Switzerland, and Long Beach (VA).

## Dataset
Source: [UCI Machine Learning Repository — Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease)

## Files
- `FDS_Project_Heart_disease.ipynb` — main notebook
- `requirements.txt` — project dependencies

---

## Setup

> **Strongly recommended:** use a virtual environment to avoid polluting your global Python installation and ensure reproducible results.

### Windows (PowerShell)

**Step 1 — Create & activate a virtual environment**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

> If you get an execution policy error, run this first (current session only):
> ```powershell
> Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
> ```

**Step 2 — Install dependencies**
```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Step 3 — Launch Jupyter**
```powershell
jupyter notebook
```

---

### Linux / macOS (Bash)

**Step 1 — Create & activate a virtual environment**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Step 2 — Install dependencies**
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

**Step 3 — Launch Jupyter**
```bash
jupyter notebook
```

---

## Notes
- The `.venv` folder is local to this project — do not commit it to version control.
- Re-run the install step after updating `requirements.txt`.
