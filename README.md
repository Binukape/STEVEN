# STEVEN

📁 Google Drive Contents — Dementia Prediction ML Project

This folder contains all notebooks, datasets, and saved models used throughout the dementia prediction machine learning pipeline.

---

## **1. `EDA.ipynb` — Exploratory Data Analysis**

This notebook contains the initial analysis performed on the dataset.
It includes:

* Dataset overview and structure
* Missing value analysis
* Distribution plots and summary statistics
* Outlier detection
* Correlation maps and feature relationships
* Key insights that guided preprocessing and modeling steps

---

## **2. `ModelX.ipynb` — Full Machine Learning Pipeline**

This is the main notebook for all core machine learning work.
It covers:

* Data cleaning and preprocessing
* Feature engineering and encoding
* Model training (multiple algorithms)
* Hyperparameter tuning
* Performance evaluation using accuracy, precision, recall, F1-score, ROC, etc.
* Explainability (feature importance, SHAP/LIME analysis)
* Comparison of model results and selection of the final model

---

## **3. `final_pickle_models.zip` — Trained Model Archive**

A compressed folder containing all saved machine learning models generated during experimentation, including:

* Baseline models
* Tuned versions of individual models
* Ensemble / stacked models
* The final selected model
  These `.pkl` files allow models to be loaded directly without retraining.

---

## **4. `Dimentia Prediction Dataset.csv` — Project Dataset**

The main dataset used to build the dementia prediction model.
It contains:

* Patient demographic attributes
* Clinical and lifestyle-related features
* The target label indicating dementia status
  This dataset is used across both the EDA and ModelX notebooks.
