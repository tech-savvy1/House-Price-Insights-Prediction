# 🏠 House Price Insights & Prediction

## 📌 Project Overview
This project performs an end-to-end **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** on the **Ames Housing Dataset** to understand the key factors influencing house prices and to build a predictive model.

The goal is not just prediction accuracy, but **clear data understanding, feature reasoning, and insight-driven modeling**, making this project suitable for ML portfolios and interviews.

---

## 🎯 Objectives
- Understand the structure and distribution of housing data
- Identify important features affecting house prices
- Handle missing values and categorical variables correctly
- Visualize relationships using meaningful plots
- Build a baseline regression model for price prediction
- Evaluate model performance using standard metrics

---

## 🗂 Dataset
- **Dataset Name:** Ames Housing  
- **Rows:** ~2,900  
- **Features:** 79 (numeric + categorical)  
- **Target Variable:** `SalePrice`

This dataset is widely used for demonstrating real-world data preprocessing and regression tasks.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  

---

## 🧹 Data Cleaning & Preprocessing
- Dropped columns with excessive missing values
- Filled numerical missing values using **median**
- Filled categorical missing values using **mode**
- Engineered new features such as:
  - `TotalBath = FullBath + 0.5 × HalfBath`
- Converted categorical variables using **one-hot encoding**

---

## 📊 Exploratory Data Analysis (EDA)
Key analyses performed:
- Distribution of house prices
- Correlation heatmap of numerical features
- Identification of top features correlated with `SalePrice`
- Scatter plots to visualize relationships (e.g., living area vs price)

### 🔍 Key Insights
- **Overall Quality** is one of the strongest predictors of price
- **Living Area (GrLivArea)** shows a strong positive correlation
- Newer houses generally sell for higher prices
- Certain neighborhoods form clear price clusters

---

## 🤖 Machine Learning Model
- **Model Used:** Linear Regression (baseline)
- **Train/Test Split:** 80% / 20%
- **Why Linear Regression?**
  - Simple
  - Interpretable
  - Strong baseline for regression problems

---

## 📈 Model Evaluation
The model was evaluated using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

These metrics provide an interpretable measure of how far predictions deviate from actual prices.

---

## 🏁 Results
- The baseline model achieves reasonable performance for a first-pass regression
- Results can be further improved using:
  - Feature scaling
  - Log transformation of `SalePrice`
  - Tree-based models (Random Forest, Gradient Boosting)
  - Cross-validation and hyperparameter tuning

---

## 🚀 Future Improvements
- Apply log transformation to reduce price skewness
- Use `Pipeline` and `ColumnTransformer` for cleaner preprocessing
- Experiment with advanced models like XGBoost
- Add cross-validation for more robust evaluation
- Deploy the model using a simple API (FastAPI / Flask)

---

## 🧠 What This Project Demonstrates
- Strong understanding of **EDA concepts**
- Ability to reason about **data cleaning decisions**
- Practical **feature engineering**
- End-to-end **ML workflow**
- Clear and structured **technical communication**
