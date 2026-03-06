# car-price-prediction-ml
Car Price Prediction using Linear Regression in Python

# Car Price Prediction using Linear Regression

## Problem Statement
The objective of this project is to predict the price of a car using Machine Learning techniques. The model analyzes different car features such as engine size, mileage, and age to estimate the car price. Linear Regression is used to understand the relationship between these features and the target variable (car price).

---

## Dataset Description
The dataset used in this project is a manually created dataset consisting of **15 records**. It is stored and managed using a **Pandas DataFrame**.

### Features in the Dataset

| Feature Name | Description |
|---------------|-------------|
| Engine_Size | Engine capacity of the car |
| Mileage | Fuel efficiency of the car |
| Age | Age of the car in years |
| Car_Price | Price of the car (Target Variable) |

---

## Data Exploration
The dataset was explored using the following methods:

- Viewing the first and last 5 rows of the dataset
- Checking dataset shape
- Identifying data types
- Checking for missing values

---

## Data Visualization
To understand the data distribution and relationships, the following visualizations were created:

- Scatter Plot – Relationship between engine size and car price
- Histogram – Distribution of car prices
- Boxplot – Identifying price spread and possible outliers

---

## Model Used
A **Linear Regression model** from the **Scikit-learn** library was used for predicting car prices.

Steps performed:
1. Selected input features and target variable
2. Split dataset into **training and testing sets**
3. Trained the Linear Regression model
4. Generated predictions
5. Evaluated model performance

---

## Evaluation Metrics
The model performance was evaluated using:

- **MAE (Mean Absolute Error)** – Measures the average prediction error
- **R² Score** – Measures how well the model explains the variance in the data

---

## Results
The trained model was able to predict car prices based on the input features.  
Feature experiments were also performed by removing and adding features to observe the impact on model performance.

---

## Conclusion
This project demonstrates how Linear Regression can be applied to predict car prices using basic features such as engine size, mileage, and age. Proper data exploration, visualization, and feature selection help improve model performance and provide better predictions.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
