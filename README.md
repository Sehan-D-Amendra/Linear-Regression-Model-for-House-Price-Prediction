# House Price Prediction Project

## Project Overview
This project implements a linear regression model to predict house prices based on key features including square footage, number of bedrooms, and number of bathrooms. The implementation uses the popular Ames Housing dataset, which contains detailed information about residential properties.

## Dataset Description
The dataset includes:

- Training data with extensive property features and their corresponding sale prices
- Test data with the same features but without sale prices (for prediction)
- Features include property characteristics such as lot size, building type, year built, quality ratings, and room counts

## Key Features Used
The model focuses primarily on three critical features:
- Square Footage: Total living area (GrLivArea) and potentially other area measurements
- Bedrooms: Number of bedrooms above ground (BedroomAbvGr)
- Bathrooms: Combined bathroom count (including full and half baths)

## Implementation Details
The project implements:

- Data preprocessing and cleaning
- Exploratory data analysis with visualizations
- Feature selection focusing on area, bedrooms, and bathrooms
- Linear regression model building and evaluation
- Prediction on test data and submission file generation


## How to Run
Instructions for setting up and running the model in a local environment, including any requirements installation steps and command execution details.

## Evaluation Metrics
The model's performance is evaluated using metrics such as:

- Mean Squared Error (MSE)

- Root Mean Squared Error (RMSE)

- R² Score (coefficient of determination)
