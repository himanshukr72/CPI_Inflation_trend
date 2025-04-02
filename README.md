# CPI-Dashboard

### Dashboard Link : (https://bitmesra-my.sharepoint.com/:u:/r/personal/ied10008_23_bitmesra_ac_in/Documents/CPI_Dashboard.pbix?csf=1&web=1&e=bHRmF7)


## Problem Statement

This dashboard helps in understanding inflation trends over the years. It allows an analysis of price variations of goods and services, identification of inflation patterns, and assessment of sector-wise and state-wise economic changes. Policymakers and businesses can use this dashboard to make informed decisions regarding economic stability and price control measures.

Since inflation impacts different economic groups in varying degrees, understanding these trends is crucial. The dashboard provides insights into yearly inflation fluctuations, average inflation per sector, and state-wise economic disparities.

### Steps followed 

- Step 1 : Loaded data into Power BI Desktop; dataset was a CSV file.
- Step 2 : Opened Power Query Editor & enabled "Column Distribution," "Column Quality," & "Column Profile."
- Step 3 : Ensured "Column Profiling Based on Entire Dataset" was selected.
- Step 4 : Handled missing values, especially in sector-wise inflation data.
- Step 5 : Filtered out null values while calculating mean inflation, as they accounted for less than 1% of the dataset.
- Step 6 : Applied a consistent theme in the Report View for visual clarity.
- Step 7 : Added a visual for inflation trends using various economic indicators.
- Step 8 : Added Visual Filters (Slicers) for four fields: "Year Selection (2014-2024)," "Economic Groups," "Subgroup Selection," & "State-wise Selection."
- Step 9 : Added card visuals to the canvas, representing "Average Inflation Rate," "Standard Deviation of Inflation," & "Inflation Rate for Selected Year."
- Step 10 : Added a bar chart & a line chart to the report design area representing inflation across years & economic groups.
- Step 11 : Used visual level filters to unselect null values for consideration in calculations.
- Step 12 : Created a calculated column where inflation categories were grouped and new excel sheet is created.
- Step 13 : Added visuals representing state-wise inflation trends.
- Step 14 : Inserted text boxes for the report title & organization name.
- Step 15 : Added a MoSPI logo & design elements for branding.
- Step 16 : Published the report to Power BI Service.

---

## Insights

A single-page report was created in Power BI Desktop & published to Power BI Service. The following insights were drawn:

### [1] Overall Inflation Trends (2014-2024)

- Inflation fluctuated due to global economic conditions, crude oil price changes, & supply chain disruptions.
- The COVID-19 pandemic (2020) showed significant inflation volatility.

### [2] Sector-wise Inflation Analysis

| Economic Group        | Average Inflation Rate |
|----------------------|----------------------|
| Food & Beverages    | 4.2% |
| Housing            | 3.5% |
| Clothing & Footwear | 3.8% |
| Fuel & Light       | 6.1% |
| Miscellaneous      | 4.5% |
| Pan & Tobacco      | 5.3% |

- "Fuel & Light" saw the highest inflation due to crude oil fluctuations.
- "Housing" remained relatively stable.

### [3] State-wise Inflation Trends

- Certain states consistently had inflation rates above the national average.
- Urban areas had higher inflation in "Housing" & "Services."
- Rural areas experienced more fluctuation in "Food" & "Fuel Prices."

### [4] Inflation Volatility (Standard Deviation Analysis)

- "Fuel & Light" exhibited the highest volatility.
- Inflation rates spiked in 2020 due to supply chain disruptions.
- "Food & Beverages" remained relatively stable over the years.

---
