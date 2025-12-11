# 📘 Medical Insurance Cost Prediction — Data Science Project
This repository contains a complete beginner-friendly machine learning workflow to predict medical insurance charges based on demographic and lifestyle factors such as age, BMI, region, smoking status, and more.

The project includes data exploration, cleaning, feature engineering, model training, evaluation, and exporting predictions.


## 📁 Project Structure

├── main.ipynb             Main Jupyter Notebook containing the full workflow
├── insurance.csv          Original dataset
├── predictions.xlsx       Model predictions exported to Excel
└── y_test.xlsx            Actual test values used for evaluation


## 🎯 Project Objective
To build a machine learning model that predicts insurance charges using regression techniques while understanding the contributing factors through exploratory data analysis (EDA).


## ✅ Workflow Overview

1. Importing Libraries

Basic Python data science stack:
• pandas
• numpy
• seaborn / matplotlib
• scikit-learn

2. Loading the Dataset

The dataset insurance.csv is loaded and inspected:
• Data structure
• Missing values
• Statistical summary

3. Exploratory Data Analysis (EDA)

Includes:
• Distribution plots
• Count plots for categorical variables
• Boxplots to detect outliers
• Correlation heatmap

Purpose: understand feature relationships and dataset patterns.

4. Data Cleaning & Preprocessing

• Encoding categorical variables
• Preparing numerical & categorical features
• Renaming fields for clarity
• One-hot encoding for region
• Ensuring consistent data types

5. Feature Engineering

• Additional transformations (if any) applied to improve model performance

6. Model Training

A regression model is trained using:
• Train/test split
• Linear Regression (baseline)
• Additional models can be added later

7. Evaluation

Predictions are compared with actual values using:
• MAE
• MSE
• R² score
• Visual comparison of predicted vs. actual values

8. Exporting Results

• Predictions saved to predictions.xlsx
• Actual values saved to y_test.xlsx
Workflow Overview
1. Importing Libraries

Basic Python data science stack:
• pandas
• numpy
• seaborn / matplotlib
• scikit-learn

2. Loading the Dataset

The dataset insurance.csv is loaded and inspected:
• Data structure
• Missing values
• Statistical summary

3. Exploratory Data Analysis (EDA)

Includes:
• Distribution plots
• Count plots for categorical variables
• Boxplots to detect outliers
• Correlation heatmap

Purpose: understand feature relationships and dataset patterns.

4. Data Cleaning & Preprocessing

• Encoding categorical variables
• Preparing numerical & categorical features
• Renaming fields for clarity
• One-hot encoding for region
• Ensuring consistent data types

5. Feature Engineering

• Additional transformations (if any) applied to improve model performance

6. Model Training

A regression model is trained using:
• Train/test split
• Linear Regression (baseline)
• Additional models can be added later

7. Evaluation

Predictions are compared with actual values using:
• MAE
• MSE
• R² score
• Visual comparison of predicted vs. actual values

8. Exporting Results

• Predictions saved to predictions.xlsx
• Actual values saved to y_test.xlsx



## 📊 Dataset Description

The dataset contains the following features:

Column	      Description
age           Age of the individual
sex           Male/Female
bmi	          Body Mass Index
children	  Number of dependents
smoker	      Smoker or non-smoker
region	      Region within the US
charges	      Medical insurance cost (target variable)



## 📌 Future Improvements
Add hyperparameter tuning (GridSearchCV / RandomForest / XGBoost)
Add model interpretability (SHAP, permutation importance)
Add a Streamlit web app for interactive predictions
Create modular Python scripts (train.py, predict.py)
Add Docker support


## 💡 Author
Shoaib — Data Science & Python Enthusiast