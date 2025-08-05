# credit-card-analysis-dashboard

This project is a deep dive into the world of credit card users, where I built an interactive dashboard using Power BI, Power Query, and DAX. I started with a raw SQL database containing multiple relational tables customer data, transaction details, credit usage patterns, and more. I connected this SQL data source directly to Power BI, ensuring real-time query handling and better performance when filtering and analyzing.

The idea behind the project was simple: If I were a data analyst at a financial institution, how could I help the company understand its credit card customers better? With that in mind, I focused on identifying key user behaviors like spending patterns, cash advances, credit utilization ratios, and average monthly transactions. The dashboard was designed to be dynamic, easy to interpret, and focused on actionable business insights.
I handled the data transformation in Power Query and created several DAX measures to calculate KPIs like Monthly Spend, Usage Ratio, and Customer Segmentation. This helped break down insights by demographic filters like age group, gender, and card type. The goal was to not just visualize data, but to tell a story through it a story that could help business leaders make smarter decisions.

Although I initially explored this concept by watching a few online tutorials, I made sure to build this version entirely on my own writing SQL queries, cleaning datasets, creating relationships, and designing visuals from scratch. This dashboard reflects both my technical skillset and my ability to think from a business point of view.

If you're someone who enjoys turning raw data into meaningful decisions, I hope you find this project as exciting as I did!

## Intro

An end-to-end Business Intelligence project using *SQL, Power BI, Power Query, and DAX* to analyze credit card user behavior, identify customer segments, and derive business insights.

##  Business Use Case

Understanding how customers use credit cards helps financial institutions make data-driven decisions around credit limits, rewards, fraud detection, and customer engagement. This dashboard enables quick visibility into key metrics like usage ratio, monthly spending, and customer segmentation.

##  Problem Statement

Banks collect large amounts of transactional data, but without a structured dashboard, it becomes difficult to interpret and act on. This project solves that gap by offering a clean, dynamic, and insightful dashboard using real credit card user data.

##  Objectives

- Analyze credit card usage trends across demographics  
- Identify high and low value customers  
- Visualize key financial KPIs for better decision making  
- Enable interactive filtering and drill down for business users

## Tools & Technologies Used

- *SQL Server* - Data extraction and transformation  
- *Power BI* - Dashboard creation and storytelling  
- *Power Query* - Data cleaning and shaping  
- *DAX* - Measures and calculated fields for KPIs

## Key Features

- Customer segmentation based on credit card behavior  
- KPIs like Monthly Spend, Cash Advance Ratio, Credit Utilization  
- Age, Gender, and Card Type filters for targeted analysis  
- Clean, mobile-friendly dashboard layout

## Dataset Overview

The dataset is sourced from a relational SQL database and includes:

- customer.csv - Customer demographics 
- credit_card.csv - Usage data like balance, purchases, payments 
- cust_add.csv - Customer address and region data 
- cc_add.csv - Additional attributes and flags 

