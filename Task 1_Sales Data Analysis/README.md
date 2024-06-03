# MeriSkill-Sales_Data_Analysis

## Introduction

Effective decision-making and strategic planning in business require an analysis of sales data. Monthly and daily sales data are essential components of this analysis as they aid in determining daily sales patterns and seasonal trends. The total of quality scores indicates both product performance and customer satisfaction, while total sales and revenue metrics offer information about the company's financial standing. By assessing profitability, pricing and cost-management strategies are guided by the analysis of profit margins. In-depth information about product popularity and long-term trends can also be found in the sum of sales by product and sum of sales by month.
 
Analysing sales data from different angles yields more insights. As an illustration, the top 5 cities for high salaries show off potential geographic markets for customised marketing initiatives. Sales totals broken down by weekdays show trends in customer behaviour, which helps determine the best times to run promotions. A thorough understanding of a product's performance is provided by the total quality arranged by product, which guides quality improvement and control. When combined, these qualities enable companies to make data-driven decisions that maximise customer satisfaction, increase profitability, and optimise operations.


## Description

This comprehensive sales data analysis aims to facilitate data-driven decision-making and strategic planning. The analysis encompasses multiple key attributes including month, day, total sales, sum of quality, profit margin, revenue, sum of sales count by product, sum of sales by month, top 5 cities with high salaries, sum of sales by weekdays, and sum of quality ordered by product. The objective is to extract actionable insights and trends that can drive business optimization and profitability.

Monthly and daily sales data are scrutinized to identify seasonal trends and daily sales patterns, enabling precise demand forecasting and resource allocation. Key performance indicators (KPIs) such as total sales and revenue are assessed to provide a holistic view of the company's financial health and market penetration. The sum of quality scores is analyzed to gauge customer satisfaction and product performance, while profit margins are evaluated to understand product profitability, guiding pricing strategies and cost management.

Further, the sum of sales count by product and sum of sales by month offer detailed insights into product popularity and long-term sales trends. Temporal analysis through the sum of sales by weekdays reveals consumer behavior patterns, optimizing promotional activities and sales events. Geospatial analysis targets the top 5 cities with high salaries to identify high-potential markets. Finally, the sum of quality ordered by product informs quality control and product development efforts. This multi-faceted analysis enhances business operations, boosts profitability, and improves customer satisfaction through rigorous, data-driven insights.

## About the Dataset

The dataset has sales data from January 2019 to January 2020. It consists originally of 6 columns which was modified further for the purpose of the analysis;

order_id: Unique identifier for each order placed by a customer
Product: Electronics Products sold by the store
quantity: Quantity ordered for each product
order_date: Date the order was placed
Price Each: Price of each product in USD
Purchase Address: Address of each customer who placed an Order


## Business Task

Q1. What are the top 5 cities with highest sales?

Q2. What are the profit margin and revenue?

Q3. What are the Products performance by Quantity?

Q4. What are the top 5 products with highest sales count?

Q5. What are the total sales by month?

Q6. What is the revenue contribution in weekdays?


## Analysis

The analysis was done using Microsoft Power BI.


## Steps

### Data Import: 
I imported and converted the raw data which was in CSV file format into Microsoft Excel.

### Data Cleaning: 
I cleaned the data to ensure accuracy and consistency this included standardizing the formats, and correcting errors.

### Data Transformation: 
I transformed the data to make it suitable for analysis. This transformation includes calculations, aggregations, and filtering operations. I also created new columns required for the analysis using Microsoft Excel.

### Data Visualization: 
Data Visualization: I visualized the analyzed data using the charts and graphs available on Microsoft Power BI. I also created a dashboard using the insights from the analyzed data.


# Insights

Total Orders - 186K
Number of Products - 19
Total Quantities Sold - 209K
Total revenue - $34.4M
Average revenue/order - $185.5


### What is the overall sales trend?

#### Sales per Quarter

Qtr 4 recorded the highest revenue with a total of $11.5M which is 33.49% of the total revenue, while Q1 with a total of $6.8M which is 19.81% of the total revenue recorded the lowest revenue generated.


#### Sales per Month

The most productive month is December with a total revenue of $4.61M which is 13.38% of the total revenue generated. While January has the lowest performance with a total of $1.82M revenue generated which is 5.28% of the total revenue generated. Sales are low at the beginning of the year and highest at the end of the year.

<img width="403" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/b360b089-3f46-4966-867d-ba44ef1c1516">


