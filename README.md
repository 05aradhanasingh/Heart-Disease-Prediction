# Heart Disease Prediction

## Overview
Cardiovascular diseases (CVDs) are a major global health concern, causing millions of deaths each year. Early detection can help reduce risks and improve treatment outcomes. This project develops machine learning models to predict heart disease based on key medical indicators.

## Dataset Information
The dataset is compiled from five independent heart disease datasets available from the UCI Machine Learning Repository. After data cleaning, it contains **918 records** with **11 features** for prediction.

### Source Datasets:
- Cleveland: 303 observations  
- Hungarian: 294 observations  
- Switzerland: 123 observations  
- Long Beach VA: 200 observations  
- Stalog (Heart) Data Set: 270 observations  
- **Final dataset size:** 918 observations (after removing duplicates)

### Features Used for Prediction:

| Feature        | Description |
|---------------|-------------|
| Age           | Age of the patient (years) |
| Sex           | Gender (M: Male, F: Female) |
| ChestPainType | Chest pain type (TA, ATA, NAP, ASY) |
| RestingBP     | Resting blood pressure (mm Hg) |
| Cholesterol   | Serum cholesterol (mg/dl) |
| FastingBS     | Fasting blood sugar (1: >120 mg/dl, 0: otherwise) |
| RestingECG    | Resting ECG results (Normal, ST, LVH) |
| MaxHR         | Maximum heart rate achieved |
| ExerciseAngina | Exercise-induced angina (Y: Yes, N: No) |
| Oldpeak       | ST depression induced by exercise |
| ST_Slope      | Slope of peak exercise ST segment (Up, Flat, Down) |
| HeartDisease  | Target variable (1: Heart disease, 0: Normal) |

## Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- Naïve Bayes  
- K-Nearest Neighbors (KNN)  

## Results

| Model                | Validation Accuracy | Test Accuracy |
|----------------------|--------------------|--------------|
| Logistic Regression | 0.8487             | 0.8859       |
| Decision Tree       | 0.8079             | 0.7935       |
| Random Forest       | 0.8515             | 0.8913       |
| SVM                 | 0.8610             | 0.8859       |
| Naïve Bayes         | 0.8542             | 0.8859       |
| KNN                 | 0.8446             | 0.9185       |

## Future Improvements
- Hyperparameter tuning for better optimization  
- Implementation of deep learning models (Neural Networks) for improved accuracy  



