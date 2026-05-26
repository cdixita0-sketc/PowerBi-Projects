# Data Leverager – Power Query ETL Project

## Project Overview
Data Leverager is an ETL (Extract, Transform, Load) project developed using Power Query in Power BI. The project focuses on importing, cleaning, transforming, merging, and preparing sales and employee datasets for analytical reporting.

The objective of this project is to demonstrate practical data preparation techniques commonly used in real-world business intelligence and data analytics workflows.

---

## Business Problem
Organizations often receive raw sales data from multiple sources and periods. These datasets may contain:
- Missing values
- Inconsistent formatting
- Duplicate information
- Invalid records
- Unstructured data

The goal of this project was to transform raw datasets into a clean and analysis-ready format for reporting and decision-making.

---

## Datasets Used

### Sales Datasets
- Sales_Jan.xlsx
- Sales_Feb.xlsx
- Sales_Mar.xlsx

### Employee Dataset
- Employee_Data.xlsx

The datasets contain:
- Order details
- Employee information
- Product data
- Sales transactions
- Regional information

---

## ETL Process Performed

### 1. Data Extraction
- Imported multiple Excel files into Power BI
- Loaded datasets into Power Query

### 2. Append Operations
- Combined January, February, and March sales datasets using:
  - Append Queries as New

### 3. Data Cleaning
- Handled null values
- Removed invalid records
- Replaced missing values with appropriate defaults
- Standardized text formatting
- Corrected incorrect data types

### 4. Data Transformation
- Split OrderID into:
  - MonthCode
  - OrderNumber
- Added Index Column
- Created Conditional Columns for sales categorization
- Applied Trim and Clean transformations

### 5. Merge Operations
- Merged Sales and Employee datasets using:
  - EmployeeID
- Applied Left Outer Join
- Expanded employee-related attributes into the sales dataset

### 6. Aggregation & Grouping
Performed Group By operations to calculate:
- Total Sales
- Average Order Value
- Transaction Count by Region

---

## Tools & Technologies
- Power BI
- Power Query
- Microsoft Excel

---

## Skills Demonstrated
- ETL Workflow
- Data Cleaning
- Data Transformation
- Query Append
- Query Merge
- Conditional Logic
- Aggregation & Grouping
- Data Preparation
- Power Query Operations

---

## Project Screenshots
The repository includes screenshots demonstrating:
- Append Queries
- Merge Queries
- Conditional Columns
- Final Cleaned Dataset

---

## Conclusion
Data Leverager demonstrates a complete beginner-to-intermediate ETL workflow using Power Query. The project highlights practical data cleaning, transformation, merging, and aggregation techniques used in modern business intelligence projects.
