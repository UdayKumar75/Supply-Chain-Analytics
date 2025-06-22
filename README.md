# 📦 Supply Chain Analytics Dashboard – Power BI

This project presents an end-to-end **Supply Chain Dashboard** built in **Power BI**, aimed at analyzing service levels and delivery performance for an FMCG company.

## 📊 Overview

The dashboard helps stakeholders monitor and improve key supply chain KPIs, including:

- **On-Time Delivery (OT%)**
- **In-Full Delivery (IF%)**
- **On-Time In-Full (OTIF%)**
- **Delivery Delays**
- **Order Distribution by City, Category & Customer**

## 🧩 Data Model

The project follows a **star schema** with the following tables:

- `fact_order_lines`: Contains order-level facts like delivery dates, delivery status, quantity, and delay.
- `fact_orders_aggregate`: Aggregated delivery KPIs per customer and order.
- `dim_customers`: Customer metadata (city, name).
- `dim_date`: Calendar table for time-based slicing.
- `dim_products`: Product categories and names.
- `dim_targets_orders`: KPI targets (On-Time, In-Full, OTIF%) per customer.

## 🔍 Key Insights

- Total Orders: **31.7K**
- Late Deliveries: **13K** orders were delayed, with an **average delay of 1.69 days**.
- Performance by City: Compared Ahmedabad, Surat, and Vadodara.
- Category Analysis: Food, Beverages, and Dairy order performance breakdown.
- Customer-Level Target vs Actual Analysis (OT, IF, OTIF).
- Trends by Week: Time-series visualizations for operational tracking.

## 📈 Tools & Technologies

- **Power BI** for data modeling, DAX calculations, and interactive visualizations
- **Excel** as data source for simulation
- Custom slicers, matrix views, bar charts, trend lines, donut charts, and KPI cards

## 🚀 Impact

- Helped identify underperforming customer regions and delivery types
- Supported decision-makers in reducing delays and improving service levels
- Potential to **save 20% on operational expansion costs** by optimizing logistics

## 📁 Pages in the Report

- **Orders Overview**
- **Key Metrics (OT, IF, OTIF)**
- **City & Product Performance**
- **Customer-Level Service Scorecards**
- **Service Level Scatter Analysis**

---
