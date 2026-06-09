# 🍔 Zomato Marketplace Optimization & Revenue Performance Suite

## 📌 Project Quick Links
*   📊 **[Download Dashboard (.pbix)](https://drive.google.com/drive/u/3/folders/1uiJXsCPkkss843CoMRan76lpV7_AMOjn)** — *Open the complete interactive project file directly.*
*   🔢 **[View DAX Modeling Folder (./dax-queries/)](https://github.com/Nikhil-Sagar29/Zomato-Bengaluru-Restaurant-Dashboard/blob/main/04-Zomato%20DAX%20Formulas/Important%20DAX%20formulas%20used.txt)** — *Explore the clean relational DAX formulas.*
*   📂 **[Access Source Dataset (./dataset/)](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants/data)** — *Review the regional 51K merchant sample records.*

---

## 📸 Dashboard Preview

### Page 1: Executive Revenue & Platform Performance
![Executive Dashboard](https://github.com/Nikhil-Sagar29/Zomato-Bengaluru-Restaurant-Dashboard/blob/main/03-Zomato%20Dashboard%20Image/02_Dashboard%20Overview.jpg)

### Page 2: Merchant Insights & Cloud Kitchen Expansion
![Merchant Analytics](https://github.com/Nikhil-Sagar29/Zomato-Bengaluru-Restaurant-Dashboard/blob/main/03-Zomato%20Dashboard%20Image/04_Business%20Insights.jpg)

### Page 3: Consumer Trends & Experience Analytics
![Customer Insights](https://github.com/Nikhil-Sagar29/Zomato-Bengaluru-Restaurant-Dashboard/blob/main/03-Zomato%20Dashboard%20Image/05_Customer%20Insights.jpg)

---

## 📊 Platform Scale at a Glance (Macro Totals)
*   **Gross Merchandise Value (GMV):** ₹28.53M  
*   **Total Platform Orders:** 51,717  
*   **Zomato Net Corporate Income:** ₹6.52M  
*   **Blended Corporate Take Rate:** 22.86%  
*   **Average Order Value (AOV):** ₹552  

---

## 🚀 Business Insights & Strategic Problem-Solving Matrix

The analysis transitions raw marketplace data into targeted operational resolutions for Zomato's corporate leadership:


| Core Business Problem | Analytical Solution / Approach | Actionable Business Insight Found |
| :--- | :--- | :--- |
| **Merchant Feature Under-Monetization** <br><br> Sales teams struggle to convince restaurants to adopt premium app features. | Developed a **Feature Monetization Lift Analysis** comparing Average Order Values (AOV) across segments. | Activating the "Table Booking" feature triggers a **40%+ jump in basket sizes** inside high-margin categories like *Buffet* and *Drinks & Nightlife*. |
| **Cloud Kitchen Deployment Blindspots** <br><br> High-population counts mask true culinary supply shortages. | Constructed a custom **Demand Volume Per Restaurant** tracking metric (`Votes / Unique Partner Names`). | Bypassed standard order counts to uncover massive, underserved delivery voids in specific target neighborhoods like *Bellandur*. |
| **Inefficient Merchant Acquisition** <br><br> High-volume zones over-saturate resources compared to low-volume, high-margin hubs. | Deployed a **Price Elasticity Scatter Matrix** mapping individual merchant names against platform take-rates. | Outlier mapping proved that specific premium neighborhoods generate identical income to massive cash cows with **half the order volume** due to inflated basket checkouts. |

### 🔍 Deep-Dive Business Insight Interpretations

### Key Takeaways

* **🏆 The Marketplace Power Law:** Budget vs. Luxury dynamics.
  * **Traffic Drivers:** A tiny **1% tier of budget restaurants captures 80% of customer votes**, driving platform engagement.
  * **Margin Sustainers:** A separate tier of luxury fine-dining outlets sustains net corporate profit margins.
* **📈 The Table Booking Value Pitch:** B2B monetization strategy.
  * **AOV Lift:** Activating table bookings proves a significant mathematical lift in customer basket size.
  * **Action:** Merchant success teams can use this proof to pitch premium features to high-volume casual dining spots.
* **⚖️ Volume vs. Margin Balance:** Fleet and logistics optimization.
  * **Fleet Footprint:** Premium zones match the total revenue of high-volume student hubs with a fraction of the delivery traffic.
  * **Action:** Optimizes rider distribution by shifting resources toward high-basket routes to maximize efficiency.
* **🚨 Supply Shortage Anomalies:** Smart cloud kitchen expansion.
  * **Pressure Mapping:** Dividing engagement by unique vendor counts uncovers true supply voids missed by standard data.
  * **Action:** Enables the real estate team to pitch ready-to-convert spaces to target culinary brands.
---

## 🎯 Project Objectives
*   **Calculate True Revenue:** Separate commissions from third-party gateway fees and tax liabilities (GST).
*   **Map Market Saturation:** Spot neighborhood supply voids to guide cloud kitchen expansions.
*   **Prove Premium Feature Value:** Measure check-size premium when partners adopt table reservations.
*   **Clean Data Anomalies:** Safely isolate `"NEW"` or `"-"` text values without biasing macro averages.

---

## 👥 Data Handling & Custom Segmentation
Raw rating strings (like `"4.1/5"`) were parsed and grouped using conditional logic into active visual tiers:
*   **Unrated / New:** Newly onboarded partners lacking a historical data footprint.
*   **Very Good (Top-Tier):** High-compliance merchants maintaining a metric rating $\geq 4.0$.
*   **Average (Mid-Market):** Stable marketplace vendors scaling between $3.0$ and $3.9$.
*   **At-Risk (High-Churn):** Low-performing danger sectors tracking below a $2.9$ score.

---

## ⚙️ Technical Implementation Summary

### 🔹 Core Toolstack
*   **Power BI Desktop:** Modern dark-themed application layer (`#1C1C1C` base / `#242424` containers).
*   **Power Query / M-Language:** Fraction delimiter splitting, type assignments, and null mapping.
*   **Advanced DAX:** Explicit measures contained inside a separate data folder.

### 🔹 Engineering Solutions Applied
*   **Cleared Label Clutter:** Solved overlapping dual-axis text blocks by hiding column totals and optimizing line scales.
*   **Eliminated Visual Friction:** Replaced competing location bar charts with a single, high-contrast scatter plot matrix.
*   **Fixed PDF Export Backgrounds:** Overrode the white PDF print bug by shifting colors directly to the Canvas Background at `0%` transparency.

---

## 🙌 Author
**Nikhil Sagar**  
*Aspiring Data Analyst | Power BI | SQL | Excel*

⭐ *If you find this project structure or design helpful, consider starring the repository to support my work!* ⭐
