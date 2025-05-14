---
layout: project-top
title: "Housing Price Predictions"
description: "Regression models to predict house sale prices using Ridge, Lasso, and Random Forests."
date: 2025-4-20
weight: 4
permalink: /projects/housing-prices
thumbnail: "/assets/images/housing-prices/housing_prices_thumbnail.png"
image: "/assets/images/housing-prices/housing_prices_thumbnail.png"
client: "Kaggle Practice Competition"
categories: ["Machine Learning", "Regression", "Python"]
role: "Data Scientist - Basic Level"
#gallery:
---

> This project involved predicting house prices using real estate data with 80+ features and strong multicollinearity. I explored and compared Ridge Regression, Lasso Regression, and Random Forests to find the most accurate and interpretable model.

---

### Key Features
- Cleaned & encoded 80+ features from the Ames Housing dataset
- Diagnosed multicollinearity using a correlation matrix
- Trained Ridge & Lasso models with cross-validation to tune regularization strength (`alpha`)
- Trained & tuned a Random Forest using grid search
- Exported final predictions as CSV for Kaggle submission

---

### My Role
- Handled preprocessing: null imputation, encoding, standardization
- Built regression pipelines using `sklearn` and `StandardScaler`
- Used 5-fold cross-validation to tune hyperparameters
- Interpreted Lasso feature elimination vs. Ridge shrinkage
- Tuned Random Forests to outperform linear models

---

### Tech Stack
- **Language:** Python  
- **Models:** Ridge, Lasso, Random Forest  
- **Libraries:** `sklearn`, `pandas`, `matplotlib`, `seaborn`  
- **Tools:** Jupyter Notebook, GitHub

---

### 📊 Model Comparison

| Model            | Best RMSE (CV) | % of Avg Sale Price |
|------------------|----------------|----------------------|
| Ridge Regression | 34,370         | 19.0%                |
| Lasso Regression | 35,319         | 19.5%                |
| Random Forest    | **30,751**     | **17.0%**            |


**Kaggle Submission RMSE: 🏅 0.15047 (public leaderboard)**

Ridge outperformed Lasso on this multicollinear dataset, but after careful hyperparameter tuning and preprocessing, Random Forests yielded the best performance overall. The final model generalized well, with its Kaggle leaderboard RMSE (0.15047) slightly outperforming the internal CV score — indicating a solid, well-validated pipeline.
---

🔗 [View full project on GitHub](https://github.com/inaya-r/Housing-Prices-Predictions)
