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
* DAX Measures
Each visualization was designed to answer a specific business question.


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


# Results and Business Recommendations
# Results and Discussion

## 1. Are Our Products Competitively Priced?

**Visualization**


* Clustered Column Chart: **Average Product Price vs Competitor Price**

### Findings

The comparison between the store's average product price and the average competitor price indicates that pricing remains generally competitive across the products analyzed. Any noticeable price differences highlight areas where the business may be pricing above or below competitors.

### Discussion

Pricing is one of the strongest determinants of purchasing behaviour. Products priced significantly higher than competitors may discourage price-sensitive customers, while consistently lower prices could reduce profitability. Monitoring competitor pricing enables the business to maintain a balance between competitiveness and profit margins.

### Business Recommendation

* Continuously benchmark product prices against competitors.
* Adjust prices strategically based on market conditions and customer demand.
* Review products with large price differences to determine whether premium pricing is justified.

---

## 2. Are Discounts Attracting Customers?

**Visualization**

* Clustered Column Chart: **Impact of Discounts on Customer Footfall**

### Findings

The analysis shows that average customer footfall generally increases as discount levels increase. Higher discount ranges attract more visitors, suggesting that customers respond positively to promotional pricing.

### Discussion

Discounts encourage customer purchases by reducing the perceived cost of products. However, increasing discounts indefinitely may eventually reduce profitability. The objective is to identify the discount level that maximizes customer traffic while maintaining healthy profit margins.

### Business Recommendation

* Continue using discounts to increase customer traffic.
* Identify the optimal discount range that balances increased customer visits with profitability.
* Regularly evaluate promotional campaigns to avoid unnecessary discounting.

---

## 3. Are Promotional Campaigns Increasing Customer Visits?

**Visualization**

* Column Chart: **Impact of Promotion Intensity on Customer Footfall**

### Findings

Higher promotion intensity is associated with increased customer footfall, indicating that stronger promotional activities encourage more customers to visit the store.

### Discussion

Promotional campaigns improve product awareness and customer engagement. While stronger promotions appear effective, they should be monitored to ensure that additional marketing expenditure produces measurable improvements in customer traffic.

### Business Recommendation

* Continue investing in promotional activities with demonstrated success.
* Measure campaign performance regularly using customer traffic and other business KPIs.
* Focus on promotions that generate the highest return on investment.

---

## 4. Is Advertising Spending Effective?

**Visualizations**

* Line & Clustered Column Chart: **Advertising Spend vs Customer Traffic and Satisfaction**
* KPI Card: **Advertising Effectiveness**

### Findings

The dashboard indicates that increased advertising expenditure is generally associated with higher customer footfall and improved customer sentiment. The Advertising Effectiveness KPI further measures how efficiently advertising spending attracts customer visits.

### Discussion

Advertising plays a significant role in driving customer awareness and store traffic. While higher advertising expenditure appears beneficial, increasing budgets indefinitely may not always generate proportional increases in customer visits. Businesses should continuously evaluate advertising performance to ensure efficient use of marketing resources.

### Business Recommendation

* Allocate advertising budgets to campaigns that consistently generate customer traffic.
* Monitor advertising effectiveness using customer visits and customer sentiment.
* Review underperforming campaigns and optimize marketing strategies.

---

## 5. Is Inventory Meeting Customer Demand?

**Visualizations**

* Line & Clustered Column Chart: **Inventory Levels vs Customer Demand and Satisfaction**
* KPI Card: **Average Stock Level**

### Findings

The analysis suggests that stores with higher inventory levels generally experience stronger customer demand and improved customer satisfaction. Maintaining adequate inventory appears to support customer purchasing behaviour.

### Discussion

Inventory shortages may result in lost sales and dissatisfied customers, while excessive inventory increases storage costs. Maintaining an optimal inventory level helps ensure product availability while minimizing unnecessary inventory holding costs.

### Business Recommendation

* Maintain sufficient inventory levels to satisfy customer demand.
* Use inventory planning techniques to reduce stock shortages.
* Continuously monitor inventory performance alongside customer demand indicators.

---

# Overall Business Insights

The dashboard demonstrates that pricing strategies, discounts, promotions, advertising investment, and inventory management all contribute to customer behaviour and overall retail performance.

Key observations include:

* Competitive pricing supports market positioning.
* Discounts successfully attract additional customer traffic.
* Promotional campaigns increase store visits.
* Advertising positively influences customer traffic and customer sentiment.
* Maintaining adequate inventory improves customer satisfaction and supports customer demand.

These findings provide decision-makers with actionable insights for improving pricing strategies, optimizing marketing investments, and strengthening operational performance.



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

## Tools Used
* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel (CSV Dataset)


## Dashboard Features
* Interactive KPI Cards
* Business-focused Visualizations
* Retail Performance Dashboard
* Actionable Business Insights
