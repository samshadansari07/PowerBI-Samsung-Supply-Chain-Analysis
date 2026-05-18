# Samsung Sales & Supply Chain Analytics Dashboard

## Project Overview
This project focuses on analyzing Samsung’s sales and supply chain operations using Power BI.  
The dashboard provides interactive insights into sales performance, inventory management, production analysis, supplier performance, shipment tracking, and customer trends to support data-driven business decisions.

---

## Objectives
- Monitor sales and inventory performance
- Analyze production and procurement activities
- Track shipment operations and supplier efficiency
- Understand customer purchasing behavior
- Build interactive dashboards for business analysis

---

## Tools & Technologies Used
- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Dataset Information
The project includes multiple dimension and fact tables related to Samsung sales and supply chain operations.

### Dimension Tables
- dim_customer
- dim_date
- dim_facility
- dim_product
- dim_supplier

### Fact Tables
- fact_inventory
- fact_procurement
- fact_production
- fact_sales
- fact_shipment

---

## Data Cleaning & Transformation
Data cleaning and transformation were performed using Power Query in Power BI.

### Cleaning Steps
- Removed null values
- Removed duplicate records
- Fixed inconsistent data types
- Renamed columns for better readability
- Standardized formatting across datasets

---

## Dashboard Features
The Power BI dashboard includes:

- Sales Performance Analysis
- Inventory & Production Monitoring
- Supplier Performance Tracking
- Shipment Analysis
- Customer Insights
- Interactive Filters & Slicers
- KPI Tracking Dashboard

---

## Project Structure

```text
SUMSUNG_SALES_PRODUCT_ANALYTICS/
│
├── Clean_data/
│   └── sumsung clean data.xlsx
│
├── Power_bi/
│   └── sumsung sells project 1.pbix
│
├── Reports/
│   ├── customer.png
│   ├── Homepage.png
│   ├── Inventory and production.png
│   ├── overview.png
│   ├── shipment.png
│   └── supplier.png
│
├── Row_data/
│   ├── dim_customer.csv
│   ├── dim_date.csv
│   ├── dim_facility.csv
│   ├── dim_product.csv
│   ├── dim_supplier.csv
│   ├── fact_inventory.csv
│   ├── fact_procurement.csv
│   ├── fact_production.csv
│   ├── fact_sales.csv
│   └── fact_shipment.csv
│
└── README.md