
# 📊 Walmart Sales Forecasting Using Machine Learning

## 🧠 Objective
The goal of this project is to **predict weekly sales** for Walmart stores using historical data, economic indicators, and promotional markdowns. This helps Walmart:
- Optimize inventory management  
- Plan better promotional strategies  
- Forecast sales especially around **key holidays**

---

## 📁 Dataset Information

The project uses three main datasets:

- **`train.csv`**: Weekly sales for each department in each store  
- **`features.csv`**: External data like fuel prices, CPI, unemployment, markdowns, and holiday indicators  
- **`stores.csv`**: Information about store size and type

**Total records**: ~4.2 million rows  
**Date range**: 2010 – 2012  

---

## 🧹 Data Cleaning & Preparation

- ✅ Merged datasets using `Store` and `Date`  
- ✅ Converted `Date` column to datetime format  
- ✅ Handled missing values (especially in `MarkDown` columns)  
- ✅ Feature engineered new columns: `Year`, `Month`, `Week`  
- ✅ Applied One-Hot Encoding to categorical features (e.g., `Store Type`)  

---

## 📊 Exploratory Data Analysis (EDA)

Visual insights include:
- 📈 Sales trend over time  
- 🏬 Sales comparison by **store type**  
- 🎉 Holiday impact on sales  
- 🔥 Correlation heatmap of economic indicators  

---

## 🧠 Model Building

Built a **Linear Regression** model to predict weekly sales.

### Features Used:
- Store Type and Size
- Holiday indicator (`IsHoliday`)
- MarkDown1 to MarkDown5
- Temperature, CPI, Unemployment

### Target Variable:
- Weekly_Sales

---

## 📈 Evaluation Metric

Used Root Mean Squared Error (RMSE) to evaluate the model's performance on the test set.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Walmart-Sales-Forecasting/
├── data/
│   ├── train.csv
│   ├── features.csv
│   └── stores.csv
│
├── notebook/
│   └── walmart_sales_forecast.ipynb
│
├── README.md
```

---

## ✅ Comparison

- Random Forest/XGBoost model for performance comparison


---

## 🙌 Author

**Raghav Jha**  
Aspiring Data Analyst | Python • SQL • Power BI  
📧 raghavjha1810@gmail.com | 🔗 www.linkedin.com/in/raghav-jha-7114b0337

---
