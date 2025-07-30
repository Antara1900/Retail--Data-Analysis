# Retail--Data-Analysis
## Conducted exploratory data analysis on retail datasets to derive actionable insights and visualize KPIs using Python-based tools.
## DATASET
-<a href = "https://github.com/Antara1900/Retail--Data-Analysis/blob/main/Retail_Dataset.csv"> Retail_dataset</a>

##  Dataset Features

The dataset (`Retail_Dataset.csv`) contains the following columns:

- `OrderDate`: Date when the order was placed
- `Product`: Name of the product
- `Customer`: Name/ID of the customer
- `Quantity`: Number of units sold
- `Price`: Price per unit
- `Sales`:(Quantity × Price)

 ## Key KPIs Calculated
 - Total Sales

- Average Order Value (AOV)

- Top 5 Products by Sales

- Monthly Revenue Trends

- Customer-wise Total Purchase

- Unique Products

 ##  Exploratory Analysis & Visualizations

###  Monthly Revenue Trend

- Extracted month from `OrderDate` and calculated total sales
- Line chart used to show month-over-month sales trend

 -<a href = "https://1drv.ms/i/c/67403cc5b6a101f0/ET4IOVDe5v9Hq1O3j1de17QBC7Zk-ESC7zkQDoc3kJKsQw?e=5SkjfR"> Monthly_Revenue_Trend</a>
  

###  Top 5 Products by Quantity Sold

- Grouped by product and summed quantity
- Identified most in-demand products for marketing or inventory decisions

###  Sales by Product – Bar Chart

- Visual comparison of total sales per product
- Helps identify top revenue-generating items
  
 -<a href = "https://1drv.ms/i/c/67403cc5b6a101f0/EeckL3U7xkhJho2KHAsLy2kBZ8iUJ-pZPUCkAvgKEDDeiQ?e=cRev7t">Total_Sales By Product</a>

###  Share of Each Product – Pie Chart

- Product quantity distribution visualized as percentages
- Useful for inventory mix and category-level planning

 -<a href = "https://1drv.ms/i/c/67403cc5b6a101f0/EWkOZDuP45tPixZEpFn1MUoBQCMTIhai9jsFzltl0pxvNQ?e=UI6usg">Share Of Each Product</a>

###  Day with Highest Sales

- Aggregated daily sales
- Revealed top-performing sales day

###  Customer-wise Total Purchase

- Sales grouped by customer
- Identified high-value customers for loyalty targeting

###  Correlation Heatmap 

- Analyzed relationships between `Quantity`, `Price`, and `Sales`
- Highlights which factors most influence revenue

 -<a href = "https://1drv.ms/i/c/67403cc5b6a101f0/EfwqV0EZRgtGn2K0SXdrpLwBcily6yaHeiNcKy3wIWou2g?e=kPXm9H">Correlation Heatmap</a>

## Insights

###  Focus Marketing on Top-Selling Products
Observation: A small number of products account for the majority of sales and quantity sold.
Action:

Promote these high-performing products through targeted advertising.

Bundle them with slow-moving items to increase overall basket size.

Ensure these products are always in stock to prevent lost sales.

### Prioritize High-Value Customers
Observation: A few customers are responsible for a significant portion of total revenue.
Action:

Build a loyalty program to retain and reward these top customers.

Offer personalized discounts or early access to new products.

Analyze their buying behavior to create customer personas.

### Leverage Sales Trends for Planning
Observation: Monthly and daily sales trends reveal peak periods (seasonal highs or weekends).
Action:

Increase inventory and staff during high-sales months or specific days.

Run promotions or flash sales during low-performing periods.

Use the trend data to forecast future demand more accurately.



