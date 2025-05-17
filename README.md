# Superstore-Sales

![image](https://github.com/user-attachments/assets/f797e137-076a-41b8-b688-38c0d5519113)

Interactive Power BI dashboard analyzing Superstore's global sales data to provide actionable insights for strategic decision-making on market expansion and product performance.

---
## Summary
This project presents an interactive Power BI dashboard analyzing Superstore's global sales data. The objective is to provide Senior Management with crucial business insights, supporting strategic decisions on market expansion and key product selection. The dashboard focuses on sales performance, product profitability, market potential, and risks associated with product returns.

---

## Table of Contents
- [Introduction & Objectives](#introduction--objectives)
- [Dataset & Preprocessing](#dataset--preprocessing)
- [Methodology & Tools](#methodology--tools)
- [Dashboard Overview & Key Pages](#dashboard-overview--key-pages)
    - [Business Performance Overview](#business-performance-overview)
    - [Product Performance & Strategic Selection](#product-performance--strategic-selection)
    - [Market Potential & Revenue Share](#market-potential--revenue-share)
    - [Return Rate & Operational Risk](#return-rate--operational-risk)
- [Key Insights & Recommendations](#key-insights--recommendations)
- [Usage Instructions](#usage-instructions)
- [Project Deliverables](#project-deliverables)

---

## Introduction & Objectives
Superstore requires a visual tool for Senior Management to grasp the business situation, identify growth opportunities, and select strategic products. This project develops an interactive Power BI dashboard to address core business questions regarding sales performance, market trends, and product portfolio management, thereby supporting strategic decisions for market expansion.

---
## Dataset & Preprocessing
-   **Dataset:** Superstore's global sales data (2011-2014) comprising three tables: `Orders` (transaction details), `People` (sales personnel), and `Returns` (returned transactions).
    -   Source: Superstore sample dataset.
    -   Schema Details: Available in original data files.
-   **Preprocessing (Power Query):**
    -   Connected and cleaned data (handled missing values, standardized data types).
    -   Built a data model, establishing relationships between tables.
    -   Created calculated columns and measures using DAX for analysis (e.g., `Return Rate %`, `Sales Growth YoY`).

---
## Methodology & Tools
-   **Design Thinking Process:**
    -   Applied Design Thinking methodology to deeply understand stakeholder (Senior Management) needs and current challenges.
    -   Identified key business questions and critical Key Performance Indicators (KPIs) to track.
    -   The entire Design Thinking process and its outcomes are documented in detail in the Excel file included in the project deliverables.


**Stage 1: Empathize**

<p align="center">
  <img src="https://github.com/user-attachments/assets/3dbb6bf5-a117-4de4-8bbf-55d8a558147d" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/0559cccd-44f8-41eb-8e44-f8f47784feb7" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/5bda57e1-4e65-4a9a-a7b7-0ee38985e50a" width="600">
</p>


**Stage 2: Define POV**

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b22e569-22d6-44c5-833b-621572e55e2b" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/188c3692-5cae-4318-8a04-93e63b0e5180" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4f9da449-f490-4592-bded-b433adf3a31d" width="600">
</p>



**Stage 3: Ideate**

<p align="center">
  <img src="https://github.com/user-attachments/assets/e4a7dbb9-64e7-4421-9d8e-768585f5b2c6" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/8cb30af8-699d-451f-8421-2c9712a335e2" width="600">
</p>


**Stage 4: Prototype and Review**

<p align="center">
  <img src="https://github.com/user-attachments/assets/db689fd2-a5c9-4aec-ae7c-5d908a1741ed" width="600">
</p>



-   **Dashboard Development:**
    1.  **Tools:** Microsoft Power BI Desktop, Microsoft Excel (for Design Thinking).
    2.  **Language:** DAX (Data Analysis Expressions).
    3.  **Process:** Data loading and processing -> Data modeling -> DAX measure development -> Design and construction of interactive dashboard pages.
    4.  Detailed insights and recommendations are compiled and presented in the Design Thinking file (see Project Deliverables).

---
## Dashboard Overview & Key Pages
The dashboard consists of four interactive pages, each focusing on a specific aspect of Superstore's sales performance:

### Business Performance Overview
Provides a high-level summary of key business metrics, sales trends, and regional revenue contributions.
*   **Key Visuals:** KPIs (Total Sales, Avg. Orders/Customer, Return Rate, Avg. Revenue/Order), Total Sales and Sales Growth YoY trend, Top 3 Region Revenue, Top 5 Products with Highest Sales, Return Rate (%) overtime.

![image](https://github.com/user-attachments/assets/d3dd2aa8-f196-478b-babc-75886e5846f7)


---
### Product Performance & Strategic Selection
Dives into product-level analysis, focusing on revenue trends, profitability, sales consistency, and return risk.
*   **Key Visuals:** Top Revenue Products Over Time, Revenue by Category/Sub-Category (Treemap), Top 5 Profitable Products, High Sales vs. Low Returns (Scatter Plot), Top 5 Consistent Products by Sales.
![image](https://github.com/user-attachments/assets/e3762477-d117-4f88-a5a4-47cb278b9db5)


### Market Potential & Revenue Share
Analyzes market performance by region, revenue share, and identifies growth opportunities.
*   **Key Visuals:** Revenue Share by Region & Category, Sales & Growth by Region, Top 6 Market Opportunity Bubble, Top 6 Profitable Regions, Product Distribution by Region (Quantity).
![image](https://github.com/user-attachments/assets/1cc01d39-1da0-46c6-97ee-5bbaaf0a4cfc)


### Return Rate & Operational Risk
Focuses on understanding product returns, identifying high-risk categories/products, and their financial impact.
*   **Key Visuals:** KPIs (Return Rate, Highest Return Category, Avg. Order Value of Returns), Monthly Return Rate Trend, High Sales – High Return Risk Products, Most Frequently Returned Products, Financial Impact of Returns.
![image](https://github.com/user-attachments/assets/91a27a50-e0d6-4628-a0c2-963f4de46d38)


---

## Key Insights & Recommendations
Below is a summary of key actionable insights and recommendations derived from the dashboard (more details in the Design Thinking file):

**1. Overall Business Health:**
*   **Insight:** Substantial total sales (12.64M), but YoY growth shows volatility, slowing significantly in early 2013. The Central region is a major contributor but shows slowing growth.
*   **Recommendation:** Investigate causes of slowing growth, especially in the Central region. Monitor and address spikes in return rates.

**2. Product Strategy:**
*   **Insight:** High-revenue products (e.g., Apple Smart Phone) are not always the most profitable (Canon ImageCLASS leads). The Technology category has high sales but also a high return rate (~11%).
*   **Recommendation:** Prioritize high-profit products. Reduce return rates in the Technology category. Balance portfolio with stable and high-growth/high-risk products.

**3. Market Opportunities:**
*   **Insight:** The large Central region shows negative growth. Oceania demonstrates positive growth. North Asia is a potential emerging market.
*   **Recommendation:** Retain market share in large markets (Central). Invest in growth markets (Oceania, North Asia). Tailor product assortment regionally.

**4. Managing Return Risk:**
*   **Insight:** Furniture has the highest return rate (11.87%). High-value items (e.g., Cisco) have a significant financial impact when returned.
*   **Recommendation:** Prioritize addressing returns for high financial impact items. Analyze frequent returns of low-value items. Reduce return rates in Furniture and Technology.

---

## Usage Instructions
-   Open the `.pbix` file using Microsoft Power BI Desktop.
-   Interact with the dashboard via Slicers (filter by Date, Region, etc.) and cross-filtering by clicking on chart elements. Hover for tooltips.

---
## Project Deliverables
The complete project deliverables are available in a Google Drive folder, including:
1.  **Design Thinking Excel File:** Documenting the design thinking process, including detailed insights and recommendations [View File](https://github.com/Dung040125/Superstore-Sales/raw/main/Design%20Thinking.xlsx)
2.  **Power BI Dashboard (`.pbix` file):** [View Dashboard](https://github.com/Dung040125/Superstore-Sales/raw/main/Project%202.pbix)
