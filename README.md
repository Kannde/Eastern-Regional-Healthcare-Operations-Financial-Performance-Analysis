Project Title
Healthcare Operations & Financial Performance Dashboard to Identify Cost Drivers, Revenue Leakage, and Access Gaps.

Overview<br>
Built an executive-ready, multi-page BI application analyzing healthcare cost drivers, encounter trends, workforce load, and financial risk. Implemented synced slicers, global reset UX, dual-axis cost vs volume analysis, and contextual insight tooltips to support leadership decision-making.<br>
________________________________________

**Business Problem** <br>
Healthcare leadership needs visibility into where money is being spent, where revenue is leaking, how clinical operations are performing, and whether access to care is equitable across facilities.<br>
This project answers key business questions such as:<br>
•	Which facilities generate the highest cost and encounter volume?<br>
•	Are inpatient encounters disproportionately driving total costs?<br>
•	How do payment rejection rates vary by insurance type?<br>
•	Which providers handle the highest workload relative to experience?<br>
•	Are rural facilities underutilized or underfunded?<br>
•	What factors are associated with high-cost encounters?<br>
The goal is to provide an executive-ready dashboard to support better financial control, operational efficiency, and access planning.
________________________________________

 Dataset Overview<br>
•	Source: Simulated healthcare operational and financial dataset<br>
•	Size: ~11,000 encounter records<br>
•	Time period: 2023-2027<br>
•	Encounter Date<br>
•	Facility<br>
•	Department<br>
•	Encounter Type (Emergency, Inpatient, Outpatient)<br>
•	Provider Name<br>
•	Years of Experience<br>
•	Total Cost (USD)<br>
•	Payment Status (Paid, Pending, Rejected)<br>
•	Insurance Type<br>
•	Length of Stay (LOS)<br>
•	Lab Tests Ordered<br>

________________________________________
🛠 Tools Used
•	Excel – initial data inspection<br>
•	Power Query – data cleaning and transformation<br>
•	Power BI – modeling, DAX, and dashboard visualization<br>
________________________________________

Data Cleaning & Preparation<br>
Key data quality issues and how they were handled:<br>
•	Removed duplicate encounter records<br>
•	Standardized facility and department naming (e.g., “Rural Health Center”)<br>
•	Converted date fields into proper date format and extracted Year & Month<br>
•	Handled missing cost values and flagged missing cost entries<br>
•	Created calculated columns and measures, including but not limited to:<br>
o	High-Cost Encounter Flag (based on encounter-type thresholds)<br>
o	Cost per Encounter<br>
o	Revenue Received (Paid encounters only)<br>
o	Rejected Revenue and Pending Revenue<br>
o	Workload weighted by years of experience<br>

•	Built a clean star-style model to support slicing by facility, department, provider, encounter type, insurance type, and time

________________________________________

 **Key Questions & Analysis**<br>
•	Which facilities drive the highest cost and encounter volume?<br>
•	Are inpatient encounters responsible for a disproportionate share of total costs?<br>
•	How do encounter volumes and costs trend over time?<br>
•	Which insurance types have the highest rejection rates and revenue leakage?<br>
•	Which providers carry the highest workload relative to experience?<br>
•	Which departments generate the most lab test demand?<br>
•	Are rural facilities underutilized compared to urban facilities?<br>
•	What factors are associated with high-cost encounters?<br>
________________________________________

 **Key Insights <**br>
•	Urban clinics and district hospitals account for the highest total cost and encounter volume, indicating where most resources are consumed.<br>
•	Inpatient encounters represent a smaller share of volume but drive a disproportionately high share of total cost.<br>
•	Payment rejection rates vary by insurance type, contributing to measurable revenue leakage.<br>
•	Junior providers carry a higher workload relative to experience, highlighting potential burnout and quality-of-care risks.<br>
•	Rural facilities show significantly lower encounter volumes, suggesting potential access gaps or underutilization of services.<br>
•	A small proportion of encounters account for a large share of total cost, indicating high-cost care pathways that warrant further review.<br>
________________________________________

Dashboard / Visualization<br>
The Power BI report is structured as a 3-page executive application:<br>
**Executive Overview:**<br>
High-level KPIs, cost and volume by facility, rejection rates by insurance type, and monthly trends.<br>
**Clinical Operations & Workforce**:<br>
Provider workload vs experience, LOS trends, lab demand by department, and encounter distribution.<br>
**Access, Equity & Financial Risk:**<br>
Rejected and pending revenue, high-cost encounter segmentation, rural utilization, and average cost by facility.<br>
**The dashboard includes**:<br>
1. Synced slicers across pages
2. Global reset button
3. App-style navigation
4. Contextual “Key Insight” tooltips

<img width="576" height="329" alt="image" src="https://github.com/user-attachments/assets/8b7819b6-6d40-4448-9fd3-d9c6b28bc042" />

Cover page with summaries 

________________________________________


<img width="587" height="353" alt="Screenshot 2026-02-06 112910" src="https://github.com/user-attachments/assets/4363db82-dc79-49fe-b1fd-7513f1f10b6d" />

Execurtive level view
________________________________________

<img width="582" height="354" alt="Screenshot 2026-02-06 105220" src="https://github.com/user-attachments/assets/692f6b46-f391-4089-a65e-b9c2bad6bf5a" />

Operations

________________________________________

<img width="587" height="353" alt="Screenshot 2026-02-06 112910" src="https://github.com/user-attachments/assets/94f12a10-4c01-4003-a3ab-d2a6ed98755d" />

Risks


________________________________________

You can interact with the dashboard at: 

 Recommendations
•	Review inpatient care pathways to identify opportunities for cost containment without compromising care quality.<br>
•	Strengthen claims and billing processes for insurance types with higher rejection rates to reduce revenue leakage.<br>
•	Rebalance provider workload by supporting junior staff and redistributing cases where possible.<br>
•	Investigate barriers to utilization in rural facilities and explore outreach or service expansion to improve access.<br>
•	Monitor high-cost encounter drivers to manage financial risk proactively.<br>
________________________________________
 Conclusion
This analysis provides leadership with clear visibility into cost drivers, revenue leakage, workforce pressure, and access gaps.<br>
The dashboard enables data-driven decisions to improve operational efficiency, financial sustainability, and equitable healthcare access.<br>
________________________________________

⚠️ Limitations (Optional but Powerful)
•	The dataset does not include patient outcomes, case severity, or payer contract details, which would improve cost and performance interpretation.<br>
•	Financial figures represent billed values and payment status but not full reimbursement timelines.<br>

If you want to have a look on Power Bi app, you can contact me: https://www.linkedin.com/in/ehm-kannde/
