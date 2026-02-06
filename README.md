# Call-Center-Analysis
## 🚀 Project Overview

This project transforms raw call center telecommunication data into an actionable intelligence dashboard. The goal was to move beyond basic reporting to identify **operational inefficiencies**, **agent performance trends**, and **customer friction points**.

By analyzing **5,000 unique interactions**, I developed a suite of KPIs that allow management to monitor real-time health and long-term service quality.

### 📊 Interactive Dashboard

> **View the Live Dashboard on Tableau Public:** [(https://public.tableau.com/app/profile/srujana.konkala/viz/CallCenterAnalysis_17702289020660/Dashboard1?publish=yes)]

---

## 💡 Key Business Insights

Through this analysis, several critical operational insights were discovered:

* **Capacity Issues:** An **Abandonment Rate of 18.92%** was identified, suggesting a need for better peak-hour staffing.
* **Efficiency vs. Quality:** While agents like **Becky** and **Stewart** handled high volumes, I correlated their *Average Speed of Answer* with *Satisfaction Ratings* to ensure speed didn't come at the cost of service.
* **Resolution Trends:** Technical Support calls showed a different resolution pattern compared to Payment queries, highlighting specific areas for agent training.

---

## 🛠️ Technical Implementation

* **Data Processing:** Cleaned and structured raw call logs, handling null values for abandoned calls to ensure accurate percentage calculations.
* **Calculated Fields:** Developed custom formulas in Tableau for **Abandonment Rate** and  ** Call Resolution **.
* **Data Visualization:** Utilized a mix of Bar Charts , Highlight tables and used a sequential color scale in highlight tables to draw the eye directly to outliers
## 📈 KPIs Tracked

| Metric | Definition |
| --- | --- |
| **Total Calls** | Total volume of customer inquiries. |
| **Answered vs. Abandoned** | The percentage of customers who hung up before reaching an agent. |
| **Average Speed of Answer (ASA)** | The average time (in seconds) a customer waits in the queue. |
| **Customer Satisfaction (CSAT)** | Average score (1-5) based on post-call surveys. |
| **Agent Throughput** | Volume of calls handled per agent vs. their average talk duration. |

---

## 📁 Repository Structure

* `Call Center Data.csv
