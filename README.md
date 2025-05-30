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
  <img src="https://github.com/user-attachments/assets/eb53477d-5ed2-475a-8ecf-6f81f5d40d2a" alt="Design Thinking: Ideate - Brainstorming Superstore" width="800">
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
  <img src="https://github.com/user-attachments/assets/a1a3338f-7b45-4fde-aa55-a17da30e9070" alt="Business Performance Overview Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
* **Detailed Insights:**
1.  **Overall KPIs:**
    *   **Total Sales:** $12.64M (over the entire analysis period).
    *   **Average Orders/Customer:** 15.75 -> indicating high customer loyalty or repeat purchase behavior.
    *   **Return Rate (%):** 2.3% –> a relatively low overall average.
    *   **Average Revenue/Order:** $504.99 -> a good average order value.

2.  **Total Sales and Sales Growth YoY:**
    *   **Sales Trend:** Stable growth from 2011-2014.
    *   **Seasonality:** Q4 typically shows lower sales compared to other quarters within the same year, with the exception of Q4/2014 which experienced outstanding growth. Q2 and Q3 are generally strong quarters.
    *   **YoY Growth:** Consistently positive throughout 2011-2014, with no quarters showing negative growth.

3.  **Top 5 Region Revenue:**
    *   "Central" is the leading region, primarily driven by "Consumer" and "Corporate" segments.
    *   "South" follows as the second highest. Other regions contribute less.

4.  **Top 3 Highest Sales Product In Each Category:**
    *   **Technology:** Smartphones lead with high sales revenue.
    *   **Furniture:** Office/premium items perform well.
    *   **Office Supplies:** Top products in this category have significantly lower individual sales revenue.

5.  **Quarterly Return Rate (%) by Category:**
    *   **Office Supplies:** Consistently the lowest and most stable return rate (typically below 2%).
    *   **Furniture & Technology:** Higher and more volatile return rates, but show a significant declining trend over the years. Peaks in return rates for these categories in early 2011 and early 2012 are noteworthy.

* **Key Data Story:**
The business demonstrates a **loyal customer base** (averaging 15.75 orders/customer) with a **healthy average order value** ($504.99). From 2011 to 2014, sales **consistently grew**, highlighted by a **significant surge in Q4/2014**. The **"Central" region is the primary revenue driver**, with Technology and Furniture products contributing substantially. While the overall average return rate is low (2.3%), a deeper dive by category reveals that Furniture and Technology historically had higher return rates. However, a notable success is the **declining trend in return rates** for these two categories over the years, while Office Supplies has consistently maintained a **very low return rate**.

### **Page 2: Product Performance & Strategic Selection**
<p align="center">
  <img src="https://github.com/user-attachments/assets/b838e9c7-9558-4d14-93e9-d4c7be458274" alt="Product Performance & Strategic Selection Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
* **Detailed Insights:**
1.  **Quarterly Revenue by Category:**
    *   All three categories (Technology, Furniture, Office Supplies) exhibit a **general upward revenue trend** from Q1 2011 to Q4 2014.
    *   **"Technology" consistently leads in revenue**, with a strong surge from mid-2012 onwards.
    *   Seasonality is evident, with Q4 often being strong (especially Q4/2014), while Q1 may be slower.

2.  **Category Profitability & Performance (Category Profitability Bar Chart & Key Metrics Matrix):**
    *   **"Technology":** Leads in Total Profit ($663K) and Profit Margin (14%). However, its Return Rate (6% at Category level, with some Sub-Categories like "Accessories" at 7%) needs monitoring for further optimization. "Copiers" and "Accessories" demonstrate very high profit margins (17%).
    *   **"Office Supplies":** Second highest profit ($518K) with an impressive Profit Margin (14%), matching Technology. Its standout strength is the **lowest Return Rate (5-6% at Category level)** and the highest number of orders. "Paper" is a highlight with a 24% profit margin. "Appliances" have a higher return rate (7%) within this group.
    *   **"Furniture":** Lowest profit ($285K) and an alarming Profit Margin (7%). **"Tables" is the most critical issue with a negative profit (-$64K) and -8% margin**, coupled with the highest return rate in the Furniture group (8%). Other Sub-Categories like "Bookcases" and "Chairs" are profitable but also have return rates needing improvement (6%).

