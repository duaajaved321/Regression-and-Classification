# Chronic Kidney Disease (CKD) — Regression and Classification

This is my machine learning milestone project. I used the **UCI Risk Factor Prediction of Chronic Kidney Disease** dataset to practice regression and classification in Python.

## What I Did

- Loaded and explored the dataset.
- Checked missing values and prepared the data for modeling.
- Used **Linear Regression** to predict an approximate GFR value from the dataset's GFR ranges.
- Used **Logistic Regression** to classify CKD and non-CKD records.
- Split the data into training and testing sets.
- Used preprocessing pipelines for numerical and categorical features.
- Evaluated the models using metrics and graphs, and compared them with simple baselines.
- Used cross-validation on the classification training data.

## Tools and Libraries

Python, Google Colab, pandas, NumPy, Matplotlib, scikit-learn, and ucimlrepo.

## How to Run

1. Open `CKD_Regression_Classification_Reviewed.ipynb` in Google Colab.
2. Go to **Runtime → Run all**.
3. The notebook installs `ucimlrepo` and loads the dataset automatically, so an internet connection is needed.
4. Check the outputs and graphs to see the model results.

## Note

This project is for learning and experimentation only. The dataset is small (200 records), so the results may not generalize well. The regression target is an **approximation from GFR ranges**, not an exact measurement. It is not intended for medical diagnosis.

**Dataset:** [Risk Factor Prediction of Chronic Kidney Disease — UCI](https://archive.ics.uci.edu/dataset/857/risk+factor+prediction+of+chronic+kidney+disease) (CC BY 4.0).
