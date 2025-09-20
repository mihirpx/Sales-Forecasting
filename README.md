# Walmart Sales Forecasting

Forecast Walmart weekly sales using ARIMA, Prophet, and LSTM models based on historical data.

## Dataset
[Walmart Dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset)  
*(Replace with exact dataset you used if different)*

## Objective
Predict future weekly sales to help Walmart plan inventory and marketing strategies.

## Features
- Date: week of sale
- Weekly_Sales: total sales for the week
- Additional optional features: store number, department, holidays (if available)

## Models Used
- ARIMA (AutoRegressive Integrated Moving Average)
- Prophet (from Facebook/Meta)
- LSTM (Long Short-Term Memory Neural Network)

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Steps
1. Load and preprocess dataset
2. Aggregate weekly sales
3. Visualize trends in sales
4. Train-test split
5. Apply forecasting models: ARIMA, Prophet, LSTM
6. Evaluate performance and compare models
7. Visualize actual vs predicted sales

## Usage
1. Clone the repository or download the notebook.
2. Install dependencies:
```bash
pip install -r requirements.txt
