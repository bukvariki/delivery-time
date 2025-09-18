# Delivery Time Prediction

This project predicts **food delivery time** based on order and courier features using machine learning (Linear Regression).

## Project Overview
The dataset comes from food delivery services and contains information about couriers, orders, and distances.  
The goal is to build a regression model that estimates the **delivery time (in minutes)**.

The workflow includes:
1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature scaling
4. Model training (Linear Regression)
5. Model evaluation (Mean Absolute Error)

## Dataset

The dataset `delivery-time.csv` contains the following columns:

- `ID` – unique order ID  
- `Delivery_person_ID` – courier ID  
- `Delivery_person_Age` – courier’s age  
- `Delivery_person_Ratings` – courier’s rating  
- `distance_meters` – distance between restaurant and customer (in meters)  
- `order_Drinks`, `order_Meal`, `order_Snack` – ordered product categories  
- `vehicle_electric_scooter`, `vehicle_motorcycle`, `vehicle_scooter` – delivery vehicle type (encoded)  
- `Time_taken_min` – target variable, delivery time in minutes  
