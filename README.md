# Car Price Prediction Model

This project aims to build a machine learning model to predict the selling price of cars based on various features such as year, present price, kilometers driven, fuel type, seller type, transmission, and owner count.

## Dataset

The dataset used in this project contains information about car sales. It consists of the following columns:

- `Car_Name`: Name of the car
- `Year`: Year of manufacture
- `Selling_Price`: Selling price of the car
- `Present_Price`: Current price of the car
- `Kms_Driven`: Total kilometers driven by the car
- `Fuel_Type`: Type of fuel used (Petrol, Diesel, CNG)
- `Transmission`: Type of transmission (Manual, Automatic)

The dataset contains 301 entries and has a mixture of numerical and categorical data.

## Data Preprocessing

- Categorical data such as `Fuel_Type`, `Seller_Type`, and `Transmission` were encoded using label encoding to convert them into numerical format for model training.

## Model Building

Two regression models were used for this project:

1. **Linear Regression**: A basic linear regression model was trained using the `LinearRegression` class from scikit-learn.
2. **Lasso Regression**: Lasso regression, which applies L1 regularization to the regression model, was trained using the `Lasso` class from scikit-learn.
