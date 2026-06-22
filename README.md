# XDA Retail Sales Analysis
*Tools Used: SQL & Power BI*
Refer to the file (report/Retail_dashboard.pbix) for a detailed and interactive report.
## 1. Project Overview

This project analyses retail sales data using SQL and Power BI.

SQL was used to clean, validate, organise, and transform more than 26,000 transaction records. The prepared data was then imported into Power BI to create an interactive dashboard covering sales performance, product profitability, customer behaviour, and store efficiency.

The purpose of the project was to transform raw retail data into clear business insights that could support decisions related to sales, inventory, marketing, and store operations.

### 1.1 Project Objectives
The main objectives were to:
- Clean and organise raw retail data using SQL
- Validate data quality and table relationships
- Create analysis-ready tables and SQL views
- Calculate key sales and profitability metrics
- Build an interactive Power BI dashboard
- Identify trends, performance gaps, and business opportunities

### 1.2 Tools and Technologies
- SQL – data cleaning, validation, transformation, joins, aggregation, and views
- Power BI – data modelling, DAX calculations, visualisation, and dashboard development
- Power Query – data loading and additional data preparation
- DBeaver – database connection and SQL query execution
- GitHub – project documentation and version control

## 2. Methodology

The project followed three main stages:
- Data preparation with SQL: Cleaned, validated, and organised the data, and created key calculated fields.
- Data modelling in Power BI: Built a relational model connecting sales with product, customer, store, and date data.
- Dashboard development: Created DAX measures and visualisations to analyse performance and trends.

### 2.1 Data Cleaning and Transformation

Key SQL tasks included:

- Removing duplicates and handling missing values
- Validating keys and data formats
- Joining tables and preparing analysis-ready data
- Creating calculated fields and SQL views

**Main calculated fields:**

- Revenue = Quantity * Unit_Price
- Cost = Quantity * Unit_Cost
- Profit = Revenue - Cost
- Profit_Margin = Profit / Revenue

**Key Performance Indicators:**

- Revenue, profit, cost
- Orders and units sold
- Average order value and profit margin
- Store efficiency metrics

## 3. Dashboard Pages

The report includes four main pages.

### 3.1 Executive Overview

High-level summary of performance, including revenue, profit, orders, trends, and category performance.

### 3.2 Product Analysis

Focuses on product sales, profitability, and category performance.

### 3.3 Customer Analysis

Examines customer segments, demographics, and purchasing behaviour.

Customer age groups:

Under 25
25–34
35–44
45–54
55–64
65+
### 3.4 Store Analysis

Compares store performance, efficiency, and demand across locations and channels.

## 4. Key Insights

The analysis highlighted several important patterns.

### 4.1 Sales Performance
Revenue and profit changed across different months, indicating seasonal or time-based variations in customer demand.
Periods with high revenue did not always produce the highest profit, showing that sales growth should be evaluated alongside cost and margin.
Sales trends can help the business identify strong periods and prepare for slower months.
### 4.2 Product Performance
A relatively small number of products and categories generated a significant proportion of revenue.
High-selling products were not always the most profitable products.
Some products generated strong sales volumes but had lower profit margins, which could reduce their overall contribution to the business.
Category and subcategory analysis revealed differences in demand and profitability across the product range.
### 4.3 Customer Behaviour
Customer groups showed different purchasing patterns based on age, gender, and location.
Some customer segments generated higher average order values than others.
A small group of high-value customers contributed a larger share of total revenue.
Customer analysis can support more targeted marketing and promotional activity.
### 4.4 Store Performance
Stores varied significantly in revenue, profit, demand, and operational efficiency.
Stores with the highest total revenue were not always the most efficient when performance was adjusted for store size.
Revenue and profit per square metre provided a more balanced comparison between stores of different sizes.
Product demand differed by location, suggesting that inventory requirements should not be identical across all stores.
### 4.5 Sales Channels
Online and physical stores showed different sales and product demand patterns.
Online performance should be assessed separately rather than treated as a traditional store location.
Channel-level analysis can help identify where specific products or customer groups perform most strongly.
## 5. Recommendations
Based on the analysis, the business should consider the following actions.

### 5.1Product and Inventory Strategy
Prioritise high-revenue and high-margin products in inventory planning.
Maintain sufficient stock levels for products with consistently strong demand.
Review products with high sales volume but low profit margins.
Consider pricing, supplier cost, or promotional changes for low-margin products.
Reduce excess inventory for products with weak and declining demand.
### 5.2 Customer and Marketing Strategy
Target customer groups with higher average order values through personalised promotions.
Develop retention campaigns for high-value customers.
Use customer age, location, and purchasing behaviour to create more relevant marketing segments.
Promote related products to customers based on purchasing patterns and category preferences.
### 5.3 Store Operations
Evaluate stores using both total performance and efficiency measures such as profit per square metre.
Investigate underperforming stores by reviewing product mix, customer demand, location, and store size.
Apply successful practices from high-performing stores to similar locations.
Adjust store-level inventory based on local product demand instead of using the same stock strategy across every store.
### 5.4 Channel Strategy
Develop separate sales and product strategies for online and physical channels.
Increase online promotion for products that perform strongly through digital channels.
Review products that perform well in stores but poorly online, and vice versa.
Use channel-specific trends to improve inventory allocation and promotional planning.
### 5.5 Performance Monitoring
Monitor revenue, profit, margin, and average order value together rather than relying on sales alone.
Review monthly and yearly performance to identify seasonal changes.
Add year-on-year comparisons to evaluate business growth.
Use dashboard filters to investigate changes by product, customer segment, location, and channel.

## 6. Business Value

The dashboard provides decision-makers with a central view of retail performance.

It allows users to:

- Monitor sales and profitability KPIs
- Identify high-performing products and categories
- Compare customer groups and purchasing behaviour
- Evaluate store performance and operational efficiency
- Compare online and physical sales channels
- Detect underperforming areas
- Support inventory, marketing, pricing, and operational decisions
- Move from raw transaction data to evidence-based recommendations
