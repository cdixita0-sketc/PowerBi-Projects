# Data Modeler - Building a Normalized Star Schema Data Model

## Project Objective

Designed and implemented a normalized data model in Power BI using industry-standard data modeling practices. The project focused on relationship management, schema design, hierarchies, data categories, and model validation.

## Skills Demonstrated

- Data Modeling
- Star Schema Design
- Fact & Dimension Modeling
- Relationship Management
- Cardinality Configuration
- Cross Filter Direction
- Active & Inactive Relationships
- Hierarchy Creation
- Data Categories
- Matrix-Based Validation

## Tools Used

- Power BI Desktop
- Power Query
- Model View

## Data Model Architecture

### Star Schema Model

![Star Schema Model](Star_Schema_Model.png)

The model follows a Star Schema design with `Sales_Fact` as the central fact table and supporting dimension tables for Customer, Product, Date, and Region.

## Relationship Management

![Manage Relationships](Manage_Relationship.png)

Implemented:
- One-to-Many Relationships
- One-to-One Relationships
- Single-Direction Filtering
- Relationship Validation

## Inactive Relationship

![Inactive Relationship](Inactive_Relationship.png)

An inactive relationship was created between Return_Fact and Date_Dim using ReturnDateKey. This was used to demonstrate how Power BI handles multiple relationship paths and ambiguity scenarios while maintaining a clean data model.

## Power Query Transformations

![Power Query Transformation](Power_Query_Transformation.png)

Performed data preparation and table structuring using Power Query.

## Data Categories

![Data Categories](Data_Category.png)

Configured:
- Country → Country/Region
- State → State/Province
- City → City

## Hierarchies

### Date Hierarchy

![Date Hierarchy](Date_Hierarchy.png)

Year → Quarter → Month → Date

### Region Hierarchy

![Region Hierarchy](Region_Hierarchy.png)

Country → State → City

### Product Hierarchy

![Product Hierarchy](Product_Hierarchy.png)

Category → Subcategory → Product Name

## Advanced Modeling

### Inactive Relationship

![Inactive Relationship](Inactive_Relationship.png)

Created and managed inactive relationships to handle alternate filter paths.

## Model Validation

![Model Verification](Model_Verification_Matrices.png)

Validated relationship flow using Matrix visuals:

1. Sales by Product Category and Region
2. Return Reasons by Fiscal Year
3. Revenue by Customer Segment

## Key Learning Outcomes

- Understanding Fact vs Dimension Tables
- Designing Star Schema Models
- Managing Cardinality
- Handling Ambiguous Filter Paths
- Creating Hierarchies
- Applying Data Categories
- Validating Relationship Flow
