# Sales Performance Dashboard (Power BI)

## Objective
Analyze sales data to identify trends, profit margins, and top-performing regions.

## Tools Used
- Power BI
- DAX
- Excel

## Key Insights
- Identified top revenue regions
- Analyzed profit trends
- Highlighted best-selling products

## Features
- Interactive dashboard
- KPI cards
- Filters for dynamic analysis

## DAX Used
- Total Sales = SUM(Sales[Sales])
- Profit = SUM(Sales[Sales]) - SUM(Sales[Cost])
- Profit % = DIVIDE([Profit], [Total Sales], 0)
