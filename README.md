# 📊 Power BI Retail & Sales Analysis Project

*Data Technician Bootcamp – Week 2 Project*

## 📌 Project Overview

* This project was completed as part of a Data Technician bootcamp, focusing on developing practical skills in Microsoft Power BI for data transformation, modelling, calculation and visual storytelling.

* Using the AdventureWorks reseller sales data, the project demonstrates proficiency with Power Query, DAX measures, interactive reports with slicers, and visuals that compare sales against targets.

## 🔗 Live Report

👉 [**View the interactive report on Power BI Service**](https://app.powerbi.com/view?r=eyJrIjoiMDAyYTkzZDEtZmM3Ny00OTY5LWFkYzYtMmY3YWQyYTMxNzk5IiwidCI6IjNlYTdjMTI4LWM2MDEtNDQ3OS1hMDAzLWUxNGQwMGMwYjVjYiJ9)

The report is published to the Power BI service (app.powerbi.com) and can be explored with the Year slicer.

## 🧰 Skills & Techniques Used

### 🔍 Data Transformation & Cleaning (Power Query)

Prepared the source data before loading it into the model:

* Connected to a SQL Server database (AdventureWorksDW2020) and to a CSV file of sales targets
* Loaded and profiled 8 queries (employee, product, reseller, territory, sales and targets tables) using column quality and distribution checks
* Cleaned the Salesperson table using applied steps: Filtered Rows, Removed Other Columns, Merged Columns and Renamed Columns
* Set correct data types (for example Year and EmployeeID as whole numbers)
* Loaded the cleaned tables into the data model with Close & Apply

### 🧮 DAX Calculations

Created calculations in the semantic model to turn raw sales into business measures:

* **Profit** – sales profit by category and by order date
* **Profit Margin** – profit as a percentage of sales
* **Target** – sales targets per salesperson
* **Variance** – difference between sales and target
* **Variance Margin** – variance as a percentage of target

### 🎛️ Interactive Reporting

* **Year slicer** to filter the whole report by financial year (e.g. FY2018)
* Filters and cross-highlighting between visuals
* KPI cards that update instantly when a filter is applied

### 📊 Visualisations

* Clustered bar charts comparing Sum of Sales and Target by month
* KPI cards for Sum of Sales, Target, Variance and Variance Margin
* Tables and matrices for sales by category, salesperson and order date

## 🗂️ Project Tasks Completed

* Getting data from a SQL Server database and a CSV file
* Cleaning, merging and transforming tables in Power Query
* Creating DAX measures for profit, profit margin, variance and variance margin
* Designing report pages with tables, charts, cards and a slicer
* Publishing the finished report to the Power BI service


## 📁 Included Outputs

* Published Power BI report (link above)
* Power BI project file (`.pbix`)
* Screenshots of the Power Query, report design and DAX work
* Sales vs target dashboard filtered by year

## 🎓 Key Learning Outcomes

This project strengthened skills in:

* Data cleaning and transformation with Power Query
* Connecting to multiple data sources (SQL Server and CSV)
* Writing DAX measures for profit, margin and variance
* Building interactive reports with slicers and filters
* Choosing clear visuals to compare performance against targets
* Using data storytelling to turn retail and sales data into insights


## 📸 Report Visuals

📸 Sales Report



📸 AdventureWorks Report

<img width="1428" height="800" alt="image" src="https://github.com/user-attachments/assets/acca747f-2723-491b-b3be-29182fe15c9a" />

<img width="1108" height="690" alt="Screenshot 2026-10-28 at 14 45 21" src="https://github.com/user-attachments/assets/9e6022f1-4a5e-4d7c-9f3a-ed3dd8b80d92" />

[[Link to My Report]](https://app.powerbi.com/view?r=eyJrIjoiMDAyYTkzZDEtZmM3Ny00OTY5LWFkYzYtMmY3YWQyYTMxNzk5IiwidCI6IjNlYTdjMTI4LWM2MDEtNDQ3OS1hMDAzLWUxNGQwMGMwYjVjYiJ9)






