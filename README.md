### Supply Chain Analytics Dashboard (Power BI)
## Project Overview

This project presents an end-to-end Supply Chain Analytics dashboard built using Power BI, focusing on transforming raw operational data into actionable business insights.
The dashboard is designed to support executive decision-making, supplier evaluation, and inventory & logistics optimization using a star schema data model and DAX measures.

## Tools & Technologies

Power BI Desktop

DAX (Measures)

Power Query

Star Schema Data Modeling

## Repository Contents
Supply-Chain-Analytics-PowerBI
│
├── PowerBI_Supplychain_dashboard.pbix
│
├── Model_Supplychain.png
│
├── Report_SC_Executive overview.png
├── Report_SC_SupplierPerformance.png
├── Report_SC_Inventory&logistics.png
│
├── DAX_measures.png
│
└── README.md

## Data Model

Implemented a star schema with a centralized fact table

Dimension tables represent:

Product

Supplier

Location

Logistics

Customer

All relationships are one-to-many (1:*) with single-direction filtering

Refer to Model_Supplychain.png for the full model view.

## Dashboard Pages
### Executive Overview

Objective: High-level visibility into supply chain performance

Key KPIs:

Total Revenue

Profit

Average Lead Time

Average Defect Rate

Visuals:

Revenue by Product Type

Cost by Transportation Mode

Screenshot: Report_SC_Executive overview.png

### Supplier Performance

Objective: Evaluate supplier efficiency, quality, and cost trade-offs

Visuals:

Supplier vs Average Defect Rate (Table)

Average Lead Time by Supplier (Bar Chart)

Cost vs Defect Rate (Scatter Plot)

Screenshot: Report_SC_SupplierPerformance.png

### Inventory & Logistics

Objective: Monitor inventory health and logistics costs

Visuals:

Stock Levels by Product

Shipping Cost by Route

Units Sold by Location

 Screenshot:, Report_SC_Inventory&logistics.png

## DAX Measures

Key DAX measures were created to support all dashboard visuals, including:

Total Revenue

Total Cost

Profit

Average Lead Time

Average Defect Rate

Total Units Sold

Total Stock

Total Shipping Cost

Refer to DAX_measures.png for the complete list of measures.

## Key Insights

Some suppliers offer lower costs but exhibit higher defect rates, indicating quality risk

Transportation mode significantly impacts both cost and lead time

Inventory levels vary by product, highlighting opportunities for stock optimization

Sales volume differs across locations, informing demand planning decisions

## How to Use

Download the .pbix file

Open in Power BI Desktop

Use slicers to explore insights across products, suppliers, locations, and logistics

## Skills Demonstrated

Business-oriented dashboard design

Dimensional modeling (star schema)

DAX measure creation and usage

Supply chain performance analysis

Executive-level data storytelling

## Suitable For Roles

Data Analyst

Business Analyst

BI Analyst

Supply Chain Analyst

Operations Analyst

## Final Note

This project demonstrates real-world Power BI practices and reflects how supply chain analytics dashboards are built and consumed in industry.

## Author
Kavyashree Nagaraju
