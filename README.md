# Mobile Sales Analysis Dashboard
<img width="807" height="449" alt="Screenshot 2026-07-06 073150" src="https://github.com/user-attachments/assets/383665a8-cfdb-448a-84fe-fb1cb0662b7f" />



An interactive Power BI dashboard analyzing mobile phone sales performance across brands, customers, cities, and time periods.

## Overview
This report uses a star-schema data model (`FactSales` fact table linked to `Dim Calendar`, `DimBrand`, and `DimCustomer` dimensions) to surface sales KPIs and trends.

## Pages
- **Analytical Dashboard** – high-level KPI overview (Total Sales, Total Qty, Avg Selling Price, Customer count)
- **Apple sales over the Month** – monthly trend of Apple product sales
- **Avg selling Price by Gender** – pricing patterns segmented by customer gender
- **Sales over the year** – yearly/YTD sales trend with year-over-year comparison

## Key Measures
- Total Sales
- Total Qty
- Avg SP (Average Selling Price)
- Total YTD / Previous Year
- Bangalore Sales
- Apple Sales

## Tech Stack
- Power BI Desktop (.pbix)
- DAX measures
- Star schema data modeling

## How to Use
1. Download `Dashboard.pbix`
2. Open in Power BI Desktop
3. Refresh data source connections (if applicable)
4. Explore via slicers and cross-filtering on each page

## Screenshots
