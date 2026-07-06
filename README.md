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
<img width="1132" height="639" alt="Screenshot 2026-07-06 073734" src="https://github.com/user-attachments/assets/c99b87a6-c042-408d-882f-12792ccd5d99" />

<img width="811" height="464" alt="Screenshot 2026-07-06 073539" src="https://github.com/user-attachments/assets/20c0f5b1-f4d5-45c2-b28f-06057924f228" />

<img width="816" height="459" alt="Screenshot 2026-07-06 073514" src="https://github.com/user-attachments/assets/9b01a09e-3b3a-4fef-a3e9-6ca87898dfe9" />

## This is a Mobile Sales Analysis Dashboard built in Power BI. Here's a breakdown of the project:
** Overview **
A retail analytics dashboard tracking mobile phone sales performance across brands, customers, cities, and time periods.
## Data Model
The report is built on a star schema with these tables:

  FactSales — the transactional fact table (sales amount, quantity, average selling price, customer count, brand-specific and city-specific sales measures)
  DimBrand — mobile phone brand dimension
  DimCustomer — customer details (name, gender, city)
  Dim Calendar — date/time dimension (month, year, YTD, previous year)

## Pages
1. Analytical Dashboard (main page, 12 visuals)

    KPI cards: Total Sales, Total Qty, Avg Selling Price, Customer count
    Bar chart: Sales by Brand
    Clustered column charts: Quantity by Brand & City, Customers by City
    Pie chart: Avg Selling Price by Gender
    Line charts: Apple sales trend by month; Sales YTD vs. Previous Year
    Bar chart: Sales & Bangalore-specific sales by Customer
    Slicers: Brand, City, Month (for interactive filtering)

2. Avg Selling Price by Gender — focused pie chart breakdown
3. Sales Over the Year — YTD vs. previous year trend line
4. Apple Sales Over the Month — line chart tracking Apple brand sales by month
## Purpose
The dashboard appears designed to help a business (likely a mobile phone retailer) monitor sales performance, compare brand popularity, understand customer demographics (gender, city), and track sales trends over time — with a particular focus on Apple as a brand and Bangalore as a key city


