# 🩺 Breast Cancer Prediction using Logistic Regression
## 📌 Project Overview
This project applies Logistic Regression to the Breast Cancer Wisconsin Dataset to predict whether a tumor is benign or malignant based on cell measurements. Logistic Regression was chosen for its interpretability and effectiveness in binary classification problems.

## 📊 Dataset
- Source: Breast Cancer Wisconsin Dataset (UCI/Kaggle)
- Features: 30 numerical features (cell nucleus measurements)
- Target: Diagnosis (M = Malignant, B = Benign

## ⚙️ Steps in the Project

 ### 1. Data Exploration & Cleaning

- Removed irrelevant columns (id, Unnamed: 32)
- Converted diagnosis labels into binary (1 = Malignant, 0 = Benign)
- Checked for missing values

### 2. Exploratory Data Analysis (EDA)
-Visualized missing values
-Checked class distribution
-Examined feature correlations

### 3. Preprocessing
- Standardized features for better model performance

### 4. Model Training
- Trained a Logistic Regression classifier using Scikit-Learn

### 5. Evaluation
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve
