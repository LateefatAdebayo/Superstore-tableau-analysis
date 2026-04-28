# KPI Dictionary – Superstore Performance Dashboard

This document explains the key metrics and elements used in the Superstore Performance Dashboard. It is meant to help users quickly understand what each number and chart represents.

## Total Sales
Total Sales represents the overall revenue generated from all customer orders within the selected time frame.  
It gives a quick summary of how the business is performing in terms of revenue.
*Calculation:*  
SUM(Sales)

## Sales Growth Rate
Sales Growth Rate shows how sales have increased or decreased over time.  
A positive value (like the 21.4% shown in the dashboard) indicates that sales are improving compared to the previous period.
*Calculation:*  
(SUM(Sales) - LOOKUP(SUM(Sales), -1)) / LOOKUP(SUM(Sales), -1)

## Profit Margin
Profit Margin measures how much of the total sales is retained as profit after costs.  
This helps evaluate how efficient the business is at turning revenue into actual profit.
*Calculation:*  
SUM(Profit) / SUM(Sales)

## Average Order Value (AOV)
Average Order Value shows the average amount spent per customer order.  
It helps understand customer purchasing behavior and overall spending patterns.
*Calculation:*  
SUM(Sales) / COUNTD(Order ID)

## Sales & Profit Over Time
This chart tracks how sales and profit change across months.  
It helps identify trends, patterns, and seasonality.  
For example, the dashboard highlights a peak in November, likely due to holiday demand.

## Profit by Category
This visual shows how much profit each product category contributes.  
In this dashboard, Technology performs the best, followed by Office Supplies, while Furniture contributes the least.

## Sales by Region
This chart compares sales across different regions (West, East, Central, and South).  
It helps identify high-performing and low-performing regions.  
From the dashboard, the West region leads in sales, while the South region performs the lowest.

## Filters
The dashboard includes interactive filters for:
•⁠  ⁠Order Date  
•⁠  ⁠Region  
•⁠  ⁠Category  
•⁠  ⁠Segment  
These allow users to customize the view and focus on specific parts of the data.

## Annotation
An annotation is included in the dashboard to highlight a key insight —  
the noticeable increase in sales around November, likely driven by seasonal demand and promotions.

## Layout & Interactivity
The dashboard is built using containers for a clean and structured layout.  
Navigation buttons are included to allow users to move between different sections such as Data Source and Definitions.

This KPI dictionary is designed to support the dashboard by providing clear explanations of each metric, making it easier for users to interpret insights and make informed decisions.
