# Adventure Works PowerBI Analysis Project

Welcome to the Adventure Works PowerBI Analysis project! This project focuses on analyzing data from the Adventure Works shop, covering Orders, Customers, and Products tables.

## Project Overview

1. **Data Preprocessing**: The project begins with data preprocessing using Power Query to ensure clean and structured data.

2. **Data Modeling**: A Snowflake Schema, an extension of the Star Schema, is implemented by establishing one-to-many connections between fact tables and dimension tables.

3. **Measures**: DAX (Data Analysis Expressions) is used to create measures, optimizing space utilization and enabling flexibility in data analysis.

## Dashboard Pages

### 1. Executive Dashboard
- Key Performance Indicators (KPIs): Total Revenue, Total Profit, Total Orders, Overall Return Rate.
- Dynamic time series map for revenue trending with drill-up and drill-down capabilities.
- Horizontal bars showcasing orders by category with customized tooltips.
- Monthly revenue, orders, and returns with responsive targets.
- Matrix displaying the top 10 products with the highest revenue, supporting drill-through functionality.
- Customized filter pane with year and continent filters.

### 2. Map
- Visualizes continent-wise orders from around the world.

### 3. Product Details
- Gauge Charts for monthly orders vs. target, monthly revenue vs. target, and monthly profit vs. target.
- Numeric range parameters and fields parameters for scenario visualization.
- Insight into profit scenarios based on different sales scenarios.
- Trend analysis for returns across categorical metrics.

### 4. Customer Details
- Donut charts illustrating orders by income level and occupation.
- Time series line chart showcasing customer trends with a time slicer for dynamic analysis.
- Matrix displaying the top 100 customers with the highest revenue for each time frame.
- Cards identifying the most valuable customers and their order statistics for each time frame.

## Demo Video

Watch a video demonstration of this project [here](#).

## Feedback and Questions

If you have any queries or suggestions, please feel free to drop them in the comment section of the video or reach out through the GitHub repository. Your feedback is greatly appreciated!

Happy learning! 🙌
