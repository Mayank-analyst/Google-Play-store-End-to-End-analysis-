# 📊 Google Play Store End-to-End Data Analytics Project  

## 🚀 Project Overview  

This project is a complete **End-to-End Data Analytics workflow** built using the Google Play Store dataset.

The objective was to:

- Clean and prepare raw data  
- Perform SQL-based exploratory analysis  
- Build business insights using Power BI  
- Design a multi-page interactive dashboard  

This project demonstrates practical skills across **Excel, SQL, and Power BI**.

---

# 🛠 Tools & Technologies Used  

- Microsoft Excel – Data Cleaning & Preprocessing  
- SQL (MySQL) – Data Exploration & Query Analysis  
- Power BI – Dashboard Development & DAX  
- Power Query  
- DAX  

---

# 📂 Project Workflow  

## 🥇 1. Data Cleaning (Excel)

Performed:

- Removed invalid and duplicate records  
- Cleaned "Installs" column (removed commas and + signs)  
- Converted "Price" from text ($ format) to numeric  
- Corrected incorrect Category values (e.g., 1.9 error)  
- Handled missing ratings  
- Standardized data types  

Prepared clean dataset for SQL import.

---

## 🥈 2. SQL Analysis

Imported cleaned dataset into SQL and performed 20 analytical queries including:

- Total number of apps  
- Average rating  
- Total installs  
- App count by type (Free vs Paid)  
- Top 5 categories by installs  
- Revenue estimation (Price × Installs)  
- Category-wise average ratings  
- High-install high-rating apps  
- Revenue by category  
- Content rating analysis  

Used:

- GROUP BY  
- ORDER BY  
- LIMIT  
- CASE statements  
- Aggregate functions (SUM, AVG, COUNT)  
- DISTINCT  
- Filtering with WHERE  

This phase helped validate business logic before dashboard creation.

---

## 🥉 3. Power BI Dashboard Development  

Built a **3-page interactive dashboard**:

### 📄 Page 1 – Overview  

- Total Apps  
- Total Installs  
- Average Rating  
- Free vs Paid Distribution  
- Top Categories  
- Install Distribution  

Purpose: Executive Summary View

---

### 📄 Page 2 – Category Performance  

- Installs by Category  
- Average Rating by Category  
- Revenue by Category  
- Free vs Paid Distribution  

Purpose: Performance comparison across segments

---

### 📄 Page 3 – Monetization & Pricing Insights  

- Total Paid Revenue  
- Average Paid Price  
- Revenue by Price Range  
- Distribution of Paid Apps by Pricing Tier  
- Revenue Efficiency by Category  

Purpose: Understand pricing strategy & monetization behavior

---

# 📐 Key DAX Measures Created  

- Total Paid Revenue  
- Average Paid Price  
- Revenue per Install  
- Price Range Segmentation  
- Install Range Segmentation  
- Distinct App Count  

Functions Used:

- CALCULATE()  
- SUMX()  
- SWITCH(TRUE())  
- DIVIDE()  
- DISTINCTCOUNT()  

---

# 📊 Key Insights  

- Free apps dominate total installs.  
- Paid apps represent a small share of volume but generate concentrated revenue.  
- Most paid apps are priced in lower tiers ($1–$5 range).  
- Certain categories outperform others in revenue efficiency.  
- Higher price does not always correlate with higher installs.  

---

# 🎯 Business Value  

This project demonstrates:

- Data Cleaning & Preparation  
- SQL Query Writing & Aggregation  
- Revenue Estimation Modeling  
- DAX & Data Modeling  
- Dashboard Design & Storytelling  
- Business Insight Extraction  

---

# 📷 Dashboard Preview  

## 📄 Page 1 – Overview  

![Overview Dashboard](Screenshot%20%28279%29.png)

---

## 📄 Page 2 – Category Performance  

![Category Performance Dashboard](Screenshot%20%28280%29.png)

---

## 📄 Page 3 – Monetization & Pricing Insights  

![Monetization Dashboard](Screenshot%20%28281%29.png)



# 👤 Author  

Mayank Bisht 
Data Analyst(Fresher)  




