# Sales_Data_Analysis

## Overview
This project analyzes sales data to derive insights into different product categories, profit margins, customer ratings, and sales trends. It involves data preprocessing, grouping, aggregation, and visualization using Python libraries such as Pandas and Matplotlib.

## Dataset
The dataset contains 100 sales records with the following attributes:
- **OrderID**: Unique identifier for each order
- **Category**: Main category of the product (Clothing, Electronics, Furniture, Home Appliances)
- **SubCategory**: Specific sub-category of the product
- **SalesPrice**: Selling price of the product
- **Cost**: Cost price of the product
- **ProfitMargin**: Profit earned per product
- **CustomerRating**: Customer rating on a scale of 1 to 5
- **QuantitySold**: Number of units sold
- **DateOfSale**: Date of the transaction

## Features and Analysis
### 1. Data Loading and Inspection
- The dataset is loaded using Pandas.
- Data types and memory usage are analyzed.

### 2. Data Aggregation
- **Total Sales by Category**: The total sales amount is calculated for each category.
- **Profit Margin Analysis**: Profit margins are grouped by category and sub-category.
- **Statistical Aggregation**:
  - Sum, max, mean, and min values are calculated for various attributes.
  - Multiple aggregate functions are applied to different columns.

### 3. Data Visualization
- **Line Chart**: Sales trend over the years.
- **Bar Chart**: Sales distribution by category.
- **Scatter Plot**: Relationship between sales price and profit margin.
- **Histogram**: Distribution of sales prices.

## Requirements
To run the analysis, install the following Python packages:
```bash
pip install pandas matplotlib
```
## Results and Insights
- The Clothing category has the highest total sales.
- The Electronics category has a lower sales count but a higher average profit margin.
- There is a positive correlation between sales price and profit margin.
- Sales show seasonal trends based on historical data.
- 
![SalesDistribution](https://github.com/user-attachments/assets/daba36fa-aa3f-4985-ba7d-56e9dbb1bf01)

![Sales_vs_Profit](https://github.com/user-attachments/assets/f6fa2f60-50db-4062-8587-c757fe6dfaa0)

![Sales_Trend](https://github.com/user-attachments/assets/0a4c033c-ee05-49bf-9b34-56883b277970)



  

## Future Enhancements
- To Implement machine learning model to predict future sales trends.
- Integrate additional data sources for better insights.
- Developing an interactive dashboard for real-time sales monitoring.

## Author
**Varun Kumar Koppula**



