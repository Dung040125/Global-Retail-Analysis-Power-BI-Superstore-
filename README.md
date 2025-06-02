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
- **Understand overall business health and sales trends** by examining sales patterns and Year-over-Year (YoY) growth.
- **Evaluate product performance to guide strategic selection,** by identifying top-performing products (by sales and profitability) and pinpointing those with high return rates.
- **Identify market potential and optimizing revenue share** by analyzing regional/category performance and uncovering untapped growth opportunities.
- **Assess operational risks** by analyzing product and category-specific return rates.

👤 **Who is this project for?**
*   Senior Management & Decision-Makers at Superstore
*   Sales & Marketing Strategists
*   Business Analysts & Data Analysts.

---

## 📂 Dataset Description & Data Structure

📌 **Data Source**
*   **Source:** Superstore sample dataset (simulating global sales data).
*   **Content:** Comprises three main data tables: `Orders` (transaction details), `People` (regional personnel information), and `Returns` (returned transactions).
*   **Time Period Analyzed:** 2011 - 2014.
*   **Format:** Typically Excel (`.xlsx`) or CSV (`.csv`) files.

📊 **Data Structure & Relationships**
The data model consists of three tables: the `Orders` fact table and two dimension tables: `Returns` and `People`.

---

## 🧠 Design Thinking Process
This project applied **Design Thinking principles** to thoroughly understand stakeholder needs and define the dashboard's scope for strategic decision-making. 

1️⃣ **Empathize:** Understood Senior Management's challenges in viewing sales performance and their objectives for market expansion and product strategy.
<p align="center">
  <img src="https://github.com/user-attachments/assets/494069b4-8dea-4005-9eef-9e35eec785bc" alt="Design Thinking: Empathize - Superstore" width="950">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/9fbe401a-3d40-4f0e-b90c-17bc99c6945b" alt="Design Thinking: Empathize - Stakeholder Map Superstore" width="950">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/07e7e3ec-685e-46d9-ade2-7b338ce7567f" alt="Design Thinking: Empathize - Journey Map Superstore" width="450">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/60b6c305-76d4-457a-9bf7-fc6b6c304a92" alt="Design Thinking: Empathize - Journey Map Superstore" width="450">
</p>

2️⃣ **Define (Point of View):** Articulated the core problem: Need for an interactive dashboard to track sales, identify trends, and make data-driven strategic decisions.
<p align="center">
  <img src="https://github.com/user-attachments/assets/4e8837b2-9995-4411-bc03-17f44e451dd5" alt="Design Thinking: Define - POV Superstore" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4da45d16-db8f-4dbe-accd-7af4da960752" alt="Design Thinking: Define - HMW Questions Superstore" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/104cbb88-042a-422c-92fe-cf604ee76b82" alt="Design Thinking: Define - User Needs Superstore" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/1da0783f-9664-4eae-939c-65e46a7bb9c6" alt="Design Thinking: Define - User Needs Superstore" width="650">
</p>

3️⃣ **Ideate:** Brainstormed relevant KPIs, effective visualizations, and user-friendly dashboard layouts.
<p align="center">
  <img src="https://github.com/user-attachments/assets/eb53477d-5ed2-475a-8ecf-6f81f5d40d2a" alt="Design Thinking: Ideate - Brainstorming Superstore" width="600">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/2d556571-15f9-44e1-89e0-2aed519cb2de" alt="Design Thinking: Ideate - Prioritization Superstore" width="850">
</p>

4️⃣ **Prototype and Review:** Developed and iteratively refined Power BI dashboard prototypes based on analytical goals and assumed stakeholder feedback.
<p align="center">
  <img src="https://github.com/user-attachments/assets/4e050424-b681-41bb-8a9a-83d3db19d250" alt="Design Thinking: Prototype - Dashboard Sketch Superstore" width="900">
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
  <img src="https://github.com/user-attachments/assets/3b57cf3d-ac5e-4105-a28c-2733dad21f54" alt="Business Performance Overview Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
The business demonstrates robust health with a **loyal customer base** (averaging 15.75 orders/customer) and a **strong average order value** ($504.99), underpinning **consistent sales growth** from 2011-2014. This upward sales trend follows a **clear seasonal pattern** (lower in H1, uplift in Q3/Q4), offering opportunities for **optimized inventory and marketing planning**.

