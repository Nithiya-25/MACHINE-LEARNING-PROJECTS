# MACHINE-LEARNING-PROJECTS
🤖 Machine Learning Projects

> A collection of Machine Learning projects developed as part of my learning and internship journey, covering classification, regression, fraud detection, healthcare prediction, accident severity prediction, car price prediction, and music genre classification.

---

## 👋 About This Repository

This repository contains **5 Machine Learning projects** developed using Python and Scikit-learn.

The projects cover different types of real-world Machine Learning problems, including:

- Binary Classification
- Multi-Class Classification
- Regression
- Data Preprocessing
- Exploratory Data Analysis
- Model Evaluation
- Machine Learning Pipelines

Each project follows a practical Machine Learning workflow from **data preprocessing to model evaluation **.

---

# 📂 Projects

| No. | Project | Problem Type | Best Model |
|---|---|---|---|
| 1 | 💳 Credit Card Fraud Detection | Binary Classification | Logistic Regression |
| 2 | 🩺 Diabetes Detection | Binary Classification | Best performing classification model |
| 3 | 🚗 Accident Collision Severity Prediction | Multi-Class Classification | Random Forest |
| 4 | 🚘 Second-Hand Car Price Prediction | Regression | Linear Regression |
| 5 | 🎵 Music Genre Classification | Multi-Class Classification | Random Forest |

---

# 1️⃣ 💳 Credit Card Fraud Detection

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning.

The objective is to classify transactions into:

- **Legitimate Transaction**
- **Fraudulent Transaction**

The project includes data preprocessing, feature scaling, model training, evaluation, and confusion matrix analysis.

### 🔧 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- StandardScaler
- Logistic Regression
- Git & GitHub

### 🔄 Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Preprocessing
   ↓
Feature Scaling
   ↓
Train/Test Split
   ↓
Logistic Regression
   ↓
Model Evaluation
   ↓
Confusion Matrix
📊 Evaluation

The model was evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
📁 Project Folder
Credit_Card_Fraud_Detection/
2️⃣ 🩺 Diabetes Detection
📌 Overview

This project predicts whether a person is likely to have diabetes based on medical and demographic features.

The dataset contains features such as:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
🎯 Target

Outcome

0 → No Diabetes
1 → Diabetes
🔧 Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SimpleImputer
StandardScaler
Logistic Regression
KNN
Decision Tree
Random Forest


🔄 Workflow
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
EDA
   ↓
Train/Test Split
   ↓
Data Preprocessing
   ↓
Multiple Classification Models
   ↓
Model Evaluation
   ↓
Best Model
  
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
Confusion Matrix

📁 Project Folder
Diabetes_detection/
3️⃣ 🚗 Accident Collision Severity Prediction
📌 Overview

This project uses Machine Learning to predict the severity of an accident based on accident, road, weather, lighting, and junction-related information.

🔑 Important Features
Collision Reference Number
Policing Area
Collision Severity
Weekday of Collision
Day of Collision
Month of Collision
Hour of Collision
Carriageway Type
Speed Limit
Junction Detail
Junction Control
Pedestrian Crossing Information
Light Conditions
Weather Conditions
Road Surface Conditions
Special Conditions at Site
🎯 Target

Collision Severity

🔧 Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SimpleImputer
StandardScaler
OneHotEncoder
Logistic Regression
Decision Tree
Random Forest


🔄 Workflow
Accident Dataset
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Numerical & Categorical Feature Separation
       ↓
Preprocessing
       ↓
Model Training
       ↓
Model Comparison
       ↓
Random Forest
       ↓
Evaluation
       ↓
Deployment

📊 Model Comparison
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	89.25%	79.65%	89.25%	84.18%
Decision Tree	85.02%	85.40%	85.02%	85.21%
Random Forest	89.60%	86.08%	89.60%	85.60%
🏆 Selected Model

Random Forest Classifier

📁 Project Folder
Accident_Survival/
4️⃣ 🚘 Second-Hand Car Price Prediction
📌 Overview

This project predicts the price of a second-hand car using information about the vehicle.

🔑 Features
Name
Label
Location
Kms Driven
Fuel Type
Owner
Year
Company
🎯 Target

Price

🔧 Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SimpleImputer
StandardScaler
OneHotEncoder
Linear Regression
Decision Tree Regressor
Random Forest Regressor


🔄 Workflow
Car Dataset
    ↓
Data Understanding
    ↓
Data Cleaning
    ↓
Price Conversion
    ↓
EDA
    ↓
Train/Test Split
    ↓
Numerical & Categorical Preprocessing
    ↓
Regression Models
    ↓
Model Evaluation
    ↓
Best Model Selection
    
📊 Model Comparison
Model	MAE	RMSE	R² Score
Linear Regression	199,966	438,613	0.5610
Decision Tree	243,209	578,903	0.2353
Random Forest	197,938	531,820	0.3547
🏆 Selected Model

