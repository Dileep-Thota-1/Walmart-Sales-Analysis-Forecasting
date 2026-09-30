# Walmart-Sales-Analysis-Forecasting-Capstone-Project

# 📊 Retail Intelligence from Data: Walmart Weekly Sales Analysis and Forecasting

## 📁 Project Overview
This capstone project focuses on analyzing and forecasting Walmart's weekly sales to derive actionable business insights. The goal is to help improve inventory management by understanding sales trends, seasonality, and the impact of economic factors.

## 🎯 Objectives
- Clean and preprocess weekly sales data from 45 Walmart stores.
- Perform exploratory data analysis to uncover trends and patterns.
- Model and forecast future sales using SARIMA and machine learning.
- Provide business recommendations based on insights.

## 🧾 Dataset
**Source:** Provided `walmart.csv`  
**Rows:** 6,435  
**Columns:** 8  

| Column          | Description                                      |
|-----------------|--------------------------------------------------|
| Store           | Store number (1–45)                              |
| Date            | Week of sales                                    |
| Weekly_Sales    | Sales for that store in that week                |
| Holiday_Flag    | Indicates if the week is a holiday (1 or 0)      |
| Temperature     | In Fahrenheit                                    |
| Fuel_Price      | Fuel cost in the region                          |
| CPI             | Consumer Price Index                             |
| Unemployment    | Unemployment rate in the area                    |

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Statsmodels (SARIMA modeling)
- Scikit-learn (Random Forest)
- Google Colab (Notebook execution)
- Streamlit (Optional for dashboard)
- GitHub (Version control)

## 📊 Exploratory Data Analysis (EDA)
- Time series trend of total weekly sales
- Correlation between sales and:
  - Temperature
  - Fuel Price
  - CPI
  - Unemployment
- Top & bottom performing stores
- Holiday vs Non-holiday sales comparison

## 🔮 Forecasting Techniques
- **SARIMA Model**: For capturing seasonality and trends.
- **Random Forest Regressor**: For multivariate regression using economic indicators.
- Evaluation Metrics: MAE, RMSE

## 📈 Business Insights
- Seasonality is evident, especially in November–December.
- CPI and Unemployment affect some stores more than others.
- Certain stores underperform and need attention (e.g., Store 20).
- Holidays boost sales significantly.

## ✅ Project Deliverables
- 📄 Final report: `Walmart_Capstone_Final_Report.docx`
- 📊 Google Colab notebook: Full EDA + Forecasting code
- 📂 Cleaned dataset: `Walmart_Cleaned.csv`
- 🖥️ (Optional) Streamlit Dashboard

## 💼 Recommendations
- Optimize inventory ahead of high-sales months.
- Investigate and support underperforming stores.
- Monitor economic indicators to anticipate changes in demand.
