# 📊 Global Retail Analysis - Power BI

<p align="center">
  <img src="https://github.com/user-attachments/assets/f797e137-076a-41b8-b688-38c0d5519113" alt="Superstore Sales Dashboard Overview" width="1100">
</p>

* **Author:** Nguyen Thi Thuy Dung
* **Date:** 2025-04
* **Tools Used:** Microsoft Power BI, DAX, Excel (for Design Thinking)

---

## 📑 Table of Contents
[📌 Background & Overview](#-background--overview)  
[📂 Dataset Description & Data Structure](#-dataset-description--data-structure)  
[🧠 Design Thinking Process](#-design-thinking-process)  
[⚒️ Main Process: Data Preparation & Dashboard Development](#️-main-process-data-preparation--dashboard-development)  
[📊 Key Insights & Visualizations (Dashboard Pages)](#-key-insights--visualizations-dashboard-pages)  
[🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)  
[🚀 Usage Instructions](#-usage-instructions)  
[📂 Project Deliverables](#-project-deliverables)  
[💡 Design Discussions and Decisions](#-design-discussions-and-decisions)

---

## 📌 Background & Overview

### Objective
📖 **What is this project about?**

The primary objective is to provide **Senior Management** with crucial business insights, thereby supporting **strategic decisions related to market expansion and key product selection**. The dashboard focuses on delivering a clear understanding of sales performance, product profitability, market potential, and risks associated with product returns.

This project analyzes Superstore's sales data to:
*   ✔️ Understand overall **business health** and sales trends.
*   ✔️ Evaluate **product performance** and guide strategic selection.
*   ✔️ Identify **market potential** and optimize revenue share.
*   ✔️ Assess **operational risks** by analyzing return rates.

👤 **Who is this project for?**
*   Senior Management & Decision-Makers at Superstore
*   Sales & Marketing Strategists
*   Business Analysts & Data Analysts.

❓ **Business Questions:**
This dashboard addresses critical questions such as:
*   What are the overall sales trends and YoY growth?
*   Which regions and product categories drive revenue and profit?
*   What are our top-performing products by sales and profitability?
*   Are there products/categories with high return rates?
*   Where are untapped market potentials for growth?

🎯 **Project Outcome:**
*   **Comprehensive Performance Overview:** Visualized total sales (12.64M), order metrics, and return rates, highlighting YoY growth volatility.
*   **Product Strategy Insights:** Differentiated high-revenue vs. high-profit products and identified high-return categories.
*   **Market Potential Identification:** Pinpointed growth markets vs. saturated/declining ones.
*   **Risk Mitigation Foundation:** Provided insights into products with high financial impact from returns.

---

## 📂 Dataset Description & Data Structure

📌 **Data Source**
*   **Source:** Superstore sample dataset (simulating global sales data).
*   **Content:** Comprises three main data tables: `Orders` (transaction details), `People` (regional personnel information), and `Returns` (returned transactions).
*   **Time Period Analyzed:** 2011 - 2014.
*   **Format:** Typically Excel (`.xlsx`) or CSV (`.csv`) files.

📊 **Data Structure & Relationships**
The Superstore dataset consists of structured tables. For this analysis, a relational data model was built in Power BI to connect the `Orders`, `People`, and `Returns` tables, enabling comprehensive analysis. Key relationships were established primarily using `Order ID` (to link `Orders` and `Returns`) and `Region` (to potentially link sales data with personnel).

---

## 🧠 Design Thinking Process
This project applied **Design Thinking principles** to thoroughly understand stakeholder needs and define the dashboard's scope for strategic decision-making. 

1️⃣ **Empathize:** Understood Senior Management's challenges in viewing sales performance and their objectives for market expansion and product strategy.
<p align="center">
  <img src="https://github.com/user-attachments/assets/3dbb6bf5-a117-4de4-8bbf-55d8a558147d" alt="Design Thinking: Empathize - Superstore" width="700">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/0559cccd-44f8-41eb-8e44-f8f47784feb7" alt="Design Thinking: Empathize - Stakeholder Map Superstore" width="700">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/5bda57e1-4e65-4a9a-a7b7-0ee38985e50a" alt="Design Thinking: Empathize - Journey Map Superstore" width="700">
</p>

2️⃣ **Define (Point of View):** Articulated the core problem: Need for an interactive dashboard to track sales, identify trends, and make data-driven strategic decisions.
<p align="center">
  <img src="https://github.com/user-attachments/assets/4b22e569-22d6-44c5-833b-621572e55e2b" alt="Design Thinking: Define - POV Superstore" width="700">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/188c3692-5cae-4318-8a04-93e63b0e5180" alt="Design Thinking: Define - HMW Questions Superstore" width="700">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4f9da449-f490-4592-bded-b433adf3a31d" alt="Design Thinking: Define - User Needs Superstore" width="700">
</p>

3️⃣ **Ideate:** Brainstormed relevant KPIs, effective visualizations, and user-friendly dashboard layouts.
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4a7dbb9-64e7-4421-9d8e-768585f5b2c6" alt="Design Thinking: Ideate - Brainstorming Superstore" width="700">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/8cb30af8-699d-451f-8421-2c9712a335e2" alt="Design Thinking: Ideate - Prioritization Superstore" width="700">
</p>

4️⃣ **Prototype and Review:** Developed and iteratively refined Power BI dashboard prototypes based on analytical goals and assumed stakeholder feedback.
<p align="center">
  <img src="https://github.com/user-attachments/assets/db689fd2-a5c9-4aec-ae7c-5d908a1741ed" alt="Design Thinking: Prototype - Dashboard Sketch Superstore" width="700">
</p>

---

## ⚒️ Main Process: Data Preparation & Dashboard Development

### 1️⃣ Data Preparation (Power Query & DAX)
*   Connected to Superstore source files (Orders, People, Returns) in Power BI.
*   Cleaned and transformed data using **Power Query Editor** (handled missing values, standardized data types).
*   Built a relational data model, establishing table relationships.
*   Created essential **DAX measures** and calculated columns for key metrics (e.g., `Return Rate %`, `Sales Growth YoY`, `Total Sales`).

### 2️⃣ Power BI Visualization & Dashboarding
Developed a multi-page interactive dashboard in Power BI focusing on clear data presentation for strategic decision-making.

---

## 📊 Key Insights & Visualizations (Dashboard Pages)

🔍 **Dashboard Previews & Analysis**

The Superstore Sales dashboard is structured into four user-centric pages:

### **Page 1: Business Performance Overview**
<p align="center">
  <img src="https://github.com/user-attachments/assets/62d9d836-3e5a-4182-87a0-e060fb007c20" alt="Business Performance Overview Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **Overall Performance:** The dashboard reveals **Total Sales of 12.64M** and an Average Revenue/Order of 504.15. However, **Sales Growth YoY trend shows significant volatility**, with a notable slowdown in early 2013.
*   **Regional Contributions:** The **Central region is a major revenue contributor** but shows signs of slowing growth.
*   **Return Rate:** An overall low **Return Rate of 2.3%** is positive, but overtime visuals show occasional spikes.
*   **Recommendations:** Investigate causes of YoY growth volatility and Central region's slowdown. Address return rate spikes proactively.

### **Page 2: Product Performance & Strategic Selection**
<p align="center">
  <img src="https://github.com/user-attachments/assets/a41168b9-726d-4329-8d7b-1d03a63db26f" alt="Product Performance & Strategic Selection Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **Revenue vs. Profitability:** Key distinction between top revenue-generating products (e.g., Apple Smart Phone) and **most profitable ones (e.g., Canon ImageCLASS)**.
*   **Category Performance:** **Technology category drives high sales but also has a high return rate (~11%)**. Office Supplies are safer with lower returns but lower sales.
*   **Sales Consistency:** Some products show more consistent sales, crucial for stable revenue forecasting.
*   **Recommendations:** Prioritize high-profit products. Mitigate high return rates in Technology. Balance portfolio with consistent performers and high-growth items.

### **Page 3: Market Potential & Revenue Share**
<p align="center">
  <img src="https://github.com/user-attachments/assets/f8744e14-2e8d-474b-8478-f5213e51e0db" alt="Market Potential & Revenue Share Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **Regional Growth Dynamics:** Central region, despite high revenue, shows negative sales growth. **Oceania and North Asia emerge as high-potential growth markets**.
*   **Revenue Share by Category:** Varies significantly by region, suggesting differing market demands.
*   **Product Distribution:** Quantity-based distribution highlights regional product preferences.
*   **Recommendations:** Retain market share in large, slowing markets. Invest in growth markets (Oceania, North Asia). Tailor regional product assortment and marketing.

### **Page 4: Return Rate & Operational Risk**
<p align="center">
  <img src="https://github.com/user-attachments/assets/7dbf5ef0-b0e7-483b-9613-c8c4ef2f73f7" alt="Return Rate & Operational Risk Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **High-Risk Categories:** **Furniture category has the highest return rate (11.87%)**. Technology also shows high returns.
*   **Financial Impact of Returns:** High-value items (e.g., Cisco, Canon) have substantial financial impact per return.
*   **Frequently Returned Products:** Low-value items like "Staples" incur operational costs due to frequent returns.
*   **Recommendations:** Prioritize addressing returns for high financial impact items. Analyze root causes for frequently returned items. Implement targeted strategies for high-risk categories.

---

## 🔎 Final Conclusion & Recommendations
👉🏻 Based on the comprehensive analysis facilitated by the Power BI dashboards, Superstore's Senior Management should consider the following strategic actions for enhanced operational control and cost-efficiency:

📌 **Key Takeaways & Actionable Recommendations:**
*   ✔️ **Strategic Market Focus:** Invest in high-potential markets like **Oceania and North Asia** while developing strategies to rejuvenate growth in established but slowing regions like **Central**. This involves tailored marketing and potentially differentiated product offerings.
*   ✔️ **Product Portfolio Optimization:** Prioritize and promote **high-profitability products** (e.g., Canon ImageCLASS). Implement targeted measures to reduce return rates in high-risk, high-sales categories such as **Technology and Furniture** (e.g., clearer product descriptions, improved packaging, or post-purchase support).
*   ✔️ **Enhanced Customer Experience & Regional Tailoring:** Leverage insights on regional product preferences and customer behavior (from market potential and product distribution visuals) to **tailor product assortments and marketing campaigns** for specific regions, potentially increasing sales and customer satisfaction.
*   ✔️ **Operational Risk Management & Efficiency:** Actively manage product returns by addressing root causes for both **high-financial-impact returns** (e.g., Cisco products) and **frequently returned low-value items** (e.g., Staples) to reduce operational overhead and protect margins.
*   ✔️ **Continuous Data-Driven Improvement:** Regularly utilize the developed dashboards to **monitor key performance indicators (KPIs)**, identify new trends or anomalies, and make agile, informed business decisions to adapt to changing market conditions.

---

## 🚀 Usage Instructions
*   Open the `.pbix` file using **Microsoft Power BI Desktop**.
*   Interact with the dashboard using **Slicers** (e.g., for `Date`, `Region`, `Category`) and by clicking on visual elements for **cross-filtering**.
*   Hover over visuals to view detailed **tooltips**.

---

## 📂 Project Deliverables
1.  **Power BI Dashboard (`.pbix` file):** [View Dashboard](https://github.com/Dung040125/Superstore-Sales/raw/main/Project%202.pbix)
2.  **Design Thinking Excel File:** Documents the user-centric design process, detailed analysis, and initial recommendations. [View file](https://github.com/Dung040125/Superstore-Sales/raw/main/Design%20Thinking.xlsx)
3.  **This README.md file:** Provides a comprehensive overview of the project.

---
## 💡 Design Discussions and Decisions
Key interpretations and design choices for this project included:
*   **Focus on Strategic KPIs for Senior Management:** Prioritized metrics directly relevant to market expansion strategies, product performance evaluation, and overall business health.
*   **User-Centric Dashboard Navigation:** Organized insights into four distinct and intuitively named dashboard pages (`Business Performance Overview`, `Product Performance & Strategic Selection`, `Market Potential & Revenue Share`, `Return Rate & Operational Risk`) for targeted and clear analysis pathways.
*   **Emphasis on Visual Storytelling:** Selected chart types (e.g., YoY trends, treemaps for category revenue, bubble charts for market opportunities) specifically to convey complex sales performance data and relationships in an accessible manner for executive review.
*   **Iterative Design Based on Assumed Needs:** The dashboard structure and featured visualizations were developed iteratively, anticipating the core questions and analytical requirements of a typical senior management team in an e-commerce context.

*(Further details supporting these decisions are documented in the Design Thinking Excel File.)*
