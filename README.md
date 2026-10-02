# B2B Distribution Analytics & Decision Support System

## 1.1 Overview

B2B distributors manage large product catalogs, recurring retailer orders, inventory movement, credit-based sales, collections, and employee incentives. Looking at these processes separately can make it difficult for management to understand where money is being generated, tied up, or put at risk.

This project builds a synthetic B2B distribution analytics system that brings these operational areas together and turns transaction-level data into business insights and management decisions.

The project is inspired by operational and inventory analytics work observed during a data analyst internship in the building-materials distribution sector. All data, names, values, and business entities used in this project are fictional and created for portfolio purposes.

## 1.2 Project Objective

The goal is to build an end-to-end analytics workflow that answers questions such as:

Which products and categories are driving revenue?
Which products are selling quickly and may require replenishment?
Which products are becoming slow-moving or dead stock?
Where is inventory getting tied up?
Which customers are paying late?
How much revenue is still pending collection?
How are sales and incentive payouts distributed?
What operational patterns should management investigate?

The final output is a decision-support layer that connects business metrics with possible management actions.


## 1.3 Organizational Structure

The business operates across:
-Premium & Economy Tiles
-Premium & Economy Granite
-Marble
-Sanitaryware & CP Fittings
-Adhesives & Installation Accessories

The dataset covers:
October 1, 2024 – September 30, 2026, with an analytical as-of date of September 30, 2026.

The synthetic environment contains approximately:
-120 SKUs
-120 customers
-6,000–8,000 orders
-9 employees
-24 months of operational activity

## 1.4 Methodology
The methodology followed a systematic and structured approach to ensure accurate data analysis and meaningful outcomes. Below represents the 
```text
RAW OPERATIONAL DATA
        ↓
DATA MODELLING
        ↓
SQL ANALYSIS
        ↓
POWER BI
        ↓
BUSINESS INSIGHTS
        ↓
DECISION SUPPORT
```
The workflow begins by collecting raw inventory and sales data, then cleaning and preprocessing it to ensure accuracy and consistency. The cleaned data is then transformed and structured for analysis. Exploratory Data Analysis (EDA) is performed to identify patterns and trends, after which interactive dashboards are developed using Power BI. Finally, insights are generated to support business decision-making and improve operational efficiency.



```text
                 B2B DISTRIBUTOR
                       │
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
    INVENTORY       SALES         COLLECTIONS
        │              │              │
   What's stuck?   What's moving?  Who pays late?
   What needs      What's slowing   How much cash
   restocking?     down?            is outstanding?
        │              │              │
        └──────────────┼──────────────┘
                       ↓
                BUSINESS DECISIONS
                       │
                       ↓
              INCENTIVE / PROCESS
                 AUTOMATION
```

### Key Insights
--------------------           
