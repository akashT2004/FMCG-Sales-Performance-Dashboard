# FMCG Sales Performance Dashboard

## Project Overview

This project focuses on analyzing FMCG (Fast-Moving Consumer Goods) sales data to understand revenue performance, product category trends, sales channels, brand performance, regional performance, and sales activity over time.

The dashboard helps business managers, sales teams, and decision-makers monitor key sales KPIs, identify high-performing products and categories, compare sales channels, and understand revenue trends for better business planning and decision-making.

The analysis was performed using **Google Sheets and Looker Studio**, with an interactive dashboard containing KPIs, charts, and filters.

## Problem Statement

FMCG businesses generate large volumes of transactional sales data across different products, brands, categories, regions, and sales channels. Analyzing this data effectively is important for understanding sales performance and identifying opportunities for business growth.

The main objectives of this project are:

* Analyze overall FMCG sales and revenue performance.
* Track revenue and unit sales trends over time.
* Compare revenue across different product categories.
* Analyze sales performance across different channels.
* Identify high-performing brands.
* Analyze sales performance across different regions.
* Monitor stock availability, deliveries, and promotional activity.
* Provide an interactive dashboard for business performance monitoring.
* Support data-driven sales and operational decision-making.

## Tools and Technologies

* **Google Sheets**
* **Looker Studio**
* **Data Cleaning and Transformation**
* **Calculated Fields**
* **KPI Scorecards**
* **Interactive Filters**
* **Time-Series Analysis**
* **Data Visualization**
* **Dashboard Design**

## Live Dashboard

**Looker Studio Dashboard:**
https://datastudio.google.com/reporting/9a0698d0-f429-4a51-90d5-ed64cb2afd53

## Dataset Information

The dataset contains FMCG transaction-level sales and operational data covering the period **2022–2024**.

The dataset includes information related to products, brands, categories, sales channels, regions, pricing, promotions, deliveries, inventory, units sold, and revenue.

| Column            | Description                                           |
| ----------------- | ----------------------------------------------------- |
| `Transaction ID`  | Unique identifier for each transaction                |
| `date`            | Date on which the transaction occurred                |
| `sku`             | Unique product/SKU identifier                         |
| `brand`           | Brand associated with the product                     |
| `segment`         | Product segment                                       |
| `category`        | FMCG product category                                 |
| `channel`         | Sales channel such as Retail, E-commerce, or Discount |
| `region`          | Geographic sales region                               |
| `pack_type`       | Packaging type of the product                         |
| `price_unit`      | Selling price per unit                                |
| `promotion_flag`  | Indicates whether a promotion was applied             |
| `delivery_days`   | Number of days required for delivery                  |
| `stock_available` | Quantity of stock available                           |
| `delivered_qty`   | Quantity delivered                                    |
| `units_sold`      | Number of units sold                                  |
| `Revenue`         | Revenue generated from the transaction                |

## Dataset Period

**Time Period:** 2022–2024

**Data Type:** Transaction-level FMCG sales data

**Business Domain:** Fast-Moving Consumer Goods (FMCG)

The dataset covers multiple product categories including:

* Yogurt
* Milk
* ReadyMeal
* SnackBar
* Juice

It also contains multiple brands, regions, sales channels, packaging types, and promotional transactions.

## Data Preparation

### Step 1: Data Extraction

* Connected the FMCG dataset to **Google Sheets**.
* Reviewed the available transaction-level sales and operational fields.
* Used the Google Sheets dataset as the data source for Looker Studio.

### Step 2: Data Cleaning and Preparation

* Verified column names and data structure.
* Ensured the date field was suitable for time-series analysis.
* Verified numerical fields such as price, stock, delivered quantity, units sold, and revenue.
* Checked categorical fields such as category, brand, channel, and region.
* Prepared the dataset for visualization and dashboard reporting.

### Step 3: Looker Studio Integration

* Connected the Google Sheets dataset to **Looker Studio**.
* Configured dimensions and metrics according to the analysis requirements.
* Created calculated metrics and aggregations where required.
* Added interactive filters and dashboard controls.
* Designed the final sales performance dashboard.

## Key Performance Indicators

### 1. Total Revenue

Displays the total revenue generated across all FMCG transactions.

**Dashboard Value:** £19.95M

### 2. Total Units Sold

Shows the total number of units sold across all products and transactions.

**Dashboard Value:** 3.8M

### 3. Total Transactions

Displays the total number of transactions recorded in the dataset.

**Dashboard Value:** 190.8K

### 4. Average Unit Price

Shows the average selling price per unit across the dataset.

**Dashboard Value:** 5.3

These KPIs provide a quick overview of the overall sales performance before analyzing individual categories, brands, channels, and time periods.

## Dashboard Visualizations

