# Car-Price-Prediction-Using-Machine-Learning
# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the selling price of a used car based on various features such as year, present price, fuel type, seller type, transmission, and more. It uses supervised machine learning techniques, including Linear Regression, Lasso Regression, and Random Forest with cross-validation and hyperparameter tuning.

---

## 📌 Project Overview

- **Problem Statement**: Estimate the price of used cars to help buyers and sellers make informed decisions.
- **Dataset**: `car data.csv` (provided by a car dealership), includes car attributes and actual selling prices.
- **Goal**: Build an accurate and robust regression model to predict car prices.

---

## 📊 Features Used

| Feature            | Description                         |
|--------------------|-------------------------------------|
| `Year`             | Year of manufacturing               |
| `Present_Price`    | Current ex-showroom price (in Lakhs)|
| `Kms_Driven`       | Kilometers driven                   |
| `Fuel_Type`        | Petrol, Diesel, or CNG              |
| `Seller_Type`      | Dealer or Individual                |
| `Transmission`     | Manual or Automatic                 |
| `Owner`            | Number of previous owners           |

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values and data imbalance
- Encoded categorical features (Fuel_Type, Seller_Type, Transmission)
- Visualized feature distributions and correlations using Seaborn and Matplotlib

---

## 🧠 Models Implemented

| Model              | R² Score (Test) | RMSE (Test) |
|--------------------|----------------|-------------|
| Linear Regression  | ~0.87          | ~1.05       |
| Lasso Regression   | ~0.84          | ~1.15       |
| ✅ Random Forest    | **0.98**        | **0.52**     |

> Random Forest with GridSearchCV produced the best results with 97.9% accuracy.

---

## ⚙️ Techniques Used

- Data Preprocessing & Label Encoding
- Train-Test Split (90%-10%)
- Cross-Validation (5-Fold)
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation using R² Score and RMSE
- Visualization of Predicted vs Actual Prices

---

## 📦 Libraries Used

- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn



