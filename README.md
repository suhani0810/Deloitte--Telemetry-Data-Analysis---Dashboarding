# 📊 Telemetry Data Analysis & Dashboarding

### 📄 Project Overview
Completed as part of the **Deloitte Australia Technology Job Simulation**. This project involved analyzing telemetry data to identify manufactory failure hotspots and visualize global machine performance.

### 🎯 Objective
To process unstructured JSON data and create an interactive dashboard that helps engineering teams pinpoint high-risk facilities and equipment failures.

### 🛠️ Tech Stack
* **Tool:** Tableau Desktop.
* **Data Format:** Unstructured JSON logs.
* **Technique:** End-to-End Data Pipeline (ETL & Visualization).

### ⚙️ Methodology
Unlike standard analysis on pre-cleaned data, this project required significant **Data Preparation** within Tableau:
1.  **Data Ingestion:** Connected directly to raw JSON telemetry files.
2.  **Transformation (ETL):** Utilized Tableau's data preparation layer to:
    * Parse nested JSON structures.
    * Clean and format timestamp data.
    * Create calculated fields to flag specific failure types.
3.  **Visualization:** Built an interactive dashboard to map failure rates geographically.

### 💡 Key Insights
* **High-Risk Zone:** Identified **Tokyo** as the facility with the highest operational risk.
* **Failure Analysis:** Isolated the top 3 failure types causing production downtime.
* **Trend Detection:** Visualized failure frequency across Japan, Germany, China, and the USA.

### 📈 Dashboard
*![Tableau Dashboard](Tableau-Dashboard(Deloitte).png)
