**Customer Segmentation Analysis using Power BI & Python**
**Project Introduction**
Customer Segmentation is one of the most important business analytics techniques used to divide customers into groups based on similar characteristics such as income, spending behavior, demographics, and purchasing patterns.
This project demonstrates how businesses can use Data Analytics, Machine Learning, and Visualization Tools to better understand customer behavior and improve decision-making.
**Problem Statement**
Businesses often struggle to:
Identify valuable customers
Understand customer purchasing behavior
Target the right audience
Improve customer retention
This project solves these problems by analyzing customer data and creating meaningful customer segments.
**Project Goals**
Perform customer behavior analysis
Group customers into different segments
Create visual dashboards in Power BI
Generate business insights
Learn real-world data analytics workflow
**Tools & Technologies**
Tool
Purpose
Power BI
Dashboard & Data Visualization
Python
Data Processing & Clustering
SQL
Data Querying
Pandas
Data Analysis
Scikit-learn
Machine Learning
Matplotlib
Data Visualization
Machine Learning Technique Used
K-Means Clustering
K-Means clustering is an unsupervised machine learning algorithm used to group similar customers together.
Features Used:
Annual Income
Spending Score
Purchase Frequency
**Benefits:**
Easy customer grouping
Identifies hidden patterns
Useful for marketing strategies
Dataset Information
The dataset contains customer details including:
Feature
Description
CustomerID
Unique ID
Age
Customer Age
Gender
Male/Female
AnnualIncome
Income per year
SpendingScore
Customer spending rating
PurchaseFrequency
Shopping frequency
Region
Customer location
Segment
Customer category
**Workflow**
Step 1: Data Collection
Customer data is collected from retail/business systems.
Step 2: Data Cleaning
Remove missing values
Handle duplicates
Format columns properly
Step 3: Data Analysis
**Analyze:**
Customer income
Spending behavior
Regional performance
Step 4: Customer Clustering
Apply K-Means clustering algorithm using Python.
Step 5: Dashboard Creation
Import cleaned data into Power BI and build visual reports.
Power BI Dashboard Features
KPI Cards
Total Customers
Average Income
Average Spending Score
Total Purchases
Charts Used
Bar Chart
Pie Chart
Scatter Plot
Donut Chart
Slicers & Filters
Insights Generated
High-income customers spend more
Some low-income customers are frequent buyers
Regional purchasing patterns differ
Python Implementation
Required Libraries
Python
import pandas as pd
import numpy as np
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
Running the Project
Bash
python customer_segmentation.py
SQL Analysis Queries
Average Income by Segment
SQL
SELECT Segment, AVG(AnnualIncome)
FROM Customers
GROUP BY Segment;
Total Customers by Region
SQL
SELECT Region, COUNT(*)
FROM Customers
GROUP BY Region;
Business Benefits
Better customer targeting
Personalized marketing
Increased sales
Improved customer retention
Better decision-making
Learning Outcomes
By completing this project, you will learn:
Data preprocessing
Customer analytics
Machine learning basics
Power BI dashboard development
Business intelligence concepts
Future Improvements
Add AI-based predictions
Connect live databases
Deploy dashboard online
Use Deep Learning models
Real-time customer analytics
Conclusion
This project provides a complete end-to-end customer segmentation solution using Python and Power BI. It helps businesses understand customer behavior and supports data-driven decision-making through analytics and visualization.
**author:**
Kotni Bhavani
github:https://github.com/kotni-bhavani
linked in: https://www.linkedin.com/in/bhavani-kotni
Developed for Data Analytics, Machine Learning, and Power BI portfolio projects.
