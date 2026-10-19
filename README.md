# TechMart - Retail Sales Dashboard | Excel

![TechMart Dashboard](TechMart_Dashboard.png)

## Overview
Analyzed 200 sales transactions for TechMart electronics retailer to track revenue performance and profitability.

## Key KPIs
- **Total Orders:** 200
- **Total Quantity:** 640
- **Total Revenue:** $421,499
- **Total COGS:** $287,102
- **Total Gross Profit:** $134,397
- **Profit Margin:** 31.9%

## Business Insights
- **Profitability:** Business operates at 31.9% gross margin, meaning $0.32 profit per $1 sale.
- **Top Category:** Smartphones generated highest revenue ($205,546).
- **Top Brand:** Brand 123 leads revenue by brand.
- **Seasonality:** July is peak revenue month ($66,303), September is lowest.
- **Sales Channel:** Online store dominates revenue share.

## Formula Used (Attention to Detail)
Profit Margin was not hard-coded. It is dynamically linked:
`KPI!H27 = G27/D27` = Gross Profit / Total Revenue
Dashboard shape = `=KPI!H27` (linked for auto-update)

This replaces meaningless `Sum of Unit Price` with real business metric.

## Tools Used
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers, Shape Linking)
- Data Cleaning, KPI Cards, Interactive Dashboard

## Files
- `TechMart.csv` - Raw raw data
- `TechMart.xlsx` - Cleaned data + Pivot + Dashboard
- `TechMart_Dashboard.png` - Final dashboard image

## Author
Aspiring Data Analyst | Excel | Building portfolio for entry-level roles.
