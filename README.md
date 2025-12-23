# 🚗 Car Price Prediction using Machine Learning

📌 Project Overview


The Car Price Prediction project is a machine learning–based system that predicts the selling price of a car based on its technical specifications and features. The project uses supervised learning algorithms to analyze historical car data and generate accurate price predictions, helping users understand the key factors affecting car prices.


🎯 Objectives


To analyze real-world car data and identify important factors influencing car prices

To build and compare multiple regression models for price prediction

To evaluate model performance using standard machine learning metrics

To create a reusable and scalable prediction system


🧠 Machine Learning Approach


Type: Supervised Learning (Regression)

Models Implemented:

Linear Regression

Ridge Regression

Lasso Regression

Random Forest Regressor


📊 Dataset Description


Dataset contains 205 car records with 26 features

Key features include:

Car name, brand

Engine size, horsepower, fuel type

Mileage (city & highway)

Number of doors, car body type


🛠️ Technologies Used


Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib

Environment: Jupyter Notebook


🔍 Data Preprocessing & Feature Engineering


Handled missing and inconsistent values

Extracted car brand from car names

Converted categorical variables using label encoding

Performed exploratory data analysis (EDA) to understand relationships


📈 Model Evaluation


Models were evaluated using:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Random Forest Regressor showed the best performance among all models.


💾 Model Deployment


The trained model was saved using Pickle

The saved model can be reused for predicting prices of new car data


🚀 Results & Insights


Engine size, horsepower, and mileage significantly impact car prices

Machine learning models can accurately estimate car prices when trained on quality data


📂 Project Structure

├── car_data.csv

├── car_price.ipynb

├── model.pkl

└── README.md


📌 Conclusion


This project demonstrates the complete machine learning workflow — from data preprocessing and model training to evaluation and prediction. It provides practical exposure to regression techniques and real-world data handling.
