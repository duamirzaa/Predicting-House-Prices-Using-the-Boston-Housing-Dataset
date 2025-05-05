# Predicting-House-Prices-Using-the-Boston-Housing-Dataset
Regression model comparison using custom implementations of Linear Regression, Random Forest, and XGBoost on the Boston Housing dataset. Includes performance evaluation and feature importance visualizations.
# 🏡 Boston Housing Price Prediction - Regression Models from Scratch

This project implements **Linear Regression**, **Random Forest**, and **XGBoost** from scratch to predict housing prices using the Boston Housing dataset. It includes model training, evaluation using RMSE and R² metrics, and visualizations such as RMSE comparison and feature importance plots for tree-based models.

---

## 📌 Features

- ✅ Linear Regression (closed-form solution)
- 🌲 Random Forest Regressor (simplified custom implementation)
- 🚀 XGBoost Regressor (gradient boosting from scratch)
- 📏 Normalization of input features
- 📊 Model performance evaluation using:
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
- 📉 RMSE comparison across models (bar chart)
- 🔍 Feature importance visualization for:
  - Random Forest
  - XGBoost

---

## 📂 Dataset

- **Boston Housing Dataset**
- 13 input features + 1 target variable (`MEDV`)
- Predicts the median value of owner-occupied homes in $1000s

---

## 🛠️ Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (for evaluation only)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

```bash
pip install numpy pandas matplotlib scikit-learn
