🏥 Healthcare Billing Analytics Dashboard – Power BI
Welcome to the Healthcare Billing Analytics Dashboard project! This repository showcases how Power BI can transform complex healthcare billing data into actionable insights for hospital administrators, finance teams, and healthcare decision-makers.

🎯 Project Objective
Deliver a centralized, interactive reporting solution that reveals key billing metrics, highlights cost-intensive procedures and departments, and empowers healthcare stakeholders to enhance operational efficiency and patient care strategy.

🌟 Project Highlights
End-to-End ETL & Visualization: Complete pipeline from data ingestion and cleaning to interactive dashboards.

Interactive Map View: Assess city-wise billing trends and identify regional hotspots.

Comprehensive Cost Breakdown: Visualize billing by department, procedure, and diagnosis.

Service Type Insights: Analyze Emergency, Inpatient, and Outpatient services using stacked visuals.

Dynamic DAX KPIs: Track metrics such as Avg. Treatment Cost, % Share by Procedure, Avg. Insurance Coverage, and more.

🛠️ Tech Stack
Power BI Desktop: Power Query for data cleaning, data modeling, and interactive visualizations.

DAX: Advanced KPIs for % contribution, averages, and departmental billing logic.

Power BI Service (optional): For publishing and sharing dashboards with stakeholders.

🔄 Project Workflow
1. Data Ingestion & Cleaning
Integrated data from multiple tables: Billing, Patients, Procedures, Departments, Diagnosis, Date.

Addressed nulls, corrected mismatches, and standardized naming conventions.

2. Data Modeling
Designed a Star Schema:

Fact Table: Visits

Dimension Tables: Patients, Procedures, Departments, Diagnosis, Date, City

3. KPI Development with DAX
Created measures for:

Total Billing, Insurance, Medication, Treatment, Room Charges, Out-of-Pocket

Per-patient averages for Billing, Insurance, Treatment, Medication, Room Charges

% Share by Department and Procedure

Patient Satisfaction & Length of Stay (if available)

4. Dashboard Design
Visuals: Bar, stacked bar, map, and KPI cards.

Interactive filters: City, Department, Procedure, Service Type.

Designed for both high-level overviews and detailed drilldowns.

📁 Project Structure

```bash
📦 PowerBI-Healthcare-Billing-Dashboard
├── 📊 HealthcareDashboard.pbix
├── 📁 Screenshots/
│   ├── MainDashboard.png
├── 📄 README.md
```

---

## 📷 Dashboard Snapshots

### 🗺️ City-wise Billing Overview
![City Billing](Screenshots/MainDashboard.png)

---

🔍 Key Insights & Takeaways
X-Ray procedures account for 31% of total billing—the most used and billed procedure.

Cardiology contributes over 25% of all department-level billing.

Out-of-pocket costs exceed $1.13M, highlighting potential gaps in insurance coverage.

Cities like Birmingham and Manchester are high billing zones, suggesting higher patient loads or larger facilities.

Diagnosis patterns: Fracture and Asthma dominate emergency/inpatient services, while Migraine and Hypertension are more common in outpatient settings.

🚀 Suggested Outcomes
Optimize cost structures for high-volume procedures like X-Ray and CT Scan.

Evaluate insurance coverage policies and improve billing transparency to reduce out-of-pocket burden.

Enhance resource allocation in departments such as Cardiology and Orthopedics.

Use city-wise billing data for strategic planning and operational streamlining.

📌 Business Recommendations
Implement bundled care pricing models for high-cost procedures.

Expand preventive outpatient programs for chronic conditions like hypertension.

Negotiate with insurers for better coverage on common inpatient treatments.

Align costs with outcomes using patient satisfaction data (if available).

🧠 Skills Demonstrated
Star schema design in Power BI

Advanced DAX for KPIs and detailed breakdowns

Dashboard UX with drill-throughs and dynamic slicers

Domain expertise in healthcare finance and service analytics

📬 Contact
Email: mayurmeshram1297@gmail.com
LinkedIn: https://www.linkedin.com/in/mayur-meshram9/
