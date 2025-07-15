# Predicting Electric Vehicle Range Based On Features

This project explains for the Module end project based on the topic name -"Predicting Electric vehicle range based on features".

# Introduction 

The Electric Vehicle population dataset from Washington Technology Solutions (WaTech) is part of the Washington Open Data Program, which allows all state agencies to publish public data at https://data.wa.gov.Categorical features in the dataset are encoded, while numerical features are transformed using the Yeo-Johnson method to correct skewness. Outliers are handled using a capping technique. Five machine learning regression models are implemented: Linear Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and Gradient Boosting. These models are evaluated using performance metrics such as MAE, MSE, R² score, and RMSE. The objective is to identify the best-performing model and the key features that influence electric vehicle range prediction. This analysis can support companies in developing effective sales and marketing strategies.
The goal of this project is to design and implement a robust data preprocessing system that addresses challenges such as:

# Goal of the Project 

Build a machine learning model that can accurately predict the Electric vehicle range ,using various feature.

# Data Story/Source

The dataset used in this project is the Electric Vehicle Population dataset, originally sourced from Data.gov. It contains 235,692 records and 17 features, comprising both numerical and categorical variables that provide detailed information about electric vehicles in Washington, USA.

each entry in the dataset represents a vehicle record, with attributes such as VIN (1–10), County, City, State, Postal Code, Model Year, Make, Model, Electric Vehicle Type, Clean Alternative Fuel Vehicle (CAFV) Eligibility, Electric Range, Base MSRP, Legislative District, DOL Vehicle ID, Vehicle Location, Electric Utility, and 2020 Census Tract.

The target variable is Electric Range, which indicates the driving range of each electric vehicle in the dataset.

# About dataset

Source of the data is from Data.gov Machine Learning Repository. Link: https://catalog.data.gov/dataset/electric-vehicle-population-data

# Conclusions

* The Random Forest Regressor achieved the highest performance among all five models with 99% accuracy, demonstrating strong predictive capability for estimating electric vehicle range.

* When evaluated on unseen data, it maintained high accuracy, indicating robust generalization and effective pattern recognition.

* The dataset was clean and well-prepared, with no missing values or duplicates.

* Preprocessing techniques such as feature encoding and scaling contributed to all models achieving over 95% accuracy.

* Hyperparameter tuning had minimal impact on the performance of the Random Forest Regressor, implying it was already well-optimized.

# FUTURE WORK

* Model Maintenance: Regularly refresh the model using recent data to help it stay responsive to evolving trends and user behavior.
* Enhanced Feature Design: Explore the creation of new features or refinement of current ones to uncover deeper insights and improve the model’s predictive performance.

--- The End --- 
