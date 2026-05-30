# 📈 Walmart Weekly Sales Forecasting using Machine Learning

<div align="center">

### Predicting Retail Sales Trends with Machine Learning

Forecasting Walmart weekly sales using Machine Learning models to uncover seasonal patterns, business insights, and improve sales prediction accuracy.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📌 Project Overview

Accurate sales forecasting is essential for inventory management, resource planning, and strategic business decisions in the retail industry.

This project leverages historical Walmart sales data and Machine Learning techniques to predict future weekly sales. The project follows a complete end-to-end Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction generation.

The objective is not only to forecast sales accurately but also to identify the key factors influencing store performance and revenue fluctuations.

---

## 🎯 Problem Statement

Retail organizations generate massive amounts of transactional data every week. Understanding sales trends and predicting future demand helps businesses:

- Optimize inventory management
- Improve supply chain planning
- Reduce operational costs
- Identify seasonal demand fluctuations
- Improve business decision-making

The goal of this project is to build a robust Machine Learning model capable of forecasting Walmart's weekly sales using historical retail data.

---

## 🏗️ Machine Learning Pipeline

```text
Raw Walmart Dataset
         │
         ▼
Data Cleaning & Preprocessing
         │
         ▼
Exploratory Data Analysis
         │
         ▼
Feature Engineering
         │
         ▼
Train-Test Split
         │
         ▼
Model Training
         │
         ▼
Model Evaluation
         │
         ▼
Sales Forecasting
         │
         ▼
Business Insights
```

---

## 📊 Dataset Information

The dataset contains historical Walmart sales records along with several business and economic indicators.

### Features Used

| Feature | Description |
|----------|-------------|
| Store | Store Number |
| Date | Weekly Date |
| Weekly_Sales | Target Variable |
| Holiday_Flag | Indicates Holiday Week |
| Temperature | Average Temperature |
| Fuel_Price | Fuel Cost |
| CPI | Consumer Price Index |
| Unemployment | Unemployment Rate |

---

## 🔍 Exploratory Data Analysis (EDA)

Several exploratory analyses were performed to better understand the dataset:

### Analysis Performed

- Missing value analysis
- Sales trend visualization
- Holiday impact analysis
- Correlation analysis
- Feature distribution analysis
- Outlier detection
- Store-wise sales comparison

### Key Findings

- Holiday periods significantly impact sales.
- Certain stores consistently outperform others.
- Seasonal trends strongly influence weekly sales.
- Economic indicators contribute to sales fluctuations.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were implemented:

- Missing value handling
- Date feature extraction
- Data type conversion
- Feature selection
- Data transformation
- Train-Test split preparation

---

## 🧠 Machine Learning Models

Multiple regression models were trained and compared to identify the best-performing approach.

### Models Implemented

#### Linear Regression

Used as a baseline model to establish performance benchmarks.

#### Lasso Regression

Applied regularization to improve generalization and reduce overfitting.

#### Random Forest Regressor

Used ensemble learning techniques to capture complex relationships within the data.

---

## 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### Performance Summary

| Model | Performance |
|---------|------------|
| Linear Regression | Baseline Model |
| Lasso Regression | Improved Generalization |
| Random Forest Regressor | Best Performance |

---

## 🏆 Best Model

### Random Forest Regressor

✅ R² Score: **0.91**

The Random Forest model achieved the highest predictive performance by effectively capturing nonlinear relationships and feature interactions within the dataset.

---

## 📌 Business Insights Generated

The analysis revealed several valuable business insights:

- Holiday seasons significantly boost sales.
- Sales patterns vary across stores.
- Economic indicators influence customer purchasing behavior.
- Historical trends can effectively predict future demand.
- Machine Learning can assist retail businesses in strategic planning.

---

## 🛠️ Technology Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

### Development Environment

- Jupyter Notebook

### Machine Learning Techniques

- Linear Regression
- Lasso Regression
- Random Forest Regression

---

## 📂 Project Structure

```bash
Walmart-Weekly-Sales-Forecasting-using-ML-Models/
│
├── Sales_Analysis_and_Cleaning.ipynb
├── Walmart_Sales_Prediction.ipynb
├── walmart_sales_processed.csv
├── walmart_next_week_sales_prediction.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/maneesh6531/Walmart-Weekly-Sales-Forecasting-using-ML-Models.git
```

### Navigate to Project Directory

```bash
cd Walmart-Weekly-Sales-Forecasting-using-ML-Models
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📸 Project Screenshots

> Add the following screenshots for a professional GitHub repository:

- Sales Trend Analysis
- Correlation Heatmap
- Feature Importance Plot
- Actual vs Predicted Sales Visualization

Example:

```md
![Sales Trend](images/sales_trend.png)
![Heatmap](images/heatmap.png)
![Predictions](images/predictions.png)
```

---

## 🔮 Future Enhancements

- Hyperparameter Optimization using GridSearchCV
- XGBoost Implementation
- LightGBM Integration
- Model Deployment using FastAPI
- Docker Containerization
- Automated ML Pipeline
- Real-Time Dashboard Development
- Cloud Deployment on AWS

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Model Evaluation
- Sales Forecasting
- Business Intelligence
- Data Visualization

---

## 👨‍💻 Author

### Karlapudi Maneesh

📧 Email: maneesh6531@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/maneeshkarlapudi

💻 GitHub: https://github.com/maneesh6531

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

</div>
