# DEX_Depo - Power BI DAX Analysis Project

## Overview

DEX_Depo is a Power BI project designed to demonstrate practical implementation of DAX (Data Analysis Expressions), Data Modeling, Time Intelligence, Filter Context, Relationship Functions, and Matrix-based reporting.

The project uses a Star Schema data model consisting of Sales and Returns fact tables connected to Customer, Product, Region, and Date dimension tables.

---

## Project Objectives

- Build an optimized Star Schema model
- Create calculated columns and measures using DAX
- Implement logical, text, date, iterator, and relationship functions
- Analyze filter context behavior using CALCULATE(), FILTER(), and ALL()
- Perform Time Intelligence analysis
- Organize measures using a dedicated Measure Table
- Create business-focused Matrix reports

---

## Data Model

### Fact Tables
- Sales_Fact
- Returns_Fact

### Dimension Tables
- Customer_Dim
- Product_Dim
- Region_Dim
- Date_Dim

---

## DAX Concepts Covered

### Calculated Columns
- Profit
- ReturnFlag
- Customer Full Name
- Sales Category
- Sales Status
- Priority Sale

### Aggregation Functions
- SUM()
- AVERAGE()
- MAX()

### Counting Functions
- DISTINCTCOUNT()
- COUNTX()

### Logical Functions
- IF()
- AND()
- OR()
- SWITCH()

### Text Functions
- CONCATENATE()
- UPPER()
- LEFT()

### Date Functions
- YEAR()
- MONTH()
- EOMONTH()

### Relationship Functions
- RELATED()

### Filter Context Functions
- CALCULATE()
- FILTER()
- ALL()

### Time Intelligence Functions
- TOTALYTD()
- SAMEPERIODLASTYEAR()
- DATESINPERIOD()
- DATESBETWEEN()

### Iterator Functions
- SUMX()
- AVERAGEX()
- COUNTX()

---

## Key Measures

- Total Sales
- Total Cost
- Total Profit
- Total Returns
- Total Transactions
- Return Rate %
- Average Sale per Transaction
- Previous Month Sales
- Month Difference
- Previous Year Sales
- YTD Sales
- Running Total
- Revenue × Quantity
- Transaction Count X

---

# Project Screenshots

## Star Schema Data Model

![Star Schema Model](Screenshots/Star_schema_Model.png)

---

## Relationships View

![Relationships View](Screenshots/Relationships_View.png)

---

## Measure Table

![Measure Table](Screenshots/Measure_Table.png)

---

## Basic DAX Functions Matrix

![Basic DAX Functions](Screenshots/Basic_DAX_Functions_Matrix.png)

---

## Conditional Logic Functions

![Conditional Logic Functions](Screenshots/Conditional_Logic_Functions.png)

---

## Conditional Logic Output

![Conditional Logic Table](Screenshots/Conditional_Logic_Functions_table.png)

---

## Text Functions

![Text Functions](Screenshots/Text_Functions.png)

---

## Date Functions

![Date Functions](Screenshots/Date_handling.png)

---

## RELATED Function

![RELATED Function](Screenshots/RELATED_Function.png)

---

## Filter Context Analysis

![Filter Context Matrix](Screenshots/Filter_Context_Matrix.png)

---

## Month-over-Month Quick Measure

![Month Over Month](Screenshots/Month_Over_Month_Quick_Measure.png)

---

## Year-over-Year Quick Measure

![YOY Change](Screenshots/Quick_Measure_YOY_Change.png)

---

## Time Intelligence Table

![Time Intelligence Table](Screenshots/Time_inteligence_table.png)

---

## Time Intelligence Matrix

![Time Intelligence Matrix](Screenshots/Time_Intelligence_Matrix.png)

---

## Iterator Functions Matrix

![Iterator Functions Matrix](Screenshots/Iterator_Functions_Matrix.png)

---

## Final DAX Analysis Matrix

![Final DAX Matrix](Screenshots/Final_DAX_Depo_Matrix.png)

---

## DAX Formula Documentation

![DAX Formula](Screenshots/DAX_Formula.png)

---

## Additional Documentation

### Calculated Columns Documentation

- Calculated Columns.txt

Contains all calculated column formulas used in the project.

---

## Skills Demonstrated

- Power BI Data Modeling
- Star Schema Design
- DAX Development
- Calculated Columns
- Measures
- Filter Context Analysis
- Time Intelligence
- Iterator Functions
- Relationship Functions
- Business Reporting
- Matrix Visualization Design

---

## Tools Used

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling

---

## Project Structure

```text
DEX_Depo/
│
├── DEX_Depo.pbix
├── README.md
│
├── Calculated Columns.txt
│
└── Screenshots/
    ├── Star_schema_Model.png
    ├── Relationships_View.png
    ├── Measure_Table.png
    ├── Basic_DAX_Functions_Matrix.png
    ├── Conditional_Logic_Functions.png
    ├── Conditional_Logic_Functions_table.png
    ├── Text_Functions.png
    ├── Date_handling.png
    ├── RELATED_Function.png
    ├── Filter_Context_Matrix.png
    ├── Month_Over_Month_Quick_Measure.png
    ├── Quick_Measure_YOY_Change.png
    ├── Time_inteligence_table.png
    ├── Time_Intelligence_Matrix.png
    ├── Iterator_Functions_Matrix.png
    ├── Final_DAX_Depo_Matrix.png
    └── DAX_Formula.png
```

---

## Author

**Dixita**  
Data Science Student | Power BI Learner

---
