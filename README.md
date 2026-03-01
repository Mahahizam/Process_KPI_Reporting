# Process KPI Reporting & Data Quality

## Overview
This project focuses on analyzing production and operational data to identify data quality issues and calculate key performance indicators (KPIs).  
The goal is to turn raw process data into clear insights that support decision-making in industrial and business environments.

The project is designed to reflect realistic company scenarios, focusing on data cleaning, KPI calculation, visualization, and actionable recommendations.

---

## Business Context
In manufacturing and operational environments, raw data often contains inconsistencies, missing values, or errors.  
Understanding the data and calculating KPIs such as production efficiency, downtime, and defect rates are essential for operational improvement and process optimization.

This project demonstrates the ability to process raw data into actionable information for management and decision-makers.

---

## Dataset
- **Type:** Synthetic internal process dataset  
- **Origin:** Generated to simulate a realistic production workflow  
- **Format:** CSV file (`Process_KPI_Data_Project3.csv`)  

Each row represents a daily production record for a machine:
- `Machine_ID` – machine identifier  
- `Date` – daily timestamp  
- `Units_Produced` – number of items produced  
- `Downtime_Minutes` – downtime recorded for the machine  
- `Defects` – number of defective items  

Synthetic data was chosen to maintain confidentiality and control while ensuring realistic variability for analysis.

---

## Methodology
1. **Data Cleaning & Validation**  
   - Identified and handled missing values  
   - Removed impossible values (e.g., negative numbers)  
   - Converted `Date` column to datetime format  

2. **Exploratory Analysis**  
   - Summarized units produced per machine  
   - Examined downtime patterns  
   - Investigated defect trends  

3. **KPI Calculation**  
   - Average daily production per machine  
   - Downtime percentage per machine  
   - Defect rate per machine/day  
   - Machine utilization rate  

4. **Visualization**  
   - Bar charts, line charts, and heatmaps to display KPIs and trends  
   - Highlighted key insights and anomalies  

5. **Business Interpretation & Recommendations**  
   - Identified underperforming machines  
   - Recommended improvements for processes and maintenance schedules  

---

## Key Findings
- Some machines consistently underperformed due to higher downtime.  
- A small number of defects caused significant delays, highlighting process inefficiencies.  
- Data cleaning and validation were crucial for reliable KPI calculation.  

---

## Industrial Relevance
This project demonstrates:
- Analytical skills in processing and validating real-world-like data  
- Ability to calculate and visualize KPIs relevant to industrial operations  
- Capability to translate data insights into actionable business recommendations  
- Strong preparation for a role as a Fachinformatiker in Data & Process Analysis

---

## Technologies & Skills
- Python (Pandas, NumPy)  
- Data cleaning and validation  
- KPI calculation and process analysis  
- Data visualization (Matplotlib, Seaborn)  
- Analytical thinking and process-oriented problem-solving  

---

## Notes
This project is part of a growing professional portfolio.  
A summarized project overview with visuals is available in the portfolio PDF.  
Future projects will expand on data analysis, process optimization, and operational insights.

---

## Author
**Maha Hizam**
