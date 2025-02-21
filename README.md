# Dairy Products Analysis Dashboard

## Project Overview
The Dairy Products Analysis Dashboard is a comprehensive solution designed to provide insights into dairy production, sales performance, and revenue growth. Developed using Power BI, this interactive tool enables stakeholders to make data-driven decisions by visualizing key metrics and trends across the dairy industry.

## Problem Statement
In the highly competitive dairy industry, stakeholders must efficiently manage and interpret large volumes of data related to production, sales, and revenue. Traditional reporting methods often delay actionable insights, hindering timely decision-making. This project addresses these challenges by offering a modern, interactive dashboard that consolidates diverse datasets into one accessible platform, streamlining operations and driving profitability.

## Dataset
The dashboard is built upon a meticulously curated dataset that captures essential aspects of dairy production and sales:
- **File Name:** `dairy_dataset.csv`
- **File Size:** Approximately 5MB
- **Columns:**
  - **Year:** The year of data collection.
  - **Total_Cows:** Number of cows across various farms.
  - **Total_Land_Area:** Total area (in acres) of the farms.
  - **Quantity_Produced:** Total quantity of dairy products produced (liters/kg).
  - **Quantity_Sold:** Total quantity of products sold.
  - **Revenue:** Total revenue generated from sales.
  - **State:** Geographic distribution of production.
  - **Storage_Type:** Storage conditions (e.g., Refrigerated, Frozen, Ambient).
  - **Brand:** Names of dairy brands.

## Dashboard Creation Process
1. **Data Collection & Preprocessing:**
   - Imported the dataset from `dairy_dataset.csv`.
   - Applied data cleaning and transformation using Python and Pandas to ensure accuracy.
2. **Data Modeling:**
   - Established relationships between key metrics such as production, sales, storage, and revenue using Power BI.
   - Designed a data model that supports dynamic, interactive analysis.
3. **Dashboard Design & Implementation:**
   - Created multiple interactive pages focusing on overall performance, production details, and sales insights.
   - Utilized a range of visualizations, including bar charts, pie charts, maps, and line graphs.
   - Implemented filters and slicers to enhance user interactivity and enable detailed drill-down analysis.
4. **Insights & Analysis:**
   - Extracted key performance metrics and trends from the dataset, providing actionable insights for strategic decision-making.

## Key Insights
- **Total Revenue:** $58.7M, with a steady year-over-year growth of approximately 5% over the past five years.
- **Total Quantity Sold:** 1.1M units, with significant seasonal peaks observed during summer months.
- **Total Number of Cows:** 238K, underpinning large-scale production across numerous farms.
- **Farms Monitored:** 4K, with the majority concentrated in high-production states.
- **Production Distribution:** 
  - **Maharashtra:** Leads the production, accounting for over 40% of the total output.
  - **Gujarat & Rajasthan:** Contribute significantly with 20% and 15% respectively.
- **Top Brands:**
  - **Amul:** 525K units sold, dominating market share in both production and sales.
  - **Mother Dairy:** 510K units sold, consistently performing across multiple regions.
  - **Raj:** 347K units sold, showing rapid market penetration and growth.
- **Product Shelf Life:**
  - **Refrigerated:** 
    - Cheese – 58.37 days
    - Butter – 32.90 days  
    *(Indicates high quality and demand consistency.)*
  - **Frozen:** 
    - Ghee – 105.74 days
    - Ice Cream – 25.46 days  
    *(Ensures extended market availability.)*
- **Customer Demographics:** 
  - Metropolitan areas contribute to 45% of total sales.
  - Tier-2 cities account for 30%.
  - Rural regions make up 25%.
- **Operational Efficiency:** An average storage utilization rate of 82% highlights optimal management of refrigeration facilities.
- **Market Dynamics:** Detailed analysis reveals a strong correlation between regional production and sales volumes, influenced by local demand and seasonal variations.

## Visual Snapshots
### Home Page
![Image](https://github.com/user-attachments/assets/2d1f59e4-0610-48ca-af27-c0f3bd10079f)

### Production Insights
![Image](https://github.com/user-attachments/assets/5acee942-118e-4d18-a96e-01f0321f302b)
### Sales Insights
![Image](https://github.com/user-attachments/assets/19e9ba1c-a262-40e7-9137-2c5ccd584c7c)

## Tools & Technologies
- **Power BI Desktop:** For interactive dashboard visualization.
- **Python & Pandas:** For data cleaning and preprocessing.
- **DAX:** For advanced data calculations and metrics.


## Contributors
- [Anjali Dhosariya](https://github.com/AnjaliDhosariya)

