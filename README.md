# E-Commerce_Customer_Churn_Analysis_SQL

## PROJECT OVERVIEW

This project analyzes customer churn in an e-commerce dataset using SQL. It focuses on understanding why customers leave by studying factors like complaints, tenure, and payment methods. Data cleaning and transformation were done to prepare the dataset for analysis. Basic analysis was performed to find patterns and trends in customer behavior. The insights help businesses improve customer retention and reduce churn.

## TOOLS USED

 * MySQL (for data cleaning, transformation, and analysis)
 * SQL Workbench (query execution )

## DATASET

Source: https://drive.google.com/uc?export=download&id=1iKKCze_Fpk2n_g3BIZBiSjcDFdFcEn3D

## Key Columns: 

CustomerID, Tenure, PreferredPaymentMode, PreferredOrderCat, CityTier, WarehouseToHome, HoursSpentOnApp, OrderCount, CouponUsed, SatisfactionScore, CashbackAmount, Churn, Complain

## STEPS FOLLOWED

### 1.  Data Collection

 * Obtained the e-commerce customer churn dataset

 * Dataset includes customer behavior, transactions, and churn details

### 2.  Data Cleaning

 * Handled missing values using mean (numerical) and mode (categorical)

 * Removed outliers in WarehouseToHome column

 * Standardized categorical values for consistency

### 3.  Data Transformation

 * Renamed incorrect column names

 * Created new fields like ComplaintReceived and ChurnStatus

 * Removed unnecessary columns

### 4. Data Exploration & Analysis

 * Analyzed the count of churned vs active customers.

 * Calculated average tenure and cashback for churned customers.

 * Examined churn based on complaints, city tier, and preferred order category.

 * Identified the most preferred payment method among active customers.

 * Segmented customers based on marital status, warehouse distance, and satisfaction score.

 * Identified top 3 order categories based on average cashback.

 * Categorized customers by warehouse distance (Very Close, Close, Moderate, Far).

## KEY INSIGHTS

 * Customers with complaints have a significantly higher churn rate.

 * City Tier-1 records the highest churn, especially in the Laptop & Accessories category.

 * Credit Card is the most preferred payment method among active customers.

 * Single customers who prefer mobile phones tend to show higher order value.

 * Electronics, Fashion, and Groceries are the top categories offering cashback.

 * Warehouse distance strongly impacts churn, with customers located farther away more likely to leave.

## FILES INCLUDED

 * E-Commerce Customer Churn db.sql – Contains table creation scripts and sample data insertion.

 * E-Commerce_Customer_Churn_Analysis.sql – Includes cleaned and transformed dataset queries.

 * README.md – Project documentation and description.
