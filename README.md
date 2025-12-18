# 🦠 COVID-19 Analytics Dashboard (Power BI / Excel)

An end-to-end **COVID-19 Analytics project** built using **Excel and Power BI**, focused on analyzing **global trends, India-specific insights, vaccination progress, monthly comparisons, and economic impact**.

This project demonstrates real-world **data cleaning, data modeling, DAX, dashboard design, and analytical storytelling** skills.

---

## 🎯 Project Objectives

- Analyze **global and India-level COVID-19 spread**
- Track **daily and monthly confirmed, recovered, and death cases**
- Analyze **vaccination progress** at country and state level
- Compare **monthly global vs country-wise trends**
- Understand **economic impact (GDP loss)** due to COVID-19
- Build an **interactive, insight-driven Power BI dashboard**

---

## 🧰 Tools & Technologies Used

- **Power BI Desktop**
  - DAX measures
  - KPI cards & interactive visuals
  - Data modeling (fact & dimension tables)
  - Time-based analysis (daily, monthly)

- **Microsoft Excel**
  - Data cleaning & preprocessing
  - Column standardization
  - Date formatting & validation
  - Data consistency checks

- **Git & GitHub**
  - Version control
  - Project documentation
  - Portfolio showcase

---

## 📂 Project Folder Structure

```text
Covid-19-Analytics/
│
├── data/
│   ├── raw/
│   │   ├── Country_wise_daily_new_cases.csv
│   │   ├── covid_19_india_daily_new_cases.csv
│   │   ├── covid_19_india_daily_new_Test_cases.csv
│   │   ├── covid_vaccine_statewise_daily_new_selected.csv
│   │   ├── india_gdp_loss_covid_simulated.csv
│   │
│   ├── processed/
│   │   ├── covid_19_india_monthly_report.csv
│   │   ├── monthly_new_by_country.csv
│
├── PowerBI/
│   ├── Covid_19_Analytics.pbix
│
├── docs/
│   ├── screenshots/
│   │   ├── global_overview.png
│   │   ├── india_overview.png
│   │   ├── vaccination_analysis.png
│   │   ├── monthly_overview.png
│   │   ├── economic_impact.png
│   │
│   ├── data_dictionary.md
│   ├── project_report.md
│
├── README.md
├── LICENSE
├── .gitignore
```

---

## 📊 Dashboard Pages Overview

### 1️⃣ Global Overview
- Total Confirmed, Recovered, Deaths, Active Cases
- Top 10 countries by confirmed cases and deaths
- Global daily trends
- Interactive slicers: **Country, Year, Month**

### 🌍 Global Overview
![Global Overview](docs/screenshots/global_overview.png)

### 2️⃣ Indian Overview
- India-specific KPIs
- State/UT-wise confirmed and death analysis
- Daily COVID trends for India

### 🇮🇳 India Overview
![India Overview](docs/screenshots/india_overview.png)

### 3️⃣ Vaccination Analysis
- Daily and weekly vaccination trends
- Total doses by state
- Vaccination intensity map
- Dose-level insights (Dose 1, Dose 2, Booster)

### 💉 Vaccination Analysis
![Vaccination Analysis](docs/screenshots/vaccination_analysis.png)

### 4️⃣ Monthly Overview
- Monthly confirmed, recovered, and deaths (Global)
- Top country by monthly confirmed cases
- Country ranking by cases
- Monthly comparison visuals

### 📅 Monthly Global & Country Comparison
![Monthly Comparison](docs/screenshots/monthly_comparison.png)

---

## 📘 Data Dictionary
A detailed **Data Dictionary** is maintained to explain each dataset and column used in the project.

📄 Location:  
👉 [View Data Dictionary](docs/Data_Dictionary.md)

```text
## 📁 Dataset Details
- Global daily COVID-19 cases
- India state-wise daily cases
- Vaccination state-wise data
- Simulated GDP impact data
 
## 📌 Key Learnings
- Dynamic KPIs with time intelligence
- Custom slicers (Year, Month, Country, State, Dose Type)
- Global vs Country comparison
- Weekly and monthly trend analysis
- Clean star-schema data model
- Real-world data cleaning using Excel
- Designing scalable Power BI data models
- Writing accurate and optimized DAX measures
- Handling daily vs monthly time intelligence
- Creating KPI-driven dashboards
- Translating data into actionable insights

## 🔮 Future Enhancements
- Live data integration using APIs
- Predictive analytics for future outbreak trends
- Healthcare infrastructure analysis
- Power BI Service deployment & automation

## 📷 Dashboard Preview
Screenshots are available in the `docs/screenshots` folder.

## 🚀 How to Use
1. Download the `.pbix` file from the PowerBI folder
2. Open in Power BI Desktop
3. Refresh data (if source paths are updated)

## 📈 Future Scope
- Real-time data integration
- Predictive modeling
- Automated refresh pipelines

## 🙌 Acknowledgements
This project is dedicated to healthcare workers and researchers worldwide.
```
📜 License
This project is licensed under the **MIT License**.
👉 [View License](./LICENSE)

```text
👤 Author : Yashodip Kamble
Data Analytics & Power BI Enthusiast
📌 This project framework can be reused in the future to quickly analyze and respond to similar pandemic or public health crises.
```