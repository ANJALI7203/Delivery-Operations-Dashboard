# Delivery Operations Dashboard

## Project Overview

This Power BI project analyzes delivery operations data to understand order demand, delivery performance, operational bottlenecks, and rider workforce requirements.

The dashboard transforms raw operational data into actionable insights through data cleaning, DAX calculations, KPI tracking, and interactive visualizations.

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning & Transformation
- Data Visualization

## Dashboard Pages

### 1. Order Demand & Trends

Analyzes overall order patterns and demand fluctuations.

Key metrics include:
- Total Orders
- Weekday Orders
- Weekend Orders
- Average Daily Orders
- Peak Hour Orders

The page also analyzes hourly demand, weekday patterns, and daily order trends.

### 2. Delivery & ETA Performance

Evaluates delivery efficiency and performance against expected delivery times.

Key metrics include:
- Delivered Orders
- On-Time Delivery %
- Late Delivery %
- Average Delay
- Average Delivery Time
- ETA Accuracy

The page compares expected ETA with actual delivery time and analyzes delivery-time distribution.

### 3. Operational Bottlenecks

Identifies stages and operational factors contributing to delivery delays.

The analysis includes:
- Average Packing Time
- Average Pickup Time
- Average Out-for-Delivery Time
- Average Reach Time
- Average Final Delivery Time
- Longest Delivery Time
- Rider Delay Analysis
- Top Delay Reasons

### 4. Rider Workforce Planning

Analyzes rider utilization and estimates workforce requirements based on order demand.

Key metrics include:
- Active Riders
- Orders per Rider
- Unassigned Orders
- Peak Riders Needed

The dashboard compares hourly order demand with estimated rider requirements.

## Data Preparation

The dataset was cleaned and transformed using Power Query. Major transformations included:

- Handling missing and null values
- Replacing invalid placeholder values
- Correcting data types
- Removing duplicate records
- Converting duration fields into minutes
- Creating date and time attributes
- Creating weekday and weekend classifications
- Creating delivery categories
- Creating rider assignment categories

## Key Insights

- Approximately 72% of delivered orders were completed on time.
- Peak hourly demand reached approximately 331 orders.
- Delivery performance varies across different days of the week.
- Operational stage durations help identify potential delivery bottlenecks.
- Rider requirements increase significantly during peak demand periods.
- A portion of orders remained unassigned, indicating opportunities for improved rider allocation.

## Rider Capacity Assumption

Rider requirements were estimated assuming that one rider can handle approximately **three orders per hour**.

Based on a peak demand of approximately **331 orders per hour**, the estimated peak workforce requirement is approximately **111 riders**.

## Data Quality Limitations

Some delay reasons are recorded as free-text entries and may contain inconsistent or unclear descriptions. These values were retained where appropriate to preserve the original source data.

Extreme duration values were reviewed and handled at the visualization level where necessary to prevent outliers from distorting operational analysis.

## Dashboard Preview

### Order Demand & Trends

![Order Demand & Trends](screenshots/order-demand-trends.png)

### Delivery & ETA Performance

![Delivery & ETA Performance](screenshots/delivery-eta-performance.png)

### Operational Bottlenecks

![Operational Bottlenecks](screenshots/operational-bottlenecks.png)

### Rider Workforce Planning

![Rider Workforce Planning](screenshots/rider-workforce-planning.png)

## Repository Structure

Delivery-Operations-Dashboard/
- README.md
- Delivery_Operations_Dashboard.pbix
- screenshots/
- dataset/

## Author

**Anjali Singh**

Power BI | Data Analytics | Data Visualization
