# 🏠 King County House Price Prediction

A comprehensive Data Science project to analyze and predict real estate prices in King County, USA, using advanced regression techniques and automated pipelines.

---

## 📋 Project Overview
This project focuses on predicting house prices based on various features such as square footage, number of bedrooms, construction grade, and location-based metrics. It utilizes a robust machine learning workflow from **Exploratory Data Analysis (EDA)** to **Model Deployment Pipelines**.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Pipelines, Gradient Boosting, Robust Scaling)

## 🏗️ Project Architecture
The project follows a structured data science lifecycle:

1.  **Data Cleaning:** Handling missing values and removing unnecessary identifiers (`id`, `zipcode`).
2.  **Feature Engineering:** * Calculated `house_age` from the sale date.
    * Created `years_since_renovation` to capture property value updates.
3.  **Outlier Management:** Applied **IQR Capping** to handle extreme values in numerical features to ensure model stability.
4.  **Pipeline Construction:** * Implemented `ColumnTransformer` for feature scaling.
    * Used `RobustScaler` to minimize the influence of outliers.
5.  **Modeling:** Trained a `Gradient Boosting Regressor` with Cross-Validation ($R^2$ optimization).



---

## 📊 Key Insights & Visualizations
* **Construction Grade:** A strong exponential correlation was found between the 'Grade' of the house and its final price.
* **Error Analysis:** Residual plots confirm **Homoscedasticity**, meaning the model's errors are consistent across the price range.



---

## 📈 Model Performance
The final model was evaluated using standard regression metrics:
* **R² Score:** Measures how well the model fits the data.
* **MAE (Mean Absolute Error):** Average dollar amount of error.
* **RMSE (Root Mean Squared Error):** Penalizes larger errors more heavily.