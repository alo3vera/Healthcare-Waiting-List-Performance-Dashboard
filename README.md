# Healthcare-Waiting-List-Performance-Dashboard
**Project Overview**

This project presents an end-to-end Power BI dashboard built using a Patient Wait List dataset.
The main goal of the dashboard is to help healthcare administrators, hospital management teams, and analysts gain a clear understanding of patient wait times, treatment pathways, backlogs, and overall operational bottlenecks within healthcare services.

This was my first Power BI project uploaded to GitHub. The dashboard demonstrates my ability to transform raw healthcare data into actionable insights through intuitive visuals and a clean report design.

**Key Objectives**

1. Consolidate multi-year inpatient and outpatient waitlist data into one clean model
2. Analyze wait-time delays, patient load trends, and priority categories
3. Compare Inpatient vs Outpatient performance
4. Understand specialty-level demand and bottlenecks
5. Build interactive dashboards for decision-makers in healthcare operations

**Dataset Description — “Patient Wait List”**

The dataset contains patient-level and hospital-level information related to appointment scheduling and treatment wait time monitoring. Key fields include: Age Group (0–15, 16–64, 65+), Case Type (Outpatient, Day Case, Inpatient), Speciality Name, Time Bands (0–3 months up to 18+ months), and WL Count for each category.
It also includes a Date/Archive Month field that supports multi-year trend analysis (2018–2021) and Average/Median WL values for specialty-level comparisons.
This dataset enables analysis of wait list growth, specialty performance, demographic patterns, and case-type distribution.

**Data Preparation & Modelling**
Steps Performed

1. Imported raw dataset (CSV/Excel) into Power BI.
2. The dataset consists of combined Inpatient and Outpatient waitlist records from 2018 to 2021. After appending all files, the All_Data table includes patient demographics (Age, Gender), clinical specialty, referral dates, clock start dates, treatment dates, priority categories, postcode/region details, urgency flags, and multiple time-based fields used for calculating wait durations. A separate column named Category distinguishes Inpatient vs Outpatient entries.
3. Cleaned missing and inconsistent values, especially for dates and treatment statuses.
4. Established one-to-many relationships for efficient filtering & slicing.
5. Developed multiple DAX measures that formed the analytical backbone of the dashboard and enabled accurate KPI calculations and visual insights.
6. Performed data type corrections, including date formatting and numeric conversions.


**Insights Derived From the Dashboard**
1. Outpatient services dominate the wait list - More than 72% of all wait list volume comes from Outpatient cases.
2. Sharp rise in outpatient wait list over time. The consistent climb from 502K to 629K highlights:
  Growing patient demand
  Potential resource shortages
  Increased dependency on outpatient pathways
3. Day Case and Inpatient volumes are relatively stable
  Both show minor fluctuations
  Inpatient numbers remain around 20K–23K
  Day Case stays around 50K–62K
  These services are more stable compared to outpatient, suggesting fewer bottlenecks.
4. Longest wait times are concentrated in the “18+ Months” band
The 18 Months+ time band has the highest WL volumes across age groups, meaning:
Many patients experience extremely long delays
Urgent intervention is needed for backlog clearance
5. Specialties such as A&E, Paed Cardiology, and Paediatric Dermatology show high average WL
6. Younger age groups (0–15) contribute significantly to long-waiting bands


**Skills Demonstrated**
1. Transformed messy, multi-year inpatient and outpatient files into a clean, reliable dataset.
2. Wrote several DAX measures that powered the dashboard’s KPIs, comparisons, and trends.
3. Designed an easy-to-navigate dashboard that highlights exactly where delays, bottlenecks, and high-volume cases occur.
4. Applied strong problem-solving skills to fix inconsistencies, standardize fields, and ensure accurate wait-time calculations.
5. Combined technical Power BI skills with analytical thinking to tell a clear story through data.

**Screenshots/Demo**
<img width="1279" height="720" alt="Dashboard Summary" src="https://github.com/user-attachments/assets/4eb98462-8b63-4ce4-a7ac-e1848a097426" />

