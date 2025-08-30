![Preview](https://github.com/d28006/Healthcare-and-Patient-Analytics/blob/main/Snapshot%20of%20Dashboard.PNG)

1. Project Title / Headline

🏥 Patient Waitlist Dashboard: Multi-Year Insights on Case Types, Specialties, and Age Profiles
An interactive Power BI dashboard designed to track patient waitlist trends, analyze performance across case types (Outpatient, Day Case, Inpatient), and evaluate demand across specialties and demographics—empowering healthcare providers to optimize capacity planning and improve patient outcomes.

2. Short Description / Purpose

The Patient Waitlist Dashboard provides a comprehensive analysis of healthcare waitlist metrics including total patients, average and median wait times, age band distribution, and specialty-level demand. It enables hospital administrators, clinical managers, and policymakers to monitor trends, compare patient load across case types, and identify specialties with the highest demand for strategic resource allocation.

3. Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main platform for dashboard design and storytelling

🔄 Power Query (M) – For extracting, cleaning, and transforming patient records

🧠 DAX (Data Analysis Expressions) – For calculations such as average wait times, bifurcation by case type, and specialty segmentation

🧩 Data Modeling – Structured relationships across time, case type, specialty, and age profile dimensions

🗄 SQL Server / Data Warehouse – For managing and preparing patient waitlist datasets prior to Power BI integration

💻 SQL (SELECT, GROUP BY, aggregations) – Used to pre-aggregate multi-year patient data

📁 File Format – .pbix (Power BI project) with exported dashboard snapshots for reporting

4. Data Source

Source: Hospital patient waitlist records (Jan 2018 – Mar 2021). The dataset includes:

Total waitlist patients (latest vs prior year)

Case Type distribution (Outpatient, Day Case, Inpatient)

Average and median wait times

Age profile segmentation (0–15, 16–64, 65+) across time bands (0–3 months, 3–6 months, etc.)

Specialty-level demand (e.g., Paediatrics, Dermatology, ENT, Cardiology)

Monthly patient volumes across multiple years

5. Features / Highlights

• Business Problem
Healthcare systems face increasing pressure from rising patient demand and limited capacity. Administrators need visibility into waitlist dynamics to improve scheduling, allocate resources effectively, and ensure timely care delivery.

• Goal of the Dashboard
To provide healthcare stakeholders with:

A consolidated view of multi-year waitlist trends

Case type bifurcation for outpatient, inpatient, and day cases

Specialty-level insights to prioritize resourcing

Age and time band distribution to identify long-waiting patients

Trends to inform operational planning and policy-making

6. Walkthrough of Key Visuals

Top KPIs Panel – Compares latest month’s waitlist (709K) vs previous year (640K).

Donut Chart (Waitlist by Case Type) – Outpatient (72%), Day Case (17%), Inpatient (11%).

Stacked Bar Chart (Waitlist by Time Band & Age Profile) – Breaks down patients by months waiting and age group.

Top 5 Specialties Panel – Highlights highest demand specialties (e.g., Dermatology: 168, ENT: 148).

Monthly Trend Analysis – Tracks multi-year growth of patient volumes by case type (2018–2021).

7. Business Impact & Insights

📈 Rising Demand: Total patient waitlists increased from 640K → 709K YoY, signaling growing pressure on health services.

🏥 Outpatient Dominance: 72% of patients are outpatients, requiring efficient scheduling systems.

👶 Specialty Pressures: Pediatric specialties (Dermatology, ENT, Cardiology) show high patient volumes, highlighting need for specialist resource allocation.

⏳ Wait Time Risks: Long waits (18+ months) are significant, with older patients (65+) disproportionately represented.

🎯 Strategic Planning: Insights enable hospitals to redistribute resources, prioritize high-wait groups, and develop interventions to reduce backlog.)
