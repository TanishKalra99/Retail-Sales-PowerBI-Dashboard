# Power BI Report Inventory

## Data Model Entities
- FactSales
- DimDate
- DimProduct
- DimCustomer

## Report Pages

### Executive Overview
Visuals include:
- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Paid Sales %
- MoM Growth %
- Monthly sales trend
- Sales by category
- Sales by product
- Sales by region
- Month, region, category, and customer-segment slicers

### Product Analysis
Visuals include:
- Total Sales
- Total Quantity
- Average Selling Price
- Product Rank
- Quantity by product
- Product performance table
- Segment and month slicers

### Product Detail
Visuals include:
- Product Rank
- Total Quantity
- Total Sales
- Monthly sales trend
- Month slicer

### Customer Analysis
Visuals include:
- Total Customers
- Average Order Value
- Total Orders
- Average Sales per Customer
- Sales by segment
- Sales by region
- Sales by customer
- Customer performance table
- Month, region, and segment slicers

### Product Tooltip
Contextual cards:
- Total Sales
- Total Quantity
- Average Selling Price
- Product Rank

### DAX Practice
Measures visible in the report include:
- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Pending Sales
- Paid Sales
- Refunded Sales
- North Electronics Sales
- North Region Sales
- Electronic Sales
- Calculated Sales
- Product Rank
- Sales % of Total
- Visible Categories
- Sales Ignoring Category
- Average Sales per Order
- MoM Growth %
- Sales YTD
- Previous Month Sales
- Running Sales

## Fields Used in Report Visuals

### DimDate
- Date
- Month
- Year_Month

### DimProduct
- Product_Name
- Category
- Brand

### DimCustomer
- Full_Name
- City
- Region
- Segment

### FactSales
- Net_Sales
- Measures listed above
