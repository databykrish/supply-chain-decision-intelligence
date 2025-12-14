# 📦 Supply Chain Decision Intelligence Platform

**An end-to-end BI system for performance monitoring, root cause analysis, and operational optimization**

---

## 📌 Overview
This project simulates a **real-world retail supply chain environment** and demonstrates how business intelligence can move beyond static reporting into **decision intelligence**.

Instead of only displaying KPIs, the platform is designed to help supply chain teams:
- detect performance issues early  
- understand *why* they occur  
- identify *where* the root cause lies  
- and decide *what* actions to take  

The solution reflects how modern analytics teams support operations, planning, and leadership through **data-driven decision support**.

---

## 🎯 Business Objective
Retail supply chain teams often face:
- limited visibility into inventory and fulfillment performance  
- delayed identification of bottlenecks  
- fragmented reports without clear root-cause insights  
- dashboards that show metrics but don’t guide action  

**Objective:**  
Design a **decision-first analytics platform** that enables operations teams to monitor performance, perform root-cause analysis, and optimize inventory flow and delivery reliability.

---

## 🧩 Business Questions Addressed
- Are deliveries meeting on-time targets? If not, where is the delay happening?
- Which warehouses or suppliers are impacting fulfillment performance?
- Where are stockouts or overstock situations occurring?
- Which products are slow-moving or fast-moving?
- What operational actions should be prioritized next?

---

## 🗂️ Data Sources
This project uses **publicly available datasets** to simulate a realistic retail supply chain scenario.

**Data includes:**
- Orders and shipment transactions  
- Inventory levels by product and warehouse  
- Supplier and warehouse master data  
- Simulated delay and fulfillment indicators  

The data is treated as a **production-like supply chain dataset** for analytical and reporting purposes.

---

## 🛠️ Technical Architecture

### Data Integration (ETL)
- Python (Pandas, NumPy) for data cleaning and transformation  
- SQL for structured querying and staging  

### Data Storage
- Relational database (PostgreSQL / SQL Server)

### BI & Reporting
- **Power BI**
  - Star schema data modeling  
  - DAX measures for KPIs  
  - Drill-through and interactive analysis  
  - Performance-aware report design  

### Version Control
- Git & GitHub for source and documentation management  

> *Power BI was chosen to demonstrate enterprise BI fundamentals such as data modeling, KPI frameworks, performance optimization, and drill-through analysis — concepts transferable across platforms like IBM Cognos.*

---

## 📊 Key KPIs & Metrics
- On-Time Delivery Rate (OTIF)  
- Inventory Turnover  
- Order Fulfillment Rate  
- Lead Time Analysis  
- Stockout & Overstock Indicators  
- Supplier & Warehouse Performance Metrics  

Each KPI is designed with **thresholds and context**, enabling faster interpretation and action.

---

## 🧠 Decision-First Dashboard Design
Unlike traditional dashboards that focus only on charts, this solution is structured around **decision flows**:

> *What went wrong → Where is it happening → Why is it happening → What should be done next*

The dashboard layout and navigation guide users through this analytical journey instead of relying solely on manual filtering.

---

## 🔍 Root Cause Analysis Workflow
The platform enables **guided root cause analysis** using drill-through paths:

> *KPI Deviation → Warehouse → Supplier / Carrier → Shipment → Delay Reason*


This mirrors how real operations teams investigate performance issues under time pressure.

---

## 🚨 Simulated Operational Incident (Example)
**Scenario:**  
A sudden drop in on-time delivery rate is observed during a specific period.

**Analysis Using the Dashboard:**
- KPI overview highlights the deviation  
- Drill-through isolates affected warehouses  
- Further analysis identifies a specific carrier causing repeated delays  
- Shipment-level inspection confirms the root cause  

**Outcome:**  
The dashboard enables targeted corrective action instead of broad, inefficient interventions.

---

## ⚙️ Performance & Optimization Considerations
- Star schema data modeling to reduce query complexity  
- Measures preferred over calculated columns  
- Reduced visual density per page  
- Optimized DAX for faster load times  

These practices reflect **enterprise-grade BI performance awareness**.

---

## 📈 Dashboard Views
- **Executive Overview:** KPI status, trends, and alerts  
- **Inventory Health:** stock levels, slow vs fast movers  
- **Fulfillment & Logistics:** lead time and delivery performance  
- **Root Cause Explorer:** guided drill-through analysis  
- **Incident Deep Dive:** focused analysis of operational issues  

*(Dashboard screenshots to be added)*

---

## 🚀 What Makes This Project Different
- Designed as a **decision intelligence platform**, not just a reporting dashboard  
- Emphasis on **root cause analysis**, not only KPI monitoring  
- Simulates real operational incidents and investigation workflows  
- Performance-aware data modeling and reporting practices  
- Built with a **product mindset**, focusing on user questions and outcomes  

---

## 🔮 Future Enhancements
- Demand forecasting using time-series models  
- Automated anomaly detection for KPI deviations  
- Scenario analysis for inventory planning  
- Scheduled refresh and alerting workflows  

---

📌 **This project demonstrates how BI solutions are used in real organizations — not just to report data, but to drive better decisions.**

