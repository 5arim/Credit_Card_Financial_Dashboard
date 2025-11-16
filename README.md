# 🏆 Credit Card Financial Analytics Dashboard

## 🌟 Executive Summary

This project delivers a dynamic, interactive, and production-ready financial dashboard built on **Power BI** to monitor and analyze the performance of a credit card portfolio.

It transforms raw transaction and customer data into actionable business intelligence, focusing on key metrics (KPIs), week-over-week performance tracking, and granular customer segmentation. The solution demonstrates proficiency in end-to-end data pipeline construction, advanced DAX modeling, and clear data storytelling.

| Project Focus | Metrics Covered | Key Tools Used |
| :--- | :--- | :--- |
| **Financial Performance** | Revenue, Interest Earned, Transaction Volume, Delinquency Rate, Card Utilization. | Power BI Desktop, DAX, SQL (Postgres/MySQL), CSV. |
| **Customer Segmentation** | Income Group, Age Group, Marital Status, Education Level, Card Type. | Data Modeling (Star Schema), ETL/Power Query. |
| **Business Value** | Optimized weekly reporting cycle, informed marketing strategies, and risk assessment. | GitHub, Documentation (This README). |

---

## 🎯 Business Problem & Project Objectives

The primary objective was to streamline the weekly financial reporting process and move away from static reports by providing stakeholders with real-time, interactive insights into the credit card portfolio's health and customer behavior.

### Key Objectives:

1.  **Establish a Robust Data Pipeline (ETL):** Connect Power BI directly to a structured **SQL environment** to handle future data scaling and simplify the weekly data refresh cycle.
2.  **Develop Advanced Financial Metrics:** Implement complex **DAX** logic to track critical measures like **Week-over-Week (WoW) Revenue Change** and the **Delinquency Rate**.
3.  **Drive Customer Strategy:** Segment customers by demographics and behavioral data to identify high-value groups and assess risk profiles.

---

## 💻 Technical Implementation & Skills Demonstrated

### 1. Data Architecture & ETL

* **Data Source Integration:** Successfully ingested raw transaction and customer data from CSV files into an **SQL database** (e.g., using Postgres SQL) to establish a clean, queryable source environment.
* **Power Query (M Language):** Used for initial data cleansing, type transformation, and defining the data relationships before loading into the Power BI Data Model.

### 2. Advanced Data Modeling & DAX

* **Star Schema Design:** Structured the data model with distinct fact (Transaction details) and dimension tables (Customer demographics, Date Table) to optimize query performance and ensure accurate aggregation.
* **Time Intelligence (WoW):** Created a custom measure using `CALCULATE`, `FILTER`, and `ALL` functions to calculate the percentage change in revenue and transactions between the current week and the previous week—a critical financial KPI.
* **Segmentation Logic:** Implemented **DAX `SWITCH(TRUE(), ...)`** functions to categorize customer data into digestible groups:
    * **Age Group:** (e.g., 20-30, 30-40, 60+)
    * **Income Group:** (Low, Medium, High)

### 3. Visualization and Report Structure

The final solution is organized into two primary, interconnected reports:

| Report Name | Focus | Core Insights Provided |
| :--- | :--- | :--- |
| **1. Credit Card Transaction Report** | Financial Health & Trends | **Revenue Trend:** Weekly performance visualization. **Spend Analysis:** Breakdown of revenue by Card Type (`Blue` vs. `Platinum`) and Transaction Type (`Swipe` vs. `Online`). |
| **2. Credit Card Customer Report** | Portfolio Quality & Risk | **Risk Assessment:** Delinquency rate segmented by job title and marital status. **Customer Value:** Contribution to total revenue by Income and Age Group. |

---

## 📈 Key Business Insights & Value Delivered

The dashboard provides immediate answers to critical business questions, enabling data-driven decision-making:

* **Performance Monitoring:** The **WoW Revenue Change** table immediately alerts users to significant performance shifts, allowing for prompt investigation into spikes or dips.
* **Risk Identification:** Pinpointed that the **Self-Employed** customer job group exhibited the highest rate of delinquent accounts, guiding the Risk team to refine underwriting criteria for this segment.
* **Marketing Optimization:** Confirmed that the **40-60 Age Group** and **High-Income Group** are the primary revenue drivers, recommending targeted campaigns to maximize return on investment (ROI).
* **Product Strategy:** Identified that **Blue and Silver Cards** contribute over 90% of the overall transaction volume, justifying a focus on the retention and upgrade path for these tiers.

---

## 🚀 Getting Started

To view and interact with the live report:

1.  **Prerequisite:** Ensure you have **Power BI Desktop** installed.
2.  **Clone the Repository:** Download the project files.
3.  **Open:** Open the `.pbix` file. The data will load automatically from the saved connection.
4.  **Explore:** Use the various slicers (Date, Income Group, Card Type) to drill down into the data and replicate the insights mentioned above.

***

### 📸 Dashboard Screenshots 


* <img width="608" height="343" alt="image" src="https://github.com/user-attachments/assets/3b1835bf-7633-400e-aa28-43d6902c5d48" />

* <img width="608" height="344" alt="image" src="https://github.com/user-attachments/assets/778ee61b-899c-4a60-9bbd-bffcfdbab168" />


---

## 🙋‍♂️ Author & Contact

**Connect with me! I am actively seeking roles in Data Analytics and Business Intelligence.**

| Detail | Information |
| :--- | :--- |
| **Author** | 5arim |
| **GitHub** | [https://github.com/5arim/Credit\_Card\_Financial\_Dashboard](https://github.com/5arim/Credit_Card_Financial_Dashboard) |
| **LinkedIn** | [www.linkedin.com/in/sarim-hayat](www.linkedin.com/in/sarim-hayat) |
