# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on building and evaluating multiple supervised machine learning regression models for predicting house prices using a real estate dataset. The project emphasizes:

- Regularization techniques
- Cross-validation strategies
- Tree-based regression models
- Support Vector Regression (SVR)
- Gradient Descent optimization
- Model evaluation and comparison

The main goal is to identify the best-performing model while minimizing overfitting and improving generalization on unseen data.

---

# 📂 Dataset Information

The dataset contains real estate-related features such as:

- Property size and structural attributes
- Location-based indicators
- Property age and nearby facilities
- Crime rate information

## 🎯 Target Variable
- `House Price`

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Scikit-learn | Machine Learning Models |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |

---

# 📊 Machine Learning Models Implemented

## 🔹 Regularized Linear Models
- Ridge Regression (L2)
- Lasso Regression (L1)

## 🔹 Tree-Based Models
- Decision Tree Regression
- Random Forest Regression

## 🔹 Support Vector Regression
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

---

# 🔄 Cross-Validation Techniques Used

- K-Fold Cross-Validation
- Stratified K-Fold Cross-Validation
- Leave-One-Out Cross-Validation (LOOCV)
- Time Series Split

---

# ⚡ Gradient Descent Techniques

- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🧠 Key Findings

## ✅ Best Performing Model
Random Forest Regression achieved the best overall performance with strong generalization capability and balanced training/testing scores.

## ✅ Impact of Regularization
Ridge and Lasso Regression successfully reduced overfitting and improved model stability.

## ✅ Cross-Validation Results
All cross-validation strategies produced similar results, indicating stable and reliable model performance.

## ✅ Overfitting & Underfitting Analysis
- Decision Tree showed slight overfitting.
- SVR with Polynomial Kernel showed underfitting.
- Random Forest achieved the best balance between bias and variance.

---

# 📊 Sample Results

| Model | Test R² Score |
|---|---|
| Ridge Regression | 0.9187 |
| Lasso Regression | 0.9186 |
| Decision Tree | 0.9066 |
| Random Forest | 0.9143 |
| SVR-Linear | 0.9089 |
| SVR-Poly | 0.7517 |
| SVR-RBF | 0.8236 |

---
