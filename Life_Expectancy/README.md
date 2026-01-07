# 🌍 Life Expectancy Prediction Project

## 📌 Project Overview
This project aims to analyze and predict **Life Expectancy** across countries using
machine learning techniques.  
The dataset includes health, economic, and social indicators collected by the World Health Organization (WHO).

We apply **data cleaning, feature engineering, visualization, and regression models**
to understand the most influential factors affecting life expectancy.

---

## 📊 Dataset
- Source: WHO Life Expectancy Dataset
- Target Variable: `life_expectancy`
- Features include:
  - Health indicators (Adult Mortality, HIV/AIDS, BMI, Healthcare expenditure)
  - Economic indicators (GDP, Income composition)
  - Social indicators (Schooling, Status)

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit‑Learn

---

## ⚙️ Project Workflow
1. Data Loading & Exploration
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
   - Linear Regression
   - Random Forest Regressor
6. Model Evaluation
7. Feature Importance Analysis
8. Visualization & Insights

---

## 📈 Model Performance
| Model              | R² Score | MAE | RMSE |
|-------------------|----------|-----|------|
| Linear Regression | Moderate | Higher | Higher |
| Random Forest     | High     | Lower | Lower |

✅ Random Forest achieved the best performance and generalization.

---

## 🔍 Key Insights
- Education and income composition are among the strongest predictors.
- Higher healthcare expenditure is associated with higher life expectancy.
- Adult mortality and HIV/AIDS have strong negative impacts.
- Random Forest captures non‑linear relationships better than linear models.