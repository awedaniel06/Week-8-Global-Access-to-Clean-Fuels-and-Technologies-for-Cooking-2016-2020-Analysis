
# Week 8 of Analystlab Africa Internship Programme.
# Global Access to Clean Fuels and Technologies for Cooking (2016–2020)
### A Power BI Dashboard Analysis

## Overview
This project analyzes the **"Access to Clean Fuels and Technologies for Cooking (% of Population)"** indicator between 2016 and 2020, using data from the World Development Indicators (WDI) database published by the World Bank. The goal is to identify trends and disparities among countries and communicate the findings through an interactive Power BI dashboard, supporting progress toward UN Sustainable Development Goal 7 (Affordable and Clean Energy).

## Dashboard Preview

![Dashboard](https://github.com/awedaniel06/Week-8-Global-Access-to-Clean-Fuels-and-Technologies-for-Cooking-2016-2020-Analysis/commit/16fe7148d1a4fe4b9b05e4aa937004624f194e2e)


## Dataset
- **Source:** World Development Indicators (World Bank)
- **Indicator:** Access to Clean Fuels and Technologies for Cooking (% of Population)
- **Period covered:** 2016–2020
- **Countries/territories:** 265
- **Variables:** Country Name, Country Code, Year, Indicator Value (Access Rate)

## Data Cleaning & Transformation
- Extracted the relevant indicator and years (2016–2020) using SQL
- Unpivoted year columns in Power Query to convert wide format to long format
- Renamed generated columns (Attribute → Year, Value → Indicator Value)
- Converted data types (Year → Whole Number, Indicator Value → Decimal Number)
- Removed duplicates and handled missing/null values
- Standardized country names and codes
- Created an Access Category column via DAX (0–25%, 26–50%, 51–75%, 76–100%)

## Methodology
Built in Power BI using:
- Power Query for data transformation
- DAX measures for KPI calculations
- KPI cards, line chart, donut chart, horizontal bar charts, and a matrix table
- Slicers for Year and Country Name for interactive filtering

**KPIs:** Total Countries, Average Access Rate, Highest Access Rate, Lowest Access Rate, Number of Years

## Key Findings
- 265 countries and territories analyzed across 5 years (2016–2020)
- Average global access rate: **67.05%**
- Highest access rate: **100.00%**
- Lowest access rate: **0.10%**
- Global access increased steadily over the study period
- Most countries fall within the 76–100% access category
- Countries like Andorra, Australia, Austria, Belgium, and Canada consistently achieved universal or near-universal access
- Countries including Guinea, Central African Republic, Sierra Leone, Liberia, and Burundi recorded the lowest average access rates

## Insights
- Steady global improvement from 2016 to 2020 signals progress toward universal clean energy access
- Significant disparities remain between developed and developing countries
- The gap between countries at 100% access and those below 1% highlights unequal development in clean energy infrastructure
- Countries with the lowest access rates require urgent, targeted investment

## Recommendations
1. Increase investment in clean cooking infrastructure in low-access countries
2. Expand government subsidies to make clean cooking technologies more affordable
3. Strengthen collaboration between governments, international organizations, and the private sector
4. Raise public awareness of the health, environmental, and economic benefits of clean cooking fuels
5. Continue monitoring progress through data analytics and dashboards
6. Prioritize the lowest-access countries to accelerate progress toward SDG 7

## Tools Used
- SQL (data extraction)
- Power Query (transformation)
- Power BI (DAX, visualization, dashboard)

## Deliverables
- Interactive Power BI dashboard
- Full written report (Word/PDF)
- This README

---
*Part of a data analytics portfolio developed during the AnalystLab Africa internship.*
