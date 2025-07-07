# 🛍️ Retail Demand Forecasting – Superstore Sales

This project demonstrates a complete data science workflow to **forecast retail demand** using historical sales data from a Superstore.

## 🔍 Objective
To build a supervised machine learning model that predicts future sales trends based on historical patterns across time, category, region, and customer behaviour.

---

## 📁 Dataset Overview
- **Source**: Superstore Sales Dataset (9,800 rows)
- **Features**:
  - `Order Date`, `Ship Date`, `Sales`, `Category`, `Sub-Category`
  - `Customer`, `Region`, `Ship Mode`, `Product`, `City`, `State`
- **Target**: `Sales` (continuous)

---

## 🔧 Key Components
- Data Cleaning & EDA
- Feature Engineering (lag features, date parts)
- Model Training: XGBoost, ARIMA (optional), Random Forest
- Evaluation: RMSE, MAE
- Time Series Visualisation
- Optional: Customer Segmentation using Clustering

---

## 📦 Tools & Libraries
- Python: Pandas, NumPy, Matplotlib, Seaborn
- ML: scikit-learn, XGBoost, Statsmodels
- Optional Dashboard: Streamlit or Power BI

---

## 💼 Use Cases
- Job Applications (Data Scientist, Analyst)
- PhD Research Portfolios
- Freelance Client Showcases (Retail, E-commerce)

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook retail_demand_forecasting.ipynb
