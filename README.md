1. Overview

This project analyzes customer shopping behavior to uncover patterns that help improve sales, customer satisfaction, and loyalty.
Using Python, SQL, and Power BI, the workflow covers data loading, cleaning, exploratory analysis, database querying, dashboard development, and creation of a final report and presentation.
2. Dataset

Name: Customer Shopping Behavior Dataset

Size: 3,900 rows × 18 features 

Source: Internal retail customer transactions

Key Columns:

Demographics: age, gender, location, subscription status

Shopping: item, category, amount, size, color, season

Behavior: discount usage, review ratings, previous purchases

Logistics: shipping type
3. Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Database Systems: PostgreSQL, MySQL, SQL Server

SQL Tools: pgAdmin, MySQL Workbench, SSMS

Power BI Desktop: Interactive dashboard creation

Gamma.app: Automatic PPT creation

Jupyter Notebook : Development environment
4. Project Steps
4.1 Data Loading (Python)

Import data using Pandas

Inspect structure: df.info(), df.describe()

Visualize distributions and detect anomalies

Export cleaned dataset for SQL ingestion

4.2 Exploratory Data Analysis (EDA)

Summary statistics for numerical columns

Trend and distribution charts (histograms, bar charts, box plots)

Correlation analysis

Insights discovered:

Middle-aged customers contribute highest revenue

Subscribers spend more and generate more revenue 

Express shipping users show different spending patterns

4.3 Data Cleaning

Standardized column names (snake_case)

Filled missing ratings using median per product category 

Removed duplicates

Created engineered features:

age_group

purchase_frequency

discount_dependency flags

Validated with summary checks

4.4 SQL Analysis

Cleaned data was loaded into SQL for deeper analytical queries.
Queries were written for PostgreSQL, MySQL, and SQL Server with cross-compatible syntax
Key SQL Analyses: 

Revenue by gender

High-spending discount users

Top 5 products by review rating

Standard vs express shipping comparison

Subscriber vs non-subscriber revenue

Discount-dependent products

Customer segmentation: New, Returning, Loyal

Top 3 products per category

Repeat buyer subscription likelihood

Revenue contribution by age group
4.5 Power BI Dashboard

Dashboard sections include:

KPIs: revenue, orders, average spend

Demographics: revenue by age group, gender, location

Product Insights:

Top rated products

Most purchased items

Discount-heavy items

Customer Segmentation: New / Returning / Loyal

Shipping Insights: Standard vs express spend

Subscription Analysis: total revenue & average spend

Interactive Filters: category, season, shipping type
4.6 Final Report

Based on analysis from Python, SQL, and Power BI.
Includes:

Business context

EDA outputs

SQL insights

Dashboard interpretation

Key business recommendations (loyalty programs, discount policy optimization, targeted marketing, subscription promotion)

Supported by visuals from the 4.7 Presentation (Gamma)

Automatically generated PPT summarizing project

Includes:

Business problem

Data preparation steps

Key insights

Visual dashboards

Marketing & strategic recommendationsdashboard and Python charts
Final PPT: Customer Shopping Behavior Analysis 

Customer-Shopping-Behavior-Anal…

5. Dashboard Overview

Main Pages:

Revenue Summary
KPIs + revenue heatmap

Customer Demographics
Age groups, gender split, subscription status

Product Insights
Top 5 ratings, top 3 per category, discount dependency

Shipping & Discounts
Standard vs express spend, discount effects

Customer Segments
New, Returning, Loyal counts & spend
Key Dashboard Findings:

Middle-aged customers contribute the highest revenue.

Subscribers generate higher lifetime value.

Five products exhibit high discount dependency.

Loyal customers have the highest average spend.

Express shipping customers show different purchase patterns.

6. Results & Insights

Top Insights:

Female customers generated slightly higher revenue overall 

Discount users can still be high-spenders → refine promo strategy

Express shipping users may represent premium customers

Subscription is correlated with higher revenue & repeat behavior

Highest revenue age group: Middle Age segment (35–50 years)

New customers have lower average spend; loyalty programs can improve retention

Top categories and products can guide inventory decisions
Strategic Recommendations:

Launch targeted campaigns for high-revenue age groups

Encourage subscription enrollment with benefits

Moderate heavy discounting on high-volume items

Promote highly rated products

Create loyalty rewards for returning buyers.
7. How to Run This Project
7.1 Requirements

Python 3.8+

Required packages (Pandas, NumPy, Matplotlib, SQLAlchemy)

PostgreSQL / MySQL / SQL Server installed

Power BI Desktop
7.2 Setup Steps

Clone project folder

Install Python libraries
Run EDA & cleaning notebook

Export cleaned dataset

Load dataset into SQL database

Use included .sql script

Execute SQL queries

Queries located in: customer_behavior_sql_queries.sql 

customer_behavior_sql_queries

Open Power BI file and refresh data source

Generate PPT in Gamma

Upload summary content and dashboard visuals

Review final report and deliverables



