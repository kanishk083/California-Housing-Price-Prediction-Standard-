# 🏡 California Housing Price Prediction Standard

This project builds a **Machine Learning model** to predict **median house prices** in different districts of California.  
The workflow includes **Exploratory Data Analysis (EDA)**, **data preprocessing**, **feature engineering**, and **model training** to understand how factors such as location, income, and population affect housing prices.

---

## 📘 Project Overview

The **California Housing Price Prediction** project uses the **California Census housing dataset**, commonly used in real-estate data science tasks.  
The main goal is to:
- Explore and visualize housing data.
- Prepare and clean data for machine learning.
- Train and evaluate predictive models.
- Gain insights into key factors influencing prices.

---

## 🧠 Key Steps

### 1. Exploratory Data Analysis (EDA)
- Examined dataset structure and statistics.
- Visualized distributions, correlations, and geographical relationships.
- Detected and handled missing values and outliers.
- Created geographical scatter plots (longitude vs latitude) showing median house values.

### 2. Data Preprocessing
- Handled missing values and categorical variables.
- Created income categories for **stratified sampling**.
- Performed **feature scaling** using StandardScaler.
- Separated features and target variable for ML pipelines.

### 3. Feature Engineering
- Added new features such as:
  - `rooms_per_household`
  - `bedrooms_per_room`
  - `population_per_household`
- Improved dataset representativeness for model training.

### 4. Model Building
Trained multiple models and compared performance:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Support Vector Regressor (SVR)**

Metrics evaluated:
- Root Mean Squared Error (RMSE)
- Cross-validation scores

### 5. Model Evaluation & Fine-Tuning
- Performed **GridSearchCV** for hyperparameter tuning.
- Selected the best model based on validation metrics.
- Tested on a hold-out test set to estimate generalization performance.

---

## 🧩 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 🐍 |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |

---



