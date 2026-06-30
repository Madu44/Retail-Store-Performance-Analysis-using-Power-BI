# Retail Store Performance Analysis using Power BI

## Executive Summary

This project presents an interactive Power BI dashboard designed to analyze the key factors influencing retail store performance. Using a retail dataset containing pricing, promotional activities, advertising spend, customer footfall, inventory levels, customer sentiment, weather conditions, and product return rates, the dashboard provides actionable insights to support business decision-making.
The analysis focuses on understanding how pricing strategies, discounts, promotions, advertising investment, and inventory management influence customer behaviour and overall store performance. The dashboard was developed using Power BI with DAX measures, interactive filters, KPIs, and business-focused visualizations to transform raw data into meaningful insights.


# Business Problems

The dashboard addresses the following business questions:

### 1. Are our products competitively priced?

**Objective:** Compare the store's average selling price with competitor pricing to evaluate pricing competitiveness.


### 2. Are discounts attracting customers?

**Objective:** Determine whether increasing discounts leads to higher customer footfall.


### 3. Are promotional campaigns increasing customer visits?

**Objective:** Evaluate whether stronger promotional campaigns generate higher customer traffic.


### 4. Is advertising spending effective?

**Objective:** Assess whether higher advertising expenditure results in increased customer visits and improved customer sentiment.


### 5. Is inventory meeting customer demand?

**Objective:** Evaluate whether inventory availability supports customer demand and satisfaction.


# Methodology

The project followed a structured Business Intelligence workflow:

### Data Preparation

* Imported the retail dataset into Power BI.
* Removed unnecessary columns (e.g., index column).
* Verified and assigned appropriate data types.
* Formatted monetary values as Currency ($) and percentage fields accordingly.

### Data Modelling

Created DAX measures for key business metrics including:

* Average Product Price
* Average Discount
* Average Promotion Intensity
* Average Competitor Price
* Average Footfall
* Average Advertising Spend
* Average Stock Level
* Average Customer Sentiment
* Average Return Rate
* Advertising Cost per Customer
* Total Footfall
* Total Ad Spent

### Creating Bins

Several variables in the dataset (such as **Discount**, **Advertising Spend**, and **Stock Level**) are continuous numerical values. Plotting every individual value on a column chart would create hundreds of categories, making the visuals difficult to interpret.

To improve readability, **bins** were created in Power BI.

A **bin** groups continuous numerical values into meaningful ranges.

For example:

| Original Discount Values | Discount Bin |
| ------------------------ | ------------ |
| 2.4%                     | 0–2%         |
| 3.8%                     | 2–4%         |
| 7.5%                     | 6–8%         |
| 15.9%                    | 14–16%       |

Similarly:

* Advertising Spend was grouped into spending ranges (e.g., €0–250, €250–500, etc.).
* Stock Level was grouped into inventory ranges.

Using bins made it possible to compare average business performance across logical groups rather than individual observations, making trends easier to identify and communicate.

### Dashboard Development

Interactive dashboards were created using:

* KPI Cards
* Clustered Column Charts
* Line & Clustered Column Charts
* Slicers
* DAX Measures

Each visualization was designed to answer a specific business question.

---

# Skills Demonstrated

### Business Intelligence

* Dashboard Design
* KPI Development
* Business Problem Solving
* Data Storytelling
* Performance Analysis

### Power BI

* Data Cleaning
* Data Transformation
* Data Modelling
* DAX Measures
* Interactive Dashboards
* Slicers & Filters
* Data Visualization

### Analytics

* Exploratory Data Analysis (EDA)
* Comparative Analysis
* Pricing Analysis
* Marketing Performance Analysis
* Customer Behaviour Analysis
* Inventory Analysis

---

# Results and Business Recommendations

## Pricing Strategy

Average product prices were compared with competitor prices to evaluate pricing competitiveness.

**Recommendation**

* Continuously monitor competitor pricing.
* Adjust prices strategically to remain competitive while maintaining profitability.

---

## Discount Strategy

Customer footfall increased across higher discount ranges, suggesting that discounts positively influence customer traffic.

**Recommendation**

* Continue using discounts as a customer acquisition strategy.
* Identify the optimal discount range that maximizes customer traffic without significantly reducing profit margins.

---

## Promotion Effectiveness

Stores with higher promotion intensity generally experienced increased customer footfall.

**Recommendation**

* Invest in promotional campaigns that demonstrate measurable improvements in customer traffic.
* Evaluate promotion performance regularly to optimize marketing budgets.

---

## Advertising Performance

Advertising expenditure showed a positive relationship with customer traffic and customer sentiment.

**Recommendation**

* Maintain investment in advertising channels that generate measurable customer engagement.
* Track advertising effectiveness using customer traffic and sentiment metrics to optimize future campaigns.

---

## Inventory Management

Higher inventory levels were associated with stronger customer demand and improved customer satisfaction.

**Recommendation**

* Maintain adequate stock levels to reduce the risk of lost sales.
* Use inventory planning to align stock availability with expected customer demand.

---

# What Next?

Future enhancements could further strengthen the analysis by incorporating additional retail metrics.

Potential improvements include:

* Adding sales revenue and quantity sold to measure financial performance.
* Performing sales forecasting using time-series analysis.
* Developing customer segmentation models.
* Building predictive models for customer demand.
* Performing profitability analysis.
* Creating a correlation heatmap to identify relationships between variables.
* Integrating real-time retail data using SQL or cloud data sources.
* Publishing the dashboard through the Power BI Service with automated data refresh.

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel (CSV Dataset)

---

## Dashboard Features

* Interactive KPI Cards
* Business-focused Visualizations
* Dynamic Filters and Slicers
* Retail Performance Dashboard
* Actionable Business Insights

---
