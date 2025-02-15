# Introduction
The project utilizes Power BI to analyze sales performance, identify trends, and optimize strategies for a retail business, analyzing product performance, customer demographics, and seasonal trends.

# Problem Statement
SalesStore faces challenges in optimizing its inventory, understanding
customer buying behaviors, and measuring the effectiveness of sales strategies.
The business needs an in-depth analysis of sales data to:
-	Identify top-performing products and sales trends.
-	Understand customer demographics and purchasing patterns.
-	Assess seasonal sales fluctuations.
-	Detect inefficiencies in sales operations and inventory management.
This project's main goal is to use Power BI to examine these factors and offer useful insights that aid in decision-making and enhance business results.

# Data Sourcing
The data used for this analysis was sourced from various internal systems and databases, including:
- Sales Data: Transaction-level information, including the product sold, quantity, unit price, date of sale, and any applicable discounts. 
- Customer information: including demographics (age, gender, and location) and buying patterns (frequency of purchases, average transaction value).
- Product Data: Details about the sold goods, such as prices, stock levels, and categories.
This data was provided in CSV format and was consolidated for analysis in Power BI.

# Data Transformation and Cleaning
The following steps were performed to clean and transform the raw data into a usable format for Power BI analysis:
1.	Data Merging: To enable simple filtering and drill-downs in Power BI, multiple datasets (sales, products, customers, and time) were combined into a single, cohesive dataset.
2.	Missing Data: To maintain consistency, we identified and addressed missing data in product categories and customer demographics by deleting or imputing records as needed.
3.	Outlier Detection: By establishing predetermined thresholds, outliers in sales amounts and quantities were identified and addressed. Extreme outliers were eliminated or corrected.
4.	Standardization: To facilitate data analysis and visualization, consistency across fields was ensured (e.g., standardized date formats, currency formatting).
5.	Duplicate Removal: To avoid erroneous analysis results, duplicate records in sales transactions were eliminated.
6.	Categorization: To facilitate filtering and the creation of insights, products were arranged into categories (e.g., electronics, clothing, etc.), and customers were segmented by demographics (age group, region).
After these transformations, the data was fully cleaned and structured for analysis.

[Dataset before cleaning](![image](https://github.com/user-attachments/assets/cca862a4-06c6-41cd-b1e6-a094b9dd4420))


[Dataset after cleaning](![image](https://github.com/user-attachments/assets/790cf98b-7ab7-49a1-8634-20b8e33ee3fd))

# Data Modeling and relationships
The data model was built in Power BI to ensure an efficient and accurate analysis. Key aspects of the data modeling include:
1.	Tables and Relationships: Created tables for sales transactions, products, customers, and time periods. Relationships were established between these tables to link data points appropriately (e.g., linking sales with products via the product ID).
2.	Calculated Columns: Added calculated columns for deeper analysis, such as:
-	Profit Margin: Calculated based on sales price and cost price.
-	Customer Lifetime Value (CLV): Estimated based on the frequency and total value of customer purchases.
3.	Measures: Developed key metrics for performance analysis, including:
-	Total Sales
-	Total Profit
-	Average Order Value (AOV)
-	Year-over-Year (YoY) Sales Growth
-	Product Performance (Units Sold, Revenue) These measures were created using DAX (Data Analysis Expressions) formulas for dynamic reporting.
4.	Date Table: A date table was created to enable time-based analysis and comparisons (e.g., monthly sales, quarterly revenue, year-over-year growth).
The model was optimized for performance by reducing unnecessary columns and tables, ensuring quick load times for large datasets.

[ERD](![Screenshot 2025-02-09 163031](https://github.com/user-attachments/assets/43072690-160c-4b17-a716-7af321af3eaa))


# Data Analysis and Visualization
With the transformed data and structured model, a series of visualizations were created to deliver actionable insights:
•	Sales Performance Dashboard: Displays key metrics such as total sales, total profit, and sales trends over time (by day, month, quarter).
•	Product Analysis: Interactive visuals that show top-selling products, sales by product category, and product performance (e.g., units sold, revenue per product).
•	Customer Segmentation: Insights into customer demographics (age, gender, region) and purchase behavior (e.g., high-value customers, repeat buyers).
•	Seasonal Trends: Time-based analysis to uncover sales patterns across different seasons and identify peak sales periods.
•	Inventory Insights: Visuals to compare sales with current inventory levels, helping to identify potential stock-outs or overstocked products.
The Power BI report features slicers and interactive visuals that allow stakeholders to drill down and filter data dynamically for a personalized analysis experience.

# Conclusions and Recommendations
Several important conclusions and suggestions for the Sales Store were drawn from the analysis:
To drive growth, focus on top-performing products, target high-value customers with loyalty programs, plan promotions and inventory management around seasonal spikes, align sales and inventory to prevent stock outs, and analyze past promotions to design more effective future campaigns. Analyzing past promotions can help design more effective campaigns.

The insights aim to guide business strategies in enhancing sales, optimizing inventory, and enhancing customer engagement.
.






