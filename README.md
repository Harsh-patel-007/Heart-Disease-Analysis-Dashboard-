# Heart Disease Analysis Dashboard 

This Power BI dashboard provides a dynamic and comprehensive analysis of heart failure clinical records, offering insights into survival rates, age-related risk patterns, and the impact of various clinical factors. Built as an interactive tool, it allows users to explore patient outcomes and key health metrics with ease.

## Features

* **KPI Overview:** Survival Rate, Average Age of Survival, Total Survival, and Total Death metrics.
* **Age-Group Specific Analysis:** Visualizations on survival counts, average serum creatinine, and ejection fraction across different age groups.
* **Survival Rate Trends:** A line chart showing how survival rates change with age.
* **Risk Factor Impact:** A ribbon chart illustrating the influence of smoking, high blood pressure, diabetes, and anaemia across age groups.
* **Interactive Filtering:** A gender slicer for granular data exploration.
* **Professional Design:** A custom, high-definition background with a focus on anatomical realism and a sleek, modern aesthetic.

## Technologies Used

* **Power BI Desktop:** For data ingestion, transformation, modeling, and visualization.
* **DAX (Data Analysis Expressions):** For creating calculated columns and measures.
* **Figma / Image Generation Tool:** For designing the custom dashboard background.

## Project Structure

The repository typically contains:

* `Heart_Disease_Analysis_Dashboard.pbix`: The Power BI project file.
* `README.md`: This file.
* `Images/`: (Optional) Screenshots of the dashboard.
* `Background/`: (Optional) The custom background image used (`dashboard_background.png` or `.jpg`).

##  Dashboard Visuals (Screenshots)

*(You will replace this section with actual screenshots of your dashboard. It's highly recommended to include a full dashboard view and maybe a close-up of a key chart.)*

**Full Dashboard View:**
![Full Dashboard View](Images/full_dashboard_screenshot.png)


## 💡 Key Learnings

* **Data Ingestion & Transformation:** Connecting to CSV data and preparing it for analysis.
* **DAX Formulas:** Crafting measures for KPIs (`Survival Rate`, `Total Deaths`, `Avg Age of Survival`) and calculated columns (`AGE_GROUP`, `Gender`).
* **Advanced Data Visualization:** Developing various chart types (Combo Chart, Line Chart, Ribbon Chart) and slicers.
* **Dashboard Design Principles:** Structuring a professional and aesthetically pleasing layout using custom backgrounds and visual hierarchy.
* **Interactive Storytelling:** Enabling users to derive insights through dynamic filtering and clear presentation.

##  Dataset

The dataset used for this analysis is the "Heart Failure Clinical Records" from the UCI Machine Learning Repository.

* **Source:** [https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)
* **License:** Creative Commons Attribution 4.0 International (CC BY 4.0) – [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
* **Citation:** Chicco, D., & Jurman, G. (2020). Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. *BMC Medical Informatics and Decision Making, 20*(1), 1-16.


---
