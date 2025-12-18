# Tata-Global-Sales-Analysis
# 📊 Tata Global Sales & Revenue Dashboard

## 📝 Project Overview
**Objective:** The goal of this project was to analyze the global sales performance of Tata's retail division for the year 2011, focusing on revenue trends, customer purchasing behavior, and regional demand.

**Problem Statement:** The business needed to identify top-performing international markets (excluding the UK) and high-value customers to optimize inventory and marketing strategies for the upcoming fiscal year.

## 📸 Dashboard Preview

<img width="1211" height="674" alt="image" src="https://github.com/user-attachments/assets/7b8edea8-bb1f-4186-b1bb-c3d3fcba02e3" />

## 🗝️ Key Insights Derived
Based on the visual analysis of the dashboard:
- **Revenue Performance:** The total revenue generated stands at **$10.64M** with a total of **6M** units sold.
- **Seasonal Trends:** There is a significant spike in revenue during **November 2011** (approx. $83K), indicating strong year-end or holiday season demand, followed by a dip in December.
- **Top Markets (Excluding UK):**
  - **Netherlands** leads in terms of Quantity Sold (~0.20M units).
  - **EIRE (Ireland)** shows the highest Revenue generation among international markets, surpassing Germany and France.
- **Customer Value:** The top customer (ID: 14646) contributed roughly **$0.28M** to the total revenue, highlighting the importance of key account management.

## 🛠️ Technical Workflow
1. **Data Cleaning (Power Query):**
   - Filtered out bad data (negative values in Quantity/Unit Price).
   - Created a separate "Revenue" column (`Quantity * Unit Price`).
   - Handled missing Customer IDs.
2. **Data Modeling:**
   - Modeled the data to allow filtering by Country (Excluding UK for specific visuals).
   - Created measures for `Total Revenue` and `Total Quantity`.
3. **Visualization:**
   - Used **Clustered Bar Charts** to compare Revenue vs. Quantity for top countries.
   - Utilized **Map Visuals** to show the global spread of product demand.
   - Implemented **Card Visuals** for immediate high-level KPI tracking.

## 🚀 Conclusion
The analysis suggests that marketing efforts should be intensified in **EIRE and Netherlands** as they are the most lucrative international markets. Additionally, inventory stocking should be prioritized in **October** to prepare for the November sales surge.
