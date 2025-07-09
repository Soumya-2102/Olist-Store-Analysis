# Olist-Store-Analysis (Domain: Ecommerce)

## Project Objective
The objective of this project is to analyze the Olist Store dataset to uncover meaningful insights that support data-driven decision-making in the e-commerce domain. By examining key metrics such as order status, review scores, payment types, and product categories, the project aims to improve sales strategies and customer satisfaction. It focuses on understanding customer behavior patterns, shipping performance, and seller efficiency to enhance operational effectiveness. The analysis also evaluates city-wise pricing trends and delivery times to identify logistical bottlenecks. Using tools like Excel, MySQL, Power BI, and Tableau, the project transforms raw data into visual dashboards and actionable intelligence. Ultimately, the goal is to optimize marketing efforts, streamline logistics, and strengthen customer retention strategies. This helps businesses on platforms like Olist stay competitive and grow sustainably in the dynamic e-commerce market.

# Dataset Used
- <a href="https://github.com/Soumya-2102/Olist Store Analysis/commit/08f6e84d3aa7a64342f2e9f31b95c7240a54185a">Oliststoreanalysisdata</a>

## Questions(KPI'S)
1. Weekday Vs Weekend (order_ purchase_timestamp) Payment Statistics
2. Number of Orders with review score 5 and payment type as credit card.
3. Average number of days taken for order_delivered_customer_date for pet_shop
4. Average price and payment values from customers of sao paulo city
5. Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.
6. Average shipping day by review Score.
7. Top 10 Product Category by Number of Orders

## Process
1. Data Collection
The dataset was sourced from Olist, a Brazilian e-commerce platform.
It contains multiple tables including:
Orders
Customers
Payments
Reviews
Sellers
Products
Geolocation

2. Data Cleaning & Preprocessing
Using Excel and MySQL:
Merged relational tables via common keys (e.g., order_id, customer_id)
Removed missing values and duplicates
Handled inconsistent category names and converted them to English
Standardized date formats (purchase, delivery, etc.)
Created calculated fields such as:
Shipping time = order_delivered_customer_date - order_purchase_timestamp
Weekend vs Weekday flag
Review score averages per category or city

3. KPI Identification
Key Performance Indicators selected for analysis:
Total Unique Customers: 96.1K
Total Profit: 2.42M
Total Sellers: 3095
Total Sales: 16.01M
Product Count: 32.34K
Average Shipping Days
Review Score Distribution
Payment Type Distribution

4. Visualization & Dashboard Creation
Using Power BI (and possibly Tableau for some visual slices):
Pie charts for:
Payment value by weekday/weekend
Shipping days vs review score
Bar charts for:
Payment type vs review score
Product categories by order count
Shipping days by product category
Average price and payment value by city
Metrics cards for KPIs (Total Sales, Customers, etc.)

5. Insights & Trend Analysis
Credit card is the most used payment type with high 5-star reviews.
Weekdays have higher sales volume than weekends.
Product categories like “computers” and “tablets” have longer average shipping days.
Sao Paulo and Sao Bernado cities show high average payment values.
There's a positive relation between faster shipping and higher review scores.

## Key insights
1. High Customer Base & Sales Volume
Olist has 96.1K unique customers, 3,095 sellers, and a total sale of 16.01M.
This reflects a robust and active e-commerce ecosystem in Brazil.

2. Credit Card is the Dominant Payment Method
Most orders (4.2K+) with high review scores were made using credit cards.
Other payment types like boleto and debit card had significantly fewer orders.
Indicates customer preference and trust in credit card transactions.

3. Sales Are Higher on Weekdays
Weekdays account for 77.21% of total payment value, compared to 22.79% on weekends.
Suggests weekday shopping habits dominate Olist customer behavior.

4. Shipping Time Impacts Customer Satisfaction
Average shipping time is 12.09 days, but customers giving higher reviews had faster delivery (~3.84 days).
Indicates a strong correlation between quick delivery and higher satisfaction.

5. Top Performing Product Categories
Categories with the highest number of orders include:
Computers & accessories
Tablets & electronics
DVDs/Blu-ray
These are the most popular and fast-moving product types.

6. City-Based Spending Patterns
Customers from São Paulo spent the most with an average payment value of ₹154 and price of ₹121.
São Bernardo also had high average values.
Major cities drive higher-value transactions, suggesting targeted marketing potential.

7. Review Score Distribution is Skewed
The review score distribution shows imbalanced ratings, with a majority leaning toward 5-star or very low ratings.
Requires careful analysis and sentiment monitoring for product/service improvements.

8. Shipping Delays in Specific Categories
Categories like "computers" and "tablets" experience longer average shipping durations (13+ days).
Indicates a need to optimize delivery logistics for tech products.

## Conclusion
In conclusion, the Olist Store Analysis project offers valuable insights into Brazil’s e-commerce landscape by exploring customer behavior, payment trends, delivery performance, and product preferences. The analysis revealed that credit cards are the most preferred payment method, and customer satisfaction is closely linked to faster delivery times. Sales are significantly higher on weekdays, and major cities like São Paulo contribute the most to revenue. Popular product categories such as electronics and media dominate order volumes. Despite challenges like inconsistent data and review score imbalances, the project successfully highlighted key growth areas. Using tools like Excel, MySQL, Power BI, and Tableau, data was cleaned, processed, and visualized for better decision-making. Overall, the project supports the importance of data-driven strategies to optimize logistics, enhance user experience, and boost business performance in a competitive e-commerce environment.

