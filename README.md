# House Price Prediction

## Project Description

This project aims to predict house prices based on various features such as size, location, number of bedrooms, number of bathrooms, year built, and more. The dataset is provided in the `HousePricePrediction.xlsx` file.

House price prediction is a crucial task in the real estate industry. Accurate predictions can assist buyers, sellers, and real estate agents in making informed decisions. The primary goal of this project is to develop a machine learning model that can accurately predict house prices using the given features. 

We will start by exploring the dataset to understand the distribution of features and their relationship with house prices. Data preprocessing steps, such as handling missing values and encoding categorical variables, will be performed to prepare the data for modeling. 

We will then build multiple machine learning models, including Linear Regression, Decision Trees, Random Forests, and Gradient Boosting, to find the best-performing model. Hyperparameter tuning will be conducted to optimize the selected model's performance.

Finally, we will evaluate the model using various metrics and visualize the results to understand its predictive power. This project demonstrates the entire workflow of a machine learning project, from data exploration and preprocessing to model building and evaluation.



## Dataset

The dataset contains the following columns:
- `Size`: Size of the house in square feet.
- `Location`: Location of the house.
- `Bedrooms`: Number of bedrooms.
- `Bathrooms`: Number of bathrooms.
- `YearBuilt`: Year the house was built.
- `Price`: Price of the house.

## Requirements

- Python 3.6 or above
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - openpyxl (for reading the Excel file)
