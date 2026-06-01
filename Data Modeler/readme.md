# Data Modeler - Building a Normalized Star Schema Data Model

## Project Overview

This project focuses on Data Modeling in Power BI using a normalized dataset. The objective was to design an efficient data model, create relationships between tables, implement hierarchies, configure data categories, and validate filter flow using matrix tables.

## Tools Used

- Power BI Desktop
- Power Query
- Model View

## Dataset Structure

### Fact Tables
- Sales_Fact
- Return_Fact

### Dimension Tables
- Customer_Dim
- Product_Dim
- Date_Dim
- Region_Dim

## Data Modeling Tasks Completed

### Power Query Transformations
- Verified data types
- Cleaned and structured tables
- Prepared dimension and fact tables

### Relationship Management
- Created One-to-Many relationships
- Demonstrated Many-to-One relationships
- Demonstrated One-to-One relationship
- Configured Single Cross Filter Direction
- Tested Bidirectional Filtering
- Created an Inactive Relationship
- Identified and resolved ambiguity issues

### Hierarchies Created

#### Date Hierarchy
Year → Quarter → Month → Date

#### Region Hierarchy
Country → State → City

#### Product Hierarchy
Category → Subcategory → ProductName

### Data Categories Applied

- Country → Country/Region
- State → State/Province
- City → City

## Schema Design

The model follows a Star Schema architecture where the Sales_Fact table acts as the central fact table connected to multiple dimension tables.

## Ambiguity Resolution

An ambiguity issue occurred between:

Return_Fact → Sales_Fact → Date_Dim

and

Return_Fact → Date_Dim

To avoid multiple filter paths, the relationship between Return_Fact and Date_Dim was kept inactive.

## Verification Using Matrix Tables

The model was verified using Matrix visuals:

1. Sales by Product Category and Region
2. Return Reasons by Fiscal Year
3. Revenue by Customer Segment

## Key Concepts Demonstrated

- Star Schema Design
- Relationship Cardinality
- Cross Filter Direction
- Active vs Inactive Relationships
- Hierarchies
- Data Categories
- Filter Propagation
- Ambiguity Resolution

## Project Screenshots

- Model View
- Relationship Management
- Hierarchies
- Data Categories
- Inactive Relationship
- Matrix Verification

## Learning Outcomes

This project improved my understanding of:

- Data Modeling in Power BI
- Fact and Dimension Tables
- Relationship Design
- Schema Architecture
- Filter Flow Management
- Model Optimization
