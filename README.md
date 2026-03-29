#Target E-Commerce Data Analysis

Analysis of Target's e-commerce orders using Python and SQL to uncover insights on revenue, customer behavior, and delivery performance.

##Overview

This project performs an end-to-end exploratory data analysis of Target's e-commerce operations in Brazil. Using Python and SQLite, I analyzed 1M+ orders across 7 interconnected tables to answer 20 real-world business questions covering customer behavior, revenue trends, seller performance, and operational metrics.

##Dataset

* Source: __e-Commerce (Target) Sales Dataset — Kaggle__
* Size: 1M+ orders
* Period: 2016 to 2018
* Coverage: Target's e-commerce operations across Brazil
* Tables: orders, customers, products, sellers, payments, order_items, geolocation
  
##Tools & Technologies

* Python — Pandas, Matplotlib, Seaborn
* Database — SQLite
* Environment — Jupyter Notebook
  
##Business Questions Answered

###Basic Analysis
1. List all unique cities where customers are located
2. Count the number of orders placed in 2017
3. Count the number of customers from each state
4. Calculate the number of orders per month in 2018
   
###Intermediate Analysis
1. Find the total sales per product category
2. Calculate the percentage of orders paid in installments
3. Find the average number of products per order grouped by customer city
4. Calculate the percentage of total revenue contributed by each product category
5. Find the correlation between product price and purchase frequency
6. Rank sellers by total revenue generated
7. Find states with the highest average order value
8. Which payment method is most popular per state
9. What are the peak ordering hours during the day
10. Which seller has the highest order cancellation rate
11. Find the average delivery time per state
    
###Advanced Analysis
1. Calculate the moving average of order values for each customer over their order history
2. Calculate cumulative sales per month for each year
3. Calculate the year-over-year growth rate of total sales
4. Calculate the retention rate of customers — defined as the percentage of customers who make another purchase within 6 months
5. Identify the top 3 customers who spent the most money in each year
   
##Key Insights

* Installment Payments: 49% of customers paid in installments rather than in full
* Top Revenue Category: Bed-Table-Bath contributed the highest revenue
* Peak Ordering Hour: Most orders were placed at 16:00, suggesting customers shop in the evening
* Customer Retention: None of customers made a repeat purchase within 6 months, suggesting low customer loyalty
* Delivery Performance: SP(São Paulo)had the fastest average delivery time at X days while [State name] had the slowest at X days
* Top State by Order Value: PB(Paraíba) had the highest average order value at $248.33
* YoY Growth: Total sales grew by 20% from 2017 to 2018
  
##What I Learned

* Writing complex SQL queries including window functions, CTEs, and subqueries
* Handling and cleaning real-world messy data with 1M+ rows
* Translating business questions into SQL queries and Python visualizations
* Identifying meaningful patterns and insights from raw data
* Building an end-to-end data analysis pipeline from CSV files to visual insights
