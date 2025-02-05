# OLA-Performance-Analysis

## Overview

This repository contains the analysis of OLA's performance for the period 01-07-2024 to 30-07-2024. The project involves data cleaning using Excel, analysis with SQL, and visualization using Power BI.

## Data Used

The dataset used for this analysis contains OLA booking records, including details such as:
Booking ID, Customer ID, Vehicle Type, Payment Method, Booking Value
Booking Status (Success, Cancelled by Customer, Cancelled by Driver)
Ride Distance, Customer Ratings, Driver Ratings

## Key Trends and Insights

### Overall Performance

- Total Bookings: 20,407

- Total Booking Value: ₹7M

- Success Rate: 62%

- Cancellation Rate: 17.91%

### Revenue Insights

- Revenue by Payment Method:

- Cash: ₹4M

- UPI, Credit Card, Debit Card: Slightly below ₹1M each.

- Top 5 Customers by Total Booking Value:

- CID836942: ₹3.8K

- CID749265: ₹3.4K

### Cancellation Insights

- Canceled Rides By Customers:

- "Change of plans": 29.31%

- "Driver asked to cancel": 15.38%

- Canceled Rides By Drivers:

- "Personal & Car related issues": 34.56%

- "Customer-related issues": 29.12%

## SQL Queries Used

[List of all SQL queries used in the project]

## Power BI Dashboard 

The following visualizations are used in the Power BI dashboard:

- Booking Status Breakdown - A pie chart or bar chart depicting the success and cancellation rates.

- Ride Volume Over Time - A line chart showing booking counts over time.

- Revenue by Payment Method - A bar chart illustrating the distribution of revenue across different payment methods.

- Ride Distance Distribution Per Day - A line chart detailing the sum of ride distances per day.

- Top 5 Customers by Total Booking Value - A bar chart listing the top customers with the highest booking values.

- Canceled Rides Insights - Separate bar charts for cancellations by customers and drivers, highlighting the main reasons.

## Links and References

- Dataset

- Power BI Dashboard

- Project Repository

## Suggestions for Improvements

- Reduce Cancellations - Identify high-risk customers/drivers and implement policies to lower cancellations.

- Enhance Revenue Tracking - Optimize fare pricing and encourage digital payments.

- Improve Ride Experience - Collect feedback from customers and drivers to improve services.

- Dashboard Optimization - Enhance Power BI reports for real-time analytics.

## Repository Structure

|-- data/
|   |-- ola_bookings.csv  # Cleaned dataset used for analysis
|
|-- sql_queries/
|   |-- ola_analysis_queries.sql  # All SQL queries used
|
|-- dashboards/
|   |-- ola_performance.pbix  # Power BI dashboard file
|
|-- README.md  # Project Documentation

