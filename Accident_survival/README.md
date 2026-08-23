# 🚗 Accident Collision Severity Prediction

> Machine Learning project for predicting accident collision severity using road, weather, lighting, junction, and time-related information.

---

## 📌 Project Overview

Road accidents can vary significantly in severity depending on factors such as road conditions, weather, lighting, speed limits, junction characteristics, and the time of the collision.

This project applies Machine Learning techniques to analyze accident-related data and predict the **Collision Severity** of an accident.

The project includes:

- Data preprocessing
- Missing value handling
- Numerical feature scaling
- Categorical feature encoding
- Exploratory data analysis
- Multiple Machine Learning models
- Model evaluation
- Confusion matrix visualization
- Model selection
- Streamlit deployment

---

## 🎯 Objective

The main objective of this project is to develop a Machine Learning model that can predict accident collision severity based on available accident and environmental conditions.

### Input Features

The model uses features such as:

- Policing Area
- Weekday of Collision
- Day of Collision
- Month of Collision
- Hour of Collision
- Carriageway Type
- Speed Limit
- Junction Detail
- Junction Control
- Pedestrian Crossing Conditions
- Light Conditions
- Weather Conditions
- Road Surface Conditions
- Special Conditions at Site

### 🎯 Target

**Collision Severity**

---

## 🧠 Machine Learning Models

Three classification algorithms were evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest

### Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 89.25% | 79.65% | 89.25% | 84.18% |
| Decision Tree | 85.02% | 85.40% | 85.02% | 85.21% |
| **Random Forest** | **89.60%** | **86.08%** | **89.60%** | **85.60%** |

### 🏆 Best Model

**Random Forest Classifier** achieved the best overall performance among the tested models.

- Accuracy: **89.60%**
- Precision: **86.08%**
- Recall: **89.60%**
- F1 Score: **85.60%**

---

## 🔄 Machine Learning Workflow

```text
Raw Accident Dataset
        ↓
Data Understanding
        ↓
Data Cleaning
        ↓
Missing Value Handling
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Numerical Feature Scaling
        ↓
Categorical Feature Encoding
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Random Forest Selection
        ↓
Model Saving
        ↓
Streamlit Deployment

BY AUTHOR
   NITHIYA SRI G RMKCET 🔥