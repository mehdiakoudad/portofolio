# Multiclass Health Test Prediction with Machine Learning

This project presents a machine learning solution designed to classify patient health test results into three categories: **Normal**, **Abnormal**, and **Inconclusive**. The goal is to assist healthcare providers in identifying patterns and predicting test outcomes based on key clinical data.

The project walks through a full machine learning pipeline—from **data acquisition and cleaning** to **model training, evaluation**, and **interpretation of results**. It also includes **feature engineering** and **ensemble learning techniques** to improve predictive performance.

📖 **Read the full article on Medium:**  
👉 [Multiclass Health Test Prediction with Machine Learning](https://medium.com/@akoudadmehdi01/multiclass-health-test-prediction-with-machine-learning-3a1d92faf994)

---

## 🧠 Problem Statement

Given a dataset containing anonymized patient attributes and test parameters, the task is to build a model that accurately classifies test results into one of the three possible outcomes. This is a **multiclass classification** problem that requires balanced performance across all three labels.

---

## 📊 Techniques Used

- **Exploratory Data Analysis (EDA):**
  - Visualized distributions, correlations, and outliers
  - Identified class imbalance and data quality issues
- **Data Preprocessing:**
  - Null handling, encoding, normalization
  - Stratified train-test splitting to preserve class distribution
- **Feature Engineering:**
  - Selected top features via correlation and importance scores
  - Tested polynomial combinations for model boost
- **Model Training:**
  - Compared multiple classifiers: Random Forest, XGBoost, CatBoost
  - Hyperparameter tuning using GridSearchCV
- **Evaluation Metrics:**
  - Accuracy, Precision, Recall, F1-Score (macro/micro)
  - Confusion matrix and classification report
- **Model Interpretation:**
  - Feature importance via SHAP and built-in tree methods

---

## 🛠️ Tools & Libraries

- **Languages:** Python
- **Libraries:**
  - `pandas`, `numpy` — for data wrangling
  - `matplotlib`, `seaborn` — for visualization
  - `scikit-learn`, `xgboost`, `catboost` — for modeling
  - `SHAP` — for model explainability
- **Environment:** Jupyter Notebook

- ## 🙌 Feedback

This project is part of my open portfolio.  
I welcome **feedback**, **collaborations**, and **job opportunities** in data analytics and machine learning.

---

📩 Contact: [LinkedIn](https://www.linkedin.com/in/mehdiakoudad/) | [Medium](https://medium.com/@akoudadmehdi01)
