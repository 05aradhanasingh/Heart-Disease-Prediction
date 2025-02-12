Heart Disease Prediction

📌 Overview

Cardiovascular diseases (CVDs) are the leading cause of death globally, responsible for approximately 17.9 million deaths annually, accounting for 31% of all global deaths. Many of these fatalities occur due to heart attacks and strokes, and one-third of these deaths are premature (under 70 years old).

This project aims to develop machine learning models to predict the likelihood of heart disease based on 11 key medical features. Early detection of heart disease can help in effective management and prevention, thereby reducing mortality rates.

🏥 Dataset Information

The dataset used in this project is a combination of five independent heart disease datasets, curated from the UCI Machine Learning Repository. It consists of 918 records after removing duplicate entries.

🔹 Source Datasets:

Cleveland: 303 observations

Hungarian: 294 observations

Switzerland: 123 observations

Long Beach VA: 200 observations

Stalog (Heart) Data Set: 270 observations

Total (before cleaning): 1190 observations

Final dataset: 918 observations (after removing 272 duplicates)

🔹 Features Used for Prediction:

Feature

Description

Age

Age of the patient (years)

Sex

Gender of the patient (M: Male, F: Female)

ChestPainType

Type of chest pain (TA, ATA, NAP, ASY)

RestingBP

Resting blood pressure (mm Hg)

Cholesterol

Serum cholesterol (mg/dl)

FastingBS

Fasting blood sugar (1: >120 mg/dl, 0: otherwise)

RestingECG

Resting ECG results (Normal, ST, LVH)

MaxHR

Maximum heart rate achieved

ExerciseAngina

Exercise-induced angina (Y: Yes, N: No)

Oldpeak

ST depression induced by exercise

ST_Slope

Slope of the peak exercise ST segment (Up, Flat, Down)

HeartDisease

Target variable (1: Heart disease, 0: Normal)

🔍 Machine Learning Models Used

Several machine learning models were implemented and evaluated to determine the most accurate model for heart disease prediction:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Naïve Bayes

K-Nearest Neighbors (KNN)

📊 Results

Model

Validation Accuracy

Test Accuracy

Logistic Regression

0.8487

0.8859

Decision Tree

0.8079

0.7935

Random Forest

0.8515

0.8913

SVM

0.8610

0.8859

Naïve Bayes

0.8542

0.8859

KNN

0.8446

0.9185

💡 Future Improvements

Hyperparameter tuning to further optimize model performance.

Use of deep learning models (Neural Networks) for improved accuracy.


