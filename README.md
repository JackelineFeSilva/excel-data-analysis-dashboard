# Bike Sales Dashboard | Excel

I built this Excel dashboard as practice while following an **Alex The Analyst tutorial**. The project idea and dataset came from the tutorial. I cleaned the data, explored it with PivotTables, and created charts and slicers to compare bike purchases across different groups.

## Project overview

The workbook opens on `Working Sheet`, the prepared dataset used for analysis. The `bike_buyers` tab preserves the raw data, while `Pivot Table` contains the summaries and `Dashboard` presents the interactive view. The public workbook opens with all slicer items selected and is configured to refresh its PivotTables when opened in Microsoft Excel.

## Dataset and preparation

The source tab contains **1,026 rows** and 13 fields covering customer demographics, income, commute distance, and bike purchase status. I used **Data > Remove Duplicates** to remove 26 repeated rows, leaving **1,000 distinct records** in the working sheet.

In the working sheet, I used **Find and Replace** to change the gender codes `M` and `F` to `Male` and `Female`. Marital status codes were also expanded to `Married` and `Single`. A nested `IF` formula adds age brackets for under 31, ages 31–59, and over 59. The workbook uses the labels `Adolescent`, `Midle Age`, and `Senior` (including the original spelling of `Midle Age`).

## Analysis and dashboard

Four PivotTables compare purchase status by average income and gender, commute distance, age bracket, and individual age. The dashboard presents three charts with slicers for marital status, children, education, and region. Open the workbook in Excel to interact with the slicers and PivotCharts.

### Key insights from all 1,000 records

- **481 buyers (48.1%)** purchased a bike.
- **200 of 366** buyers with a 0–1 mile commute purchased a bike, compared with **33 of 111** with a commute over 10 miles.
- The `Midle Age` bracket contains **405 purchases among 775** records.
- Average income is approximately **54,875** for non-purchasers and **57,963** for purchasers. The workbook does not specify a currency.

## Skills and tools

Microsoft Excel: Find and Replace, Remove Duplicates, nested `IF` formulas, PivotTables, PivotCharts, slicers, and dashboard layout.

## Files

| File | Description |
| --- | --- |
| [`workbook/bike_sales_excel_dashboard.xlsx`](workbook/bike_sales_excel_dashboard.xlsx) | Excel workbook with the working data, PivotTables, charts, and dashboard. Personal author and local-path metadata were removed for public sharing. |
