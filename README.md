# Car-Price-Prediction-using-Machine-Learning
Machine learning project to predict car prices using regression models, feature engineering, and model evaluation techniques.
Project Overview

This project was developed during my Data Science internship and focuses on predicting car prices using machine learning techniques.
The goal is to build an accurate regression model based on vehicle attributes such as model, transmission, fuel type, mileage, engine size, and year.

🎯 Problem Statement
Accurately estimating the resale price of a car is challenging due to multiple influencing factors.
This project aims to predict car prices using historical data and compare the performance of various regression models.

📊 Dataset
Dataset Name: Audi Car Dataset
File: audi.csv
Target Variable: price
Features Includes
Model
Year
Transmission
Fuel Type
Mileage
Engine Size
Mileage (mpg)

🛠️ Technologies & Tools Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
CatBoost
XGBoost
Random Forest Regressor
Jupyter Notebook

🔍 Exploratory Data Analysis (EDA)
Checked missing values and duplicates
Analyzed feature distributions
Used Pandas Profiling for automated EDA
Identified correlations between features and target variable

⚙️ Data Preprocessing
Label Encoding for categorical features
One-Hot Encoding for transmission
Feature Scaling using StandardScaler
Train-Test Split (80% Train, 20% Test)

🤖 Machine Learning Models Implemented
Linear Regression
Random Forest Regressor
Extra Trees Regressor
CatBoost Regressor
Hyperparameter Tuning using RandomizedSearchCV

📈 Model Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)

🏆 Best Model Performance
catBoost Regressor achieved the best accuracy
High R² score with low prediction error
Model saved using pickle for future predictions