*   #### **Primary Growth Driver:**
    The "**Central**" region, particularly fueled by "**Consumer**" and "**Corporate**" segments, is the main revenue engine.
    *   💡 Focus marketing resources on the "**Central**" region for these key segments and conduct deeper analysis to **replicate success** in other potential regions.

*   #### **Product Performance & Return Rates:**
    *   High-value categories like **Technology** (e.g., Smartphones) and **Furniture** (premium items) are major sales contributors.
    *   While Furniture & Technology historically had higher return rates than **Office Supplies** (consistently stable below 2%), a significant success is the **clear declining trend in return rates** for these two categories over the years.
    *   💡 Continue initiatives that have successfully reduced returns for Furniture & Technology. Leverage Office Supplies' low return rate and potential high purchase frequency for **customer retention strategies** (e.g., product bundling).

*   #### **Overall:**
    The overall average return rate is **low (2.3%)**, indicating **good product quality** and **customer satisfaction**.

### **Page 2: Product Performance & Strategic Selection**
<p align="center">
  <img src="https://github.com/user-attachments/assets/c298242c-f2b4-4671-a2aa-a6795f0e6d2e" alt="Product Performance & Strategic Selection Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   #### **Technology: Growth Engine & Superior Profitability**
    *   The **"Technology"** category not only **consistently leads in revenue** but also boasts an **impressive profit margin (14%)**. Products like "Copiers" and "Phones" stand out as ⭐ with very high margins (17%).
    *   Nevertheless, the category's return rate (6%, with "Accessories" at 7%) requires monitoring for further optimization.
    *   💡 Continue investing in and developing "Star" products. Conduct a deeper analysis of return reasons for "Accessories" to improve, even though it remains a profitable **Cash Cow (🐄)**.

*   #### **Office Supplies: Operational Efficiency & High Reliability**
    *   **"Office Supplies"** achieves a **high profit margin (14%)** comparable to Technology, primarily driven by high order volume and the **lowest return rate (5-6%)** – a significant strength. "Paper" is a highlight with a 24% profit margin.
    *   "Appliances" is a sub-category to note with a higher return rate (7%) than the category average.
    *   💡 Maintain and leverage the strength of low return rates. Exploit the potential from high order volume and stability for cross-selling strategies or loyalty programs.

*   #### **Furniture: Significant Profitability & Return Risk Challenges**
    *   The **"Furniture"** category faces an **alarming profit margin (only 7%)**. The most critical issue lies with the **"Tables"** sub-category, which is currently **loss-making (-$64K, -8% margin)** and has the highest return rate in its group (8%).
    *   Other sub-categories like "Bookcases" and "Chairs", while profitable, also have return rates (6%) that need improvement.
    *   💡 **Prioritize urgent resolution** for "Tables": thoroughly review quality, pricing, sourcing, or consider delisting. Simultaneously, develop a comprehensive plan to **reduce return rates** for the entire Furniture category.

*   #### **Overall Strategic Outlook:**
    While all categories demonstrate revenue growth, **optimizing profitability and strictly managing return risks** are crucial for sustainable development. Resources should be focused on addressing the issues within the Furniture category, while capitalizing on the strengths of Technology and Office Supplies.

### **Page 3: Market Potential & Revenue Share**
<p align="center">
  <img src="https://github.com/user-attachments/assets/49e14801-ebc0-4307-9413-0bb31cf2e9c5" alt="Market Potential & Revenue Share Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
The regional performance map reveals a clear differentiation: **"Central" is the primary driver** for both revenue and profit ($0.31M) with stable growth. Meanwhile, a group of regions including **"Canada," "Southeast Asia," "EMEA," and "Africa" are experiencing very rapid revenue growth (55-60% YoY) but extremely low profitability**, posing a challenge for optimization strategies.

*   #### **Maximize Core Pillars:**
    *   **"Central," "North," and "North Asia"** are core markets contributing significantly to profit. **"Technology"** is a key category in "Central" and "North," while **"Furniture"** is strong in "North Asia."
    *   💡 Strengthen the position in "Central." Optimize product mix and marketing strategies based on the specific category strengths of "North" and "North Asia" to enhance profitability.

