# Revenue Metrics & Churn Analysis Dashboard (Tableau)

## 📌 Project Overview
This project focuses on building an interactive Business Intelligence (BI) dashboard designed for product managers to monitor **Monthly Recurring Revenue (MRR)** dynamics, evaluate monetization performance, and analyze key drivers of user retention and churn. 

The dashboard processes raw transaction data stored in a PostgreSQL database and visualizes critical financial and behavioral metrics using **Tableau Public**.

---

## 🛠️ Tech Stack & Tools
* **Database & Querying:** PostgreSQL, SQL (CTEs, Window Functions like `LAG`/`LEAD`)
* **Visualization:** Tableau Public
* **Documentation:** Markdown

---

## 📈 Key Metrics & Features
The project tracks 10+ core monetization and retention metrics divided into logical blocks:
* **Revenue Metrics:** Monthly Recurring Revenue (MRR), New MRR, Expansion MRR, Contraction MRR, Churned Revenue, Average Revenue Per Paid User (ARPPU), and Customer Lifetime Value (LTV).
* **User & Churn Metrics:** Paid Users, New Paid Users, Churned Users, Churn Rate, Revenue Churn Rate, and Customer Lifetime (LT).
* **Interactive Filters:** Global filters included for **Date (Month of Payment)**, **User Language**, and **User Age**.

---

## 📊 Dashboard Architecture
The dashboard consists of 5+ core visual components that break down business performance:
1. **MRR & Paid Users Breakdown:** Factor charts showing month-over-month revenue and user growth drivers (New, Expansion, Contraction, Churned).
2. **Churn Rates Trend:** Visualizing fluctuations in customer churn and revenue churn percentages over time.
3. **Customer Value Trends:** Tracking Customer Lifetime (LT) and Customer Lifetime Value (LTV) dynamics.
4. **Customer Analytics Dashboard:** Includes detailed analysis of payment methods against revenue and tracking repeat purchase frequencies.
5. **High-Level KPI Cards:** Instant overview of New MRR, ARPPU, Total MRR, and Total Paid Users.

![Uploading Dashboard 1.png…]()


---

## 💡 Business Insights & Impact
Based on the dashboard visualization and factor analysis, the following key findings were identified:
* **Revenue & Churn Drivers:** Month-over-month comparisons successfully highlight periods of active user expansion versus critical revenue contraction, allowing product managers to isolate the exact drivers behind financial shifts.
* **Targeting & Segmentation:** Utilizing age, language, and payment method filters revealed high-value user segments, helping to optimize targeting for marketing and retention campaigns.
* **Product & Monetization Stability:** Tracking recurring revenue sources (New vs. Expansion MRR) alongside churn rates provides a clear picture of long-term product viability and customer lifecycle value (LTV).

---

## 
You can explore the interactive live dashboard on Tableau Public:
👉 [View Tableau Public Dashboard](https://public.tableau.com/app/profile/mariia.pantiukh/viz/MonthlyRevenueUserGrowthAnalytic/Dashboard1 )

---

## 📂 Repository Structure
* `sql/` — Contains the SQL script used to extract, aggregate, and process transaction data from the database.
* `README.md` — Project documentation and business case overview.
