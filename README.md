# 🚗 Uber Trip Analysis Dashboard


**Author:** Reem Saeed Metwally  
**Tools Used:** Power BI, Power Query  
**Dataset:** [Kaggle – Uber Data 2016](https://www.kaggle.com/datasets/bhanupratapbiswas/uber-data-analysis)

---

## 📊 Project Summary

This dashboard project presents an exploratory data analysis of Uber ride data for 2016 using **Power BI**. It tracks core KPIs like **Total Bookings**, **Trip Distance**, and **Trip Purpose** across time, location, and category dimensions.

---

### 🔧 Objectives
- Understand user behavior trends across time and geography.
- Reveal business insights to support decisions in operations and marketing.
- Identify peak usage windows and key business trip patterns.

---

## 📁 Data Cleaning & Transformation (ETL)

Performed in **Power Query**:

- ✅ Removed duplicates and corrected data types (`START_DATE`, `MILES`)
- 🧩 Handled 49% missing values in `Purpose` column using fill-down
- 📆 Extracted year, month, weekday, hour, time-of-day categories
- 🔄 Converted trip distances to kilometers
- ⏱️ Calculated trip duration

---

## 📈 Key Metrics

| Metric                   | Value           |
|--------------------------|------------------|
| Total Bookings           | 1,150            |
| Total Trip Distance      | 19,626 km        |
| Avg Trip Distance        | 17.01 km         |
| Farthest Trip            | 499.4 km         |
| Avg Trip Duration        | 23.24 minutes    |

---

## 📌 Dashboard Highlights

### 🕒 Time-Based Trends
- Most trips occur between **9 AM–5 PM**
- **Fridays** are the busiest day; **December** has highest monthly bookings
- Distance spikes near the **25th of each month**

### 🧭 Location Patterns
- Most pickups & drop-offs happen in **Cary**, **Morrisville**, and **Whitebridge**
- These business hubs dominate trip volume and distance

### 🎯 Purpose Analysis
- **93%** of trips are **Business**
- Top purposes: **Meetings**, **Meal/Entertainment**, **Site Visits**

---

## 💡 Recommendations

1. Prioritize driver allocation during **weekday business hours**
2. Target **Cary, Morrisville, Whitebridge** for supply-demand balance
3. Create **purpose-based ride plans** (e.g., “Meeting Rides”)
4. Run seasonal campaigns in **September & May**
5. Promote personal rides to diversify trip categories

---

## 📌 Report & Portfolio

📎 [Full Report (PDF)](https://github.com/ReemSaeedMetwally/Uber_Data_Analysis_Dashboard/blob/main/Uber%20Data%20Analysis%20Report.pdf)  
📊 [Portfolio](https://github.com/ReemSaeedMetwally)  
🔗 [LinkedIn](https://www.linkedin.com/in/reem-saeed-b34b00216/)

---

## 🖼️ Dashboard Preview

> *(Add screenshots of your Power BI dashboard here — overview, time analysis, etc.)*
