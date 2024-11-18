# Bicycle-Manufacturing-Data-Analysis-with-Python-SQL-Power-BI
This project analyzes the AdventureWorks database to optimize manufacturing and inventory processes of a fictional bicycle company. Using SQL Server, Python, and Power BI, it delivers insights through interactive dashboards with KPIs, cost analysis, and production trends. Visual tools like Pareto charts highlight inefficiencies for data-driven dec.



# Bicycle Manufacturing Data Analysis Using Python, SQL, and Power BI

## Overview

This project presents a comprehensive analysis of the Microsoft AdventureWorks database, a fictional dataset representing a bicycle manufacturing company. The database encompasses data from various organizational aspects such as Human Resources, Product Management, Manufacturing, Inventory, Sales, and Administration. This analysis focuses specifically on the Manufacturing and Inventory processes. An interactive dashboard was created using Power BI, with data sourced from SQL Server to provide valuable insights.

## Data Source

[AdventureWorks Database Installation and Configuration Guide](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)

## Data Model

The dashboard employs a star schema design to enhance data efficiency and refresh speed. Below is an image of the data model used:

<img width="1024" alt="DataModel" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/DataModel.png">

### Key Tables:
- **Production Location**: Details parts and assembly locations.
- **Production Product**: Contains product details, physical attributes, and pricing.
- **Production ProductCategory**: Classifies products into categories.
- **Production ProductSubcategory**: Sub-categorizes products.
- **Production ProductInventory**: Tracks inventory of manufactured products.
- **Production ScrapReason**: Logs manufacturing waste.
- **Production WorkOrder**: Tracks production transactions.
- **Production WorkOrderRouting**: Schedules production activities.
- **Sales SalesOrderDetail**: Stores sales transaction data.

## Tools Used

- [Python](https://www.python.org/)
- [Power BI](https://powerbi.microsoft.com/en-us/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Analysis

### Main Dashboard Page

The dashboard serves as a navigational hub with sections for **Production Overview** and **Inventory Overview**, each offering detailed insights and KPIs.

<img width="1024" alt="Main Page" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/Main%20Page.png">

### Production Overview

The production analysis uses fiscal years starting October 1st and includes custom KPIs, fiscal segregation, and visualizations.

<img width="1024" alt="Production Overview Page" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/Production%20Overview%20Page.png">

#### Key Charts:
1. **Cumulative Production Trends**: Multiline chart comparing fiscal year production trends.
2. **Cost Distribution**: Donut chart showing assembly line costs.
3. **Waste Cost Trends**: Line chart displaying waste costs over the years.

<img width="1024" alt="Production Overview KPI" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/Production%20Overview%20KPI.png">

### Product Category Analysis

This section includes:
- **Pareto Charts**: Identify critical production components and bike categories.
- **Waste Cost Matrix**: Analyze waste causes and financial impacts.
- **On-Time Production Chart**: Displays timely production by category.

<img width="1024" alt="Production Category Analysis" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/Production%20Category%20Analysis.png">

### Inventory Overview

This section examines inventory trends, assuming a single distribution location, and includes:
- **KPIs**: Highlight critical inventory metrics.
- **Area Charts**: Show inventory value and quantity by assembly location.
- **Inventory Turnover Trends**: Compare fiscal year inventory turnover rates.

<img width="1024" alt="Inventory data overview" src="https://raw.githubusercontent.com/ritik8801/Data-Analysis-of-Bicycle-Manufacturing-Company-Using-Python-SQL-and-PowerBI/main/Dashboard%20Screenshots%20and%20Features/Inventory%20data%20overview.png">

This project demonstrates an in-depth analysis of manufacturing and inventory processes, offering actionable insights through a user-friendly and dynamic dashboard.