3.  **Product Portfolio Analysis (Bubble Chart):**
    *   **"Stars" (High Profit, Good Growth):** "Copiers" and "Phones" (Technology).
    *   **"Cash Cows" (Good Profit, Stable Growth):** "Accessories" (Technology), "Bookcases" (Furniture), "Storage" (Office Supplies).
    *   **"Question Marks" (Decent Growth, Profitability Needs Improvement):** "Chairs" (Furniture), "Machines" (Technology).
    *   **"Dogs" / Urgent Action Needed (Low/Negative Profit):** **"Tables" (Furniture)**. Many smaller Office Supplies Sub-Categories and "Furnishings" (Furniture) also reside in lower performance anan.

*   **Key Data Story:**
This dashboard reveals a multi-faceted picture: **"Technology" stands out as the undisputed leader** in both revenue and profitability, with "stars" like "Copiers" and "Phones" boasting **impressive profit margins**. **"Office Supplies" emerges as an "efficiency powerhouse"**; despite a lower average order value, its **superior order volume**, high profit margin, and **extremely low return rate** contribute significantly to overall profitability. Conversely, **"Furniture" faces substantial profitability challenges**, most critically with the **"Tables" Sub-Category incurring significant losses** and having the **highest return rate** within its group. While all categories show overall revenue growth, **optimizing profitability and managing return risks**, especially for Furniture, are crucial for sustainable development.

### **Page 3: Market Potential & Revenue Share**
<p align="center">
  <img src="https://github.com/user-attachments/assets/933db2e8-ea83-4459-b1f6-45dc2d628d92" alt="Market Potential & Revenue Share Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **Detailed Insights:**
1.  **Regional Performance Matrix (Bubble Chart):**
    *   **"Central":** Leads in Sales, Profit, and has good YoY Growth (~50%).
    *   **"North," "North Asia":** Good profitability, stable growth (~45-50%).
    *   **High Growth - Low Profit Group:** "Canada," "Southeast Asia," "EMEA," "Africa" show high Sales Growth YoY % (55-60%) but very low profits.
    *   **Lower Performance Group:** "East," "Caribbean."

2.  **Revenue Share by Region & Category:**
    *   **"Technology"** holds a large revenue share in strong markets like Central (36.8%) and North (39.7%).
    *   **"Furniture"** has a high revenue share in North Asia (39.6%) and Southeast Asia (35.4%).
    *   **"Office Supplies"** contributes significantly to revenue share, highest in EMEA (34.3%), Africa (34.0%), and Central Asia (37.8%).

3.  **Regional Profitability Ranking:**
    *   "Central" ($0.31M) is the most profitable region by a significant margin.
    *   "North" ($0.19M) and "North Asia" ($0.17M) follow.
    *   "Caribbean" ($0.03M) and "Southeast Asia" ($0.02M) have very low profitability.

4.  **Regional Product Distribution (by Quantity):**
    *   **"Office Supplies" dominates in quantity** in many markets: **Canada (74%)**, Central (63%), EMEA (65%), Africa (67%).
    *   "Technology" has a much lower quantity share compared to its revenue share in most regions, indicating higher product value.
    *   The difference between revenue share and quantity share highlights the varying average product values of Categories in each Region.

