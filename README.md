# Portfolio Case Study: Drug Sales Performance Analysis

---
## Introduction:
This case study takes a deep dive into drug sales data from 2022 to 2023, focusing on customer segmentation, revenue trends, and product performance. A dashboard was developed to break down sales by demographics, countries, buyer types, and time periods—highlighting key patterns and insights to support strategic business decisions.

---
## Problem Statement
1. Which drug products generate the most revenue, and how do customer types and demographics influence product performance?
2. Which customer segments are driving the most revenue, and how can we better understand our buyer profiles to improve targeting and sales strategy?
3. What are the key revenue trends over time, and how do seasonal or quarterly patterns affect overall drug sales performance?

## Data Source
There are 3 datasets provided in CSV format, described as below:
- `fact_sales.csv` is a fact table that records individual drug sales transactions, which used for tracking and analyzing sales performance over time, across products, regions, and customer types
- `dim_drug.csv` is a dimension table containing detailed information about each drug in the dataset
- `dim_customers` is a dimension table containing demographic and identification information of customers

## Skills demonstrated
The following Power BI features were incorporated:
1. Bookmarking,
2. Measures, new tables
3. Page navigation
4. Filters
5. Tooltips
6. Button
7. DAX 
8. Modelling
The project follows the star schema model, which has 2 dimension tables and 1 fact table. The dimension tables are all joined to the fact table with a one-to-many relationship.

## Visualization
The report consists of 3 following pages:
1. Top/Bottom Analysis
2. Customers Analysis
3. Trend Analysis

The report is available for interaction at the link provided

## Results/Insight
### 1. Top/Bottom Analysis

![Overview](Images/Overview.png)

### 2. Customer Analysis

![customer](Images/customer.png)

### 3. Trend Analysis

![trend](Images/trend.png)

## Recommendations
1. Strengthen Sales in High-Performing Regions
- Focus marketing and partnerships in Canada and Australia which bring over 66% of total revenue.
- Explore expansion in Germany and the UK, which show promising mid-tier contributions.

2. Target Older Demographics
- Develop targeted campaigns and loyalty programs for the 50+ age group, your most profitable segment.
- Promote age-appropriate medications such as Clonazepam, Ergocalciferol, and Lisinopril.

3. Optimize for Seller Partnerships
- With 87% of revenue from Sellers, invest in B2B strategies such as: Discount tiers, Volume incentives, Exclusive product access

4. Leverage Revenue Seasonality
- Capitalize on revenue spikes in Feb, Jun, and Aug through promotions and stock planning.

- Investigate and address dips in Jan, Jul, and Oct by understanding seasonal demand changes.

5. Product Strategy
- Increase supply and marketing of Doxycycline and Clonazepam, your top earners.
- Bundle lower-performing drugs with high-demand items to boost sales across the board.

6. Enhance Weekday Promotions
Run targeted weekday deals—especially on Monday, Wednesday, and Friday—when earnings are highest across key products.

## Tools & Technologies
Power BI (assumed from visual style, update me if different)

Data Prep: Power Query / Excel transformations

Data Modeling & Relationships

KPI Cards and Slicers for interactivity

Custom formatting for visual clarity
