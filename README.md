# Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench
## Overview

In this project, you will step into the shoes of an entry-level data analyst at the fictional Mint Classics Company, helping to analyze data in a relational database with the goal of supporting inventory-related business decisions that lead to the closure of a storage facility.

## Project Scenario

Mint Classics Company, a retailer of classic model cars and other vehicles, is looking at closing one of their storage facilities. 

To support a data-based business decision, they are looking for suggestions and recommendations for reorganizing or reducing inventory, while still maintaining timely service to their customers. For example, they would like to be able to ship a product to a customer within 24 hours of the order being placed.

As a data analyst, you have been asked to use MySQL Workbench to familiarize yourself with the general business by examining the current data. You will be provided with a data model and sample data tables to review. You will then need to isolate and identify those parts of the data that could be useful in deciding how to reduce inventory. You will write queries to answer questions like these:

1) Where are items stored and if they were rearranged, could a warehouse be eliminated?

2) How are inventory numbers related to sales figures? Do the inventory counts seem appropriate for each item?

3) Are we storing items that are not moving? Are any items candidates for being dropped from the product line?

The answers to questions like those should help you to formulate suggestions and recommendations for reducing inventory with the goal of closing one of the storage facilities. 

## Project Objectives

1. Explore products currently in inventory.

2. Determine important factors that may influence inventory reorganization/reduction.

3. Provide analytic insights and data-driven recommendations.

## Your Challenge

Your challenge will be to conduct an exploratory data analysis to investigate if there are any patterns or themes that may influence the reduction or reorganization of inventory in the Mint Classics storage facilities. To do this, you will import the database and then analyze data. You will also pose questions, and seek to answer them meaningfully using SQL queries to retrieve data from the database provided.

In this project, we'll use the fictional Mint Classics relational database and a relational data model. Both will be provided.

After you perform your analysis, you will share your findings.

## Project Tasks
### 1. Database Setup:
- The mintclassicsDB.sql script is used to create a comprehensive nine-table relational database in MySQL Workbench.

### 2. Exploratory Data Analysis (EDA):
- Key questions related to inventory, storage, and sales are addressed using SQL queries.
- Warehouse distribution, inventory-sales correlation, and identification of stagnant items are explored.

### 3. Data-Driven Recommendations:
- Recommendations are formulated based on the analysis to optimize inventory and potentially close a storage facility.
- Findings are presented in a clear and actionable manner, addressing areas for improvement in inventory management.

## Key Findings
### 1. Warehouse Distribution:
- Items are distributed across North, East, West, and South warehouses, suggesting potential for rearrangement to optimize storage.

### 2. Inventory-Sales Correlation:
- The analysis reveals the correlation between inventory numbers and sales figures, identifying items with low sales and high inventory for further scrutiny.

### 3.Stagnant Items:
-The project identifies a stagnant item, the "1985 Toyota Supra," with no recorded sales, suggesting a potential candidate for removal from the product line.

## Recommendations
### 1. Optimizing Storage Facility:
- Consider rearranging items within warehouses to maximize space utilization.
- Evaluate the possibility of eliminating or downsizing a storage facility.

### 2. Inventory Management:
- Review products with low sales and high inventory for potential reduction in orders.
- Consider discontinuing items with poor performance to streamline the product line.

### 3. Product Line Optimization:
- Assess stagnant items for potential removal or revitalization in the product line.
- Focus on high-performing products to enhance overall sales.

## Conclusion
The Mint Classics Inventory Optimization Project successfully utilizes SQL queries to explore and analyze the provided database, offering actionable insights for improving inventory management. The findings and recommendations provide a valuable foundation for strategic decision-making in the context of warehouse distribution, sales correlation, and product line optimization. The project's documentation is clear, well-structured, and serves as a valuable resource for addressing inventory-related challenges in the classic model car retail industry.
