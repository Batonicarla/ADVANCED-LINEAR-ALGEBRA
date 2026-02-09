# PCA Formative — Carla

Short README for the PCA formative notebook and dataset in this repository.

**Overview**
- This repository contains a Jupyter notebook exploring Principal Component Analysis (PCA) applied to a CO2 emissions dataset for African countries. The analysis includes data loading, preprocessing, PCA transformation, and visualizations.

**Files**
- [PCA_Formative_1_Carla (2).ipynb](PCA_Formative_1_Carla(2).ipynb) — the notebook with the PCA analysis.
- [data/co2 Emission Africa.csv](data/co2 Emission%20Africa.csv) — dataset used by the notebook.

**Requirements**
- Python 3.8+
- Recommended packages: `jupyter`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.

Quick install (PowerShell):
```powershell
cd "C:\Users\HP\ADVANCED-LINEAR-ALGEBRA"
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install jupyter pandas numpy scikit-learn matplotlib seaborn nbstripout
```

**Run the notebook**
- Start Jupyter Lab / Notebook and open the notebook file above, or execute it headlessly:
```powershell
jupyter lab
# or to execute the notebook end-to-end and save outputs:
jupyter nbconvert --execute --to notebook --inplace "PCA_Formative_1_Carla (2).ipynb"
```

**Dataset**
- The dataset is located in the `data/` folder. If your dataset files are large (>50MB) consider using Git LFS. The CSV included here is small and already present at `data/`.

**Repository status**
- Notebook outputs have been stripped to keep the repository lightweight. If you want to re-run and commit outputs, run the notebook and commit as usual.


**Author**: Carla
