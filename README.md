# AeroMax Airways — Operations & Performance Analysis

## Project Overview
End-to-end data analytics project for AeroMax Airways 
analyzing 5,000 passenger and flight records. Project 
covers full data pipeline from raw data cleaning in Excel 
to interactive Power BI dashboard.

## Tools Used
- Microsoft Excel — data cleaning and preprocessing
- Power BI Desktop — interactive dashboard
- DAX — custom measures and calculations
- Power Query — data transformation

## What Was Done in Excel
- Removed 89 duplicate rows
- Fixed missing values in time columns
- Standardized category names and formats
- Created Age_Group column using IF formulas
- Created Delay_Category column
- Created Revenue_Cost_Ratio column
- Created Distance_Category column
- Built PivotTables for delay, satisfaction and revenue
- Created 5 charts for visual analysis

## What Was Done in Power BI
- Connected to cleaned Excel data
- Built 3 interactive dashboard sections
- Created DAX measures for KPI cards
- Built interactive sidebar navigation using Bookmarks
- Applied Z Pattern layout for intuitive reading
- Used consistent dark navy theme throughout

## Dashboard Sections
1. Flight Delay Analysis
   - Top 10 most delayed flights
   - Most congested departure and arrival airports
   - Delay category breakdown

2. Customer Satisfaction Analysis
   - Satisfaction by age group
   - Satisfaction by ticket class
   - Frequent flyer satisfaction comparison

3. Revenue & Fuel Performance
   - Revenue vs operating cost by route
   - Revenue by ticket class
   - Fuel consumption by flight distance
   - Top revenue cost ratio flights

## Key Insights
- Only 17.74% of flights are On-Time — critically low
- FL0032 has highest avg delay of 226.5 mins
- DXB and LAX most congested airports
- 30-39 age group has lowest satisfaction at 3.00/5.00
- AMS-ICN most profitable route at 581% revenue ratio
- DFW-DEN biggest loss-making route at only 20% ratio
- Long-haul flights most fuel efficient at 5.09L per km

## Recommendations
- Investigate FL0032 and FL0059 for recurring issues
- Focus improvements on DXB and LAX airports
- Target 30-39 age group for satisfaction improvements
- Discontinue or restructure DFW-DEN route
- Expand AMS-ICN and JFK-SIN frequency
