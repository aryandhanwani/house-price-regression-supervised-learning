# 🏠 House Price Prediction – Supervised Learning

## 📌 Project Overview

This project focuses on predicting house sale prices using supervised machine learning regression techniques.

The **Ames Housing Dataset** is used for this project. Different regression models are trained, evaluated, compared, and tuned to find the best-performing model for house price prediction.

---

## 🎯 Objective

The main objective of this project is to:

- 📊 Explore and understand the housing dataset
- 🧹 Handle missing values and outliers
- 🔧 Perform feature engineering
- 🔤 Encode categorical features
- 📈 Transform and scale numerical features
- 🤖 Train different regression models
- ⚙️ Tune model hyperparameters
- 📏 Compare model performance
- 💾 Save the final trained model as a reusable pipeline

---

## 📂 Dataset

**Dataset:** Ames Housing Dataset

The dataset contains information about residential properties and their sale prices.

### 🎯 Target Variable

`SalePrice`

The target variable represents the final sale price of each house.

---

## 🔍 Exploratory Data Analysis

The following analysis was performed:

- Dataset shape and information
- Descriptive statistics
- Numerical and categorical feature analysis
- Missing-value analysis
- SalePrice histogram
- Q-Q plot
- Log transformation of SalePrice
- Numerical feature distributions
- Skewness analysis
- Categorical feature countplots
- Correlation heatmap
- Scatterplots
- Boxplots
- Outlier identification

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- 🔎 Missing-value analysis
- 🗑️ Removal of extreme GrLivArea outliers
- 🏠 Creation of `TotalSF`
- 📅 Creation of `HouseAge`
- 🔨 Creation of `RemodAge`
- 🚗 Creation of `HasGarage`
- 🏊 Creation of `HasPool`
- 🔢 Ordinal encoding of quality-related features
- 🔤 One-hot encoding of nominal categorical features
- 📉 Log transformation of highly skewed numerical features
- 📏 Standard scaling of continuous numerical features

---

## 🤖 Machine Learning Models

The following regression models were implemented:

1. 📈 Linear Regression
2. Ridge Regression
3. Lasso Regression
4. 🌲 Random Forest Regression
5. ⚡ XGBoost Regression

Hyperparameter tuning was also performed using `RandomizedSearchCV`.

---

## 📊 Model Evaluation

The models were evaluated using:

- 📉 RMSE – Root Mean Squared Error
- 📏 MAE – Mean Absolute Error
- 📈 R² Score
- 🔄 Cross-validation RMSE
- ⏱️ Training time

The models were compared using a final performance comparison table.

---

## ⭐ Best Model

The best-performing model was selected based on its overall performance, mainly considering:

- Lower RMSE
- Lower MAE
- Higher R² Score
- Cross-validation performance

### 🏆 Final Model

**Best Model:** `WRITE YOUR BEST MODEL HERE`

**Test RMSE:** `WRITE YOUR VALUE`

**Test MAE:** `WRITE YOUR VALUE`

**Test R²:** `WRITE YOUR VALUE`

---

## 📌 Feature Importance

The most impactful features were identified from the final model.

### Top 5 Important Features

1. `Feature 1`
2. `Feature 2`
3. `Feature 3`
4. `Feature 4`
5. `Feature 5`

These features provide useful information about which property characteristics have the strongest influence on predicted house prices.

---

## 📉 Residual Analysis

Residual analysis was performed to understand the prediction errors of the final model.

The following plots were created:

- Residual plot
- Q-Q plot of residuals

The Q-Q plot was used to check whether the residuals approximately follow a normal distribution and to identify possible heavy tails.

---

## 💾 Saved Model

The final model was saved as:

```text
house_price_model.pkl
