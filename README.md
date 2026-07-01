# Car Price Prediction using Linear Regression

This project develops a machine learning model to predict automobile prices based on technical and design specifications. Utilizing a structured data science workflow in R, the model uncovers the primary drivers of vehicle valuation and provides reliable price estimates.

---

## 📌 Project Overview

The dataset, sourced from Kaggle, contains **205 car records** detailing various vehicular characteristics. Because the dataset contains no missing values, all observations are retained for comprehensive analysis. The data is thoroughly cleaned, explored, and used to train a Linear Regression model.

### 🎯 Objectives
* **Clean & Preprocess** the dataset for optimal model performance.
* **Explore Relationships** between distinct vehicle features and their market price.
* **Build a Linear Regression Model** to accurately estimate car prices.
* **Evaluate Performance** using standard statistical metrics.
* **Identify Key Drivers** to determine the most influential factors affecting car prices.

---

## 📊 Dataset Profile

* **Source:** Kaggle
* **Observations:** 205 automobiles
* **Target Variable:** `price`
* **Key Features:** Engine size, horsepower, fuel type, body style, curb weight, fuel system, city/highway MPG, and more.

---

## 🛠️ Technologies & Libraries

* **Language:** R
* **Core Libraries:**
  * `tidyverse` & `dplyr` (Data manipulation and tidying)
  * `ggplot2` & `corrplot` (Exploratory data analysis & correlation visualization)
  * `caret` (Data splitting and model training evaluation)
* **Model Framework:** Ordinary Least Squares (OLS) Linear Regression

---

## 🔄 Project Workflow

The project is executed through a structured, step-by-step data science lifecycle:

1. **Data Collection:** Sourcing and loading the automobile dataset.
2. **Data Preprocessing:** Cleaning, encoding categorical variables, and preparing data types.
3. **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations with `price`.
4. **Feature Engineering:** Selecting and transforming the most impactful predictive variables.
5. **Model Development:** Training the Linear Regression model on the prepared dataset.
6. **Model Evaluation:** Assessing accuracy and fit using statistical metrics (e.g., $R^2$, RMSE).
7. **Prediction & Interpretation:** Drawing actionable insights from the model coefficients.
