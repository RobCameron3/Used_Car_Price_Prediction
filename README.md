Used Car Price Prediction

Overview

This project focuses on predicting used car prices using a regression-based machine learning approach. The goal is to help businesses align car pricing with market value and customer expectations, improving overall profitability. By identifying which features drive pricing, the model allows for data-backed strategic decisions in customer acquisition, pricing, and retention.

Business Relevance

Accurate price prediction models impact several business metrics:

CAC (Customer Acquisition Cost): Lower acquisition cost by targeting and converting the right customers faster using optimized pricing.

CLTV (Customer Lifetime Value): Boost long-term satisfaction and retention by aligning prices with value expectations.

MRR (Monthly Recurring Revenue): Create consistent pricing models to help stabilize revenue from recurring used car programs or financing plans.

Churn Rate: Reduce churn by preventing customer frustration caused by pricing inconsistencies.

ARPU (Average Revenue Per User): Raise average revenue by offering tiered pricing or upsell strategies based on predicted price sensitivity.

ROI (Return on Investment): Optimize business investments in inventory, marketing, and customer service by using predictive insights.

Dataset Information

The dataset contains 26 columns with features like:

Categorical: fuel type, engine type, car body, drive wheel, aspiration

Numerical: car width, engine size, horsepower, curb weight, mileage (city/highway), price

Source: Kaggle Dataset

Methodology

Data Cleaning & Exploration:

Checked for nulls, outliers, and skewness

Explored feature relationships through correlation heatmaps and scatterplots

Feature Engineering:

Log transformation on price to normalize skew

Dummified categorical variables

Multicollinearity Checks:

VIF (Variance Inflation Factor) analysis to drop highly correlated features

Modeling:

Used OLS Linear Regression via statsmodels

Evaluated using R-squared, RMSE, MAE, and MAPE

Validation:

Performed k-fold cross-validation

Analyzed residuals for homoskedasticity and normality

Key Findings

Features like car width, engine size, and horsepower have strong positive relationships with price.

Car length and stroke showed negative relationships with price.

Log-transformed price improved model performance.

Final model achieved R-squared around 0.85 with low MAPE (~15%).

Takeaways

The model enables businesses to assess the value of individual vehicles with precision.

Pricing decisions can be made dynamically based on predicted price tiers.

Businesses can test how changes in features or packages affect customer-perceived value.

Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Sklearn)

Jupyter Notebook

GitHub for version control

