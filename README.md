## B2B Distribution Analytics & Decision Support System
# 1.1 Overview
Inspired by operational and inventory analytics work during a data analyst internship, where I worked with operational/Tally data, inventory records, reporting, and business processes. I have built this synthetic B2B distribution analytics system to understand how transactional data can support management decisions.

The project models sales, inventory, customer collections, and employee incentives across a 24-month period. I have used Python, SQL, and Power BI to identify revenue drivers, inventory risk, receivables exposure, and operational priorities. 
The incentive component is also modeled in the project, as I worked with the founder on the TDL incentive system to encourage and motivate reps.

# 1.2 Object of the project
The primary objective of this project is to bridge the gap between theoretical concepts and their practical implementation in industry by building an end-to-end **business analytics and decision support system** that converts operational data into actionable management insights.

# 1.3 Understanding the problem
Even if a distributor may have hundreds of transactions and thousands of items, this information does not always indicate how the data aids in the organization's decision-making:
- Which products are actually driving revenue?
- Which inventory is sitting unused?
- Which products need to be reordered?
- Which customers are paying late?
- How much money is currently tied up in receivables?
- How much inventory captital is sitting idle?
- How much incentive should employees recieve?
- Which operational areas require attention?

# 1.4 Methodology
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

                 
