# 🚗 Second-Hand Car Price Prediction

> A Machine Learning regression project that predicts the price of second-hand cars using vehicle, ownership, location, fuel, and usage-related information.

---

## 📌 Project Overview

Buying or selling a second-hand car can be difficult because the price depends on several factors such as the car's age, kilometres driven, fuel type, company, location, and ownership history.

This project uses Machine Learning to predict the **price of a second-hand car** based on these features.

The project follows a complete Machine Learning workflow:

- Data understanding
- Data cleaning
- Exploratory Data Analysis
- Missing value handling
- Categorical feature encoding
- Numerical feature scaling
- Train-test splitting
- Regression model training
- Model evaluation
- Model comparison
- Model saving
- Streamlit deployment

---

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can estimate the price of a second-hand car based on its available features.

### Input Features

The model uses the following features:

- **Name** – Name of the car
- **Label** – Car label/category
- **Location** – Location where the car is listed
- **Kms_driven** – Kilometres driven by the car
- **Fuel_type** – Type of fuel used
- **Owner** – Ownership information
- **Year** – Manufacturing year
- **Company** – Car manufacturer

### 🎯 Target Variable

**Price**

---

## 🧠 Machine Learning Models

The following regression algorithms were trained and compared:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

---

## 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| **Linear Regression** | **199,966** | **438,613** | **0.5610** |
| Decision Tree | 243,209 | 578,903 | 0.2353 |
| Random Forest | 197,938 | 531,820 | 0.3547 |

### 🏆 Selected Model

**Linear Regression** was selected as the final model based on its overall evaluation, particularly its **highest R² score** and **lowest RMSE** among the tested models.

### Final Performance

- **MAE:** 199,966
- **RMSE:** 438,613
- **R² Score:** 0.5610

The R² score indicates that the model explains approximately **56.1% of the variation in car prices** on the test data.

---

## 🔄 Machine Learning Workflow

```text
                  Car Dataset
                      │
                      ▼
              Data Understanding
                      │
                      ▼
                Data Cleaning
                      │
                      ▼
                     EDA
                      │
                      ▼
              Feature Separation
                      │
                      ▼
               Train/Test Split
                      │
                      ▼
              Data Preprocessing
                 /          \
                /            \
       Numerical Features   Categorical Features
              │                    │
       Median Imputation     Most-Frequent Imputation
              │                    │
       StandardScaler        OneHotEncoder
                \              /
                 \            /
                  ▼          ▼
                 Model Training
                      │
                      ▼
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       Linear      Decision     Random
     Regression      Tree       Forest
          │           │           │
          └───────────┼───────────┘
                      ▼
              Model Evaluation
                      │
                      ▼
              Best Model Selection
                      │
                      ▼
               Model Serialization
                      │
                      ▼
              Streamlit Deployment

    BY AUTHOR
    G.NITHIYA SRI (AI&DS) RMKCET 🔥