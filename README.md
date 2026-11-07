# SwiftLog-Logistics-Analytics
# SwiftLog Logistics Supply Chain Analytics & Business Intelligence

**AnalystLab Africa Experience Lab Internship Programme | Data Analytics Track**

## Project Overview

This project focuses on developing a Business Intelligence solution for SwiftLog Logistics Limited, a logistics and supply chain company facing the challenges of monitoring performance across orders, inventory, warehouses, suppliers and customer deliveries.

The goal is to transform operational data into actionable insights using data preparation, data modelling, DAX measures and interactive Power BI dashboards.

## Business Objectives

- Monitor revenue and order performance.
- Analyse customer purchasing behaviour.
- Improve inventory visibility and warehouse efficiency.
- Evaluate supplier and product performance.
- Monitor shipments, delivery delays and returns.
- Develop KPIs to support operational decision-making.
- Recommend practical improvements based on verified findings.

## Tools and Technologies

- **Microsoft Power BI:** Data modelling, DAX and interactive dashboards.
- **Power Query:** Data cleaning and transformation.
- **DAX:** KPI calculations and business metrics.
- **Microsoft Excel:** Data inspection and supporting analysis.
- **GitHub:** Project documentation and version tracking.

# SwiftLog Logistics: Supply Chain Analytics & Business Intelligence

**Programme:** AnalystLab Africa Experience Lab, Week 5
**Track:** Data Analytics
**Author:** Oluwayomi Precious Similoluwa
**Tool:** Power BI

## About the project

SwiftLog Logistics Limited is a fast-growing Nigerian logistics company. As it has grown, it has run into late deliveries, inventory problems, uneven supplier performance and little visibility for management.

My task is to turn SwiftLog's raw data into a Power BI solution that helps leadership see what is happening, find bottlenecks and make better decisions.

## What I'm building

- A cleaned, connected data model across customers, orders, order items, products, inventory, warehouses, shipments, deliveries, suppliers and returns
- KPIs written in DAX (revenue, orders, delivery time, on-time rate, return rate, inventory and more)
- A five-page interactive dashboard: Executive, Customers, Inventory & Warehouse, Shipment & Delivery, Supplier & Product
- An executive report and presentation with recommendations

## Status

Complete. The data is cleaned and modelled, the five-page Power BI dashboard is built, and the executive report and presentation are written.

## Key findings

- Only about a third of shipments arrive on time, and delays are similar in every city and warehouse, so the cause is process, not place.
- Late delivery is the most common reason for returns.
- Stock is large but moves slowly, while some warehouse and product pairs run low.
- Ibadan has the most customers but no warehouse.

## Assumptions and Data Limitations

Real data is rarely perfect, so these are the assumptions I'm working with:

- **Suppliers:** The data has no direct link between suppliers and products or shipments. I treat the suppliers file as a standalone reference table. Any supplier analysis will rely on clearly stated assumptions.
- **Warehouse capacity:** No capacity figures were provided. Utilisation is estimated from proxies: stock quantity held, number of unique products and shipments handled. It is an estimate, not true capacity.
- **Inventory records:** Repeated warehouse and product combinations are stock movements, not duplicates. I sum quantities per warehouse and product and do not delete them.
- **Data dictionary:** The dictionary is simplified, so meanings such as "Delayed" and "On Time" are inferred from column names and documented in the report.

## Folder structure

```
Week5_DataAnalytics_SwiftLog_OluwayomiPrecious/
├── Data/            original datasets
├── Dashboard/       SwiftLog_Analytics.pbix
├── Report/          Executive_BI_Report.pdf, Dashboard_Screenshots.pdf
├── Presentation/    Executive_Presentation.pptx
├── Images/
├── README.md
└── References/
```

---
*Part of the AnalystLab Africa Experience Lab. #AnalystLabAfrica*
## Datasets

The project specification identifies the following datasets:

- Customers
- Orders
- Order Items
- Products
- Suppliers
- Warehouses
- Inventory
- Shipments
- Delivery Performance
- Employees
- Returns
- Data Dictionary

The supplied data dictionary will be used to understand the fields and validate relationships. Original datasets will be added to the project repository only where sharing is permitted.

## Planned Dashboard Pages

1. **Executive Dashboard:** Revenue, orders, delivery performance and returns.
2. **Customer Analytics:** Customer revenue, order frequency and purchasing trends.
3. **Inventory & Warehouse:** Stock levels, low-stock products, turnover and warehouse utilisation.
4. **Shipment & Delivery:** Shipment status, delivery times, delays and regional performance.
5. **Supplier & Product:** Supplier performance, product revenue, categories and returns.

## Planned Analytical Measures

The analysis will cover total revenue, total orders, total customers, total products, total shipments, average order value, average delivery time, average delivery delay, inventory turnover, return rate, supplier performance, on-time delivery rate, warehouse utilisation and customer retention.

Measure definitions will be documented and validated against the available data before conclusions are drawn.

## Repository Structure

```text
SwiftLog-Logistics-Analytics/
├── Data/
│   └── Original Datasets/
├── Dashboard/
│   └── SwiftLog_Analytics.pbix
├── Report/
│   ├── Executive_BI_Report.pdf
│   └── Dashboard_Screenshots.pdf
├── Presentation/
│   └── Executive_Presentation.pptx
├── Images/
├── References/
└── README.md
```

This structure represents the intended organisation of the project. Files will be added as they are completed.

## Current Status

The project scope, business objectives, dataset requirements, planned KPIs and dashboard structure have been documented.

Practical data preparation, modelling, DAX development, dashboard implementation and business findings remain subject to completion and validation.

## Expected Outcome

The intended outcome is an interactive Business Intelligence solution that helps SwiftLog identify operational challenges, monitor performance and make evidence-based decisions.

**Note:** No analytical results or performance improvements are claimed until they have been established using the supplied datasets.

## Acknowledgement

Prepared as part of the AnalystLab Africa Experience Lab Internship Programme, Data Analytics Track.
