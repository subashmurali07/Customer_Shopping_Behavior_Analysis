# Customer_Shopping_Behavior_Analysis
Data analytics project using Python,Sql and PowerBi

🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using a dataset of 3,900 transactions. The goal is to identify spending patterns, customer segments, product performance, and subscription insights using Python, SQL, and Power BI.

📂 Dataset Summary

Rows: 3,900

Columns: 18

Includes:

Demographics (Age, Gender, Location)

Purchase details (Item Purchased, Category, Amount, Season, Size, Color)

Behavior metrics (Discount Applied, Previous Purchases, Review Rating, Shipping Type)

Subscription status

Missing Values: 37 values in Review Rating

🧹 Data Cleaning & EDA (Python)

Key steps performed:

Loaded and explored the dataset (info, describe)

Renamed columns to snake_case

Filled missing review_rating using median by category

Created new features:

age_group

purchase_frequency_days

Removed redundant column: promo_code_used

Exported cleaned dataset to SQL analysis

🧮 SQL Business Analysis 

SQL queries were used to extract insights such as:

Revenue by gender

Customers using discounts but spending above-average

Top 5 products by average rating

Spending comparison: Standard vs Express shipping

Subscribers vs Non-subscribers—average spend & revenue

Products most dependent on discount-based sales

Customer segmentation: New, Returning, Loyal

Top 3 products in each category

Repeat buyers and their subscription tendencies

Revenue by age group

📊 Power BI Dashboard

Created an interactive Power BI dashboard visualizing:

Sales and revenue trends

Customer segments

Product performance

Discount usage patterns

Subscription impact

Age-group & shipping analysis

🎯 Key Business Insights

Encourage subscriptions by offering exclusive perks

Strengthen loyalty program for returning customers

Optimize discount strategy to protect margins

Promote top-rated and top-selling products

Target high-revenue age groups and express-shipping users

🛠️ Tech Stack

Python

SQL

Power BI

Jupyter Notebook
