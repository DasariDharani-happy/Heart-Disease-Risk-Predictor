# Heart Disease Risk Predictor

## Overview
This project focuses on predicting the likelihood of heart disease in individuals using supervised machine learning techniques. The goal is to assist in early detection and medical diagnosis by analyzing patient health attributes such as age, cholesterol level, blood pressure, heart rate, and other clinical indicators.

The model aims to provide a decision-support tool that can contribute to preventative healthcare and risk assessment.

## Objectives
- To build a predictive model for heart disease classification
- To evaluate the contribution of various health-related features to risk prediction
- To provide interpretable and reliable outputs for clinical support

## Dataset Information
- **Source**: UCI Machine Learning Repository (Heart Disease Dataset)
- **Number of Records**: 303 (or as used in this project)
- **Target Variable**: Presence or absence of heart disease (binary classification)

### Input Features Include:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope of ST segment
- Number of major vessels
- Thalassemia

## Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling

2. **Exploratory Data Analysis**
   - Distribution plots for key variables
   - Correlation heatmaps to identify key predictors

3. **Model Development**
   - Applied machine learning algorithms (e.g., Logistic Regression, Random Forest, SVM)
   - Model selection based on accuracy, precision, recall, and F1-score

4. **Evaluation**
   - Confusion matrix
   - ROC Curve and AUC Score
   - Feature importance analysis

## Results
The trained model effectively classifies the presence or absence of heart disease with high accuracy and reliability. Evaluation metrics indicate balanced performance across both classes.

## Tools and Technologies
- Python
- NumPy, Pandas for data handling
- Matplotlib, Seaborn for visualization
- Scikit-learn for machine learning and evaluation

## Applications
- Early heart disease risk screening
- Clinical decision support systems
- Educational tools for health analytics
- Research in predictive cardiology


