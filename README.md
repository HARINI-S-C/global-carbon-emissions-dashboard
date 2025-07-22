# 🌍 Global Carbon Emissions & Climate Risk Dashboard

An interactive Power BI dashboard visualizing **global CO₂ emissions**, **energy consumption by sector**, and **company sustainability scores**. Built using open datasets from Our World in Data, Kaggle, and CDP, this project provides insights into climate change and environmental risk through data storytelling.

---

## 📚 Table of Contents

- [Project Objectives](#project-objectives)
- [Dashboard Features](#dashboard-features)
- [Tools & Technologies](#tools--technologies)
- [Data Sources](#data-sources)
- [Key Insights](#key-insights)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [How to Run](#how-to-run)
- [About Me](#about-me)

---

## 🎯 Project Objectives

- Track global CO₂ emissions trends over time  
- Visualize emissions by fuel type (coal, oil, gas, cement)  
- Compare countries by total and per capita emissions  
- Showcase corporate sustainability rankings and targets  
- Forecast future emissions based on historical trends

---

## 📊 Dashboard Features

- 🌐 **Global Emissions Timeline** – track CO₂ output by country and year  
- 📈 **Emissions by Sector** – break down by coal, gas, oil, and cement  
- 🗺️ **Interactive Map** – filter by year, region, or emission volume  
- 🏢 **Company Scorecard** – simulated company ESG performance  
- 🔮 **Forecasting Visuals** – project emissions up to 2050 using Power BI

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                  |
|-----------------|-------------------------------------------|
| Power BI        | Data modeling and dashboard creation      |
| Power Query     | Data cleaning and transformation          |
| SQL / Snowflake | Optional backend transformation           |
| GitHub          | Version control and portfolio hosting     |
| CSV             | Dataset storage and loading               |

---

## 📂 Data Sources

- **Our World in Data** – CO₂ and energy data:  
  https://ourworldindata.org/co2-emissions  
  *(Note: Simulated data used for company scores)*

---

## 📈 Key Insights

> _These are sample insights. Replace with actual findings from your dashboard._

- 🌍 CO₂ emissions peaked globally in 2019, then dipped during the COVID-19 pandemic.  
- 🔥 Coal is still the highest-emitting fuel source, especially in emerging economies.  
- 🏭 10 countries are responsible for more than 70% of global emissions.  
- ✅ Some companies have already set net-zero targets for 2030–2040.

---

## 📁 Folder Structure

```bash
global-carbon-dashboard/
├── PowerBI/
│   └── CarbonDashboard.pbix
├── Data/
│   ├── raw/
│   │   └── owid-co2-data.csv
│   └── cleaned/
├── SQL/
│   └── transform_emissions.sql
├── Images/
│   └── dashboard-preview.png
└── README.md

