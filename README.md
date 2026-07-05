# ⛽ Fuel Station Operational Intelligence

> **I Built a decision-support system from 12 months of operational transaction data to help management improve profitability, optimize staffing, and improve operational visibility despite missing inventory records, maintenance logs, and shift schedules.**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-Custom%20Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📖 Executive Summary

Operational dashboards often answer **"What happened?"**

This project was designed to answer **"What should management do next?"**

Using **12 months of fuel station transaction data**, I developed a Power BI operational intelligence solution that transforms raw sales records into actionable business insights. Despite significant data limitations—including the absence of inventory reconciliation, maintenance history, and predefined shift schedules—the solution provides management with visibility into profitability, workforce performance, customer demand, payment operations, and operational efficiency.

Instead of forcing conclusions the data could not support, this project explicitly identifies uncertainty where appropriate and demonstrates how analytical reasoning can still drive business decisions under real-world constraints.

---

# 🎯 Business Problem

The fuel station processed thousands of transactions each month but lacked visibility into critical operational questions.

Management needed answers to questions such as:

- Which customer segments generate the highest profit?
- Which attendants consistently deliver stronger performance?
- When should staffing increase or decrease?
- Which payment methods create operational complexity?
- Can transaction data reveal operational anomalies despite missing inventory records?

### Business Constraints

| Available Data | Missing Data |
|----------------|--------------|
| Transaction records | Inventory deliveries |
| Pump meter readings | Stock reconciliation |
| Payment methods | Maintenance history |
| Fuel types | Shift schedules |

Rather than treating these limitations as blockers, this project demonstrates how engineered business metrics can still provide valuable operational insight.

---

# 🏗 Solution Overview

## Analytical Approach

| Challenge | Solution |
|-----------|----------|
| Twelve independent Excel workbooks | Unified through Power Query ETL |
| No shift schedules | Derived Shift Period from timestamps |
| No maintenance history | Pump utilization & throughput analysis |
| Manual reporting | Interactive Power BI dashboards |

### Data Pipeline

```text
Monthly Excel Files
        │
        ▼
Power Query ETL
        │
        ▼
Data Cleaning & Transformation
        │
        ▼
Star Schema Data Model
        │
        ▼
Custom DAX Measures
        │
        ▼
Interactive Power BI Dashboard
        │
        ▼
Business Decision Support
````

---

# 📊 Dashboard Overview

| Dashboard               | Business Question                              |
| ----------------------- | ---------------------------------------------- |
| Executive Overview      | How is the business performing?                |
| Operations Audit        | Which pumps or attendants require attention?   |
| Pricing & Profitability | Which customer segments create the most value? |
| Throughput Analysis     | When should resources be allocated?            |

---

# 🔍 Key Business Insights

## 1️⃣ Profitability Is Concentrated in One Customer Segment

The **Bus** segment generated approximately **₦36.19M** in profit contribution, substantially exceeding every other customer segment.

| Vehicle Group | Profit Contribution |
| ------------- | ------------------: |
| 🚌 Bus        |             ₦36.19M |
| 🏍 Motorcycle |             ₦15.51M |
| 🚗 Car        |              ₦7.63M |
| ⚡ Generator   |              ₦2.87M |

### Business Insight

The station's profitability is highly concentrated within a single customer segment. Protecting high-value fleet relationships may have a greater financial impact than simply increasing transaction volume.

---

## 2️⃣ Attendant Performance Can Be Measured Objectively

Transaction-level analysis identified measurable differences in throughput and average ticket value across attendants.

| Attendant | Average Ticket | Throughput |
| --------- | -------------: | ---------: |
| Kemi      |          ₦359K |    358.94K |
| Bola      |          ₦355K |    354.75K |
| Emeka     |          ₦353K |    353.21K |
| Ibrahim   |          ₦352K |    351.65K |
| Tunde     |          ₦347K |    346.76K |
| Chiamaka  |          ₦345K |    345.15K |

### Business Insight

Operational performance can be evaluated using measurable KPIs instead of subjective observation, enabling more consistent coaching and performance management.

---

## 3️⃣ Customer Demand Is Highly Concentrated

Nearly half of all station transactions occurred during the afternoon period, while Saturday represented the busiest operating day.

| Shift     | Transactions | Share |
| --------- | -----------: | ----: |
| Afternoon |       15,246 | 47.8% |
| Morning   |       14,820 | 46.5% |
| Night     |        1,829 |  5.7% |

### Business Insight

Demand patterns indicate opportunities to optimize staffing levels and equipment availability without increasing labor costs.
---

# 💼 Business Recommendations

| Priority  | Recommendation                                                     |
| --------- | ------------------------------------------------------------------ |
| 🔴 High   | Validate Meter Variance calculations before operational use        |
| 🔴 High   | Introduce attendant performance scorecards                         |
| 🔴 High   | Prioritize retention of high-value fleet customers                 |
| 🟠 Medium | Review pricing strategy across lower-profit customer segments      |
| 🟠 Medium | Monitor reconciliation performance for digital payments            |
| 🟢 Low    | Align staffing with observed demand patterns                       |
---

# 📈 Project Impact

This project demonstrates how business intelligence can support operational decision-making even when important datasets are unavailable.

Instead of waiting for perfect data, the solution extracts practical insights from existing operational records while clearly communicating analytical limitations. The result is a repeatable decision-support system that enables evidence-based management decisions.
---

# 👨‍💻 About Me

I'm a **Data Analyst** passionate about transforming messy operational data into clear business decisions.

I enjoy solving real business problems using **SQL, Power BI, DAX, Excel, and data storytelling**.

### Connect with me

* 💼 LinkedIn: **(https://www.linkedin.com/in/azeez-ibraheem/)**
* 🌐 Portfolio: **(https://debest07011.github.io/Portfolio/)**
* 📧 Email: **[mailto:azeezibrahee25@gmail.com]**

---

## ⭐ Support

If you found this project valuable or learned something from it, consider giving the repository a **Star**.


## Dashboard Preview

### Executive Overview
![Executive Dashboard](visuals/executive_overview.png)

### Shift Otimization
![Shift Optimization](visuals/Shift Optimization.jpeg)

### Pricing & Profitability
![Pricing Dashboard](Shift Optimization.jpeg)

### Throughput Analysis
![Throughput Dashboard](visuals/throughput_analysis.png)
