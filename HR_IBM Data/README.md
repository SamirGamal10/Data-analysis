# HR Employee Attrition Analysis & Prediction 📊

This project focuses on analyzing IBM's HR dataset to predict employee attrition (the likelihood of an employee leaving the company) based on various factors such as age, department, and job satisfaction.

## 💡 Project Overview
- **Data Cleaning:** Removed redundant features and handled outliers using IQR clipping to improve model stability.
- **Exploratory Data Analysis (EDA):** Performed deep-dive visualizations to understand the drivers of turnover.
- **Handling Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to address the class imbalance in the target variable.
- **Machine Learning:** Built and evaluated a **Logistic Regression** model to classify potential leavers.

## 🛠 Tech Stack
* **Python 3.x**
* **Pandas & NumPy:** For data manipulation and processing.
* **Matplotlib & Seaborn:** For high-quality statistical visualizations.
* **Scikit-learn:** For model building, scaling, and evaluation metrics.
* **Imbalanced-learn:** Specifically for the SMOTE implementation.

## 📈 Key Insights
1.  **Age Factor:** Younger employees (in their 20s) show a significantly higher rate of attrition compared to older age groups.
2.  **Departmental Trends:** Department 1 (Sales/R&D typically) shows the highest volume of employees leaving.
3.  **Gender Impact:** While males have a slightly higher turnover rate, gender is not a primary driver of attrition in this dataset.