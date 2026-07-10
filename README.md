# 📈 Demand Forecasting Using ARIMA

## 📌 Project Overview
This project focuses on forecasting future sales using Time Series Analysis with the ARIMA model. The goal is to analyze historical sales data, identify trends, and predict future demand to support better business planning and inventory management.


## 🎯 Problem Statement
Businesses need accurate demand forecasting to optimize inventory, reduce stock shortages, and improve operational efficiency. This project builds a forecasting model using historical sales data.


## 📂 Dataset
- Daily Sales Dataset
- Features:
  - Date
  - Store
  - Item
  - Sales

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Google Colab

## 📊 Exploratory Data Analysis
- Data Inspection
- Date Conversion
- Feature Engineering
- Monthly Sales Analysis
- Store-wise Sales Analysis
- Top Selling Items Analysis

## 🤖 Model Used
- ARIMA (5,1,0)

## 📈 Model Evaluation

MAE: 5356.52

RMSE: 6117.13

## 📊 Visualizations
- Average Monthly Sales
- Average Sales by Store
- Top Selling Items
- Actual vs Predicted Sales

## 💡 Business Insights
- Sales show clear seasonal patterns.
- Store performance varies significantly.
- Some products consistently outperform others.
- ARIMA provides a baseline forecast but struggles with seasonal fluctuations.
- Advanced models like SARIMA or Prophet may improve forecasting accuracy.

-Demand-Forecasting-ARIMA/
│
├── data/
│   ├── train.csv
│
├── images/
│   ├── monthly_sales.png
│   ├── store_sales.png
│   ├── top_items.png
│   ├── actual_vs_predicted.png
│
├── notebook/
│   ├── Demand_Forecasting_ARIMA.ipynb
│
├── README.md
│
├── requirements.txt
│
└── LICENSE

## 🚀 Future Improvements
- Implement SARIMA
- Use Facebook Prophet
- Hyperparameter Tuning
- Deploy using Streamlit

## 👩‍💻 Author

Sushmita Poddar

Aspiring Data Scientist
