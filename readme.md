# Sales & Profit Analysis Dashboard

## Project Overview

This project presents an interactive Power BI dashboard and visual story using the Sample Superstore dataset. The goal is to analyze sales and profitability, identify regional and product-level patterns, and provide business recommendations.

## Business Question

**What factors are affecting sales and profitability, and where should the business focus?**

## Objective

- Analyze overall sales and profit performance.
- Identify regional differences in profitability.
- Compare profitability across product categories and sub-categories.
- Convert data findings into clear business recommendations.

## Dataset

**Sample Superstore**

The dataset contains retail order information including order dates, customers, regions, categories, sub-categories, sales, quantity, discount, and profit.

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX

## Key Measures

```DAX
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Total Quantity = SUM(Orders[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Total Orders = DISTINCTCOUNT(Orders[Order ID])
