# Supply Chain Visibility & Optimization – Power BI Project

## Project Overview
This project focuses on analyzing and optimizing supply chain operations using Power BI. A dimensional data model was created from the source Fact Table and supporting dimension tables to enable interactive analytics and business reporting.

## Data Used

### Fact Table
The central transactional dataset containing sales, orders, inventory, shipping, warehouse, and customer-related information.

### Dimension Tables Used
- Dim_Customer
- Dim_Product
- Dim_Category
- Dim_Shipping
- Dim_Location
- Dim_Department
- Dim_Date
- Dim_Warehouse
- Dim_Inventory
- Dim_Supplier

### Additional Forecasting Table
- Prophet_Sales_Forecast
  - Contains Actual Sales, Forecast Sales, Forecast Lower, Forecast Upper, and Date.
  - Used for sales trend analysis and future sales forecasting.

## How the Data Was Used

### Data Modeling
- Created a star-schema-based model.
- Connected dimension tables to the Fact Table through appropriate keys.
- Created a Date dimension for time intelligence analysis.
- Established relationships between sales, inventory, supplier, warehouse, shipping, and customer data.

### Supplier Analytics
- Used the Dim_Supplier table to evaluate:
  - Supplier quality scores
  - Supplier reliability percentages
  - Supplier lead times
  - Supplier ranking and performance metrics

### Sales Forecasting
- Used the Prophet_Sales_Forecast table to:
  - Compare actual sales with forecasted sales.
  - Display future sales trends.
  - Visualize forecast confidence ranges using upper and lower forecast bounds.

## Dashboards Developed

### 1. Inventory Analytics
File: Inventory_Analytics.png

Key Focus Areas:
- Inventory turnover analysis
- Stock status monitoring
- Dead stock identification
- Reorder recommendations
- Inventory value tracking

### 2. Delivery Performance
Key Focus Areas:
- On-time delivery analysis
- Late delivery tracking
- Fulfillment rate monitoring
- Delivery risk assessment
- Regional delivery performance

### 3. Supplier Performance
Key Focus Areas:
- Supplier scorecards
- Quality score evaluation
- Reliability analysis
- Lead time monitoring
- Supplier ranking and categorization

### 4. Transportation Analytics
Key Focus Areas:
- Shipping mode analysis
- Delivery performance by transportation type
- Discount and profitability analysis
- Regional transportation performance
- Late delivery trend analysis

### 5. Warehouse Efficiency
Key Focus Areas:
- Warehouse utilization monitoring
- Capacity management
- Stock distribution analysis
- Capacity risk identification
- Warehouse productivity metrics

## Outcome
The Power BI solution provides a centralized view of supply chain operations, helping stakeholders monitor inventory, delivery performance, supplier efficiency, transportation effectiveness, warehouse utilization, and future sales trends through forecasting.