#### Sales per Day of Week

Tuesdays accounted for the highest revenue generated with a total of $5M which is about 14.75% of the total revenue generated. While the day that recorded the least revenue is Thursday with a total of 4.8M which is 14% of the total revenue generated.


#### What are the top 5 cities with highest sales performance?

The Top Five Cities with highest Sales Performance are New York, Boston, San Francisco, Los Angeles, Atlanta. (Shown Below)

<img width="299" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/aa7b5452-07b4-404b-8f43-943eea778e00">


#### What are the Most Selling Products(Quantity)?

The most bought product is the AAA Batteries (4-pack) which sold about 31k quantities, while the product that sold the least number of units is LG Dryer with a total of 646 quantities sold.

<img width="313" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/664e284b-cc59-4b8a-9b72-e90cf67106af">


#### What is the Order performance per City?

The top performing City is San Francisco with a total of 45k orders which is 24% of the total orders received, while the least performing City is Austin with a total of 10k orders which is 5.33% of the total orders received.


#### What are the profit margin and revenue?
The Profit Margin is estimated to be 59% and the Total Revenue is 34,492.04K (shown below).

<img width="311" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/5aa50505-1ce2-4f76-b4bd-c29aeca6302b">


#### What is the revenue contribution in weekdays?

Sales over the weekend generated a total of revenue of $9.84M which is 28.52% of the total revenue, while sales during weekdays generated a total revenue of 24.6M which is 71.48% of the total revenue generated.

<img width="293" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/9db684e3-013e-4d39-84fe-6cdf2d6b1b59">




# Visualization


<img width="525" alt="image" src="https://github.com/Agalya1909/MeriSKILL_DataAnalyst/assets/119459631/4e5aa83d-6f29-4d2f-8d49-3f973243ad78">





# Conclusion


### Overall Sales Trend:

The fourth quarter (Q4) stands out as the highest revenue-generating period, contributing 33.49% of the total revenue, while the first quarter (Q1) records the lowest revenue at 19.81%. This indicates a seasonality trend with higher sales towards the end of the year.

December is the most productive month, contributing 13.38% of the total revenue, while January performs the lowest at 5.28%. This confirms a yearly pattern of low sales at the beginning of the year, gradually increasing towards the year-end.

Tuesdays generate the highest revenue at 14.75% of the total, while Thursdays record the lowest at 14%. This indicates variations in daily sales performance throughout the week.


#### Product Performance by Revenue:

The Macbook Pro Laptop is the top-performing product, generating $8.04M in revenue, while AAA Batteries (4-pack) is the least performing with $900k in revenue.
The AAA Batteries (4-pack) is the most sold product, with approximately 31k units sold, while the LG Dryer is the least sold with only 646 units.


#### Order Performance by City:

San Francisco is the top-performing city, accounting for 24% of total orders, while Austin performs the least with 5.33% of total orders.


#### Peak Period of the Day:

Sales peak at 7 pm every day, generating $2.4M in revenue, and reach their lowest point at 3 am daily.
Revenue Distribution Between Weekdays and Weekends:

Sales over the weekend contribute 28.52% of the total revenue, while weekday sales account for 71.48% of the total revenue
Recommendations


#### Seasonal Promotions:

Capitalize on the seasonality trend by implementing targeted marketing and promotions during Q4 to maximize revenue. Consider offering special deals during the holiday season. Monthly Strategies: Focus on boosting sales during the beginning of the year, particularly in January, through innovative marketing campaigns and product promotions to counter the post-holiday slump.


#### Day-Specific Campaigns:

Develop strategies to optimize sales on Tuesdays, the highest-performing day, and consider introducing incentives or exclusive offers to drive sales on Thursdays, the lowest-performing day.


#### Product Spotlight:

Given the high performance of the Macbook Pro Laptop, consider expanding product lines or creating bundles that include this popular item to further boost revenue.


#### Inventory Management:
Monitor and manage inventory for AAA Batteries (4-pack) and LG Dryer to ensure that stock levels match demand.


#### City-Specific Initiatives:
Explore opportunities to increase sales in cities like Austin through localized marketing efforts and tailored promotions.


#### Peak Time Promotions:
Leverage the 7 pm peak period by running special promotions or flash sales during this time to maximize revenue.


#### Weekend Marketing:
Continue to focus on weekend sales, potentially with weekend-specific promotions, while maintaining a strong weekday presence.

