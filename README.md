# Car Price Prediction Model
This repository contains a machine learning model that predicts car prices based on various features such as the car's age, mileage, fuel type, and more.

## Overview
The project uses a dataset containing details about different cars, including their selling prices. The goal is to build a model that can accurately predict the selling price of a car given its features. Various preprocessing techniques were applied to the data, and multiple algorithms, including Linear Regression, Decision Trees, Random Forest, and XGBoost, were evaluated.

## Dataset
The data was taken from here: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

## Features
The dataset contains the following features:

- name: The brand and model of the car.
- year: The year the car was manufactured.
- km_driven: The total kilometers driven by the car.
- fuel: Type of fuel the car uses (e.g., Petrol, Diesel).
- seller_type: Type of seller (e.g., Dealer, Individual).
- transmission: Type of transmission (e.g., Manual, Automatic).
- owner: Ownership details (e.g., First Owner, Second Owner).
- mileage: The mileage of the car.
- engine: Engine capacity.
- max_power: Maximum power of the car.
- seats: Number of seats in the car.
- age: Age of the car (derived from the year).
- Setup and Installation

## Algorithms Evaluated
- Linear Regression
- Decision Trees
- Random Forest
- XGBoost
Hyperparameter tuning was performed for Random Forest and XGBoost to optimize their performance.

## Results
The Random Forest model, after hyperparameter tuning, provided the best performance with a Root Mean Squared Error (RMSE) of approximately 173,697 on the validation set.
