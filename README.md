# Powering AdventureWorks: Intelligent Analytics in Action

<p align="center">
  <img src="https://github.com/user-attachments/assets/29bd54ad-4459-4ed3-83c7-6286451cec6b" width="200" />
</p>



Adventure Works Bike Shop Power BI Project Overview
This Power BI project provides a detailed analysis and visualization of the Adventure Works Bike Shop dataset, demonstrating key business insights and performance metrics. Developed as part of the "Power BI Desktop 2023" course by Maven Analytics, this project highlights a variety of advanced data analytics and visualization techniques.

Key features of the project include:

Interactive Dashboards: Custom-built dashboards that showcase important KPIs and metrics related to the bike shop's operations.
Data Modeling: Robust data models that integrate multiple data sources to offer a comprehensive view of the business.
In-Depth Reports: Analytical reports focusing on key areas such as sales performance, customer demographics, inventory management, and more.
Advanced Visualizations: A diverse set of visual elements, including bar charts, line graphs, pie charts, and geographic maps, designed to present data in an easily understandable format.
This project serves as a practical demonstration of Power BI capabilities and offers a detailed analysis of the business operations of a retail bike shop

<img alt="AdventureWorks Executive Dashboard" src="images/screenshots/exec_dashboard.gif">

## Features

- Track key performance indicators (KPIs) related to sales, revenue, profit, and returns.
- Compare performance across different regions.
- Analyse product-level trends.
- Identify high-value customers.

## Project Highlights

This project involved the following tasks:

- connecting and transforming the raw data 
- building a relational data model
- creating calculated columns and measures using **DAX**
- Created a rolling calendar using **PowerQuery M code**
- building an interactive dashboard

## Dashboard Elements

#### Executive Summary View

- high-level KPIs for revenue, profit, orders and return rates
- page-level filtering by product and product category
- drill-through per product to product detail view

#### Map View

- total orders per country

#### Product Detail View

- per-product performance against order, revenue and profit targets
- "what if" analysis via price adjustment shows adjusted profit

#### Customer Detail View

- total customer and per-customer revenue analysis

#### Custom UI Elements

- filter pane for filtering by year and geography
- custom tooltip for product category order metrics

### Insights

- Approximately $24.9 million in revenue and $10.5 million in profit was generated between 01/01/2020 and 30/06/2022. There is an appreciable dip in revenue between 01/06/2020 and 01/11/2020 (possibly due to the simulated impact of the COVID-19 pandemic), after which revenue appears to grow linearly. December 2021 was an exceptional year in terms of revenue at $1.64 million, and it would be worth investigated the cause of this. Was this due to a highly successful seasonal campaign, e.g. a Black Friday promotion?

- Understandably, tires and tubes are the most ordered product type, while cycling shorts are the most returned product type. After mountain bike fenders, sports helmets top the list of revenue-generating products, despite having relatively high return rates:

<img src="./images/screenshots/top_revenue_products.png">

- The most profitable product categories are clothing and accessories.

- There is a step change (on the order of 200 customers per week) in total weekly customers beginning 02/08/2021.

<img src="./images/screenshots/total_weekly_customers.png">

- However, revenue per customer has been declining year-on-year:

<img src="./images/screenshots/revenue_per_customer.png">

- While the United States is the largest market with 8,700 orders and $7.94 million in total revenue, The Australian market has the largest revenue per customer at $2,131.
- 

How to Download and View the Power BI Project Locally
To explore the Adventure Works Power BI project on your local machine, follow these steps:

Step 1: Download the Project File

Navigate to the GitHub repository where the project is hosted.
Look for the file with the .pbix extension in the files section.
Click on the file and then on the Download button to save it to your computer.
Step 2: Open the Project in Power BI Desktop

Launch Power BI Desktop on your computer.
Select 'Open' and navigate to the .pbix file you downloaded.
Open the file to load the project.
You can now explore and interact with the Adventure Works Power BI project on your device.
