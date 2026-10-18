
# Power BI Sales Analysis Dashboard

## Project Overview
This project analyzes sales performance using Microsoft Power BI and DAX calculations. The dashboard provides insights into sales, profit, order counts, sales targets, product categories, and geographic performance.

## Dataset Tables
- **List of Orders:** Contains order dates, order IDs, customer names, cities, and states.
- **Order Details:** Contains sales amount, profit, quantity, category, and sub-category.
- **Sales Target:** Contains monthly sales targets for each category.

## DAX Calculations

### Calculated Columns
- **Category Type:** Combines Category and Sub-Category.
- **Revenue:** Calculates revenue using Amount × Quantity.
- **Sales Category:** Categorizes sales as Above Average or Below Average.
- **Month:** Used for monthly sales analysis.

### Measures
- Total Number of Orders
- Average Profit in Delhi
- Year-to-Date (YTD) Sales
- Total Sales
- Sales Target
- Minimum Target for Each Category

## Dashboard Visualizations
1. KPI cards displaying total orders, average profit in Delhi, and YTD sales.
2. Column chart showing sales targets by category.
3. Donut chart showing profit by sub-category.
4. Line chart displaying monthly sales trends.
5. Scatter chart comparing profit and quantity by sub-category.
6. Cards comparing total sales and sales targets.
7. Matrix comparing actual sales and targets across months and categories.
8. Map visualizing sales by city.
9. Treemap showing sales distribution by sub-category.
10. Funnel chart showing order counts by state.

## Key Insights
- Total sales are approximately 432K against a target of 436K.
- Sales are close to the overall target.
- Monthly sales fluctuate, with a noticeable decline around July and recovery later in the year.
- Printers, Bookcases, and Sarees are among the major sales contributors shown in the treemap.

## Tools and Technologies
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Visualization and Reporting

## Conclusion
This dashboard helps analyze sales performance, monitor targets, identify product trends, and understand geographic sales distribution. It supports better business decisions through interactive visualizations.
