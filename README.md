# Flight-data-project
This is an end-to-end data analysis pipeline, Python EDA, and Excel model for flight booking records and project summary provided.
# Goibibo Flight Booking Data Analysis & Modeling

## Situation
* Goibibo, a major Indian online travel platform, accumulated 300K+ flight booking records across 8 airlines and 15+ routes.
* The data lacked structure and actionable insights—pricing was inconsistent, demand patterns were unclear, and manual reporting was time-consuming.
* Leadership required competitive intelligence to support dynamic pricing, upselling, and operational decisions].

## Task
* Design and execute an end-to-end data analysis pipeline on 300,261 flight records
* Identify market share dynamics, pricing trends, stop-level behavior, and route demand patterns.
* Deliver a structured framework to replace manual reporting and surface actionable pricing and demand signals

## Action
* Data Engineering**: Cleaned raw CSV—normalized price strings, standardized stop labels, parsed dates, and engineered route fields.
* Python EDA**: Utilized pandas, seaborn, and matplotlib to build analytical charts (market share, median price, route heatmaps, and class price distributions)
* Excel Model**: Developed a multi-sheet workbook containing a KPI dashboard, cleaned data subset, route analysis, and reference sheets.
* Insight Generation**: Applied the STAR methodology to translate raw findings into pricing, upselling, and operational recommendations.

## 📊 Results & Key Findings
* Market Share**: IndiGo and Air India hold a combined 41% volume share; Vistara commands the highest median price at ₹15,698.
* Stop-Level Behavior**: Confirmed that 83.6% of flights are 1-stop, highlighting non-stop upselling as a major revenue opportunity
* Route Dynamics**: Delhi–Mumbai is the highest-volume route (15,291 flights), with business class commanding ~9x the economy median price.
* Efficiency Gains**: Self-service KPI models reduced manual reporting effort by an estimated 60% and enabled 25–30% operational efficiency gains.

## 📂 Repository Contents
* `notebooks/`: Contains the Jupyter Notebook (`.ipynb`) with Python Exploratory Data Analysis.
* `excel/`: Contains the structured Excel model (`.xlsx`).
