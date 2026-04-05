# 🛒 E-Commerce Sales Dashboard — Power BI & Excel

## 📌 Project Overview
An interactive business intelligence dashboard built to analyse e-commerce sales performance. The dashboard enables stakeholders to monitor revenue trends, track product performance, and make data-driven decisions through dynamic visualisations and KPIs.

---

## 🎯 Business Problem
E-commerce businesses generate large volumes of sales data daily but often struggle to extract clear insights from it. This project addresses:
- Which products and categories are driving revenue?
- How does sales performance trend over time?
- Where are the underperforming segments?
- What does the business need to focus on to grow?

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Power BI | Dashboard development & visualisation |
| Excel | Data cleaning & preprocessing |
| DAX | Custom measures & calculations |

---

## 🔄 Project Workflow

### 1. Data Preparation (Excel)
- Cleaned raw sales data — handled missing values, removed duplicates, and standardised date formats
- Structured data into a clean tabular format ready for import into Power BI

### 2. Data Modelling (Power BI)
- Imported cleaned data and built an optimised data model
- Created relationships between tables (sales, products, customers)
- Developed custom DAX measures for KPIs

### 3. DAX Measures Created
---
Total Revenue = SUM(Sales[Revenue])
Total Orders = COUNTROWS(Sales)
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
---

### 4. Dashboard Design (Power BI)
Built an interactive single-page dashboard with:
- KPI cards for Total Revenue, Total Orders, Average Order Value
- Monthly revenue trend line chart
- Top 10 products by revenue bar chart
- Category-wise sales breakdown donut chart
- Region/segment slicers for dynamic filtering
- Drill-down capability from category → product level

---

## 📈 Key Insights
- Identified top 3 revenue-generating product categories contributing ~65% of total sales.
- Detected seasonal revenue spikes allowing better inventory planning.
- Highlighted underperforming product segments with high order volume but low revenue.
- Month-over-month trend analysis revealed consistent growth.

---

## 💡 Business Value
- Replaced manual Excel reporting with a dynamic, real-time dashboard.
- Enabled non-technical stakeholders to self-serve insights via slicers and filters.
- Reduced time spent on monthly reporting by automating KPI calculations through DAX.

---

## 🚀 How to Use
1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository
3. Open `E-Commerce Sales Dashboard.pbix` in Power BI Desktop
4. Explore the dashboard using slicers and drill-downs

---

## 👤 Author
**Aayush Tyagi**
[LinkedIn](https://www.linkedin.com/in/aayushtyagi003) • [GitHub](https://github.com/aayushtyagi)
