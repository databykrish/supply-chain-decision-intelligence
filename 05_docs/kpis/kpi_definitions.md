# KPI Definitions & Business Logic
## Supply Chain Decision Intelligence Platform

---

## 1. Purpose of This Document
This document defines the **key performance indicators (KPIs)** used in the Supply Chain Decision Intelligence Platform.

Each KPI is designed to:
- align with real supply chain business objectives  
- support operational and executive decision-making  
- enable root cause analysis when performance deviates  

The definitions ensure **consistency, clarity, and trust** in reported metrics.

---

## 2. On-Time Delivery Rate (OTIF)

**Business Objective:**  
Measure the reliability of the supply chain in meeting promised delivery dates.

**Definition:**  
Percentage of orders delivered on or before the committed delivery date.

**Formula:**  
OTIF = (Number of On-Time Deliveries / Total Delivered Orders) × 100


**Business Interpretation:**
- High OTIF indicates reliable fulfillment and logistics performance  
- Declining OTIF signals potential issues in warehouses, carriers, or planning  

**Used By:**  
Operations Managers, Supply Chain Managers

---

## 3. Inventory Turnover

**Business Objective:**  
Evaluate how efficiently inventory is managed and sold.

**Definition:**  
Measures how many times inventory is sold or used during a given period.

**Formula:**  
Inventory Turnover = Cost of Goods Sold / Average Inventory


**Business Interpretation:**
- Low turnover may indicate overstocking or slow-moving items  
- Very high turnover may signal risk of stockouts  

**Used By:**  
Inventory Planners, Supply Chain Analysts

---

## 4. Order Fulfillment Rate

**Business Objective:**  
Assess the ability to fulfill customer demand completely and accurately.

**Definition:**  
Percentage of orders fulfilled without shortages or backorders.

**Formula:**  
Order Fulfillment Rate = (Fully Fulfilled Orders / Total Orders) × 100


**Business Interpretation:**
- Low fulfillment rate indicates inventory or planning issues  
- Helps prioritize replenishment and supplier actions  

**Used By:**  
Operations Teams, Planning Teams

---

## 5. Lead Time

**Business Objective:**  
Measure responsiveness of the supply chain.

**Definition:**  
Average time taken from order placement to final delivery.

**Formula:**  
Lead Time = Delivery Date − Order Date


**Business Interpretation:**
- Longer lead times reduce supply chain agility  
- Sudden increases may indicate operational bottlenecks  

**Used By:**  
Supply Chain Managers, Logistics Teams

---

## 6. Stockout Rate

**Business Objective:**  
Identify product availability issues that impact customer satisfaction.

**Definition:**  
Percentage of products unavailable when demand exists.

**Formula:**  
Stockout Rate = (Stockout Events / Total Demand Events) × 100


**Business Interpretation:**
- High stockout rate signals poor forecasting or replenishment delays  
- Directly impacts revenue and customer trust  

**Used By:**  
Inventory Planners, Merchandising Teams

---

## 7. Overstock Indicator

**Business Objective:**  
Detect excess inventory that ties up working capital.

**Definition:**  
Identifies inventory levels exceeding defined demand thresholds.

**Logic:**  
Overstock = Inventory Quantity > Maximum Planned Stock 


**Business Interpretation:**
- Overstock leads to increased holding costs  
- Requires corrective actions like promotions or supply adjustments  

**Used By:**  
Inventory & Finance Teams

---

## 8. Supplier Performance Score

**Business Objective:**  
Evaluate supplier reliability and contribution to supply chain performance.

**Definition:**  
Composite score based on delivery timeliness, order accuracy, and fulfillment consistency.

**Sample Components:**
- On-time delivery percentage  
- Order accuracy rate  
- Average lead time  

**Business Interpretation:**
- Helps identify underperforming suppliers  
- Supports supplier negotiations and sourcing decisions  

**Used By:**  
Procurement & Supply Chain Leadership

---

## 9. KPI Thresholds & Status Indicators

Each KPI is evaluated against predefined thresholds:

| Status | Meaning |
|------|--------|
| Green | Performance within acceptable range |
| Amber | Warning – attention required |
| Red | Action required |

Thresholds are adjustable based on business priorities and targets.

---

## 10. KPI Usage in Decision-Making
KPIs are not viewed in isolation.  
They are used together to:
- identify performance deviations  
- guide drill-through root cause analysis  
- support corrective operational actions  

This ensures the dashboard functions as a **decision support system**, not just a reporting tool.

---

*This KPI framework reflects real-world supply chain performance management practices.*
