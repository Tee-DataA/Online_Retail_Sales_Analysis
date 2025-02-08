# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
The "Online Retail Transaction" dataset was selected for its coverage of customer transactions on an online retail platform. This dataset includes key attributes such as product details, purchase quantities, transaction timestamps, unit prices, unique customer identifiers, and customer locations.

- StockCode: A code used to identify the product that was purchased
- Description: A brief description of the product that was purchased
- Quantity: The quantity of the product that was purchased
- InvoiceDate: The date and time that the purchase was made
- UnitPrice: The price of one unit of the product that was purchased
- CustomerID: The unique identifier for the customer who made the purchase
- Country: The country where the customer who made the purchase is located

### This project contains the following CSV files:
#### 1. revenue_by_year.csv - contains revenue aggregated by year
####  2. revenue_by_month.csv - contains revenue aggregated by month
#### 3. revenue_by_day.csv - contains revenue aggregated by day
#### 4. revenue_by_hour.csv - contains revenue aggregated by hour
#### 5. revenue_per_customer.csv - contains revenue per customer
#### 6. UK_online_retail_final.csv - contains the final cleaned, categorised, and price-binned dataset

## Hypothesis and how to validate?
1. Most revenue comes from a few best-selling products.
    Analyse product-wise revenue distribution and apply Pareto analysis (80/20 rule).

2. Certain countries contribute disproportionately to revenue.
    Aggregate sales by country, calculate revenue share, and visualise regional differences.

3. Repeat customers generate a significant portion of revenue.
    Segment customers, compare revenue from repeat vs. new buyers, and conduct cohort analysis.

4. Sales follow seasonal trends.
    Analyse sales over time, identify peaks, and use time series analysis to detect seasonality.

## Project Plan

### High-Level Steps for Analysis

1. **Data Collection**:
   - Gather the "Online Retail Transaction" dataset from the provided source.
   - Ensure the dataset includes all necessary attributes such as product details, purchase quantities, transaction timestamps, unit prices, unique customer identifiers, and customer locations.

2. **Data Cleaning and Preprocessing**:
   - Handle missing values by either filling them with appropriate values or removing the affected rows.
   - Convert data types as needed, such as converting `InvoiceDate` to datetime format.
   - Remove any duplicate entries to ensure data integrity.
   - Create new columns if necessary, such as calculating `Revenue` by multiplying `Quantity` and `UnitPrice`.

3. **Exploratory Data Analysis (EDA)**:
   - Perform initial data exploration to understand the distribution and relationships within the data.
   - Generate summary statistics and visualizations to identify trends and patterns.
   - Use visualizations such as histograms, bar charts, and scatter plots to gain insights into the data.

4. **Hypothesis Testing and Validation**:
   - Formulate hypotheses based on business questions, such as identifying best-selling products, analyzing revenue distribution by country, and understanding customer purchasing behavior.
   - Validate hypotheses using appropriate statistical methods and visualizations.
   - Apply Pareto analysis (80/20 rule) to identify key products contributing to the majority of revenue.

5. **Data Visualization**:
   - Create visualizations to communicate insights effectively.
   - Use bar charts, line plots, pie charts, and other relevant visualizations to present findings.
   - Design a dashboard to display key metrics and visualizations for easy access and interpretation.

6. **Reporting and Documentation**:
   - Document the entire analysis process, including data collection, cleaning, analysis, and visualization steps.
   - Prepare a comprehensive report summarizing the findings and insights.
   - Include recommendations based on the analysis to inform business decisions.

### Data Management

- **Collection**: The dataset was collected from a reliable source and ensured to cover all necessary attributes for the analysis.
- **Processing**: Data was cleaned and preprocessed to handle missing values, convert data types, and remove duplicates.
- **Analysis**: Data was analyzed using various statistical methods and visualizations to extract meaningful insights.
- **Interpretation**: The results were interpreted to provide actionable recommendations for the business.

### Research Methodologies

- **Exploratory Data Analysis (EDA)**: Used to understand the data distribution and identify initial trends and patterns.
- **Hypothesis Testing**: Applied to validate business hypotheses and ensure data-driven decision-making.
- **Pareto Analysis**: Used to identify key products contributing to the majority of revenue.
- **Time Series Analysis**: Applied to detect seasonal trends and patterns in sales data.

### Rationale for Methodologies

- **EDA**: Provides a comprehensive understanding of the data and helps identify potential issues and opportunities.
- **Hypothesis Testing**: Ensures that business decisions are based on statistically significant findings.
- **Pareto Analysis**: Helps focus efforts on the most impactful products and customers.
- **Time Series Analysis**: Identifies seasonal trends, enabling better planning and forecasting.

By following this project plan, the analysis was structured and systematic, ensuring that all key aspects of the data were thoroughly examined and that the findings were reliable and actionable.



## The rationale to map the business requirements to the Data Visualisations
## The Rationale to Map the Business Requirements to the Data Visualisations

### Business Requirements

1. **Identify Best-Selling Products**:
   - **Rationale**: Understanding which products generate the most revenue helps in inventory management, marketing strategies, and identifying potential areas for product development.
   - **Data Visualisation**: Bar chart showing the top 10 products by revenue.

2. **Analyze Revenue Distribution by Country**:
   - **Rationale**: Identifying which countries contribute the most to revenue helps in targeting marketing efforts and understanding geographical market performance.
   - **Data Visualisation**: Pie chart showing the sales distribution by country.

3. **Track Monthly Sales Trends**:
   - **Rationale**: Monitoring sales trends over time helps in identifying seasonal patterns, planning inventory, and setting sales targets.
   - **Data Visualisation**: Line plot showing monthly revenue trends.

4. **Evaluate Customer Segments**:
   - **Rationale**: Understanding the revenue generated by repeat vs. new customers helps in customer retention strategies and marketing efforts.
   - **Data Visualisation**: Bar chart comparing revenue from repeat customers vs. new customers.

5. **Monitor Operational Efficiency**:
   - **Rationale**: Tracking order fulfillment times and return rates helps in improving operational processes and customer satisfaction.
   - **Data Visualisation**: Histogram showing order fulfillment times and bar chart showing return rates.

### Mapping to Data Visualisations

1. **Best-Selling Products**:
   - **Visualisation**: Bar chart of top 10 products by revenue.
   - **Purpose**: Quickly identify which products are driving the most sales.

2. **Revenue Distribution by Country**:
   - **Visualisation**: Pie chart of sales distribution by country.
   - **Purpose**: Visualize the geographical distribution of revenue to identify key markets.

3. **Monthly Sales Trends**:
   - **Visualisation**: Line plot of monthly revenue.
   - **Purpose**: Track sales performance over time and identify seasonal trends.

4. **Customer Segments**:
   - **Visualisation**: Bar chart of revenue from repeat vs. new customers.
   - **Purpose**: Compare the contribution of different customer segments to overall revenue.

5. **Operational Efficiency**:
   - **Visualisation**: Histogram of order fulfillment times and bar chart of return rates.
   - **Purpose**: Monitor and improve operational processes to enhance customer satisfaction.

By mapping these business requirements to specific data visualisations, the sales manager can gain actionable insights and make data-driven decisions to improve overall business performance.

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.