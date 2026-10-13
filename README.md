# IT Expenditure Analysis | Power BI

## Project Overview
This project analyzes IT expenditure for 2024 using Microsoft Power BI. The dashboard compares actual expenditure against planned and forecast amounts to identify budget variances, spending patterns, and areas requiring further investigation.

## Objectives
- Compare actual IT expenditure with planned and forecast expenditure.
- Analyze spending across business areas, regions, IT areas, and cost categories.
- Identify significant budget variances and unusual spending patterns.
- Provide data-driven recommendations to support financial planning and cost control.

## Tools & Technologies
- Microsoft Power BI
- Power Query for data cleaning and transformation
- DAX for measures and variance calculations
- Data modeling using relationships and a calendar table
- Microsoft Excel as the source data format

## Dashboard Pages
1. **Overall Expenditure** — Overview of expenditure, budget utilization, and spending patterns.
2. **Cost Analysis** — Detailed analysis of cost elements, cost groups, IT areas, and sub-areas.
3. **Executive Insights & Recommendations** — Summary of major findings and recommended actions, if included in the final report.

## Key Findings
- Total actual expenditure was approximately 555.73M against a plan of 900.40M.
- Actual expenditure was approximately 38.28% below plan.
- Labor was the largest cost group by actual expenditure.
- Telephone expenditure showed a substantial unfavorable variance that requires validation.
- December future actual expenditure exceeded the forecast, highlighting the need to review forecast assumptions and month-end spending.

*All amounts are reported in the source dataset's units.*

## Repository Contents
- `01_IT_Expenditure_Original_Dataset.xlsx` — Original Excel dataset.
- `02_IT_Expenditure_Analysis.pbip` — Power BI Project file.
- `IT Expenditure.Report/` — Report definition files.
- `IT Expenditure.SemanticModel/` — Semantic model definition files.
- `03_Executive_Overview_Dashboard` — Executive Overview dashboard screenshot.
- `04_Cost_Analysis_Dashboard` — Cost Analysis dashboard screenshot.

## How to Use
1. Download or clone this repository.
2. Open the `.pbip` file using a compatible version of Power BI Desktop.
3. Ensure the source dataset is available and update data source paths if necessary.
4. Refresh the data and explore the dashboard.

## Conclusion
This project demonstrates data preparation, data modeling, DAX calculations, interactive dashboard development, and financial variance analysis using Power BI.