* **Key Data Story:**
The market performance map reveals a clear differentiation: The **"Central" region is the outstanding "star"**, leading in both revenue and profit while maintaining good growth. Developed markets like **"North" and "North Asia" are also crucial profit pillars**. A group of regions, including **"Canada," "Southeast Asia," "EMEA," and "Africa," are showing very rapid revenue growth but low profitability.** What's particularly striking about **Canada is that "Office Supplies" constitute a massive 74% of product quantity sold**, indicating a large consumer base for these items but potentially lower average order values or profit margins per Office Supplies item, contributing to the region's low overall profit despite good revenue growth. Revenue share analysis shows a different picture: "Technology" often commands a larger revenue share in many areas due to higher product value, while "Furniture" has a high revenue share in markets like North Asia and Southeast Asia.

### **Page 4: Return Rate & Operational Risk**
<p align="center">
  <img src="https://github.com/user-attachments/assets/c1dfd2f0-b12f-4098-8a19-640e16c4c65d" alt="Return Rate & Operational Risk Dashboard" width="900">
</p>

📌 **Analysis & Insights:**
*   **Detailed Insights:**
1.  **Overall Return KPIs:**
    *   **Overall Return Rate:** 2.3% - company-wide average.
    *   **Average Order Value of Returns:** $268.53 - lower than the general average order value, suggesting lower-value items/orders are more frequently returned.

2.  **Quarterly Return Rate Trend (X-axis updated to Year -> Quarter):**
    *   Return rates fluctuate quarterly, with **notable peaks often appearing in Q2 and Q4 of multiple years** (e.g., Q2/2011, Q4/2011, Q2/2012, Q4/2012, Q4/2013, Q2/2014, Q4/2014). This may be linked to specific purchasing cycles or other seasonal factors.
    *   The general trend from 2011-2014 appears relatively stable or shows a slight decrease after accounting for quarterly fluctuations.

3.  **Category Risk-Reward Matrix (Sales vs. Return Rate, Sized by Profit):**
    *   **"Technology":** Highest Sales and Profit (largest bubble size), but with a moderate-to-high Return Rate (~5.8%).
    *   **"Furniture":** Significant Sales, considerably lower Profit (smaller bubble than Technology), and a similar moderate-to-high Return Rate (~5.8-6.0%).
    *   **"Office Supplies":** Lowest Sales among the three, but also the lowest Return Rate (~5.0%) and decent profitability (medium bubble size).

4.  **Detailed Product Return Analysis (Matrix Table):**
    *   **Technology:** "Copiers" and "Phones" lead in both `Return Count` and `Total Value of Returns for Product`, with product-specific return rates (`Return_Rate by Product`) around 6-7%.
    *   **Office Supplies:** Highest overall `Return Count`, but lower `Total Value of Returns` than Technology due to lower product values. "Appliances" is a Sub-Category to watch. "Paper" has a higher `Return Rate by Product` (7%) despite low return count and value.
    *   **Furniture:** (The Matrix screenshot shows partial data; full data is needed for a complete product-specific analysis).

5.  **Top Products by Financial Impact of Returns:**
    *   High-value items like **"Samsung Smart Phone, VoIP"** (approx. $19.7K in returned value) cause the largest financial hit per return.
    *   Low-value items with high return volumes, such as **"Staples"** (approx. $15.6K), also accumulate a significant financial impact.

**Key Data Story:**
While the company's overall average return rate is at an acceptable level **(2.3%)**, a deeper analysis reveals strategic areas of concern. The quarterly return trend **("Quarterly Return Rate Trend")** shows **clear volatility, with peaks typically occurring in Q2 and Q4 of several years**, suggesting seasonal factors or post-purchase cycles that need management. Category-wise, **"Furniture" and "Technology" exhibit higher return rates (around 5.8-6.0% on the Scatter Plot) than "Office Supplies" (around 5.0%)**. Notably, while "Technology" boasts high profitability (indicated by its large bubble size in the "Category Risk-Reward Matrix") to somewhat offset this risk, "Furniture" is more vulnerable due to its lower profit efficiency despite a similar return risk. A crucial finding is that the **financial impact of returns stems not only from high-value items but also from low-value items returned in large volumes, such as "Staples"**. This underscores the importance of managing return risks broadly to protect profitability and optimize operations.

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
