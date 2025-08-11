# Pizza_Stores Sales Analysis with MySQL

## Project Overview

This project aims to analyze pizza sales data using MySQL queries to extract meaningful insights into customer preferences, popular products, and overall sales trends. The analysis will help inform business decisions related to inventory management, marketing strategies, and menu optimization.

## Objectives

* Retrieve key metrics such as total orders, revenue, and sales trends.
* Identify top-selling pizza types and customer preferences.
* Use SQL queries to extract and analyze data effectively.
* Provide data-driven recommendations for business improvements.

## Questions

### Basic

* Retrieve the total number of orders placed.
* Calculate the total revenue generated from pizza sales.
* Identify the highest-priced pizza.
* Identify the most common pizza size ordered.
* List the top 5 most ordered pizza types along with their quantities.

### Intermediate

* Join the necessary tables to find the total quantity of each pizza category ordered.
* Determine the distribution of orders by hour of the day.
* Join relevant tables to find the category-wise distribution of pizzas.
* Group the orders by date and calculate the average number of pizzas ordered per day.
* Determine the top 3 most ordered pizza types based on revenue.

### Advanced

* Calculate the percentage contribution of each pizza type to total revenue.
* Analyze the cumulative revenue generated over time.
* Determine the top 3 most ordered pizza types based on revenue for each pizza category.


## Process

The project involved writing and executing various SQL queries to extract and analyze data from a relational database containing information about pizza orders, pizza types, and customer details. The following SQL functions and techniques were utilized:

* **Aggregation:** `COUNT()`, `SUM()`, `AVG()`, `MAX()`, `MIN()` were used to calculate total orders, revenue, average order value, and other key metrics.
* **Joins:** `INNER JOIN` was used extensively to combine data from different tables, such as linking orders with pizza details and customer information.
* **Grouping:** `GROUP BY` was used to aggregate data by different categories, such as pizza type, size, and order date, enabling analysis of sales patterns and trends.
* **Filtering and Sorting:** `WHERE`, `ORDER BY`, and `LIMIT` clauses were used to filter data based on specific criteria, sort results, and focus on top-performing products or time periods.
* **Subqueries:** Subqueries were used to perform calculations within queries, such as finding the highest-priced pizza.
* **Common Table Expressions (CTEs):** CTEs were used to organize complex queries and improve readability, particularly when calculating percentage contributions and average orders.


## Project Insights

* **Total Revenue:** $817,860.05
* **Top Performers:**
    * Thai Chicken Pizza: $43,434
    * Barbecue Chicken Pizza: $42,768
    * California Chicken Pizza: $41,410
* **Sales Trends:** Peak ordering times between 12 PM and 2 PM, with 2,520 and 2,455 orders, respectively.
* **Customer Preferences:** 
    * Most common pizza size ordered: Large (18,526 orders)
    * Highest category in quantity sold: Classic (14,888 pizzas sold)
* **Revenue Distribution:**
    * Thai Chicken Pizza: 5.31% of total revenue
    * Barbecue Chicken Pizza: 5.23% of total revenue
    * California Chicken Pizza: 5.06% of total revenue

## Conclusion

This project successfully demonstrated the use of SQL queries to analyze pizza sales data and extract valuable insights. The findings can be used to make informed business decisions regarding inventory management, marketing campaigns, and menu optimization. Further analysis could involve exploring customer segmentation, analyzing order cancellation rates, and predicting future sales trends.

## Project Files

Due to GitHub’s file size limit (max 25–30 MB), the full project images in PDF format are hosted externally.  
You can view or download them from the link below:

[📄 View Project PDF (Google Drive)](https://drive.google.com/drive/folders/1X7wrERo2IvhYHX-su38VehdvPuJPZXM-?lfhs=2)

> **Note:** This PDF contains all the visuals, screenshots, and analysis outputs used in this project.

