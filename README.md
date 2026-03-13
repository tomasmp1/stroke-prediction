# Stroke Prediction Using Machine Learning

This project demonstrates the use of **machine learning models** to predict the risk of **stroke** based on patient demographic and health data. It includes **exploratory data analysis (EDA)**, **data preprocessing**, and **model training/evaluation** using multiple classifiers including **Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, and XGBoost**.

---

## Key Insights

- **Age is the strongest predictor** of stroke, with higher age associated with increased risk.  
- **Other risk factors include hypertension, heart disease, and BMI**, with missing BMI values carrying predictive signal.  
- **Self-employment, marital status, and smoking patterns** show notable associations with stroke risk.  
- **Class imbalance is addressed** through stratified splitting, threshold tuning, and class-weighted models.  
- **Model performance**: Logistic Regression and XGBoost provide strong F1 scores and ROC-AUC, with feature importance highlighting key predictors.

---

## Repository Contents

- `data/`
  - `stroke-data.csv` : Original Kaggle stroke dataset  
- `notebooks/`
  - `eda.ipynb` : Exploratory Data Analysis with visualizations, missing value checks, and feature investigation  
  - `modelling.ipynb` : Data preprocessing, machine learning models, hyperparameter tuning, evaluation, and feature importance  
- `README.md` : This file  

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

It contains patient demographic and health attributes used to predict the likelihood of stroke.

---

## Getting Started

1. **Clone or download the repository**.  
2. Ensure the dataset `stroke-data.csv` is in the `data/` folder.  
3. Open the notebooks in [Google Colab](https://colab.research.google.com/) or Jupyter.  
4. Install the required packages.
