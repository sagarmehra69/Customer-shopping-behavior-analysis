
# 🛒 Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing 3,900 customer transactions to uncover spending patterns, customer segments, product preferences, and subscription behavior using Python, SQL, and Power BI.
This project transforms raw transactional data into actionable business insights through data cleaning, structured querying, and interactive dashboards.

## 📌 Project Objective

The primary goal of this project is to:
Analyze customer purchasing patterns
Identify high-value customer segments
Understand subscription impact on revenue
Evaluate discount strategies
Provide business-driven recommendations


<img width="1254" height="681" alt="Screenshot 2026-02-19 145354" src="https://github.com/user-attachments/assets/12440f2a-f2a7-49f9-a5ca-198b4a3869cf" />


## 📊 Dataset Summary

-- Total Records: 3,900
-- Total Columns: 18
-- Missing Values: 37 (Review Rating column)

## Key Features Included:
### 🔹 Customer Demographics

-- Age
-- Gender
-- Location

## Subscription Status

### 🔹 Purchase Information

-- Item Purchased
-- Category
-- Purchase Amount
-- Season
-- Size
-- Color

## 🔹 Shipping & Behavior

-- Discount Applied
-- Promo Code Used
-- Previous Purchases
-- Frequency of Purchases
-- Review Rating
-- Shipping Type

## 🐍 Phase 1: Data Analysis Using Python
### 🔹 Data Loading

-- Imported dataset using pandas
-- Checked structure using df.info()
-- Summary statistics using df.describe()

### 🔹 Data Cleaning

-- Identified missing values
-- Imputed missing Review Rating using median rating per category
-- Standardized column names to snake_case

### 🔹 Feature Engineering

-- Created age_group column by binning age
-- Generated purchase_frequency_days
-- Checked redundancy between discount_applied and promo_code_used
-- Dropped redundant columns

### 🔹 Database Integration

-- Connected Python to PostgreSQL using SQLAlchemy
-- Loaded cleaned dataset into database for SQL-based analysis

## 🗄 Phase 2: Business Analysis Using PostgreSQL

Performed structured queries to extract business insights.
Key Business Questions Solved:
Revenue comparison by gender
High-spending customers who used discounts
Top 5 highest-rated products
Standard vs Express shipping revenue comparison
Subscribers vs Non-subscribers spending behavior
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top 3 products per category
Repeat buyers and subscription correlation
Revenue contribution by age group

## 📊 Phase 3: Interactive Dashboard in Power BI

### Built a fully interactive dashboard to visualize:

Revenue trends

Customer segmentation

Age-group contribution

Shipping behavior

Product performance

Subscription impact

The dashboard enables business stakeholders to make data-driven decisions quickly.

## 🧠 Business Insights & Recommendations

✔ Promote subscription benefits to increase recurring revenue
✔ Launch loyalty programs for repeat buyers
✔ Re-evaluate discount dependency to protect margins
✔ Highlight top-rated products in marketing campaigns
✔ Target high-revenue age groups with focused advertising

## 🛠 Tech Stack

Python (Pandas, NumPy, SQLAlchemy)
PostgreSQL
Power BI
Jupyter Notebook


## 🚀 Skills Demonstrated

-- Data Cleaning & Preprocessing
-- Exploratory Data Analysis (EDA)
-- SQL Aggregations & Window Functions
-- Customer Segmentation
-- Business Intelligence Dashboarding
-- End-to-End Data Pipeline

## 📌 Key Takeaways

This project demonstrates how raw transactional data can be transformed into structured insights using a modern data stack.

It reflects practical business analysis skills rather than just theoretical querying.
