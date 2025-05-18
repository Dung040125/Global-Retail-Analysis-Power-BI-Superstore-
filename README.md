# 📊 **Project Title:** Superstore Sales Performance Dashboard

<p align="center">
  <img src="https://github.com/user-attachments/assets/f797e137-076a-41b8-b688-38c0d5519113" alt="Superstore Sales Dashboard Overview" width="1100">
</p>

**Author:** Nguyen Thi Thuy Dung
**Date:** 2025-04
**Tools Used:** Microsoft Power BI, DAX, Excel (for Design Thinking)

---

## 📑 Table of Contents
- [📌 Background & Overview](#-background--overview)
- [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
- [🧠 Design Thinking Process](#-design-thinking-process)
- [⚒️ Main Process: Data Preparation & Dashboard Development](#️-main-process-data-preparation--dashboard-development)
- [📊 Key Insights & Visualizations (Dashboard Pages)](#-key-insights--visualizations-dashboard-pages)
- [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)
- [🚀 Usage Instructions](#-usage-instructions)
- [📂 Project Deliverables](#-project-deliverables)
- [💡 Design Discussions and Decisions](#-design-discussions-and-decisions)

---

## 📌 Background & Overview

### Objective
📖 **What is this project about?**

This project presents an interactive **Power BI dashboard** designed to analyze Superstore's global sales data. The primary objective is to provide **Senior Management** with crucial business insights, thereby supporting **strategic decisions related to market expansion and key product selection**. The dashboard focuses on delivering a clear understanding of sales performance, product profitability, market potential, and risks associated with product returns.

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
*   **Content:** Comprises three main data tables: `Orders`, `People` and `Returns`.
*   **Time Period Analyzed:** 2011 - 2014.
*   **Format:** Typically Excel (`.xlsx`) or CSV (`.csv`) files.

📊 **Data Structure & Relationships**
The Superstore dataset consists of structured tables. For this analysis, a relational data model was built in Power BI to connect the `Orders`, `People`, and `Returns` tables, enabling comprehensive analysis across different facets of the sales data. Key relationships were established primarily using `Order ID` (to link `Orders` and `Returns`) and `Region` (to potentially link sales data with personnel).

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
*   Created essential **DAX measures** and calculated columns for key metrics (e.g., `Return Rate %`, `Sales Growth YoY`).

### 2️⃣ Power BI Visualization & Dashboarding
Developed a multi-page interactive dashboard in Power BI focusing on clear data presentation for strategic decision-making.

---

## 📊 Key Insights & Visualizations (Dashboard Pages)

🔍 **Dashboard Previews & Analysis**

The Superstore Sales dashboard is structured into four user-centric pages:

### **Page 1: Business Performance Overview**
<p align="center">
  <img src="https://github.com/user-attachments/assets/d3dd2aa8-f196-478b-babc-75886e5846f7" alt="Business Performance Overview Dashboard" width="700">
</p>

📌 **Analysis & Insights:**
*   **Overall Performance:** The dashboard reveals **Total Sales of 12.64M** and an Average Revenue/Order of 504.15, indicating a healthy average transaction value. However, the **Sales Growth YoY trend shows significant volatility**, with a notable slowdown and dip into negative growth in early 2013 before a slight recovery. This highlights a need for deeper investigation into factors causing these fluctuations.
*   **Regional Contributions:** The **Central region is a major revenue contributor**, particularly from the Consumer segment. However, this region also shows signs of slowing growth, warranting closer attention.
*   **Return Rate:** An overall low **Return Rate of 2.3%** is positive, but the "Return Rate (%) overtime" visual shows occasional spikes (e.g., early 2012), suggesting periods of potential product quality or customer dissatisfaction issues that need to be managed.
*   **Recommendations:** Investigate root causes of YoY growth volatility and the slowdown in the Central region. Implement proactive measures to address and prevent spikes in return rates.

### **Page 2: Product Performance & Strategic Selection**
<p align="center">
  <img src="https://github.com/user-attachments/assets/e3762477-d117-4f88-a5a4-47cb278b9db5" alt="Product Performance & Strategic Selection Dashboard" width="700">
</p>

📌 **Analysis & Insights:**
*   **Revenue vs. Profitability:** A key insight is the distinction between top revenue-generating products (e.g., Apple Smart Phone) and the **most profitable products (e.g., Canon ImageCLASS leads)**. This suggests that a strategy focused solely on sales volume might not maximize overall profitability.
*   **Category Performance:** The **Technology category drives high sales but also exhibits a high return rate (~11%)**, indicating a trade-off between revenue and operational risk. Office Supplies, while lower in sales, tend to have lower return rates.
*   **Sales Consistency:** Some products (e.g., Canon, Cisco Tel...) show more consistent sales, crucial for stable revenue forecasting, while others (e.g., 3D Systems) are more volatile.
*   **Recommendations:** Prioritize marketing and sales efforts for high-profit products. Develop strategies to mitigate high return rates in the Technology category (e.g., improved product information, quality checks). Balance the product portfolio by nurturing consistent performers alongside high-growth/high-risk items.

### **Page 3: Market Potential & Revenue Share**
<p align="center">
  <img src="https://github.com/user-attachments/assets/1cc01d39-1da0-46c6-97ee-5bbaaf0a4cfc" alt="Market Potential & Revenue Share Dashboard" width="700">
</p>

📌 **Analysis & Insights:**
*   **Regional Growth Dynamics:** The Central region, despite high revenue, is experiencing negative sales growth, indicating market saturation or increased competition. Conversely, **Oceania shows positive sales growth** albeit from a smaller revenue base, and **North Asia emerges as a high-potential market** with good growth.
*   **Revenue Share by Category:** Revenue share for categories like Technology, Furniture, and Office Supplies varies significantly by region, suggesting differing market demands or competitive landscapes.
*   **Product Distribution:** The quantity-based product distribution highlights that different product categories dominate order volumes in specific regions (e.g., Office Supplies in EMEA, Africa).
*   **Recommendations:** Implement strategies to retain market share in large but slowing markets like Central. Allocate resources to capitalize on growth in Oceania and North Asia. Tailor product assortment and marketing campaigns to specific regional demands and category strengths.

### **Page 4: Return Rate & Operational Risk**
<p align="center">
  <img src="https://github.com/user-attachments/assets/91a27a50-e0d6-4628-a0c2-963f4de46d38" alt="Return Rate & Operational Risk Dashboard" width="700">
</p>

📌 **Analysis & Insights:**
*   **High-Risk Categories:** The **Furniture category has the highest return rate (11.87%)**, posing a significant operational challenge despite not being the top sales category. The Technology category also shows high returns.
*   **Financial Impact of Returns:** High-value items (e.g., Cisco TelePresence, Canon ImageCLASS), even if not returned frequently, have a substantial financial impact per return, affecting overall profitability.
*   **Frequently Returned Products:** Lower-value items like "Staples" are frequently returned, leading to increased processing and reverse logistics costs.
*   **Return Trends:** While the overall monthly return rate trend shows a decrease since 2012, continuous fluctuations indicate ongoing underlying issues.
*   **Recommendations:** Prioritize addressing returns for products with high financial impact. Analyze root causes for frequently returned low-value items (e.g., incorrect orders, quality issues). Implement targeted strategies to reduce return rates in high-risk categories like Furniture and Technology.
---

## 🔎 Final Conclusion & Recommendations
👉🏻 Based on the dashboard analysis, Superstore's Senior Management should consider:

📌 **Key Takeaways:**
*   ✔️ **Strategic Market Focus:** Invest in high-potential markets (Oceania, North Asia) and rejuvenate growth in established regions (Central).
*   ✔️ **Product Portfolio Optimization:** Prioritize high-profitability products and manage returns in high-risk categories.
*   ✔️ **Enhanced Customer Experience:** Tailor regional product assortments and marketing.
*   ✔️ **Operational Risk Management:** Actively manage product returns by addressing root causes.
*   ✔️ **Continuous Data-Driven Improvement:** Regularly use the dashboard for performance monitoring and agile decisions.

---

## 🚀 Usage Instructions
*   Open the `.pbix` file using **Microsoft Power BI Desktop**.
*   Interact with Slicers and use cross-filtering; hover for tooltips.

---

## 📂 Project Deliverables
1.  **Power BI Dashboard (`.pbix` file):** [View Dashboard](https://github.com/Dung040125/Superstore-Sales/raw/main/Project%202.pbix)
2.  **Design Thinking Excel File:** Documents the user-centric design process. [View file](https://github.com/Dung040125/Superstore-Sales/raw/main/Design%20Thinking.xlsx)

---
## 💡 Design Discussions and Decisions

Key interpretations and design choices for this project included:
*   **Focus on Strategic KPIs:** Prioritized metrics for market expansion and product strategy relevant to Senior Management.
*   **User-Centric Dashboard Flow:** Organized insights into four distinct dashboard pages for targeted analysis.
*   **Data Storytelling through Visuals:** Selected chart types to clearly convey complex sales performance data.

*(Further details are documented in the Design Thinking Excel File.)*
