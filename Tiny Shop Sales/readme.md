# SQL Case Study : Tiny Shop Sales

[Medium Article link](https://medium.com/@LakshmiKadali/sql-case-study-tiny-shop-sales-10b636cbe00e)

#### Overview

Here is the [link](https://d-i-motion.com/lessons/customer-orders-analysis/) for this SQL Case Study. This case study uses PostgreSQL. To successfully answer all the questions you should have been exposed to the following areas of SQL:

- Basic aggregations
- CASE WHEN statements
- Window Functions
- Joins
- Date time functions
- CTEs


The Tiny Shop sales database contains four tables Products, Customers, Orders, and Order_Items. The Products table contains information about the products, such as its name, price, and quantity in stock. The Customers table stores customer details like their name, email address, and address. The Orders table contains order-specific information of each order, such as the customer who placed the order, the products that were ordered, and the order total. The Order_Items table shows the items in each order, with the order ID, product ID, and quantity.

#### Questions
1. Which product has the highest price? Only return a single row.
2. Which customer has made the most orders?
3. What’s the total revenue per product?
4. Find the day with the highest revenue.
5. Find the first order (by date) for each customer.
6. Find the top 3 customers who have ordered the most distinct products
7. Which product has been bought the least in terms of quantity?
8. What is the median order total?
9. For each order, determine if it was ‘Expensive’ (total over 300), ‘Affordable’ (total over 100), or ‘Cheap’.
10. Find customers who have ordered the product with the highest price.
