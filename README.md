# 🛍️ Online Shoppers Purchase Intentions – EDA & Prediction

This project explores a dataset of online shopping sessions to understand customer behavior and predict purchase intent using machine learning.

---

## 📊 Problem Statement

The goal is to predict whether an online user will generate revenue (i.e., complete a purchase) based on session-related behavior like page visits, time spent, bounce rate, and more.

---

## 🧠 Objectives

- Perform Exploratory Data Analysis (EDA) on session behavior.
- Preprocess features and handle categorical variables.
- Train and evaluate machine learning models.
- Interpret results using metrics and visualizations.

---

## 📁 Dataset

- Source: [Kaggle – Online Shoppers Purchasing Intention Dataset](https://www.kaggle.com/datasets/rohitsahoo/predicting-online-shoppers-intention)
- Rows: 12,330  
- Columns: 18 (including session info, traffic type, bounce rates, weekend flag, etc.)

---

## 🔍 Exploratory Data Analysis

- Null values check and type conversion
- Categorical variable distribution
- Purchase vs non-purchase trends
- Correlation heatmap and pairplots
- Class imbalance analysis

---

## ⚙️ Machine Learning Workflow

- **Encoding** categorical features
- **Feature Scaling**
- **Train-Test Split**
- **XGBoost Classifier** used for prediction
- Model evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC Curve
  - Confusion Matrix

---

## 📈 Results

- Achieved good classification performance with balanced precision and recall.
- ROC-AUC score shows strong ability to differentiate buyers vs non-buyers.

---

## 📦 Files Included

- `Online_Shopper_EDA_Model.ipynb` – Full analysis & modeling
- `Cleaned_Online_Shopper_Data.csv` – Cleaned dataset (optional)

---

## 🧰 Tools Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📌 Future Improvements

- Try other ML models (Random Forest, SVM)
- Hyperparameter tuning
- Address class imbalance with SMOTE or similar techniques

---

⭐ Feel free to fork and explore!
