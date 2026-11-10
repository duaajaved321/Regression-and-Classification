# Chronic Kidney Disease (CKD) — Regression and Classification

An educational supervised machine-learning project using the UCI Risk Factor Prediction of Chronic Kidney Disease dataset.

## Objective

- **Regression:** Estimate an approximate GFR proxy from interval-valued GFR data.
- **Classification:** Predict the dataset's CKD / not-CKD label using Logistic Regression.

## Workflow

- Inspect the dataset, data types, class distribution, and missing values.
- Convert available GFR intervals to an approximate numerical proxy for the regression exercise.
- Build separate regression and classification datasets.
- Exclude outcome-related columns such as `stage`, `affected`, and original GFR information from model inputs.
- Split training and testing data before fitting preprocessing.
- Use scikit-learn pipelines for imputation, scaling, and categorical encoding.
- Evaluate with regression and classification metrics, visualizations, and cross-validation.

## Tools

Python, Pandas, NumPy, Matplotlib, scikit-learn, ucimlrepo, Google Colab / Jupyter.

## Run the Notebook

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Open `CKD_Regression_Classification.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook from top to bottom. Dataset retrieval requires internet access.

## Dataset

[UCI Risk Factor Prediction of Chronic Kidney Disease](https://archive.ics.uci.edu/dataset/857/risk+factor+prediction+of+chronic+kidney+disease) (CC BY 4.0).

## Important Limitations

The dataset contains only 200 records. The regression target is an approximation derived from GFR ranges, not a laboratory-measured GFR value. Results are educational and are not suitable for medical decisions or diagnosis.

**Notebook:** `CKD_Regression_Classification.ipynb`
