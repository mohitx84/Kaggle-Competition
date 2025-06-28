# Kaggle-Competition
## 🏠 House Price Prediction – Kaggle Competition

### 📍 Competition Link:

[Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

---

### 📌 Overview

This project is focused on predicting final prices of homes based on various features in Ames, Iowa. It serves as a benchmark regression problem that is perfect for applying exploratory data analysis (EDA), feature engineering, and machine learning models.

---

### 🔧 Tools & Libraries Used

* Python 3.x
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* XGBoost 
* Google colab
---


---

### 📊 Data Description

* **Train.csv** — Training data with 81 features and the target variable `SalePrice`.
* **Test.csv** — Data used for prediction, does not include `SalePrice`.

Key features:

* `OverallQual`: Overall material and finish quality
* `GrLivArea`: Above grade (ground) living area square feet
* `TotalBsmtSF`: Total square feet of basement area
* `GarageCars`: Size of garage in car capacity
* `YearBuilt`: Year built

---

### 🔍 Methodology

1. **Exploratory Data Analysis (EDA)**

   * Missing value treatment
   * Correlation heatmaps
   * Outlier detection

2. **Feature Engineering**

   * Handling categorical variables (Label/OneHot encoding)
   * Log transformation for skewed features
   * Feature scaling with `StandardScaler`

3. **Modeling**

   * Linear Regression
   * Ridge / Lasso Regression
   * Random Forest Regressor
   * Gradient Boosting (XGBoost, LightGBM, CatBoost)
   * Model stacking and ensemble methods

4. **Evaluation**

   * Metric: RMSE (Root Mean Squared Error)
   * Cross-validation to prevent overfitting

---

### 📈 Results

* Best public leaderboard RMSE: `24695.459663670972`
* Model used for final submission: `CatBoostRegressor` (or whichever you chose)

---

### 💾 Submission Format

Final predictions are submitted as a CSV:

```csv
Id,SalePrice
1461,169000.00
1462,187000.00
...
```

---

### 🧠 Learnings

* Handling missing data and skewed distributions
* Feature importance analysis
* Model tuning and cross-validation
* Building robust pipelines for tabular ML problems

---

