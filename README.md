DAX-Data-Visualization
DAX (Data Analysis Expressions) Interactive  visualizations 

📊 Sales Performance & Regional Analytics Dashboard

🚀 Project Overview

This end-to-end Business Intelligence project provides deep visibility into retail sales execution, product profitability, and geographic distribution trends. By bridging raw transactional data with interactive reporting, the dashboard empowers stakeholders to monitor target achievements and make data-driven decisions. Overall, the company recorded total sales of approximately $2.15 Million, significantly surpassing the baseline target of $435.9K.

🛠️ Data Modeling & ArchitectureThe
project is built on a structured relational data model utilizing a star/snowflake schema.

Core Tables: The model integrates multiple tables, including List of Orders, Order Details, Order Data, and Sales target. 

Relationships: Clean 1-to-many relationships were established to link order-level metadata with granular product line items and target benchmarks.  

🧮 Data Preparation & Calculated Logic

To enhance analytical depth, custom calculated columns and dynamic measures were developed within the model:

Custom Categorization: Created a unified Category Type calculated column by combining category and sub-category attributes for clearer segmentation.   
Revenue Computation: Derived row-level revenue metrics by calculating the product of order amounts and quantities.  
Sales Benchmarking: Segmented transactions into "Above Average" and "Below Average" categories relative to overall performance benchmarks.   
Analytical Measures: Built core measures to track total order counts, city-specific financial metrics (such as average profit in Delhi), and time-intelligence metrics like Year-to-Date (YTD) sales.   

📈 Dashboard Visualizations & Key Insights

1. Sales Performance & Target Achievement

Visuals Used: Clustered column charts and a detailed Sales Performance Matrix.

Insights: Evaluated monthly variances and achievement percentages across product categories (Clothing, Electronics, and Furniture), highlighting consistent over-performance against monthly targets.   

2. Product Profitability Analysis
   Visuals Used: Donut charts, treemaps, and profit-versus-quantity scatter plots.

     Insights: Identified that sub-categories such as Printers, Phones, and Book Cases generate the highest profit margins, making them vital drivers of overall business profitability that require priority in inventory planning.
   
3. Geographic & Regional Sales Patterns

 Visuals Used: Interactive geographic maps and state-level funnel charts.
   
Insights: Pinpointed high-performing commercial hubs like Indore, Mumbai, Delhi, Pune, and Allahabad. State-level order count analysis revealed that Madhya Pradesh and Maharashtra record the highest order volumes
   
4. Temporal Sales Trends & SeasonalityVisuals
 
   visual Used: Line charts tracking monthly revenue.

   Insights: Monitored revenue fluctuations from May 2018 through March 2019 to capture seasonal variations in customer demand, aiding future forecasting and resource allocation.

💡 Business Impact
   The dashboard successfully equips management with a centralized tool to track financial goals, identify profitable product segments, optimize regional marketing strategies, and anticipate seasonal demand shifts.   
