# powerbi-adventureworks-sales-analysis
Sales analytics dashboard built in Microsoft Power BI Desktop using the AdventureWorks dataset. The project explores product performance, regional sales trends, and customer purchasing patterns.
# Project Overview

This project explores sales performance using the AdventureWorks dataset. The goal was to build an interactive sales dashboard in Microsoft Power BI Desktop that helps understand how products are performing, how sales vary across regions, and how customer orders contribute to overall revenue.

Before building the dashboard, the dataset was reviewed in Excel to understand the structure of the data, check column types, and identify the tables that were relevant for sales analysis. Only the tables related to sales transactions, customers, territories, and products were selected to keep the data model focused and easy to manage.

The data model follows a star schema where the sales transaction table sits at the center and the product, customer, and territory tables provide descriptive information. This structure makes the model easier to work with and improves performance when building reports in Power BI.

The final report will include interactive visuals, key performance indicators, and tooltip based insights to allow users to explore sales trends and product performance more easily.
# Project Workflow

This project was completed in several stages, starting from exploring the dataset to building the final dashboard.

## 1. Dataset Review

The AdventureWorks dataset was downloaded from GitHub.
The dataset contains many tables related to different business activities such as sales, production, purchasing, and vendors.

Since the goal of this project is sales analysis, only the tables related to sales transactions and descriptive sales information were selected.

The CSV files were first opened in Microsoft Excel to understand the structure of the data. During this step the following checks were performed:

reviewing column names

checking numeric and date columns

identifying key columns used to link tables

scanning for missing or unusual values

This step helped confirm that the dataset was suitable for analysis.

## 2. Selecting Relevant Tables

After exploring the dataset, the following tables were selected for the analysis:

Sales SalesOrderDetail

Sales SalesOrderHeader

Sales Customer

Sales SalesTerritory

Production Product

These tables provide the information needed to analyze:

sales transactions

customer orders

product information

regional sales performance

Tables related to manufacturing or purchasing processes were not included in the analysis.

## 3. Data Modeling

The selected tables were loaded into Microsoft Power BI Desktop.

A star schema structure was used for the data model. In this structure:

the sales transaction table acts as the fact table

the other tables provide descriptive information as dimension tables

This structure keeps the model simple and helps Power BI perform queries efficiently.

## 4. Dashboard Development

After creating the data model, the dashboard was built using Power BI visuals and measures. The report focuses on answering key business questions such as:

total sales performance

product level sales comparison

regional sales distribution

sales trends over time

Interactive visuals allow users to explore the data by filtering and hovering over charts.

## 5. Tooltip KPI Page

A separate tooltip page was created to display additional metrics when users hover over visuals.

This page includes small KPI visuals such as:

total sales

number of orders

average order value

sales trend

Tooltips allow additional insights to be shown without cluttering the main dashboard.
