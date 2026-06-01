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

![Star Schema Model](Screenshots/Star_Schema_Model.png)

The model follows a Star Schema design with `Sales_Fact` as the central fact table and supporting dimension tables for Customer, Product, Date, and Region.

## Relationship Management

![Manage Relationships](Screenshots/Manage Relationship.png)

Implemented:
- One-to-Many Relationships
- One-to-One Relationships
- Single-Direction Filtering
- Relationship Validation

## Power Query Transformations

![Power Query Transformation](Screenshots/Power Query Transformation.png)

Performed data preparation and table structuring using Power Query.

## Data Categories

![Data Categories](Screenshots/Data_Category.png)

Configured:
- Country → Country/Region
- State → State/Province
- City → City

## Hierarchies

### Date Hierarchy

![Date Hierarchy](Screenshots/Date_Hierarchy.png)

Year → Quarter → Month → Date

### Region Hierarchy

![Region Hierarchy](Screenshots/Region_Hierarchy.png)

Country → State → City

### Product Hierarchy

![Product Hierarchy](Screenshots/Product_Hierarchy.png)

Category → Subcategory → Product Name

## Advanced Modeling

### Inactive Relationship

![Inactive Relationship](Screenshots/Inactive_Relationship.png)

Created and managed inactive relationships to handle alternate filter paths.

## Model Validation

![Model Verification](Screenshots/Model Verification_Matrices.png)

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