Linear Regression

The model achieved an R² score of approximately 0.561, explaining about 56.1% of the variation in car prices on the test data.

📁 Project Folder
Second_Hand_Car_Price/
5️⃣ 🎵 Music Genre Classification
📌 Overview

This project predicts the genre/class of a music track using audio-related features.

🎵 Audio Features
Popularity
Danceability
Energy
Key
Loudness
Mode
Speechiness
Acousticness
Instrumentalness
Liveness
Valence
Tempo
Duration
Time Signature
🎯 Target

Class

The dataset contains 11 different classes, represented by values from 0 to 10.

🔧 Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SimpleImputer
StandardScaler
Logistic Regression
KNN
Random Forest

🔄 Workflow
Music Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Remove Artist & Track Names
     ↓
EDA
     ↓
Train/Test Split
     ↓
StandardScaler
     ↓
Classification Models
     ↓
Model Evaluation
     ↓
Random Forest
     ↓
Confusion Matrix
     ↓
Model Saving
📊 Model Comparison
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	49.56%	45.82%	49.56%	46.39%
KNN	42.58%	41.85%	42.58%	42.16%
Random Forest	49.64%	48.30%	49.64%	48.29%
🏆 Selected Model

Random Forest Classifier

The model achieved an accuracy of approximately 49.64% on the test data.

📁 Project Folder
Music_Genre_Classification/
🧠 Machine Learning Concepts Covered

Across these five projects, the following concepts were implemented:

📊 Data Handling
Pandas
NumPy
Data Loading
Data Inspection
Data Cleaning
Duplicate Removal
Missing Value Detection

🔍 Exploratory Data Analysis
Statistical Analysis
Distribution Analysis
Correlation Analysis
Box Plots
Histograms
Scatter Plots
Count Plots
Heatmaps

⚙️ Data Preprocessing
Train/Test Split
SimpleImputer
StandardScaler
OneHotEncoder
Pipeline
ColumnTransformer

🤖 Machine Learning Algorithms
Classification
Logistic Regression
K-Nearest Neighbors
Decision Tree
Random Forest
Regression
Linear Regression
Decision Tree Regressor
Random Forest Regressor

📈 Model Evaluation
Classification
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Regression
MAE
RMSE
R² Score


🔄 Overall Machine Learning Workflow
                   📂 Dataset
                       │
                       ▼
              🔍 Data Understanding
                       │
                       ▼
                🧹 Data Cleaning
                       │
                       ▼
                📊 EDA & Analysis
                       │
                       ▼
              🎯 Feature Selection
                       │
                       ▼
             ✂️ Train/Test Split
                       │
                       ▼
             ⚙️ Data Preprocessing
                       │
                       ▼
               🤖 Model Training
                       │
                       ▼
              📈 Model Evaluation
                       │
                       ▼
              🏆 Best Model Selection
                       │
                       ▼
                       │
                       ▼
                  🚀 GitHub

🛠️ Technologies Used:
Technology	Purpose
🐍 Python	Programming Language
🐼 Pandas	Data Manipulation
🔢 NumPy	Numerical Computing
📊 Matplotlib	Visualization
📈 Seaborn	Statistical Visualization
🤖 Scikit-learn	Machine Learning
💾 Joblib	Model Serialization
🌐 Streamlit	Model Deployment
🐙 GitHub	Version Control & Project Hosting
📓 Jupyter Notebook	Development Environment


MACHINE-LEARNING-PROJECTS/
│
├── Credit_Card_Fraud_Detection/
│   ├── credit_card_fraud_detection.ipynb
│   ├── Model_evaluation pics
│   ├── README.md
│   └── requirements.txt
│
├── Diabetes_detection/
│   ├── diabetes_detection.ipynb
│   ├── Model_evaluation pics
│   ├── README.md
│   └── requirements.txt
│
├── Accident_Survival/
│   ├── accident_prediction.ipynb
│   ├── Model_evaluation pics
│   ├── README.md
│   └── requirements.txt
│
├── Second_Hand_Car_Price/
│   ├── car_price_prediction.ipynb
│   ├── Model_evaluation pics
│   ├── README.md
│   └── requirements.txt
│
├── Music_Genre_Classification/
│   ├── music_genre_classification.ipynb
│   ├── Model_evaluation pics
│   ├── README.md
│   └── requirements.txt
│
└── README.md

🚀 How to Run the Projects
1. Clone the Repository
git clone <YOUR_GITHUB_REPOSITORY_URL>
2. Open the Repository
cd MACHINE-LEARNING-PROJECTS
3. Install Required Libraries

Each project contains its own requirements.txt.

For example:
cd Diabetes_detection
pip install -r requirements.txt
4. Run the Streamlit Application
streamlit run app.py


👩‍💻 Author
  G . NITHIYA SRI (AIDS) RMKCET 🔥

B.Tech Artificial Intelligence & Data Science
