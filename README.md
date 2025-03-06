# Walmart Sales Forecasting 🛒📈

## Overview  
This project predicts weekly sales for Walmart stores using historical data and Facebook Prophet. It includes data cleaning, exploratory analysis, time series modeling, and visualization.

## Tools & Libraries  
- Python  
- Pandas  
- Prophet  
- Matplotlib/Plotly  

## Dataset  
Download the [Walmart Dataset from Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting) and save it as `sales_data.csv`.

## Steps  
1. **Data Cleaning**: Handle missing values and convert dates.  
2. **EDA**: Analyze sales trends and holiday impacts.  
3. **Modeling**: Train a Prophet model for 6-month forecasts.  
4. **Evaluation**: Calculate MAE and visualize results.  

## Results  
- Forecasted sales for 26 weeks with 95% confidence intervals.  
- **MAE**: $[Your_MAE_Value]  

![Sales Trend](images/sales_trend.png)  
![Forecast](images/forecast.png)  

## How to Run  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/your-username/Walmart-Sales-Forecasting.git  
