# Zomato-Restaurant-Analytics-Dashboard-Power-BI
Zomato Restaurant Analytics Dashboard | Power BI  Developed an interactive Power BI dashboard to analyze restaurant performance, ratings, pricing, and customer preferences using Zomato data. Implemented data cleaning, data modeling, DAX measures, and interactive visualizations to uncover business insights and support data-driven decision-making.
1. Project Overview

The Zomato Restaurant Analytics Dashboard was developed using Power BI to analyze restaurant sales, orders, ratings, customer behavior, and city-level performance across India. The dashboard provides interactive visualizations and business insights that help understand customer preferences, operational performance, and market trends.

The project transforms raw restaurant and customer data into actionable insights through data modeling, DAX calculations, and interactive visualizations.

2. Business Objective

The primary objective of this project is to:

Analyze restaurant sales and order trends.
Monitor customer ratings and engagement.
Evaluate city-wise business performance.
Identify high-performing locations.
Understand customer demographics and user growth.
Support data-driven business decisions.
3. Tools & Technologies Used
Tool	Purpose
Power BI	Dashboard Development
Power Query	Data Cleaning & Transformation
DAX	KPI Calculations & Dynamic Measures
Excel/CSV Dataset	Data Source
Data Modeling	Relationship Management
4. Key Performance Indicators (KPIs)
Business Performance Dashboard

The dashboard highlights the following KPIs:

KPI	Value
Total Revenue	₹987 Million
Total Quantity Sold	2 Million
Total Ratings	148K
Total Orders	150K
Cities Covered	822
Connected Users	77,929

These KPIs provide a quick overview of overall business performance.

5. Dashboard Pages
Page 1: Executive Overview

This page provides a summary of overall business performance.

Features:

Revenue Overview
Quantity Analysis
Rating Analysis
Order Analysis
Food Category Distribution
City-wise Quantity Performance
Year-wise Quantity Trend

Key Findings:

Total revenue generated reached ₹987M.
Veg category received the highest ratings.
Electronic City (Bangalore) contributed the highest quantity of orders.
Quantity peaked in 2018 and gradually declined afterward.
Page 2: User Analytics Dashboard

This dashboard focuses on customer acquisition and retention.

KPIs:

Metric	Value
Active Users	78K
Total Users	100K
Ratings	148K
Orders	301K

User Insights:

Male users showed higher acquisition rates compared to female users.
User loss among male customers was also higher.
Most customers belong to the age group of 22–26 years.
Peak user concentration occurs around age 24.
Page 3: City Performance Dashboard

This dashboard evaluates city-wise performance metrics.

Metrics Included:

Sales by City
Ratings by City
Users by City
Orders by City
Gained Users
Lost Users

Top Performing Cities by Sales:

Tirupati – ₹43M
Electronic City, Bangalore – ₹29M
Baner, Pune – ₹27M
Raipur – ₹23M
Others – ₹22M

Top Cities by Ratings:

Bikaner
Noida Sector-1
Indirapuram
BTM Bangalore
Rohini Delhi

Top Cities by Users:

Bikaner
Noida Sector-1
Indirapuram
BTM Bangalore
Rohini Delhi

These cities demonstrate strong customer engagement and business potential.

6. Data Modeling & Transformation

The following activities were performed:

Data Cleaning
Removed null values.
Handled missing records.
Corrected data types.
Standardized city names.
Data Transformation
Created calculated columns.
Built custom measures using DAX.
Aggregated sales and order data.
Generated dynamic KPIs.
Data Modeling
Established relationships between tables.
Implemented star-schema design principles.
Optimized model performance.
7. DAX Measures Used

Examples of measures used:

Total Sales = SUM(Orders[Sales])

Total Orders = COUNT(Orders[Order_ID])

Average Rating = AVERAGE(Ratings[Rating])

Total Users = SUM(Users[User_Count])

Active Users = SUM(Users[Active_User])
8. Key Business Insights
Revenue Insights
Total business revenue exceeded ₹987M.
A small number of cities contribute significantly to overall revenue.
Customer Insights
Users aged 22–26 represent the largest customer segment.
Male users dominate both acquisition and churn metrics.
Operational Insights
Electronic City, Bangalore is a major business hub.
Tirupati generates the highest city-level sales.
Product Insights
Veg restaurants received the highest rating volume.
Non-veg restaurants generated substantial order quantities.
9. Dashboard Features
Dynamic Buttons (Amount & Quantity Toggle)
City Filters
Top N Analysis (Top 5, 10, 20, 50, 100)
Interactive Drill-downs
KPI Cards
Dynamic Charts
Responsive Layout
10. Project Outcome

The dashboard successfully converts raw Zomato data into meaningful business insights. It enables stakeholders to monitor revenue, customer behavior, city performance, and operational trends through an interactive Power BI solution.

Result

The project demonstrates practical skills in:

Data Cleaning
Data Modeling
DAX
Business Intelligence
Data Visualization
Dashboard Design
Analytical Thinking
