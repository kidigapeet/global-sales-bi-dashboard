# Global Sales Intelligence & Executive Dashboard

## **Project Overview**
This repository contains a comprehensive Business Intelligence solution developed as part of the **DSA 3050A - Business Intelligence & Data Visualization** course at USIU-Africa. The project follows a full end-to-end BI workflow—Dataset Selection, Preparation, Modelling, Development, and Publishing—to solve a real-world organizational problem using Power BI.

## **Business Scenario**
Acting as a Business Intelligence Analyst, I have sourced and transformed a real-world sales dataset to provide actionable insights into regional performance, profit trends, and product distribution. The goal is to support executive decision-making through a professional, interactive data narrative[cite: 89, 102].

---

## **Key BI Workflow Stages**

### **1. Data Sourcing & Preparation (Part A)**
**Dataset**: Sourced a high-fidelity sales dataset from Kaggle containing **10,000 rows**, exceeding the 7,000-row exam minimum.
**Transformations**: Performed extensive cleaning in **Power Query** to ensure data integrity:
    * Corrected data types (Dates, Fixed Decimals, and Text).
    * Handled missing values and removed duplicates.
    * Created derived columns, including a custom **VAT (16%)** calculation.
    * Extracted **Year, Month Name, and Quarter** attributes for time-series analysis.
* **Technical Rigor**: Maintained over **10 Applied Steps** to ensure a robust data pipeline.

### **2. Data Modelling (Part B)**
**Architecture**: Implemented a **Star Schema** structure to optimize performance and analytical clarity.
**Relationships**: Established clean **One-to-Many (1:*)** relationships between a central Fact table and Dimension tables.
* **Integrity**: Applied correct cardinality and ensured proper filter directions while avoiding many-to-many complexities.



### **3. Dashboard Development (Part C)**
Developed an interactive executive dashboard designed for decision support:
** KPI Summary**: High-level tracking of Total Revenue, Total Profit, and Units Sold.
* **Trend Analysis**: Time-series visualization of profit trends by month and year[cite: 93].
* **Comparative Analysis**: Regional and category performance distribution[cite: 94, 95].
* **Interactivity**: Fully integrated slicers and cross-filtering for dynamic data exploration[cite: 96, 97].

### **4. Deployment (Part D)**
* **Platform**: Published the final report to **Power BI Service**.
* **Accessibility**: Generated a public web link for stakeholder accessibility and review.

---

## **Project Links**
* **Live Dashboard Link**: [[DASHBBOARD LINK](https://app.powerbi.com/groups/me/reports/d94042aa-42fc-43f4-9e6a-5cae5434eb5f/88a58af84d52505b1482?ctid=16d83ee6-254a-469d-a6cc-54e2ca2313e7&experience=power-bi&bookmarkGuid=6f36b402-a62f-45bf-ad66-6828f4baecbb)]
* **Process Evidence (PDF)**: [[PDF](https://github.com/kidigapeet/global-sales-bi-dashboard/blob/main/PETER%20KIDIGA-MIDSEM.pdf)]

## **Author**
**Peter Kidiga ** *Student ID: 341 * *United States International University - Africa (USIU)* 

---

### **How to Use This Repository**
1. **Download the `.pbix` file** to explore the Power Query transformation steps and Data Model.
2. **Open the Live Dashboard Link** above to interact with the executive report in your browser.
3. **Review the PDF documentation** for a detailed breakdown of screenshots and analytical logic..
* Visualizations: Includes KPI cards, regional trend analysis, and cross-filter interactivity.Live Dashboard Link
