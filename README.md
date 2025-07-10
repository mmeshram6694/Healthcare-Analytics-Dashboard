# 🏥 Healthcare Billing Dashboard – Power BI

Welcome to my comprehensive **Healthcare Analytics Dashboard** project where I leveraged **Power BI** to turn healthcare billing data into powerful, actionable insights. This dashboard is designed for hospital administrators, finance teams, and healthcare decision-makers to understand billing trends, department-wise costs, and patient service patterns.

---

## 🎯 Project Objective

To provide a centralized reporting solution that reveals key billing metrics, highlights cost-intensive procedures and departments, and empowers healthcare stakeholders to improve operational efficiency and patient care strategy.

---

## 🌟 Project Highlights

- Complete ETL-to-Visualization solution using Power BI  
- Interactive map view to assess city-wise billing trends  
- Department, procedure, and diagnosis-based cost breakdown  
- Service type insights (Emergency, Inpatient, Outpatient) via stacked visuals  
- Dynamic DAX measures for KPIs like Avg. Treatment Cost, % Share by Procedure, Avg. Insurance Coverage, and more  

---

## 🛠️ Tech Stack Used

- **Power BI Desktop**: Power Query (data cleaning), data modeling, interactive visualizations  
- **DAX**: Advanced KPIs such as % Contribution, Averages, and Departmental Billing logic  
- **Power BI Service (optional)**: For publishing and sharing dashboards with stakeholders  

---

## 🔄 Project Workflow

### 1. Data Ingestion & Cleaning
- Handled data from multiple tables: `Billing`, `Patients`, `Procedures`, `Departments`, `Diagnosis`, `Date`  
- Cleaned nulls, corrected mismatches, standardized naming conventions  

### 2. Data Modeling
- Created a **Star Schema** with:  
  - Fact Table: `Billing`  
  - Dimension Tables: `Patients`, `Procedures`, `Departments`, `Diagnosis`, `Date`, `City`  

### 3. DAX-Driven KPI Development
- Measures created for:  
  - Total Billing, Insurance, Medication, Treatment, Room Charges, Out-of-Pocket  
  - Averages per patient: Billing, Insurance, Treatment, Medication, Room Charges  
  - % Share by Department and Procedure  
  - Patient Satisfaction & Length of Stay (if available)  

### 4. Dashboard Design
- Used bar, stacked bar, map, and KPI cards  
- Interactive filters: by City, Department, Procedure, and Service Type  
- Designed for high-level overview and detailed drilldowns  

---

## 📁 Project Structure

```bash
📦 PowerBI-Healthcare-Billing-Dashboard
├── 📊 HealthcareDashboard.pbix
├── 📁 Screenshots/
│   ├── MainDashboard.png
│   ├── Department_Insights.png
│   └── Procedure_Breakdown.png
├── 📄 README.md
📷 Dashboard Snapshots
🗺️ City-wise Billing Overview

🏥 Department Billing Breakdown

🔬 Procedure-Level Billing

## 🔍 Key Insights & Takeaways

- **X-Ray** contributed **31%** of total billing, making it the most billed procedure. This reflects heavy usage in diagnostics or imaging-based care.
- **Cardiology** generated over **25%** of total departmental billing. High volume or high-cost cardiac procedures may be driving this.
- **Out-of-Pocket costs** reached **$1.13M**, which is nearly 34% of total billing. This indicates potential gaps in insurance coverage or high deductibles.
- **Birmingham, Manchester, and Edinburgh** emerged as top billing cities, suggesting larger hospitals or more critical care centers.
- **Fracture & Asthma** cases were mainly treated under **emergency/inpatient** services, implying acute care demand.
- **Migraine & Hypertension** were mostly **outpatient**, aligning with standard chronic care models.


🚀 Suggested Outcomes
Optimize cost structures for high-volume procedures like X-Ray and CT Scan

Evaluate insurance coverage policies and billing transparency for reducing out-of-pocket burden

Improve resource allocation in departments like Cardiology and Orthopedics

Regional management can use city-wise billing to plan expansions or streamline operations

📌 Business Recommendations
Consider bundled care pricing models for high-cost procedures

Expand preventive outpatient programs for chronic conditions like hypertension

Enhance negotiation with insurers for better coverage on common inpatient treatments

Use patient satisfaction data (if captured) to align costs with outcomes

🧠 Skills Demonstrated
🧩 Star schema design in Power BI

🔢 Advanced DAX for KPIs and % breakdowns

📊 Dashboard UX design with drill-throughs and dynamic slicers

🩺 Domain understanding of healthcare finance and service patterns

📬 Let’s Connect!
📧 mmeshram@umassd.edu
🔗 LinkedIn – Mayur Meshram
