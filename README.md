## Big Mart Sales Prediction Using Machine Learning

This project focuses on predicting sales of products in Big Mart stores using historical sales data and machine learning techniques.

## Overview

Retail sales forecasting plays a crucial role in inventory management, demand planning, and revenue optimization.
This project uses machine learning models to predict product sales based on item characteristics and outlet information.

The complete pipeline includes data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## Problem Statement

To build a machine learning model that accurately predicts product sales across different Big Mart outlets using available item and store features.

The goal is to help businesses optimize inventory and improve decision making.

## Dataset Description

The dataset contains historical sales records for various products across multiple Big Mart outlets.

Key features include item weight, item visibility, item type, maximum retail price, outlet size, outlet location type, outlet type, and establishment year.

Target variable  
Item outlet sales representing the total sales of a product.

## Technologies Used

Python  
NumPy  
Pandas  
Matplotlib  
Seaborn  
Scikit learn  
Jupyter Notebook  

## Project Workflow

1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory data analysis  
4. Feature engineering  
5. Feature scaling and encoding  
6. Model training  
7. Model evaluation  
8. Sales prediction  

## Exploratory Data Analysis

Analyzed sales trends across different product categories.
Studied the impact of outlet size and location on sales.
Visualized relationships between item price, visibility, and sales.

## Data Preprocessing

Handled missing values in item weight and outlet size.
Standardized inconsistent categorical values.
Encoded categorical variables into numerical format.
Applied feature scaling where required.
Split data into training and testing sets.

## Model Selection

The following regression models were implemented and evaluated.

Linear Regression  
Ridge Regression  
Lasso Regression  
Decision Tree Regressor  
Random Forest Regressor  

Models were compared to identify the most accurate sales predictor.

## Model Evaluation

Models were evaluated using R squared score and root mean squared error.
Performance comparison helped select the final model.
The chosen model demonstrated strong predictive performance on unseen data.

## Results

The final model produced accurate sales predictions across various product and outlet combinations.
Results indicate that machine learning can effectively support retail sales forecasting.

## How to Run This Project

1. Clone the repository  
2. Install required Python libraries  
3. Open the Big Mart Sales Prediction notebook  
4. Run all cells sequentially  

## Future Improvements

Add more historical data  
Perform advanced feature engineering  
Tune hyperparameters for better accuracy  
Deploy the model as a web application  

## Conclusion

This project demonstrates the effectiveness of machine learning for retail analytics.
It highlights how data driven insights can improve sales forecasting and business strategy.

## Author

Satyam Gajjar
