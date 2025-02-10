# Online Retail Sales Analysis

## Project Overview

This project conducts an in-depth analysis of online retail sales data for a UK-based company, focusing on transactions from December 2010 to December 2011. The analysis aims to provide comprehensive insights into sales trends, customer behavior, product performance, and pricing strategies to support data-driven decision-making and business optimization.

## Dataset Content

The dataset contains the following key attributes:

- InvoiceNo: Unique identifier for each transaction
- StockCode: Product code
- Description: Product name
- Quantity: Number of items purchased
- InvoiceDate: Date and time of the transaction
- UnitPrice: Price per unit of the product
- CustomerID: Unique identifier for each customer
- Country: Customer's country of residence

## Data Processing and Analysis

### Data Cleaning and Preprocessing

1. Filtered data to include only UK transactions
2. Removed rows with missing values
3. Eliminated negative quantities and unit prices
4. Truncated the dataset to manage computational limitations

## Feature Engineering

- Broke down `InvoiceDate` into Year, Month, Day, and Hour
- Created a `TotalAmount` column (Quantity * UnitPrice)
- Categorized products into broader categories
- Applied price binning to understand product price distribution

## Key Analyses Performed

- Revenue aggregation by year, month, day, and hour
- Identification of top 10 customers by revenue
- Product categorization and analysis of category performance
- Price range analysis of products
- Identification of worst-performing products
- Analysis of least revenue-generating customers
- Detailed examination of product categories by revenue
- Investigation of sales distribution by hour of day
- Identification of top 10 most expensive products

## Key Findings

### Monthly Revenue Trends:
- Highest revenue observed in December 2010 and November 2011
- Lowest revenue in January and February 2011

### Top-Performing Categories:
- "Other" category generated the highest revenue (£507,229.88)
- Followed by "Heating & Warmth" (£74,786.31) and "Home Decor" (£68,422.84)

### Customer Analysis:
- Top customer (ID: 17511) generated £6,272.62 in revenue
- Significant variation in customer spending patterns
- Identified least revenue-generating customers for targeted marketing strategies

### Product Pricing:
- Majority of products (46,364) priced between £0-10
- Only 2 products priced over £1000
- Identified top 10 most expensive products for premium pricing strategies

### Sales Distribution:
- Peak sales hours observed between 10 AM and 3 PM
- Detailed hourly sales distribution provides insights for operational optimization

### Worst-Performing Products:
- Identified top 5 worst-performing products by quantity sold
- Insights can be used for inventory management and product line decisions

## Visualizations

The project includes several visualizations to illustrate key findings:
- Monthly Revenue Line Chart
- Monthly Quantity Sold Bar Chart
- Top 10 Products by Quantity Sold Bar Chart
- Top 10 Customers by Revenue Bar Chart
- Product Categories by Revenue Bar Chart
- Sales Distribution by Hour of Day Line Chart
- Top 5 Worst Performing Products by Quantity Sold Bar Chart
- Top 5 Least Revenue Generating Customers Bar Chart
- Product Categories by Revenue Bar Chart (Detailed)
- Top 10 Most Expensive Products Bar Chart

## Conclusions and Recommendations

- Focus marketing efforts on high-revenue months (November-December)
- Investigate and potentially expand the "Heating & Warmth" and "Home Decor" categories
- Implement a customer loyalty program to encourage repeat purchases from top customers
- Consider adjusting pricing strategies, particularly for items in the £0-10 range
- Optimize inventory and staffing during peak sales hours (10 AM - 3 PM)
- Develop strategies to improve performance of worst-performing products or consider discontinuation
- Create targeted marketing campaigns for least revenue-generating customers to increase their engagement
- Evaluate the pricing strategy for the most expensive products to ensure optimal profit margins
- Use hourly sales distribution data to optimize staffing and inventory management

## Future Work

- Conduct a more detailed analysis of the "Other" category to identify potential new product categories
- Perform customer segmentation analysis to tailor marketing strategies
- Analyze seasonal trends and their impact on different product categories
- Investigate the relationship between product pricing and sales volume
- Conduct a cohort analysis to understand customer retention and lifetime value
- Implement predictive modeling for sales forecasting and inventory optimization
- Analyze the impact of marketing campaigns on sales performance
- Investigate cross-selling and upselling opportunities based on product category analysis

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Jupyter Notebook for interactive development and analysis

## Project Structure

- `Online_Retail_Sales_Analysis.ipynb`: Jupyter notebook containing the main analysis
- `revenue_by_year.csv`: Aggregated revenue data by year
- `revenue_by_month.csv`: Aggregated revenue data by month
- `revenue_by_day.csv`: Aggregated revenue data by day
- `revenue_by_hour.csv`: Aggregated revenue data by hour
- `revenue_per_customer.csv`: Revenue data for each customer
- `UK_online_retail_final.csv`: Final cleaned and processed dataset
- 'Rough Tableau Retail Sales Dashboard.drawio'

## How to Run

1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Open and run the `Online_Retail_Sales_Analysis.ipynb` notebook

## Contributors

-  Bidhan Vhadra
   -  https://github.com/bvhadra
-  Jullian Colling
   -  https://github.com/juliancolling
-  Maha Hussain
   -  https://github.com/mahasci
-  Sayed Nazir
   -  https://github.com/Tee-DataA


## License

This project is licensed under the MIT License - see the LICENSE.md file for details.


