# Sales & Customers Dashboard

[![Dashboard Preview](https://github.com/BiancaPopescu2001/Tableau/blob/c99714fd1e4cfe094fd5417e5e274135179837de/dashboard%20preview.png)](https://public.tableau.com/app/profile/bianca.popescu/viz/SalesDashboard_17612430350950/SalesDashboard)


## TABLE OF CONTENT
- [Introduction](#introduction)
- [Sales Dashboard | Requirements](#sales-dashboard--requirements)
  - [Dashboard Purpose](#dashboard-purpose)
  - [Key Requirements](#key-requirements)
    - [KPI Overview](#kpi-overview)
    - [Sales Trends](#sales-trends)
    - [Product Subcategory Comparison](#product-subcategory-comparison)
    - [Weekly Trends for Sales & Profit](#weekly-trends-for-sales--profit)
- [Skills demonstrated](#skills-demonstrated)
- [Data Dictionary](#data-dictionarry)
- [Data Modelling](#dat-amodelling)
- [Analysis](#analysis)
- [Dashboard Link](#dashboard-link)
- [Conclusion](#conclusion)
  


## Introduction
This user story outlines the specifications for building two dashboards using Tableau to help stakeholders, including sales managers and executives to analyze sales performance and customers.

## Sales Dashboard | Requirements

### Dashboard Purpose
The purpose of Sales Dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

### Key Requirements

#### KPI Overview
Display a summary of total sales, profits and quantity for the current year and the previous year

#### Sales Trends
-	Present the data for each KPI on a monthly basis for both the current year and the previous year.
-	Identify months with highest and lowest sales and make them easy to recognize.

#### Product Subcategory Comparison
-	Compare sales performance by different product subcategories for the current year and the previous year.
-	Include a comparison of sales with profit.

#### Weekly Trends for Sales & Profit
-	Present weekly sales and profit data for the current year.
-	Display the average weekly values.
-	Highlight weeks that are above and below the average to draw attention to sales & profit performance.

## Data Dictionary

1. Customers - Each row represents a unique customer on the platform

<table>
  <tr>
    <th>Field Name</th>
    <th>Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>Customer ID</td>
    <td>Customer Name</td>
    <td>Unique ID for each user</td>
    <td>USER-00023</td>
  </tr>
  <tr>
    <td>Name</td>
    <td>STRING</td>
    <td>User’s full name</td>
    <td>Sarah Barr</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>INTEGER</td>
    <td>Age of user</td>
    <td>29</td>
  </tr>
  <tr>
    <td>Region</td>
    <td>STRING</td>
    <td>U.S. region</td>
    <td>Midwest</td>
  </tr>
  <tr>
    <td>State</td>
    <td>STRING</td>
    <td>U.S. state</td>
    <td>Illinois</td>
  </tr>
  <tr>
    <td>City</td>
    <td>STRING</td>
    <td>User’s city and state</td>
    <td>Chicago, Illinois</td>
  </tr>
  <tr>
    <td>Join_Date</td>
    <td>DATE</td>
    <td>Date user joined the platform</td>
    <td>2023-06-01</td>
  </tr>
</table>

## Data Modelling

## Analysis
2023 outperformed 2022 in all key metrics (sales, profit, and quantity).

Profitability is not evenly distributed — some high-revenue subcategories underperform in terms of profit.

The final quarter shows a noticeable upward trend, suggesting effective seasonal strategies or increased demand.


## Dashboard Link

https://public.tableau.com/app/profile/bianca.popescu/viz/SalesDashboard_17612430350950/SalesDashboard

## Conclusion

Future strategies should focus on improving margins in low-profit categories while maintaining sales growth momentum.
