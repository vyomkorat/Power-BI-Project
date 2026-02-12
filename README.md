<p align="center">
  <img src="preview image/Home.png" width="1000"/>
</p>
# 📦 Supply Chain Analytics Dashboard (Power BI)

## 📌 Project Overview

This project presents a comprehensive **Supply Chain & Logistics Analytics Dashboard** built in **Power BI**. The solution analyzes operations across **Suppliers, Inventory, Shipments, and Customers**, providing actionable insights for cost optimization, operational efficiency, and strategic decision-making.

The dashboard follows a **star-schema data model**, applies industry-standard KPIs, and includes an interactive **custom slicer panel** for dynamic filtering.

---

# 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling & visualization
- **DAX (Data Analysis Expressions)** – KPI calculations & time intelligence
- **CSV Data Sources** – Fact & Dimension tables
- **Supply Chain & Logistics KPIs** – Inventory, Lead Time, Perfect Order, Revenue Growth

---

# 🗂️ Data Model Architecture

## ⭐ Fact Tables

- `fact_sales` – Revenue, quantity sold, profit
- `fact_inventory` – Inventory value, stock levels, defective units
- `fact_shipment` – Shipment status, delay reasons, shipping cost
- `fact_procurement` – Supplier unit cost & orders
- `fact_production` – Production quantities & defects

## 📘 Dimension Tables

- `dim_date` – Date hierarchy (Year, Month, Quarter)
- `dim_product` – Product information
- `dim_supplier` – Supplier details
- `dim_customer` – Customer & channel information
- `dim_facility` – Manufacturing locations

✔ Single Date Table
✔ One-to-Many Relationships
✔ Clean Star Schema Design

---

# 📊 Dashboard Pages & Visual Insights

---

# 1️⃣ Overview Page



### Key KPIs

- Total Revenue: \~176.95M
- Profit: \~48.56M
- Profit Margin: \~27.44%
- Perfect Order Rate: \~75%

### Business Insight

The organization is financially strong but operational reliability needs improvement. Nearly **25% of orders are not fulfilled perfectly**, highlighting supply chain inefficiencies.

---

# 2️⃣ Supplier Analysis Page



### Key Visuals

- Average Lead Time by Country
- Average Quality Score by Supplier
- Total Unit Cost by Supplier
- Unit Cost Trend by Month

### Key Insights

- Vietnam & India provide shortest lead times.
- Taiwan Semiconductor & Sony Semiconductor have highest quality scores.
- Cost variation is minimal, making **lead time and quality key differentiators**.

---

# 3️⃣ Inventory & Production Page



### Key KPIs

- Inventory Value: \~160K
- Safety Stock: \~89K
- Inventory Turnover Rate
- Days of Inventory (DIO)

### Insights

- Low inventory turnover indicates slow-moving stock.
- High safety stock suggests risk mitigation strategy.
- Defective units impact order fulfillment and inventory efficiency.

---

# 4️⃣ Shipment & Logistics Page



### Key KPIs

- Total Shipments: \~8K
- Delivered %: \~75%
- Total Delays
- Shipping Cost Trend

### Delay Analysis

Major delay reasons:

- Carrier Capacity
- Documentation Issues
- Port Congestion
- Customs Clearance

### Insight

Logistics performance is the primary operational bottleneck. Carrier optimization and documentation automation can significantly improve service levels.

---

# 5️⃣ Customer & Revenue Analysis Page



### Key Metrics

- Revenue by Channel
- YoY Revenue Growth
- Profit Margin %
- Discount Analysis

### Insights

- Retail is largest revenue contributor.
- Online channel shows strong growth potential.
- Discounting is controlled and does not significantly impact margin.

---

# 🎛️ Custom Interactive Slicer Panel (New Feature)



This dashboard includes a **custom-designed slicer panel** with toggle functionality using shapes and bookmarks.

### Features:

- Category Filter
- Status Filter
- Country Filter
- Slide-in panel design
- Clean UI with close button

### Business Benefit:

- Enhances user experience
- Allows dynamic filtering without cluttering visuals
- Improves executive presentation readiness

---

# 📐 Key DAX Measures Implemented

- Total Revenue
- Profit & Profit Margin %
- Inventory Turnover Rate
- Days of Inventory (DIO)
- Total Delivered Shipments
- Delivery Success Rate %
- Year-over-Year Revenue Growth
- Total Delay by Carrier

All calculations follow **DAX best practices** using:

- `CALCULATE()`
- `DIVIDE()`
- `SAMEPERIODLASTYEAR()`
- Time Intelligence Functions

---

# 🚀 Business Impact

✔ Improved supplier evaluation (Cost vs Lead Time vs Quality)
✔ Identified logistics bottlenecks
✔ Detected slow-moving inventory risk
✔ Enhanced revenue performance visibility
✔ Interactive executive-ready dashboard design



