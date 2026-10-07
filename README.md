# Retail Sales and Delivery Analytics

## Project Overview

This Power BI dashboard analyzes 12,000 synthetic retail orders
from 2024–2025 across five Texas cities. It helps users explore
sales, profitability, online delivery performance, returns,
and customer satisfaction.

## Dashboard Preview

<!-- Drag your dashboard screenshot onto the line below. -->
<img width="1062" height="599" alt="image" src="https://github.com/user-attachments/assets/11c195b2-dec9-455e-b69c-c801411cdc86" />


## Key Insights

- Net revenue totaled $4.42 million, with a 34.4% profit margin.
- Houston generated the highest revenue at approximately $903,000.
- Of 5,348 online orders, 1,316 arrived late—a 24.6% late-delivery rate.
- Average satisfaction was 4.26/5 for on-time deliveries,
  compared with 3.14/5 for late deliveries.

## Dashboard Features

- Quarter-Year, City, and Channel slicers.
- KPI cards for revenue, profit, orders, delivery performance,
  returns, and satisfaction.
- Monthly revenue trends and city performance comparisons.
- Drill-down and drill-up to explore cities and categories
  while staying on the same report page.

## Data Science Problem

Predict whether an online order will arrive late using information
available when the order is placed, such as distance, city,
category, and promised delivery time.

The goal is to explore how prediction could help teams prioritize
fulfillment reviews before delays occur.

## Project Workflow

1. Imported the CSV dataset into Power BI.
2. Checked and assigned data types in Power Query.
3. Created a Date table and a relationship to the Orders table.
4. Created DAX measures for business KPIs.
5. Built interactive charts, cards, slicers, and a performance matrix.
6. Validated dashboard totals against the dataset.

## Data Source

The dataset is available in `retail_orders.csv`.

This project uses synthetic data for learning and portfolio purposes.
Its patterns do not represent a real company's performance.
