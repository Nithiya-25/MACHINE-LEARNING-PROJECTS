# 🎵 Music Genre Classification

> A Machine Learning classification project that predicts the genre of a music track using audio features such as energy, danceability, loudness, acousticness, tempo, and instrumentalness.

---

## 📌 Project Overview

Music contains several measurable audio characteristics that can be used to identify different genres.

This project uses Machine Learning classification algorithms to predict the **music genre (Class)** of a track based on its audio-related features.

The project follows a complete Machine Learning workflow including data preprocessing, exploratory data analysis, model training, evaluation, and model saving.

---

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can classify music tracks into different genre classes based on their audio features.

### Input Features

- **Popularity**
- **Danceability**
- **Energy**
- **Key**
- **Loudness**
- **Mode**
- **Speechiness**
- **Acousticness**
- **Instrumentalness**
- **Liveness**
- **Valence**
- **Tempo**
- **Duration**
- **Time Signature**

### 🎯 Target Variable

**Class**

The dataset contains **11 different music genre classes**, represented by class values from `0` to `10`.

---

## 🧠 Machine Learning Models

The following classification algorithms were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 49.56% | 45.82% | 49.56% | 46.39% |
| KNN | 42.58% | 41.85% | 42.58% | 42.16% |
| **Random Forest** | **49.64%** | **48.30%** | **49.64%** | **48.29%** |

### 🏆 Selected Model

**Random Forest Classifier** was selected as the final model because it achieved the best overall performance among the tested models.

### Final Performance

- **Accuracy:** 49.64%
- **Precision:** 48.30%
- **Recall:** 49.64%
- **F1 Score:** 48.29%

---

## 🔄 Machine Learning Workflow

```text
                  Music Dataset
                       │
                       ▼
              Data Understanding
                       │
                       ▼
                Data Cleaning
                       │
                       ▼
             Exploratory Data Analysis
                       │
                       ▼
             Remove Unnecessary Columns
                       │
                       ▼
                Separate X and y
                       │
                       ▼
               Train/Test Split
                       │
                       ▼
                Preprocessing
                       │
                       ▼
                 StandardScaler
                       │
                       ▼
               Model Training
                 /     |      \
                /      |       \
               ▼       ▼        ▼
          Logistic    KNN     Random
         Regression          Forest
                \      |       /
                 \     |      /
                  ▼    ▼     ▼
                Evaluation
                     │
                     ▼
              Best Model Selection
                     │
                     ▼
                Save Model
                     │
                     ▼
                  GitHub


    BY AUTHOR
        G. NITHIYA SRI (AI&DS)   RMKCET🔥