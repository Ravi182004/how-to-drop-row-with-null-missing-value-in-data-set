# 🧠 Applicant Qualification Classifier

This project builds a machine learning pipeline to predict whether applicants are **qualified or not** based on structured feature data. It compares three classification models—Logistic Regression, Decision Tree, and Random Forest—using hyperparameter tuning and metric-based evaluation.

## 📁 Project Structure

- `data/` – Raw and cleaned datasets (add if needed)
- `notebooks/` – Jupyter notebooks for EDA, training, and tuning
- `scripts/` – Python scripts to run preprocessing and models
- `README.md` – Project overview and usage guide

## 🔍 Key Features

- Categorical encoding with `LabelEncoder`
- Target mapping from `'Yes'/'No'` to binary
- Model training and evaluation:
  - ✅ Logistic Regression
  - 🌳 Decision Tree
  - 🌲 Random Forest
- Hyperparameter tuning with:
  - `GridSearchCV`
  - `RandomizedSearchCV`
- Unified evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Visualizations:
  - Feature importances
  - Coefficients for interpretability
  - Decision tree plots

## 🚀 Getting Started

### 🔧 Installation
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
