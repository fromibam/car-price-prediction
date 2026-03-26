# car-price-prediction
Predicting car prices based on specifications using Linear Regression — R² of 0.97

## Overview
A machine learning project that predicts car prices based on vehicle specifications using Linear Regression.

## Problem Statement
Car pricing can be inconsistent and hard to estimate. This project builds a predictive model to determine fair market prices based on car specifications.

## Dataset
- Source: [Car Sales Dataset](https://www.kaggle.com/datasets/gagandeep16/car-sales?resource=download)
- Features used: manufacturer, model, sales_in_thousands, year_resale_value, 
  vehicle_type, price_in_thousands, engine_size, horsepower, wheelbase, 
  width, length, curb_weight, fuel_capacity, fuel_efficiency, 
  latest_launch, power_perf_factor
- Target variable: price_in_thousands
  
## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy, Scikit-learn

## Methodology
1. Data Preprocessing & Cleaning
2. Exploratory Data Analysis (EDA)
3. Model Implementation — Linear Regression
4. Model Evaluation

## Results
|   Metric  |  Score  |
|-----------|---------|
|  R² Score |   0.97  |
|    RMSE   |   1.71  |

## How to Run
1. Download the dataset from the Kaggle link above
2. Open `car_price_prediction.ipynb` in Google Colab or Jupyter Notebook
3. Update the file path to match where you saved the dataset
4. Run all cells
