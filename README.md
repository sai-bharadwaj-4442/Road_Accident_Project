# 🚦 Road Accident Analysis Dashboard | Python + Pandas + Power BI

## 📌 Project Overview

Road accidents remain one of the leading causes of injuries and fatalities. Understanding when, where, and why accidents occur helps authorities make better decisions to improve road safety.

This project demonstrates an end-to-end Data Analytics workflow, starting from cleaning a messy dataset using **Python (Pandas)** and building an interactive dashboard in **Power BI** to uncover meaningful insights.

---

## 🎯 Business Problem

Traffic departments and policymakers need data-driven insights to answer questions such as:

- Which states report the highest accident severity?
- Which weather conditions contribute to more accidents?
- Which time period experiences the highest casualties?
- How do road types affect accident severity?
- Which locations require immediate safety improvements?

This dashboard helps answer these questions through interactive visualizations.

---

# 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Power BI
- Git & GitHub

---

# 📂 Project Workflow

```
Messy Dataset
      │
      ▼
Python Data Cleaning (Pandas)
      │
      ▼
Cleaned Dataset
      │
      ▼
Power BI Data Modeling
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
```

---

# 🧹 Data Cleaning Using Pandas

The raw dataset contained several data quality issues.

### Cleaning steps performed:

- Removed duplicate records
- Handled missing values
- Standardized text values
- Converted date columns into proper datetime format
- Extracted Hour from Time
- Created Time Period (Morning, Afternoon, Evening, Night)
- Corrected inconsistent categorical values
- Cleaned Weather column
- Cleaned Road Type column
- Corrected Severity values
- Verified data types
- Exported cleaned dataset for Power BI

---

# 📊 Dashboard Pages

## 📌 Page 1 — Executive Overview

Shows high-level KPIs including:

- Total Accidents
- Average Severity
- Total Casualties

Visuals:

- Average Severity by State
- Vehicles Involved by Weather

---

## 📌 Page 2 — Accident Analysis

Visuals include:

- Vehicles Involved vs Casualties by State
- Severity by Time Period
- Average Severity by Road Type

---

## 📌 Page 3 — Geographic & Time Analysis

Visuals include:

- Accident Map
- Casualties by Time Period
- Vehicles Involved by Month

---

# 📈 Key Insights

- Certain states consistently report higher accident severity.
- Weather conditions significantly influence accident frequency.
- Night-time records the highest casualty count.
- Accident severity varies across different road types.
- Monthly trends reveal seasonal fluctuations in vehicle involvement.

---

# 📁 Repository Structure

```
Road-Accident-Analysis/
│
├── Data/
│   ├── india_road_accident_messy_dataset.csv
│   └── cleaned_accidents.csv
│
├── Power BI/
│   └── Road_Accident_Analysis.pbix
│
├── Dashboard Images/
│   ├── Overview.png
│   ├── Analysis.png
│   └── Map.png
│
├── Python/
│   └── Data_Cleaning.ipynb
│
└── README.md
```

---

# 📷 Dashboard Preview

## Executive Overview

(Add Screenshot Here)

---

## Accident Analysis

(Add Screenshot Here)

---

## Geographic Analysis

(Add Screenshot Here)

---

# 📌 Skills Demonstrated

✔ Data Cleaning

✔ Data Wrangling

✔ Feature Engineering

✔ Data Visualization

✔ Dashboard Design

✔ Business Intelligence

✔ Exploratory Data Analysis

✔ Power BI

✔ Pandas

✔ GitHub Documentation

---

# 📚 Dataset

The dataset contains road accident records including:

- State
- City
- Weather
- Road Type
- Time
- Vehicles Involved
- Casualties
- Severity
- Latitude
- Longitude

---

# 🚀 Future Improvements

- Accident hotspot detection using clustering
- Predict accident severity using Machine Learning
- Build a Streamlit web application
- Real-time dashboard using SQL database
- Automated ETL pipeline

---

# 👨‍💻 Author

**Sai Durga Bharadwaj**

Data Analyst | Python | SQL | Power BI | Excel

GitHub: https://github.com/YourGitHubUsername

LinkedIn: https://linkedin.com/in/YourLinkedInProfile
