# Global Sales Intelligence & Executive Dashboard

## **Project Overview**
[cite_start]This repository contains a comprehensive Business Intelligence solution developed as part of the **DSA 3050A - Business Intelligence & Data Visualization** course at USIU-Africa[cite: 1, 3]. [cite_start]The project follows a full end-to-end BI workflow—Dataset Selection, Preparation, Modelling, Development, and Publishing—to solve a real-world organizational problem using Power BI.

## **Business Scenario**
[cite_start]Acting as a Business Intelligence Analyst, I have sourced and transformed a real-world sales dataset to provide actionable insights into regional performance, profit trends, and product distribution[cite: 9, 10]. [cite_start]The goal is to support executive decision-making through a professional, interactive data narrative[cite: 89, 102].

---

## **Key BI Workflow Stages**

### **1. Data Sourcing & Preparation (Part A)**
* [cite_start]**Dataset**: Sourced a high-fidelity sales dataset from Kaggle containing **10,000 rows**, exceeding the 7,000-row exam minimum[cite: 20, 25, 38].
* [cite_start]**Transformations**: Performed extensive cleaning in **Power Query** to ensure data integrity[cite: 46, 50]:
    * [cite_start]Corrected data types (Dates, Fixed Decimals, and Text)[cite: 53].
    * [cite_start]Handled missing values and removed duplicates[cite: 51, 52].
    * [cite_start]Created derived columns, including a custom **VAT (16%)** calculation[cite: 58].
    * [cite_start]Extracted **Year, Month Name, and Quarter** attributes for time-series analysis[cite: 59, 61, 62, 63].
* [cite_start]**Technical Rigor**: Maintained over **10 Applied Steps** to ensure a robust data pipeline[cite: 67].

### **2. Data Modelling (Part B)**
* [cite_start]**Architecture**: Implemented a **Star Schema** structure to optimize performance and analytical clarity[cite: 75, 78].
* [cite_start]**Relationships**: Established clean **One-to-Many (1:*)** relationships between a central Fact table and Dimension tables[cite: 78].
* **Integrity**: Applied correct cardinality and ensured proper filter directions while avoiding many-to-many complexities[cite: 78, 79].



### **3. Dashboard Development (Part C)**
Developed an interactive executive dashboard designed for decision support[cite: 87, 89, 102]:
* [cite_start]**KPI Summary**: High-level tracking of Total Revenue, Total Profit, and Units Sold[cite: 92].
* [cite_start]**Trend Analysis**: Time-series visualization of profit trends by month and year[cite: 93].
* **Comparative Analysis**: Regional and category performance distribution[cite: 94, 95].
* [cite_start]**Interactivity**: Fully integrated slicers and cross-filtering for dynamic data exploration[cite: 96, 97].

### **4. Deployment (Part D)**
* [cite_start]**Platform**: Published the final report to **Power BI Service**[cite: 104, 107].
* **Accessibility**: Generated a public web link for stakeholder accessibility and review[cite: 107, 108].

---

## **Project Links**
* **Live Dashboard Link**: [PASTE YOUR POWER BI PUBLIC LINK HERE]
* **Process Evidence (PDF)**: [Link to your uploaded PDF in this repo]

## **Author**
**Michael Okoth** *Student ID: [Your Student ID]* *United States International University - Africa (USIU)* [cite: 1, 2]

---

### **How to Use This Repository**
1. **Download the `.pbix` file** to explore the Power Query transformation steps and Data Model.
2. **Open the Live Dashboard Link** above to interact with the executive report in your browser.
3. **Review the PDF documentation** for a detailed breakdown of screenshots and analytical logic..
* Visualizations: Includes KPI cards, regional trend analysis, and cross-filter interactivity.Live Dashboard Link[https://app.powerbi.com/groups/me/reports/d94042aa-42fc-43f4-9e6a-5cae5434eb5f/88a58af84d52505b1482?ctid=16d83ee6-254a-469d-a6cc-54e2ca2313e7&experience=power-bi&bookmarkGuid=6f36b402-a62f-45bf-ad66-6828f4baecbb]
