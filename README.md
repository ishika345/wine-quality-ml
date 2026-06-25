# 🍷 Wine Quality Prediction — ML Project

A complete machine learning pipeline to classify wine quality as **GOOD** (quality ≥ 7) or **BAD** (quality < 7) using physicochemical properties.

## 📊 Dataset
UCI Wine Quality Dataset (Red Wine) — 1,599 samples, 11 features.

## 🔧 Project Steps
1. Exploratory Data Analysis (`head()`, `info()`, `describe()`)
2. Missing value & correlation analysis
3. Binary target creation (`quality_label`)
4. Train-test split
5. Logistic Regression (with & without scaling)
6. Model comparison: Logistic Regression vs KNN vs Decision Tree
7. Hyperparameter tuning with GridSearchCV
8. Feature importance analysis (permutation importance)

## 🏆 Best Model
KNN (k=5), tuned via GridSearchCV.

## 🛠️ Tools
Python, pandas, scikit-learn, matplotlib, seaborn — run in Google Colab.

## 📂 Files
- `Wine_Quality_ML_Project.ipynb` — full notebook with code, visualizations, and analysis
