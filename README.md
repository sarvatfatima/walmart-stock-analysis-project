# 📊 Walmart Stock Data Analysis Using Python

This project involves analyzing historical stock data for **Walmart Inc. (WMT)** using Python. The goal is to clean and explore the dataset, engineer useful features, and extract insights through clear visualizations.

----------

## 🧰 Technologies Used

-   **Python 3**
    
-   **Pandas** for data manipulation
    
-   **Matplotlib & Seaborn** for visualizations
    
-   **Jupyter Notebook** for interactive exploration
    

----------

## 📁 Dataset Information

The dataset contains historical stock data for Walmart.  
Each record includes the following columns:

-   `date`
    
-   `open`, `high`, `low`, `close`, `adj_close`
    
-   `volume`
    

----------

## ✅ Project Workflow

### 1. Data Cleaning

-   Removed missing/null values
    
-   Converted the `date` column to datetime format
    
-   Verified data types and fixed formatting issues
    

### 2. Feature Engineering

-   Calculated **daily returns**
    
-   Created a **daily price range** feature (high - low)
    
-   Computed **30-day and 90-day moving averages**
    
-   Added **rolling volatility** using standard deviation
    

### 3. Visual Analysis & Insights

-   📈 Adjusted Close Price Over Time
    
-   📉 Daily Price Range Trends
    
-   📊 Distribution of Daily Returns
    
-   🔼 Top 5 Gaining Days
    
-   🔽 Top 5 Losing Days
    
-   🔁 Moving Average Crossover (Golden Cross)
    
-   📉 Rolling 30-Day Volatility
    
-   🧪 Correlation Matrix (Open, High, Low, Close, Adj Close, Volume)
    
-   📦 Volume vs Daily Return Scatter Plot
    

----------

## 📌 Limitations

-   Time-based insights like grouping by **month**, **weekday**, or **year** were not included due to formatting issues with the original `date` column.
    

----------

## 📚 Conclusion

This project provides a foundational analysis of Walmart’s historical stock performance using Python. By exploring returns, volatility, and key metrics visually, we gain an understanding of the company’s stock behavior over time.

It’s a great starting point for deeper financial modeling, forecasting, or dashboarding in the future.

----------

## 🚀 Possible Future Enhancements

-   Fix `.dt` conversion issues for time-based groupings
    
-   Add forecasting using ARIMA or Facebook Prophet
    
-   Build an interactive dashboard using Streamlit or Dash
    
-   Compare Walmart with competitors like Target or Costco
    

----------

