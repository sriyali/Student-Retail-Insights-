#  Student Survey Insights – Power BI Project

##  Overview

This Power BI project analyzes student spending behavior across different store settings in the United States. The data reflects how students allocate their purchases among various categories such as video games, sports kits, books, gadgets, and more.

---

##  Project Description

The dataset used in this project, titled **“Student Survey”**, contains information collected from students across various store locations. Each record represents an individual survey with details on spending amounts, age, store type, and items purchased.

The goal is to develop an interactive Power BI report and dashboard that extracts meaningful insights, incorporates role-level security, supports scheduled data refresh, and utilizes Power BI’s Q&A feature for natural language queries.

---

##  Tasks Performed

1. **Tabular Visualization**  
   Created a table to display **Total Amount of Purchase (TAP)** by `Store Location` and `Store Setting`, with conditional formatting:
   - 🔴 Red: `0 < TAP < 35,000`
   - 🟡 Yellow: `35,000 <= TAP < 60,000`
   - 🔵 Blue: `TAP >= 60,000`

2. **Matrix Visualization**  
   Showed **Outdoor Sports spending** by `Age` and `Store Setting` with color formatting to highlight variation.

3. **Funnel Chart**  
   Displayed **TAP by Store Setting** using a funnel chart with **percentage of first** as data labels.

4. **Pie Chart**  
   Created a pie chart showing **TAP by Store Location**, filtered for **Suburban** store setting only.

5. **Scatter & SandDance Plots**
   - **Scatter Plot**: Compared **Video Games** and **Outdoor Sports** spending by age.
   - **SandDance Plot**: Analyzed **Indoor Sports** vs **Video Games** spending across age groups.

6. **Row-Level Security (RLS)**  
   Applied RLS using a **User Mapping** table, ensuring each user (e.g., Mani) can only view data relevant to their assigned `Store Setting`.

7. **Power BI Service Integration**
   - Published the report to **Power BI Cloud (Service)**
   - Designed a **Master Dashboard** with key visuals
   - Set up **scheduled refresh** every 4 hours (6 times daily)

8. **Power BI Q&A Feature**
   - Used natural language to extract:
     -  **Average age of students**
     -  **Donut chart** showing total purchases by `Store Location`

---

##  Tools & Technologies

- Microsoft Power BI Desktop
- Power BI Service (Cloud)
- Power BI Gateway (for local refresh)
- Excel (source data)
- DAX for measures and RLS filters
- Q&A and custom visual integration (SandDance)


