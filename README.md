# 🏠 House Prices: Advanced Regression Techniques

This repository contains an exploratory data analysis (EDA) project using the **House Prices** dataset from Kaggle. The goal is to understand key patterns in the data and prepare it for building predictive regression models.

## 📁 Repository Structure
├── train.csv # Training dataset
├── test.csv # Test dataset (no target column)
├── eda_House_prices.ipynb # Jupyter Notebook with detailed EDA


## 📊 EDA Overview

The EDA notebook covers:

- Data loading and inspection
- Handling missing values
- Temporal feature analysis (year sold vs. year built, remodel year, etc.)
- Discrete vs continuous numerical features
- Log transformation for skewed data
- Outlier detection using boxplots
- Categorical feature relationship with SalePrice

## ✅ Key Insights

- `OverallQual`, `Neighborhood`, and `ExterQual` are strongly correlated with house prices.
- Many continuous variables show right-skewed distributions and outliers.
- Categorical variables with high cardinality may need encoding for modeling.
- Some missing values are not random and can be meaningfully imputed.

## 🔧 Next Step: Feature Engineering

The insights from EDA will help in:

- Imputing missing values
- Creating new age-based features (e.g., `house_age`)
- Transforming skewed variables using log scale
- One-hot encoding or ordinal encoding for categorical variables

## 📦 Requirements

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn notebook
