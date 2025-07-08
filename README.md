# 🚗 Road Accident Analysis IN 2021 TO 2022 AT UK Using Power BI 

This repository contains a data analysis project that focuses on visualizing and deriving insights from historical road accident data for the years **2021 and 2022**. The analysis was performed using **Microsoft Power BI**, with data preprocessing handled via **Power Query**, and advanced measures created using **DAX (Data Analysis Expressions)**.

## 📊 Objective

To create an **interactive dashboard** that:
- Visualizes accident trends
- Provides year-on-year comparisons
- Highlights critical patterns like:
  - Accident severity (Fatal, Serious, Slight)
  - Road conditions
  - Light & weather conditions
  - Vehicle types involved
  - Urban vs Rural zones

## 🧰 Tools & Technologies

- **Power BI** (Visualization & Dashboard Building)
- **Power Query** (Data Cleaning & Transformation)
- **DAX** (KPIs, YoY Growth, Time Intelligence)
- **Excel** (Raw Data Source)

## 🛠️ Features

- **Data Cleaning**: Fixed typos (e.g., `fetal` → `fatal`), removed duplicates, handled nulls.
- **Grouping**: Simplified vehicle types, light conditions, and junction details for clear visuals.
- **Calendar Table**: Created using DAX `CALENDAR()` function for time-based filtering.
- **Time Intelligence**: Implemented `YoY`, `CY vs PY`, and `YTD` comparisons using DAX.
- **KPI Cards**: Show total casualties, fatalities, serious/slight injuries, and accident counts.
- **Slicers & Filters**: Drill down by year, district, severity, road type, etc.
- **Interactive Visuals**: Pie charts, bar graphs, time-series charts, and maps.

## 📈 Key Insights

- Casualties peaked in specific months during night-time under poor weather conditions.
- **Urban areas** showed a higher number of slight injuries.
- **Fatalities were more common** on single carriageways and in rural areas.
- Two-wheeler vehicles had the **highest involvement rate** in serious and fatal accidents.

## 👥 Stakeholders

- Ministry of Transport
- Traffic Police
- Emergency Response Teams
- Urban Planners
- Public Safety Officials

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Road-Accident-Analysis.git
