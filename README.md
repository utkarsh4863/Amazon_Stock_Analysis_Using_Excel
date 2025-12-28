# 📊 Amazon Stock Analysis Dashboard (Excel)

A polished, interactive Excel dashboard for exploring historical Amazon (AMZN) stock data (OHLCV). This workbook uses PivotTables, PivotCharts and slicers to let you quickly analyze price behavior, volume patterns, and time-based trends.

---

## 🔍 Project Overview
This project provides an easy-to-use Excel dashboard that helps you:
- Visualize price trends (Open, High, Low, Close, Adjusted Close)
- Analyze trading volume by day/month/year
- Compare day-wise and month-wise performance
- Explore yearly trends using Adjusted Close for long-term analysis

---

## 🛠 Tools & Technologies
- Microsoft Excel (2016 / 2019 / 365 recommended)
- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- Conditional Formatting
- Calculated columns for derived time fields

---

## 📂 Dataset
Source file: `AMZN_Data.xlsx`

Core columns:
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

Derived columns included in the workbook:

- Day Name (e.g., Monday)
- Month (name)
- Year

---

## 📊 Dashboard Features

### KPI Metrics
- Average Open, High, Low, Close
- Quick snapshot KPIs via PivotCards / formatted cells

### Visualizations
- Volume Over Time (day / month)
- Open vs Close comparison (day-wise)
- High vs Low (daily volatility)
- Monthly average Adjusted Close
- Yearly Adjusted Close trend

### Interactivity
- Slicers for Year, Month, Day of Week
- All charts and pivot outputs update dynamically with slicers

---

## 📈 Key Insights
- Adjusted Close is used for accurate long-term trend comparisons.
- Significant price movements often coincide with high volume days.
- Weekday patterns reveal differences in volatility and average returns.
- Clear multi-year upward trend in Adjusted Close (depending on dataset timeframe).

---

## 📸 Dashboard Screenshot

Below is a preview of the **Amazon Stock Analysis Excel Dashboard**, showcasing interactive KPIs, charts, and slicers for stock price and volume analysis.

![Amazon Stock Analysis Dashboard](https://raw.githubusercontent.com/utkarsh4863/Amazon_Stock_Analysis_Using_Excel/main/Screenshot.png)


---

## 🚀 How to use
1. Download `AMZN_Data.xlsx` from this repo.
2. Open in Microsoft Excel (2016/2019/365 recommended).
3. Enable editing if prompted.
4. Use the slicers (Year, Month, Day) to filter the dashboard.
5. Explore charts and pivot tables; modify or extend pivot fields as needed.

---

## ✅ Tips & Best Practices
- Refresh pivots if you replace or update the data (Right-click → Refresh).
- Keep the date column formatted as Date for correct grouping.
- If adding more historical data, append rows to the data table (not outside it) and refresh.

---

## 🧠 Learnings & Use Cases
- Useful for exploratory financial analysis and teaching Pivot-based dashboards.
- Can be adapted for other tickers by replacing the data file.
- Great for quick visual checks before deeper statistical or algorithmic analysis.

---


## 👤 Author
Utkarsh (GitHub: [@utkarsh4863](https://github.com/utkarsh4863))