### 1. Revenue Over Time

**Chart Type:** Time-Series / Line Chart

**Objective:**
Analyze how revenue changes over the 2022–2024 period.

**Purpose:**
Helps identify sales growth, declines, seasonal patterns, and changes in category performance over time.

The visualization compares revenue trends across major FMCG categories such as Yogurt, Milk, ReadyMeal, SnackBar, and Juice.

### 2. Revenue by Category

**Chart Type:** Bar Chart

**Objective:**
Compare total revenue generated by different FMCG categories.

**Purpose:**
Helps identify the highest and lowest revenue-generating product categories.

The dashboard allows users to compare categories such as Yogurt, Milk, ReadyMeal, SnackBar, and Juice.

### 3. Revenue by Channel

**Chart Type:** Donut Chart

**Objective:**
Analyze how revenue is distributed across different sales channels.

**Purpose:**
Helps businesses understand the contribution of different channels to overall sales performance.

The dashboard compares channels including:

* Retail
* E-commerce
* Discount

### 4. Revenue by Brand

**Chart Type:** Bar Chart

**Objective:**
Compare revenue generated by different brands.

**Purpose:**
Helps identify high-performing brands and understand their contribution to overall FMCG revenue.

The visualization allows management to compare individual brands and identify brands that may require additional attention or investment.

### 5. Revenue Trend by Product Category

**Objective:**
Compare the performance of different FMCG categories over time.

**Purpose:**
Helps identify categories with consistent growth, declining performance, or significant fluctuations during the analysis period.

## Interactive Dashboard Features

The dashboard includes interactive filters for:

* **Category**
* **Region**
* **Channel**

These filters allow users to dynamically analyze sales performance for specific product categories, geographic regions, and sales channels.

For example, users can select a particular region and channel to analyze how revenue and units sold change across the selected segment.

## Business Insights

### Insight 1

**Yogurt** is the strongest revenue-generating category in the dashboard, contributing significantly more revenue compared with the other categories.

### Insight 2

Revenue performance changes over time, with noticeable fluctuations across the 2022–2024 period. The time-series analysis helps identify periods of stronger and weaker sales performance.

### Insight 3

Revenue is distributed across **Retail, E-commerce, and Discount** channels. Comparing these channels helps businesses understand the contribution of each sales channel.

### Insight 4

Brand-level analysis shows differences in revenue contribution, allowing businesses to identify high-performing brands and evaluate their overall portfolio performance.

### Insight 5

Regional filtering allows management to investigate geographic differences in sales performance and identify regions with stronger or weaker revenue generation.

### Insight 6

The dataset combines sales information with operational variables such as **stock availability, delivered quantity, delivery days, and promotion status**, providing opportunities for deeper analysis of the relationship between sales and operations.

## Project Challenges

### 1. Transaction-Level Data

The dataset contains a large number of individual transactions. Aggregating this data correctly was important for calculating meaningful KPIs and visualizations.

### 2. Data Preparation

Different fields such as dates, numerical measures, and categorical dimensions needed to be correctly configured before building the Looker Studio dashboard.

### 3. KPI Calculation

Creating accurate aggregations for total revenue, total units sold, transaction count, and average unit price was important to ensure that the dashboard represented the underlying data correctly.

### 4. Time-Series Analysis

Displaying revenue trends across multiple years required correctly configuring the date dimension and aggregation levels.

### 5. Dashboard Design

The dashboard needed to present multiple KPIs and visualizations while maintaining a clean, readable, and business-oriented layout.

### 6. Interactive Filtering

Filters had to be configured so users could analyze the dashboard dynamically by category, region, and sales channel without creating separate dashboards for each segment.

## Project Outcome

The FMCG Sales Performance Dashboard provides an interactive solution for monitoring and analyzing sales performance.

The dashboard allows users to:

* Monitor total revenue and units sold.
* Track transaction volume.
* Analyze average unit price.
* Monitor revenue trends over time.
* Compare revenue across product categories.
* Analyze channel-wise revenue performance.
* Compare brand-level revenue.
* Analyze regional sales performance using interactive filters.
* Explore sales data dynamically using Looker Studio controls.
* Support data-driven FMCG business decisions.

## Future Enhancements

* Add profit and profit-margin analysis.
* Analyze the impact of promotions on revenue and units sold.
* Add stock-out and inventory performance analysis.
* Analyze delivery performance and delayed deliveries.
* Add year-over-year revenue growth.
* Add month-over-month sales growth.
* Create category and brand ranking metrics.
* Develop sales forecasting using historical trends.
* Add customer-level analysis if customer data becomes available.
* Integrate additional data sources for automated reporting.
* Implement scheduled and automated dashboard refreshes.
* Add advanced predictive analytics for demand and inventory planning.


