# 🚗 Used Car Price Prediction

## 📈 Overview

This project predicts used car prices using a regression-based machine learning model. The goal is to help businesses align pricing with market value and customer expectations to improve profitability. By identifying the features that influence price, the model supports smarter decisions in acquisition, pricing, and retention.

## 💼 Business Relevance

Accurate price prediction affects several core metrics:

- **🎯 CAC (Customer Acquisition Cost):** Lower costs by targeting and converting the right customers faster through optimized pricing.
- **🔁 CLTV (Customer Lifetime Value):** Improve satisfaction and retention by aligning prices with customer expectations.
- **📆 MRR (Monthly Recurring Revenue):** Stabilize income through consistent pricing in car programs or financing.
- **🚪 Churn Rate:** Reduce drop-off by preventing pricing inconsistencies that frustrate customers.
- **💵 ARPU (Average Revenue Per User):** Increase per-user revenue through tiered pricing and upsells.
- **📊 ROI (Return on Investment):** Use predictive insights to guide inventory, marketing, and service investments.

## 📂 Dataset Information

The dataset contains 26 columns with features like:

- **Categorical:** fuel type, engine type, car body, drive wheel, aspiration  
- **Numerical:** car width, engine size, horsepower, curb weight, city/highway mileage, price

**Source:** Kaggle Dataset

## 🧪 Methodology

### 🧼 Data Cleaning & Exploration

- Removed nulls, outliers, and normalized skewed distributions  
- Visualized relationships using heatmaps and scatter plots

### 🛠️ Feature Engineering

- Applied log transformation to normalize price  
- Dummified categorical variables

### 🧮 Multicollinearity

- Used VIF (Variance Inflation Factor) to remove highly correlated features

### 🧾 Modeling

- Built OLS Linear Regression with statsmodels  
- Evaluated using R², RMSE, MAE, and MAPE

### ✅ Validation

- Performed k-fold cross-validation  
- Checked residual plots for homoskedasticity and normality

## 🔍 Key Findings

- Price increases with car width, engine size, and horsepower  
- Car length and stroke were negatively correlated with price  
- Log transformation significantly improved model fit  
- Achieved **R² ≈ 0.85** with **MAPE ≈ 15%**

## 📊 How Visuals Supported Business Impact

Over 30 graphs were generated to support insight discovery and business decisions:

- **Heatmaps & scatterplots:** Identified key predictors like engine size and horsepower that positively impact price (used to optimize ARPU and CLTV).
- **Boxplots & distribution charts:** Detected outliers and skewness, helping clean data for more reliable pricing predictions (improves ROI and reduces CAC).
- **VIF bar graphs:** Diagnosed multicollinearity to remove noisy features, sharpening the model’s focus (supports better CAC targeting).
- **Residual plots & k-fold visuals:** Validated model accuracy and fairness, essential to lowering Churn Rate and sustaining MRR.

These visuals translated complex data into business-friendly insights, helping stakeholders build confidence in the model and pricing strategy.

## 🧠 Takeaways

- Enables dynamic vehicle valuation based on input features  
- Supports price tiering and feature/package optimization  
- Equips businesses with a foundation for revenue-focused pricing strategy

## 🧰 Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Sklearn  
- **Jupyter Notebook**  
- **GitHub** for version control
