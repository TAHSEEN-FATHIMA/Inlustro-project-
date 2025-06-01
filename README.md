# AI-Driven Employee Relocation Optimization System

## Overview of the project

This project builds a machine learning model to predict whether an employee is suitable for relocation. The model uses a synthetic HR dataset and considers factors like age, department, job satisfaction, and willingness to relocate. A Random Forest Classifier is optimized using Grid Search and evaluated with performance metrics and feature importance analysis.

## Objective

To develop a predictive system that helps organizations identify employees most suitable for relocation based on a combination of personal and performance-related factors. This assists HR departments in making informed, data-driven decisions for internal transfers, remote postings, and other workforce mobility needs.

## Key Activities

✅ Data Generation: Created a synthetic HR dataset of 1000 employees with realistic attributes like age, department, years at company, job satisfaction, etc.

✅ Label Creation: Defined RelocationSuitability based on business logic combining willingness to relocate, job satisfaction, and performance rating.

✅ Data Preprocessing: Encoded categorical variables using LabelEncoder.

✅ Model Training: Used RandomForestClassifier for prediction.

✅ Hyperparameter Tuning: Optimized model using GridSearchCV with cross-validation.

✅ Evaluation: Evaluated model using accuracy and classification report.

✅ Feature Importance: Visualized the most influential features driving the prediction.

## Technologies Used

Programming Language - Python 3.x

Data Manipulation	- pandas, numpy

Visualization -	matplotlib

Machine Learning - scikit-learn (RandomForest, GridSearchCV, LabelEncoder)

## Use Cases

### Internal Transfers: 
  Recommend employees for cross-department or cross-location transfers.
### Global Relocation: 
  Identify candidates for international postings or remote roles.
### HR Decision Support: 
  Provide insights into workforce mobility using predictive analytics.
### Talent Management: 
  Help retain talent by offering opportunities based on job satisfaction and performance.
