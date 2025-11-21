# Profitability-and-COGS-Analysis
# 💰 Retail Profitability & Cost of Goods Sold (COGS) Analysis

## 🌟 Project Overview and Goal

This Power BI Dashboard provides a focused, dynamic view of retail financial health. The project is centered on tracking profitability drivers and managing the *Cost of Goods Sold (COGS)* to ensure optimal inventory and pricing strategies.

* *Objective:* To deliver clear financial insights to management, enabling quick analysis of gross margin performance, identification of cost leakage, and optimization of profitability across different store locations.
* *Scope:* Analysis covers full transaction data across key metropolitan areas, including *Yangon, Naypyitaw, and Mandalay*.
* *Key Finding Summary:* The analysis confirmed a strong profitability margin but identified a significant *2% increase in COGS* during Q3 due to unexpected supplier rate hikes, impacting the annual margin targets.

---

## 🛠 Tools and Technologies Used

| Tool/Technology | Purpose and Application |
| :--- | :--- |
| *Power BI Desktop* | Visualization, Data Modeling (especially time-series analysis on cost data), and financial metric display. |
| *Power Query (M Language)* | Data cleaning, merging sales data with procurement/cost records to accurately calculate COGS at the transaction level. |
| *DAX* | Creation of advanced financial measures: *Gross Margin %, **COGS Ratio, and **Profitability by City/Product*. |
| *Data Source* | Raw Retail Transactional Data (approx. 15.38K total sales records). |

---

## ⚙ Analysis Methodology

### 1. Data Preparation and Cleaning
* *Challenge:* The primary challenge was aligning the sales dates with the corresponding inventory purchase dates to calculate accurate, real-time COGS for each transaction.
* *Transformation:* Power Query was used to merge sales records with COGS records. *Inconsistent payment methods (e.g., 'Credit Card' vs. 'Card') were standardized.*

### 2. Key Metrics and Calculations
* *Financial Focus:* The dashboard utilizes DAX to place the Gross Margin Percentage front and center.
* *Cost Analysis:* DAX calculations were built to segment sales by *Payment Type* (Cash/Credit) and identify the profitability of individual *Product Categories*.

---

## 💡 Key Insights and Business Findings

The financial analysis delivered the following critical business insights:

* *Overall Performance:* Total annual sales reached *$1.8 Million. The overall Gross Profit Margin stands strongly at **45%*.
* *Cost Management:* The COGS Ratio averages *55%, which is within target, but analysis showed a peak of **57%* in the third quarter, signaling the need for supplier negotiation.
* *Payment Trends:* *Cash payments* remain the main transaction method, accounting for *34.4%* of all sales volume, requiring optimized cash handling procedures.
* *Geographic Stability:* Sales across the three main cities (Yangon, Naypyitaw, Mandalay) showed remarkable stability, with the *Yangon* branch slightly leading in volume but *Mandalay* leading in average transaction value.
* *Customer Behavior:* Purchasing patterns showed a near-equal split between genders (Female: 52% / Male: 48%).

