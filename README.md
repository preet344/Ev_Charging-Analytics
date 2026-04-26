# ⚡ EV Charging Station Utilization Analysis  
### SQL ETL | Excel Hypothesis Testing | Power BI Dashboard  

---

## 📌 Project Overview  

This project analyzes EV charging station utilization using a time-series dataset to uncover patterns in demand, station performance, and external influencing factors such as weather and pricing.

The project follows a complete data analytics pipeline:

- SQL-based ETL & Data Cleaning  
- Excel-based Exploratory Data Analysis (EDA)  
- Hypothesis Testing using Excel  
- Interactive Dashboard using Power BI  

---

## 📊 Dataset Information  

- **Dataset Name:** EV Charging Station Availability (Time Series)  
- **Time Period:** July – December 2025  
- **Frequency:** 30-minute intervals  

### Coverage:
- 150 Charging Stations  
- 15 Cities  
- 8 Networks  

### 🔑 Key Features:
- Station Info: station_id, network, city, charger_type  
- Utilization Metrics: ports_available, utilization_rate, wait_time  
- Time Features: timestamp, hour_of_day, day_of_week, is_peak_hour  
- Pricing: current_price, pricing_type  
- External Factors: weather, traffic, gas prices  

---

## 🎯 Project Objectives  

- Identify peak demand patterns  
- Analyze utilization trends  
- Evaluate impact of pricing & external factors  
- Perform hypothesis testing using Excel  
- Build an interactive dashboard  

---

## 🛠 Tech Stack  

- **SQL (PostgreSQL / Colab)** → ETL & Data Cleaning  
- **Microsoft Excel** → EDA + Hypothesis Testing  
- **Power BI** → Dashboard & Visualization  

---

## 🔄 Project Workflow  

### 🔹 1. SQL-Based ETL & Data Cleaning  

- Removed duplicates  
- Handled missing values  
- Standardized timestamps  
- Ensured consistent 30-min intervals  
- Created new features:
  - Peak hour flag  
  - Utilization categories  
  - Time-based aggregations  

📌 Output: Cleaned dataset  

---

### 🔹 2. Exploratory Data Analysis (Excel)  

- Pivot Tables  
- Time-series charts  
- Utilization heatmaps  
- City & network comparison  

📊 Focus:
- Hourly trends  
- Peak vs non-peak usage  
- Charger performance  

---

### 🔹 3. Hypothesis Testing (Excel)  

Performed using Excel functions and Data Analysis ToolPak.

#### Hypotheses:
1. Peak-hour utilization is higher on weekdays  
2. Weather affects utilization  
3. Dynamic pricing reduces wait time  

#### Methods:
- T-Test  
- ANOVA  
- Correlation  

#### Output:
- P-values  
- Test statistics  
- Decision (Reject / Fail to Reject H₀)  

---

## 📊 Power BI Dashboard  

Includes:

- Utilization trends  
- Peak hour heatmaps  
- City & network performance  
- Pricing analysis  
- Weather impact  

---

## 📂 Project Structure  

```

EV_Charging_Analysis/
│── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│── sql/
│   └── etl_queries.sql
│── excel/
│   ├── eda_analysis.xlsx
│   └── hypothesis_testing.xlsx
│── dashboard/
│   └── powerbi_dashboard.pbix
│── images/
│   └── dashboard.png
│── README.md

```

---

## 📌 Key Insights  

- Peak demand occurs in evening hours  
- Urban stations have higher utilization  
- Fast chargers are preferred  
- Weather has moderate impact  
- Pricing affects wait time  

---

## 💡 Business Recommendations  

- Expand high-demand locations  
- Optimize pricing during peak hours  
- Improve availability tracking  
- Increase fast chargers  
- Use external data for forecasting  

---

## 🚀 How to Use  

1. Run SQL queries  
2. Open Excel files for analysis  
3. Load data into Power BI  
4. Explore dashboard  

---

## 📎 Deliverables  

- SQL ETL Queries  
- Cleaned Dataset  
- Excel EDA File  
- Excel Hypothesis Testing File  
- Power BI Dashboard  
- Insights Summary  

---

## 🔮 Future Scope  

- Real-time analytics  
- Machine learning prediction  
- Smart charging optimization  

---

## 📜 License  

MIT License  

---

## ⭐ Author  

**Preet Tyagi**  
Data Analyst | SQL | Power BI | Excel  

---