*   #### **Convert Revenue Growth into Profitability:**
    *   High-growth regions like **"Canada" and "Southeast Asia"** (very low profit, e.g., SEA $0.02M) show an imbalance between growth and efficiency.
    *   Notably, **in Canada, "Office Supplies" account for 74% of sales quantity** but do not yield corresponding profits. This indicates significant market share potential for Office Supplies, but **pricing or cost optimization** is needed to improve margins.
    *   💡 Prioritize analysis of cost structures and pricing in high-growth, low-profit regions. For **Canada**, focus on improving profitability from "Office Supplies." Reconsider pricing and product strategies for markets like "Southeast Asia," "EMEA," and "Africa."

*   #### **Restructure or Re-evaluate Underperforming Regions:**
    *   Regions like "East" and "Caribbean" demonstrate low performance and profitability.
    *   💡 Re-evaluate their potential and consider restructuring or reallocating resources to more promising markets.

*   #### **Value-Based Regional Product Strategy:**
    *   The significant disparity between revenue share (higher in "Technology") and quantity share (higher in "Office Supplies") indicates **substantial differences in product value across categories**.
    *   💡 Adjust product portfolios and pricing strategies for each region based on a combination of product value and potential market size, not just sales quantity.

### **Page 4: Return Rate & Operational Risk**
<p align="center">
  <img src="https://github.com/user-attachments/assets/2134f742-092c-4a02-83c0-1201efad26f1" alt="Return Rate & Operational Risk Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
While the overall return rate is **acceptable (2.3%)**, managing **seasonal volatility (peaks in Q2, Q4)** and category-specific risks is key to protecting profitability. Notably, lower-value orders ($268.53) are returned more frequently, indicating the issue extends beyond high-ticket items.

*   #### **Prioritize Risk Reduction for "Vulnerable" Categories:**
    *   **"Furniture" and "Technology"** share high return rates (around 5.8-6.0%), but **"Furniture" faces greater risk due to its lower profit margin compared to "Technology."**
    *   💡 **Actionable:** Focus resources on improving processes (product descriptions, quality control) for the **"Furniture"** category to reduce returns. For **"Technology,"** continue monitoring and optimizing for high return-value products like "Copiers" and "Phones."

*   #### **Address the Dual Impact: High Value & High Volume Returns:**
    *   The financial impact of returns stems from both **high-value items like "Samsung Smartphones"** (significant loss per return) and **low-value items returned in large volumes like "Staples"** (accumulating to substantial losses).
    *   This is particularly evident in **"Office Supplies"**: despite a lower total return value than Technology, it has the highest return count. "Appliances" and "Paper" are hotspots requiring attention.
    *   💡 **Actionable:** Develop a multi-faceted return management strategy: Analyze root causes for both high-value items (ensure quality, accurate information) and high-volume return items (review suppliers, customer expectations).

*   #### **Proactively Manage Peak Return Periods:**
    *   Return **surges in Q2 and Q4** necessitate resource and process preparedness.
    *   💡 **Actionable:** Allocate personnel and optimize return processing workflows during peak periods. Analyze specific drivers of increased returns in these quarters for early preventive measures.

---

## 🔎 Final Conclusion & Recommendations
👉🏻 Based on the comprehensive analysis facilitated by the Power BI dashboards, Superstore's Senior Management should consider the following strategic actions for enhanced operational control and cost-efficiency:

📌 **Key Strategic Recommendations:**
1.  **Optimize Product Portfolio:**
    *   **Urgently Address Weaknesses:** Focus on resolving issues with the loss-making "Tables" Sub-Category (Furniture) and other products/Sub-Categories with high return rates or significant financial impact from returns.
    *   **Enhance "Furniture" Efficiency:** Improve overall profit margins and reduce return rates for this category.
    *   **Leverage Strengths in "Technology" & "Office Supplies":** Continue investing in Technology's "star" performers and replicate the efficiency and low return rates of Office Supplies.

2.  **Intelligent Market Strategy:**
    *   **Strengthen Key Markets ("Central")** and nurture stable, profitable regions.
    *   Develop a profitability roadmap for **high-growth, low-profit markets** (paying special attention to Canada).
    *   Re-evaluate and strategize for underperforming markets.

3.  **Proactive Return Risk Management:**
    *   Analyze **root causes of returns** and improve processes (quality, product descriptions, shipping).
    *   Develop plans to **manage peak return periods** seasonally.

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
