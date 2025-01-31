# Dominos - Predictive Purchase Order System

## Project Overview

This project aims to optimize Dominos' ingredient ordering process by leveraging historical sales data to predict future demand. By accurately forecasting sales, we can ensure that the right amount of ingredients is stocked, minimizing waste and preventing stockouts.

## Skills Takeaway

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Time Series Forecasting
- Predictive Modeling
- Business Decision Making
- Real-World Application of Data Science

## Domain

**Food Service Industry**

## Problem Statement

Dominos needs an optimized approach to order ingredients by predicting future sales and generating purchase orders. By forecasting sales accurately, Dominos can:

- Maintain optimal inventory levels.
- Reduce costs related to excess or expired stock.
- Improve business decision-making based on sales trends.
- Optimize the supply chain for efficiency.

## Business Use Cases

- **Inventory Management:** Maintain the right stock levels.
- **Cost Reduction:** Minimize waste and unnecessary expenditures.
- **Sales Forecasting:** Use predictive models to anticipate demand.
- **Supply Chain Optimization:** Ensure smooth and efficient ordering processes.

## Approach

### 1. Data Preprocessing and Exploration

- **Data Cleaning:** Handle missing values, outliers, and formatting issues.
- **Exploratory Data Analysis (EDA):** Analyze sales trends, seasonality, and patterns. Use visualizations to identify key features.

### 2. Sales Prediction

- **Feature Engineering:** Extract meaningful features like day of the week, month, promotional periods, and holidays.
- **Model Selection:** Choose an appropriate forecasting model (ARIMA, SARIMA, Prophet, LSTM, or Regression Model).
- **Model Training:** Train the model using historical sales data.
- **Model Evaluation:** Use Mean Absolute Percentage Error (MAPE) to assess accuracy.

### 3. Purchase Order Generation

- **Sales Forecasting:** Predict pizza sales for the next week.
- **Ingredient Calculation:** Determine ingredient quantities required based on sales predictions and ingredient dataset.
- **Purchase Order Creation:** Generate a detailed order specifying required ingredient quantities.

## Results

- Accurate sales predictions.
- A comprehensive purchase order detailing required ingredients for the forecasted sales period.

## Technical Tags

- **Data Cleaning**
- **EDA**
- **Time Series Forecasting**
- **ARIMA/SARIMA/Prophet/LSTM/Regression Model**
- **Predictive Modeling**
- **Inventory Management**
- **Python, Pandas, Scikit-learn**
- **Matplotlib/Seaborn**

## Datasets

### Dataset Links

- Sales dataset
- Ingredients dataset

### Dataset Explanation

1. **Sales Data**: Historical records including Date, Pizza Type, Quantity Sold, Price, Category, and Ingredients.
2. **Ingredient Data**: Ingredient requirements for each pizza type, including Pizza Type, Ingredient, and Quantity Needed.
