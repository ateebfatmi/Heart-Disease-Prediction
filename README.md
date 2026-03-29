# Heart-Disease-Prediction

# Project Overview
Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely treatment and prevention.
This project uses Machine Learning algorithms to predict whether a person is likely to have heart disease based on medical attributes such as age, blood pressure, cholesterol level, chest pain type, etc.
The project is implemented in Python using Jupyter Notebook.

# Objective
To build a machine learning model that can accurately predict the presence of heart disease using patient health data.

# Dataset Information
The dataset contains medical information of patients.

# Features used:
Age – age of the patient

Sex – gender (0 = Female, 1 = Male)

ChestPainType – type of chest pain

RestingBP – resting blood pressure

Cholesterol – cholesterol level

FastingBS – fasting blood sugar

RestingECG – ECG results

MaxHR – maximum heart rate achieved

ExerciseAngina – exercise-induced angina

Oldpeak – ST depression value

ST_Slope – slope of ST segment

HeartDisease – target variable (0 = No disease, 1 = Disease)


The dataset contains medical information of patients.

# Technologies Used:
Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn


# Machine Learning Workflow

1. Data Collection
Heart disease dataset in CSV format.

2. Data Preprocessing
Handling missing values
Encoding categorical variables
Converting data types
Feature scaling

4. Data Visualization
Target distribution
Correlation heatmap
Feature relationships

5. Model Training
The following algorithms were used:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

5. Model Evaluation
Model performance evaluated using:
Accuracy score
Confusion matrix
Classification report

6. Prediction
The trained model predicts whether a patient has heart disease or not.

# Results
The models were compared based on accuracy.
Example results:

Logistic Regression → 84%

Random Forest → 88%

SVM → 86%

KNN → 83%

Random Forest provided the best performance.

