# Ames House Price Exploration and Advertisement Dataset Analysis

## Overview
This project focuses on developing a predictive model for house prices in the Ames area. The project is divided into two main directories: 
- Data Exploration and Cleaning
- Regression Analysis

## Data Exploration and Cleaning
The `Data Exploration and Cleaning` directory contains files related to the initial exploration and preprocessing of the dataset:

- `Ames_Housing_Data.csv`: The original dataset containing information about houses in the Ames area.
- `Ames_Housing_Feature_Description.txt`: A file describing the features present in the dataset.
- `Ames_No_Missing_Data.csv`: The dataset after removing rows with missing data.
- `Ames_my_outliers_removed.csv`: The dataset after removing outliers identified during exploratory data analysis.
- `Final_Ames_data.csv`: The final preprocessed dataset ready for modeling.
- `data_preprocessing.ipynb`: Jupyter notebook containing the code for data exploration and cleaning.

## Regression Analysis for different dataset
The `Regression Analysis` directory contains files related to building and evaluating regression models for predicting house prices:

- `Advertising.csv`: Dataset containing advertising spending and sales data.
- `final_converter.joblib`: Serialized object for converting categorical variables to numerical values.
- `final_poly_model.joblib`: Serialized object for the final polynomial regression model.
- `final_sales_polynomial_model.joblib`: Serialized object for the final polynomial regression model for sales prediction.
- `final_sales_simple_linear_model.joblib`: Serialized object for the final simple linear regression model for sales prediction.
- `linearRegression.ipynb`: Jupyter notebook containing code for simple linear regression analysis.
- `polynomialRegression.ipynb`: Jupyter notebook containing code for polynomial regression analysis.

## Usage
To reproduce the results of this project, follow these steps:
1. Navigate to the `Data Exploration and Cleaning` directory and run the `data_preprocessing.ipynb` notebook.
2. Proceed to the new `Regression Analysis` directory and run the `linearRegression.ipynb` notebook for simple linear regression analysis or `polynomialRegression.ipynb` for polynomial regression analysis.

## Contributors
- Shashank: Project Developer
