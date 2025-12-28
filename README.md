SQL Sales & Inventory Analysis Project
This project contains a series of SQL queries, views, and stored procedures designed to extract key business insights from a relational database. It covers customer behavior, inventory management, logistics, and sales performance.

Project Overview
The following tasks demonstrate advanced SQL techniques including Window Functions, Subqueries, Joins, and Database Programmability.

Customer Insights: Identifies top spenders and ranks individual order values to target high-value clients.

Inventory & Suppliers: Audits supplier portfolios, tracks product counts, and calculates total revenue per vendor through stored procedures.

Order Fulfillment: Provides a comprehensive look at the supply chain, linking customers to products, categories, and warehouses.

Sales Trends: Analyzes chronological sales flow using analytical functions to compare historical and future order quantities.

Data Integrity: Isolates successful sales by identifying products that have been ordered but never flagged for returns.

Technical Features
Window Functions: Utilizes RANK() for competitive ordering and LAG/LEAD for time-series analysis.

Aggregations: Employs GROUP BY and HAVING clauses to filter complex datasets.

Modularity: Includes a reusable View for customer summaries and a Stored Procedure for dynamic supplier reporting.

Relational Logic: Connects multiple data points including Customers, Orders, Products, Shipments, and Warehouses.
