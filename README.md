# 📊 Sales Performance Dashboard (AdventureWorks)

## 📌 Overview

This Power BI dashboard analyzes sales performance using the AdventureWorks dataset.  
It provides executive-level insight into revenue trends, order activity, and regional performance.

The report contains multiple report pages to support both high-level executive review and detailed analysis.

---

# 🖥 Dashboard – Main Overview Page

![Main Dashboard](C:\Data Analysis\adventureworks-sales-insights-report\images\adventureworks-sales-insights-report-main.png)

This page provides a high-level summary of business performance, including:

- KPI cards (Total Sales, Total Orders, Average Order Value)
- Sales trend over time
- Sales by territory comparison
- Revenue distribution by territory (donut chart)
- Interactive slicers for Territory and Date filtering

---

# 🔎 Dashboard – Details Page

![Details Page](C:\Data Analysis\adventureworks-sales-insights-report\images\adventureworks-sales-insights-report-details.png)

The Details page allows deeper analysis into:

- Transaction-level insights
- Additional breakdowns by territory or product
- Filtered drill-down reporting
- Supporting visuals for more granular exploration

---

# 📂 Data Preview (Sample Rows)

![Data Rows](C:\Data Analysis\adventureworks-sales-insights-report\images\adventureworks-sales-insights-report-rows.png)

This image shows a sample of the underlying dataset used to build the report.

The data model is based on the AdventureWorks sample database and includes fact and dimension tables such as:

- FactInternetSales
- DimDate
- DimSalesTerritory
- DimProduct

---

# 🎯 Key Metrics

The following KPIs are displayed prominently on the dashboard:

- **Total Sales**
- **Total Orders**
- **Average Order Value (AOV)**

All KPI values dynamically update based on slicer selections.

---

# 📈 Visualizations Used

- **Line Chart** – Sales trend over time  
- **Bar Chart** – Sales by Territory  
- **Donut Chart** – Revenue distribution by Territory  
- **KPI Cards** – Summary performance metrics  
- **Slicers** – Territory and Year-Month filtering  

---

# 🎨 Design Approach

The dashboard follows a structured analytical flow:

1. Filter
2. KPI Summary
3. Trend Analysis
4. Comparative Breakdown
5. Detailed Drill-Down

Design decisions include:

- Slicers positioned at the top for intuitive filtering
- KPI cards placed prominently for executive visibility
- Donut chart used for proportional revenue comparison
- Clean layout to m
