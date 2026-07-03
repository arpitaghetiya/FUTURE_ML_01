# 📊 Sales & Demand Forecasting

**Future Interns – Machine Learning Internship (Task 1)**

## 📌 Overview
This project builds a sales forecasting model using historical retail sales data (2014–2018). It predicts future monthly sales using Linear Regression, helping businesses plan inventory, cash flow, and staffing.

## 🔍 Dataset
Superstore Sales Dataset (Kaggle) — retail transaction data including order dates, sales, and product details.

## 🛠️ Approach
1. Cleaned and prepared historical sales data
2. Aggregated daily transactions into monthly sales totals
3. Engineered time-based features (month number, calendar month for seasonality)
4. Trained a Linear Regression model to learn the sales trend
5. Forecasted sales for the next 6 months
6. Evaluated model accuracy (MAE, RMSE)
7. Analyzed seasonal patterns across calendar months
8. Visualized actual vs predicted sales

## 📈 Results
- Clear upward sales trend identified from 2014–2018
- Forecasted approx. \$74,500/month sales by month 54
- Mean Absolute Error (MAE): approx. \$17,458
- Strong seasonality: Q4 (Sep–Dec) shows peak sales, especially November (~\$88K avg); February is the slowest month (~\$15K avg)

## 💡 Business Value
This forecast helps businesses:
- Plan inventory ahead of seasonal demand
- Anticipate cash flow across quarters
- Schedule staffing during high-demand periods

## 🧰 Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Google Colab

## 📂 Files
- `Sales_Forecasting_Task1.ipynb` — Full notebook with code, visualizations, and analysis
