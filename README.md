# 🏠 House Price Prediction: Storytelling with Data

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-XGBoost-red)
![Library](https://img.shields.io/badge/Library-CatBoost-orange)
![Library](https://img.shields.io/badge/Library-LightGBM-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project focuses on predicting residential housing prices using advanced regression techniques. Beyond just prediction, this notebook emphasizes **"Storytelling with Data,"** taking a deep dive into Exploratory Data Analysis (EDA) to understand the underlying factors that influence property value before applying machine learning models.

**Author:** Muhammad Atif  
*Student at The Islamia University of Bahawalpur*

## 📂 Dataset
The dataset typically used for this project is the famous **Ames Housing Dataset** (often found in Kaggle competitions). It contains 79 explanatory variables describing (almost) every aspect of residential homes.

- **Target Variable:** `SalePrice` (The property's sale price in dollars).
- **Key Features:**
  - **Physical Attributes:** `LotArea`, `TotalBsmtSF`, `GrLivArea`, `GarageArea`.
  - **Quality & Condition:** `OverallQual`, `OverallCond`, `KitchenQual`.
  - **Year Information:** `YearBuilt`, `YearRemodAdd`.

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:**
  - `scikit-learn` (Random Forest, Preprocessing, Validation)
  - `xgboost` (XGBRegressor)
  - `lightgbm` (LGBMRegressor)
  - `catboost` (CatBoostRegressor)

## 📊 Project Workflow

### 1. Data Preprocessing
- **Handling Missing Values:** Utilized `KNNImputer` to intelligently fill gaps in the data.
- **Feature Engineering:** Created new features to capture more information.
- **Encoding:** Applied `LabelEncoder` for categorical variables.
- **Scaling:** Used `StandardScaler` to normalize numerical features.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of sale prices.
- Visualized correlations between features (e.g., "Does a larger garage mean a higher price?").
- Investigated outliers that could skew predictions.

### 3. Model Building
The project implements an ensemble of powerful regressor models to achieve the best results:
- **Random Forest Regressor:** A bagging technique that reduces overfitting.
- **XGBoost Regressor:** Optimized gradient boosting for speed and performance.
- **LightGBM Regressor:** A fast, high-performance gradient boosting framework.
- **CatBoost Regressor:** Excellent for handling categorical data automatically.

### 4. Model Evaluation
Models were evaluated using robust metrics to ensure accuracy:
- **RMSE (Root Mean Squared Error)**
- **R² Score (Coefficient of Determination)**
- **K-Fold Cross-Validation**

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Atif-eng/house-price-prediction.git](https://github.com/Atif-eng/house-price-prediction.git)
