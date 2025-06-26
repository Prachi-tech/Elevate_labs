# Task 3: Housing Price Prediction using Linear Regression 🏠📈

This repository contains my implementation of **Task 3: Linear Regression** as part of the data science internship program by [Elevate Labs]. In this task, I used a **Housing Price Prediction** dataset and applied linear regression to predict house prices based on several features.

## 📁 Project Structure

- `housing.csv` — The dataset containing features like area, bedrooms, bathrooms, furnishing status, and more.
- `Task3_Housing_Price_Prediction.ipynb` — Jupyter Notebook with code, visualizations, and model implementation.
- `README.md` — Project overview and documentation.

## 🧠 Objective

To build a linear regression model that accurately predicts the **price of a house** based on various independent features.

## 🔍 Dataset Features

The dataset contains the following key features:

- `area` — Total area (in square feet)
- `bedrooms` — Number of bedrooms
- `bathrooms` — Number of bathrooms
- `stories` — Number of stories
- `mainroad` — Whether the house is on the main road (yes/no)
- `guestroom` — Availability of a guest room (yes/no)
- `basement` — Availability of a basement (yes/no)
- `hotwaterheating` — Availability of hot water heating (yes/no)
- `airconditioning` — Air conditioning available (yes/no)
- `parking` — Number of parking spots
- `prefarea` — Preference area (yes/no)
- `furnishingstatus` — Unfurnished, Semi-furnished, or Furnished
- `price` — Target variable (House price)

## 🛠️ Tools and Libraries Used

- **Python**
- **Pandas** — Data manipulation
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Linear Regression, data preprocessing, metrics

## 📊 Steps Performed

1. **Data Cleaning** – Handled categorical variables, missing values, and data types.
2. **Exploratory Data Analysis (EDA)** – Visualized distributions and correlations.
3. **Feature Engineering** – One-hot encoding of categorical variables.
4. **Model Training** – Trained a Linear Regression model using scikit-learn.
5. **Model Evaluation** – Evaluated model using R² Score and RMSE.
6. **Prediction** – Predicted prices on test data and visualized actual vs. predicted values.

## ✅ Results

- Achieved a good model fit with reasonable error margins.
- Found strong correlations between house features like area, location preferences, and price.

## 📌 Conclusion

This project helped me understand the fundamentals of **Linear Regression** and how to preprocess real-world data effectively. It also gave me hands-on experience with **feature encoding**, **visualizations**, and **model evaluation**.
