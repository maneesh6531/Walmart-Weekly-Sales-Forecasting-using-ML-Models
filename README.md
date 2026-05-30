# Walmart Weekly Sales Forecasting using Machine Learning

Predicting Walmart weekly sales using Machine Learning models to help identify sales trends, seasonal patterns, and factors influencing retail performance.

## Project Overview

This project focuses on forecasting weekly sales for Walmart stores using historical retail data. The objective is to build and evaluate machine learning models capable of predicting future sales while identifying the key factors affecting store performance.

The project covers the complete machine learning workflow including:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training and Evaluation
- Sales Forecasting
- Business Insights Generation

---

## Problem Statement

Retail businesses rely on accurate sales forecasting for inventory planning, staffing, and strategic decision-making.

The goal of this project is to:

- Predict weekly store sales
- Understand the impact of holidays and seasonal trends
- Compare multiple regression models
- Identify important sales-driving factors

---

## Dataset Features

The dataset contains information such as:

- Store Number
- Date
- Weekly Sales
- Holiday Indicator
- Temperature
- Fuel Price
- CPI
- Unemployment Rate

---

## Machine Learning Workflow

### 1. Data Preprocessing

- Handled missing values
- Converted date columns into useful features
- Removed unnecessary columns
- Prepared data for model training

### 2. Exploratory Data Analysis

Performed:

- Sales trend analysis
- Holiday impact analysis
- Correlation analysis
- Feature distribution analysis

### 3. Feature Engineering

Created meaningful features from:

- Dates
- Seasonal patterns
- Store-level information

### 4. Model Training

The following models were implemented and compared:

- Linear Regression
- Lasso Regression
- Random Forest Regressor

### 5. Model Evaluation

Evaluation metrics used:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Results

| Model | Performance |
|---------|------------|
| Linear Regression | Baseline Model |
| Lasso Regression | Improved Generalization |
| Random Forest Regressor | Best Performance |

### Best Model

**Random Forest Regressor**

- R² Score: **0.91**
- Captured non-linear relationships effectively
- Delivered the most accurate sales predictions

---

## Key Insights

- Holiday weeks significantly influence sales.
- Seasonal trends impact store performance.
- Certain stores consistently outperform others.
- Economic indicators such as fuel price and unemployment contribute to sales variations.

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Machine Learning

- Linear Regression
- Lasso Regression
- Random Forest Regressor

### Environment

- Jupyter Notebook

---

## Project Structure

```
├── data/
│   ├── raw_dataset.csv
│   └── processed_dataset.csv
│
├── notebooks/
│   ├── Sales_Analysis_and_Cleaning.ipynb
│   └── Walmart_Sales_Prediction.ipynb
│
├── outputs/
│   ├── visualizations
│   └── predictions
│
├── README.md
└── requirements.txt
```

---

## Future Improvements

- Hyperparameter Optimization using GridSearchCV
- XGBoost and LightGBM Implementation
- Model Deployment using FastAPI
- Automated Retraining Pipeline
- Real-Time Forecasting Dashboard

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Model Evaluation
- Sales Forecasting
- Data Visualization
- Business Analytics

---

## Author

**Karlapudi Maneesh**

- LinkedIn: https://www.linkedin.com/in/maneeshkarlapudi
- GitHub: https://github.com/maneesh6531
