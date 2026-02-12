# 📦 Supply Chain Analytics Dashboard (Power BI)

## 📌 Project Overview

This project presents an **end-to-end Supply Chain & Logistics Analytics Dashboard** built using **Power BI**. The dashboard provides actionable insights across **Suppliers, Inventory, Shipments, and Customers**, enabling data-driven decision-making for cost optimization, efficiency improvement, and performance monitoring.

The project uses a **star-schema data model** with multiple fact and dimension tables and applies **industry-standard KPIs** commonly used in manufacturing and supply chain analytics.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX, visualization
- **DAX (Data Analysis Expressions)** – KPI calculations
- **CSV Data Sources** – Fact & Dimension tables
- **Supply Chain Analytics Concepts** – Inventory, Logistics, Revenue Growth

---

## 🗂️ Data Model

### Fact Tables

- `fact_sales` – Sales revenue, quantity, profit
- `fact_inventory` – Inventory value, stock levels, defective units
- `fact_shipment` – Shipment status, delays, shipping cost
- `fact_procurement` – Supplier orders, unit cost
- `fact_production` – Production quantities and defects

### Dimension Tables

- `dim_date` – Date hierarchy (Year, Month, Day)
- `dim_product` – Product details
- `dim_supplier` – Supplier information
- `dim_customer` – Customer & channel data
- `dim_facility` – Manufacturing & storage locations

The model follows **best practices** for Power BI (one-to-many relationships, single date table).

---

## 📊 Dashboard Pages & Key Insights

### 1️⃣ Executive Overview

**Purpose:** High-level supply chain health monitoring

**Key KPIs:**

- Total Revenue: \~176.95M
- Profit: \~48.56M
- Profit Margin: \~27.44%
- Perfect Order Rate: \~75.3%

**Insight:**
The supply chain is financially strong, but operational reliability can be improved, as nearly **1 in 4 orders** is not fulfilled perfectly.

---

### 2️⃣ Supplier Analysis

**KPIs & Visuals:**

- Average Lead Time by Supplier & Country
- Average Quality Score by Supplier
- Total Unit Cost by Supplier

**Insights:**

- Vietnam and India provide the **shortest lead times**.
- Taiwan & Sony suppliers deliver the **highest quality scores**.
- Supplier cost variation is low, so **lead time and quality** should drive sourcing decisions.

---

### 3️⃣ Inventory Analysis

**KPIs & Visuals:**

- Inventory Value & Safety Stock
- Inventory Turnover Rate
- Days of Inventory (DIO)
- Defective Units Trend

**Insights:**

- Inventory turnover is **low**, indicating slow-moving stock.
- High safety stock suggests risk mitigation against lead-time uncertainty.
- Defective units contribute to delayed fulfillment and reduced efficiency.

---

### 4️⃣ Shipment & Logistics

**KPIs & Visuals:**

- Total Shipments & Delivered %
- Shipment Delays by Carrier
- Delay Reasons Analysis
- Shipping Cost Trend

**Insights:**

- Delivery success rate is \~75%, highlighting logistics bottlenecks.
- Major delay reasons include **carrier capacity, documentation, and port congestion**.
- Shipping costs peak toward year-end, showing strong seasonality.

---

### 5️⃣ Customer & Revenue Analysis

**KPIs & Visuals:**

- Total Revenue, Profit & YoY Growth
- Revenue by Sales Channel
- Discount % vs Quantity Sold

**Insights:**

- Retail is the largest revenue contributor, followed closely by online channels.
- Revenue growth fluctuates month-over-month, influenced by inventory availability and logistics performance.
- Discounting is controlled and does not significantly erode margins.

---

## 📐 Key DAX Measures Used

- Total Revenue
- Profit & Profit Margin %
- Inventory Turnover Rate
- Days of Inventory (DIO)
- Total Delivered Shipments
- Delivery Success Rate %
- Year-over-Year Revenue Growth

All measures are written using **DAX best practices** (`CALCULATE`, `DIVIDE`, time intelligence functions).

---

## 🚀 Business Value

- Improves **supplier selection** using cost, quality, and lead time
- Identifies **inventory inefficiencies** and overstocking risk
- Highlights **logistics bottlenecks** and delay root causes
- Supports **executive decision-making** with clear KPIs

---

## 📸 Dashboard Preview

> *(Add screenshots of Overview, Supplier, Inventory, Shipment, and Customer pages here)*

Example:

```
/screenshots/overview.png
/screenshots/supplier.png
/screenshots/inventory.png
/screenshots/shipment.png
/screenshots/customer.png
```

---

##

---

##

---



