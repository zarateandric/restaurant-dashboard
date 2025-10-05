# 📊 Dashboard - Restaurant Data Analysis with Power BI
---
## 📄 Project Description
This repository documents the creation of an **interactive Dashboard for a restaurant**, fully developed in **Power BI**.
The main goal was to transform raw sales and operations data into actionable insights, utilizing key tools such as **Power Query** for data preparation and **DAX formulas** for creating advanced metrics.

## 📁 Main Project Files
* `Restaurante-Dashboard.pbix`: Main Power BI Dashboard file.
* `Restaurante Redux, Power BI, Datos.xlsx`: Source data file (Excel) used for loading into Power BI.
---
## 🛠️ Key Development Steps
1.  **Data Import:** Loading Excel files into Power BI.
2.  **Data Modeling:** Establishing relationships (models) between the different tables.
3.  **Cleaning and Transformation (Power Query):**
    * Cleaning and standardization of columns.
    * **Table Merge:** A *merge* was performed between two key tables to consolidate historical information, resulting in a new **Historicals** table (necessary due to the original data structure).
4.  **Metric Creation (DAX):** Development of calculated measures for analysis.
    * **Calculated Table:** Creation of a new table using `SUMMARIZE` to facilitate specific analyses.
5.  **Bi-directional Relationship:** A bi-directional filter relationship was implemented between the new calculated table and the Historicals table (⚠️ *Note: This implementation is included with the warning that its use should be limited and well-justified due to potential impacts on performance and model ambiguity.*).
6.  **Dashboard Design:** Implementation of visuals, charts, and formatting for a clear and functional presentation.
---
## 📈 DAX Formulas Used
* `SUM`
* `CALCULATE`
* `DIVIDE`
* `TOTALYTD`
* `SUMMARIZE`
* `COUNTA`
* `AVERAGEX`

## 🎨 Implemented Visualizations

The final Dashboard utilizes a variety of visuals to represent the data:

* **Cards**: For Key Performance Indicators (KPIs).
* **Multi-row Cards**: For detailed summaries.
* **Clustered Column Charts**
* **Line Charts**: For trend analysis.
* **Bar Charts** (Horizontal/Lying Columns)
* **Matrices**: For detailed tabular views.
* **Maps**: For geographical analysis (if applicable).
* **Scatter Charts**
* **KPI Cards**
* **Buttons/Navigation**
---
## ✨ Dashboard
Here you can see the dashboard design and KPI's implemented in the Power BI Dashboard
### Home / Overview
<img width="1313" height="735" alt="d1" src="https://github.com/user-attachments/assets/442ba591-8223-4258-90c5-fd153a657b09" />

### Server Performance Analysis
<img width="1306" height="720" alt="d2" src="https://github.com/user-attachments/assets/bcce7fbf-16a2-4116-88fe-ed33211dd87c" />

### Server Sales and Tips
<img width="1310" height="729" alt="d3" src="https://github.com/user-attachments/assets/aec4dea5-4dc2-4f3e-8a20-c0a42a184b66" />

### Server Order Efficiency
<img width="1311" height="724" alt="d4" src="https://github.com/user-attachments/assets/3eec8689-a79c-4884-8a4b-98b30d2bdff6" />

### KPI Tracking
<img width="1308" height="729" alt="d5" src="https://github.com/user-attachments/assets/80ac9345-d12f-43ce-96f7-aa97beaea188" />
