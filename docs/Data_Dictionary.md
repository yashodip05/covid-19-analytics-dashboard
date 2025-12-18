\# 📘 Data Dictionary – COVID-19 Analytics Project



This document describes the datasets used in the \*\*COVID-19 Analytics Dashboard\*\*, including column definitions and business meaning.



---



\## 1️⃣ Dataset: Country\_wise\_daily\_new\_cases.csv



\*\*Description:\*\*  

Daily COVID-19 statistics for countries worldwide.



| Column Name       | Data Type | Description |

|------------------|----------|-------------|

| Date             | Date     | Reporting date |

| Country          | Text     | Country name |

| Confirmed        | Number   | Cumulative confirmed cases till date |

| Deaths           | Number   | Cumulative deaths till date |

| Recovered        | Number   | Cumulative recovered cases |

| New\_Confirmed    | Number   | New confirmed cases reported on the day |

| New\_Deaths       | Number   | New deaths reported on the day |

| New\_Recovered    | Number   | New recoveries reported on the day |



---



\## 2️⃣ Dataset: covid\_19\_india\_daily\_new\_cases.csv



\*\*Description:\*\*  

Daily COVID-19 case data specific to India at State/UT level.



| Column Name           | Data Type | Description |

|----------------------|----------|-------------|

| Date                 | Date     | Reporting date |

| Date\_Actual          | Date     | Actual calendar date |

| State/UnionTerritory | Text     | Indian State or Union Territory |

| Confirmed            | Number   | Cumulative confirmed cases |

| Deaths               | Number   | Cumulative deaths |

| Recovered            | Number   | Cumulative recovered cases |

| New\_Confirmed        | Number   | Daily new confirmed cases |

| New\_Deaths           | Number   | Daily new deaths |

| New\_Recovered        | Number   | Daily new recoveries |



---



\## 3️⃣ Dataset: covid\_19\_india\_daily\_new\_Test\_cases.csv



\*\*Description:\*\*  

Daily COVID-19 testing data for India.



| Column Name   | Data Type | Description |

|--------------|----------|-------------|

| Date         | Date     | Testing date |

| State/UT     | Text     | State or Union Territory |

| Total\_Tests  | Number   | Total tests conducted till date |

| New\_Tests    | Number   | New tests conducted on the day |



---



\## 4️⃣ Dataset: covid\_19\_india\_monthly\_Report.csv



\*\*Description:\*\*  

Monthly aggregated COVID-19 statistics for India.



| Column Name      | Data Type | Description |

|-----------------|----------|-------------|

| Year            | Number   | Year of record |

| Month           | Text     | Month name |

| MonthStartDate  | Date     | Start date of the month |

| Total\_Confirmed | Number   | Total confirmed cases for the month |

| Total\_Deaths    | Number   | Total deaths for the month |

| Total\_Recovered | Number   | Total recoveries for the month |



---



\## 5️⃣ Dataset: monthly\_new\_by\_country.csv



\*\*Description:\*\*  

Monthly aggregated COVID-19 data by country.



| Column Name     | Data Type | Description |

|----------------|----------|-------------|

| Country        | Text     | Country name |

| Year           | Number   | Year |

| Month          | Text     | Month |

| MonthStartDate | Date     | First date of the month |

| New\_Confirmed  | Number   | New confirmed cases in the month |

| New\_Deaths     | Number   | New deaths in the month |

| New\_Recovered  | Number   | New recoveries in the month |



---



\## 6️⃣ Dataset: covid\_vaccine\_statewise\_daily\_new\_selected.csv



\*\*Description:\*\*  

Daily COVID-19 vaccination data for India at State level.



| Column Name        | Data Type | Description |

|-------------------|----------|-------------|

| Date              | Date     | Vaccination date |

| State             | Text     | Indian State |

| Dose1\_Total       | Number   | Total first doses administered |

| Dose2\_Total       | Number   | Total second doses administered |

| Booster\_Total     | Number   | Total booster doses administered |

| Total\_Doses       | Number   | Total vaccination doses administered |



---



\## 7️⃣ Dataset: india\_gdp\_loss\_covid\_simulated.csv



\*\*Description:\*\*  

Simulated dataset representing economic impact of COVID-19 on India.



| Column Name        | Data Type | Description |

|-------------------|----------|-------------|

| Year              | Number   | Financial year |

| GDP\_Before\_COVID  | Number   | GDP before pandemic |

| GDP\_During\_COVID  | Number   | GDP during pandemic |

| GDP\_Loss          | Number   | GDP loss due to COVID-19 |

| GDP\_Loss\_Percent  | Percentage | Percentage GDP loss |

| Sector            | Text     | Economic sector (Agriculture, Manufacturing, Services, etc.) |



---



\## 🧠 Notes



\- All datasets were \*\*cleaned using Microsoft Excel\*\*

\- Date consistency ensured before Power BI import

\- Monthly aggregations created for trend analysis

\- GDP data is \*\*simulated for analytical demonstration purposes only\*\*



---



📌 This data dictionary ensures \*\*clarity, transparency, and reusability\*\* of the project for future analysis or similar pandemic studies.



