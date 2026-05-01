

---

# 📊 Manufacturing Downtime Analysis

## 📌 Overview

This project presents an in-depth analysis of **manufacturing downtime** using machine event data. The goal is to identify patterns, root causes, and performance trends to improve operational efficiency and support data-driven decision-making.

---
<img width="1550" height="876" alt="Screenshot 2026-05-01 204641" src="https://github.com/user-attachments/assets/d6b443b7-61a4-4942-9a34-fff92cd05408" />

<img width="1530" height="862" alt="Screenshot 2026-05-01 204702" src="https://github.com/user-attachments/assets/4502854b-d24e-4070-8dfd-9186c377c435" />

<img width="1531" height="862" alt="Screenshot 2026-05-01 204716" src="https://github.com/user-attachments/assets/ff686163-b61f-481e-9f6d-db926422c085" />


---

## 📂 Project Description

The project analyzes downtime events across machines, operators, and products to uncover inefficiencies and provide actionable insights.

### 🎯 Objectives

* Identify top reasons for machine downtime
* Analyze downtime across machines and departments
* Detect trends over time
* Provide actionable recommendations to reduce losses

---

## 🧾 Data Overview

* **Number of Tables:** 3
* **Main Tables:** Machines, Downtime Events, Reasons, Time
* **Time Period:** 29 Aug 2024 – 3 Sep 2024
* **Key Metrics:**

  * Total Downtime (minutes)
  * Number of Events
  * Top Machines & Reasons

---

## 🧹 Data Preparation

* Removed null values and irrelevant rows
* Established relationships between tables:

  * Product → Batch Info (one-to-many)
  * Batch Info → Downtime (one-to-many)

---

## 📐 Key Calculations

* **Average Downtime**
* **Target Batches**
* **Uptime**
* **Operator vs Non-Operator Downtime**
* **Efficiency Calculation**

---

## 🧠 Data Modeling

* Product-level tracking across batches
* Batch-level tracking of downtime events
* Relationships built using:

  * `product_id`
  * `batch_no`

---

## 📊 Dashboards & Insights

### 1. 📉 Overall Performance Dashboard

* Efficiency: **67%**
* Underperformance in:

  * Target batches
  * Operator productivity
* Peak downtime: **2 PM – 6 PM**
* Main downtime causes:

  * Machine adjustment
  * Machine failure
  * Inventory shortage

---

### 2. 🏭 Product-Level Analysis

* Total downtime: **1,388 minutes**
* Cola contributes **55%+ of downtime**
* Highest downtime product: **CO-600**
* Lowest efficiency: **OR-600 (44%)**

---

### 3. 👷 Operator Performance

* Uptime: **22.48 hours**
* Operator downtime events: **6**
* Key findings:

  * **Mac** → highest downtime contributor
  * **Charlie** → highest efficiency (71%)
  * Peak operator downtime at **2 PM**

---

## 📈 Key Insights

* Downtime is heavily influenced by **non-operator factors (≈56%)**
* Significant efficiency variation across batches (44% → 100%)
* Certain products and operators consistently underperform

---

## 🚀 Recommendations

### 🔹 Daily Operations

* Use dashboards in daily meetings
* Highlight top downtime causes

### 🔹 Real-Time Monitoring

* Integrate with live systems (SCADA, MES, PLCs)
* Enable instant response to downtime

### 🔹 Operator Improvement

* Provide performance feedback
* Implement targeted training programs

### 🔹 Maintenance Strategy

* Use downtime trends for predictive maintenance
* Set alerts for machine issues

### 🔹 Reporting

* Automate weekly/monthly reports
* Track performance improvements over time

---


## 🛠️ Tools & Technologies

* Data Modeling & Analysis
* Dashboard Visualization (Power BI)

---

## 📌 Conclusion

This project demonstrates how data analytics can significantly improve manufacturing efficiency by identifying downtime causes, optimizing workflows, and enabling proactive decision-making.


