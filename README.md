# powerbi-sales-analytics
Power BI  project for data analysts

# 📌 Project Overview

This repository contains a Power BI demo project created to help aspiring data analysts understand how real-world analytics dashboards are designed, modeled, and built.

The project demonstrates the end-to-end Power BI workflow, from data modeling and DAX calculations to interactive dashboard creation using industry best practices.
# 🎯 Purpose of This Project

Provide a hands-on learning reference for Power BI beginners

Demonstrate core data modeling concepts using a star schema

Practice writing essential DAX measures

Showcase how to turn raw sales data into business insights

This project is ideal for:

Aspiring data analysts

Students and career switchers

Anyone learning Power BI and DAX

# 🧱 Data Model (Star Schema – Simplified)

To keep the project easy to understand, a simplified star schema is used.

Tables Used
Sales_Data (Fact Table)

Contains transaction-level sales information, including:

Revenue

Profit

Order Quantity

Product details

Customer attributes

Geographic information

Transaction Date

This table serves as the central fact table.

# Date Table (Dimension)

A dedicated Date table was created to support time-based analysis, such as:

Revenue trends

Revenue YoY % comparisions

Profit Margin(%) comparisons

The Date table is marked as a Date Table in Power BI.

# 🧮 Key DAX Measures

Some of the key measures created in this project include:

Total Revenue

Total Profit

Profit Margin %

Total Customers

Average Revenue per Customer

Profit Margin % 

Revenue YoY %

All calculations are implemented as DAX measures to ensure correct aggregation and filter behavior.

# 📈 Dashboards Included
🔹 Executive Overview

Revenue, Profit, Margin KPIs

Revenue trend over time

Revenue by country

🔹 Product Performance

Top products by revenue

Revenue vs Profit scatter plot

Product hierarchy analysis

🔹 Customer Analysis

Revenue by age group

Revenue by gender

Average revenue per customer

🔹 Geographic Analysis

Revenue and profit by country

Profit by state

Regional performance comparison

# 🛠 Tools & Skills Used

Power BI Desktop

DAX (Time Intelligence, KPIs)

Data Modeling (Star Schema)

Data Visualization

Business Analytics & Storytelling
