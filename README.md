## 🍽️ Restaurant Order Analysis – SQL Guided Project

✨ <u>About this project</u>

**🎯 Objective** <br>
To analyze restaurant order data using SQL in order to uncover sales trends, customer preferences, and operational insights that support data-driven decision-making.  <br><br>

**🗄️ Database** <br>
*	SQL Platform: MySQL 
*	Key Tables: menu_items, order_details 
*	Source: Maven Analytics: [Restaurant Orders Analysis](https://mavenanalytics.io/data-playground/restaurant-orders) <br><br>


**🧰 Tools & Skills** <br>
*	SQL (Joins, Aggregations, Suqueries) 
*	Exploratory Data Analysis (EDA)  
*	Consumer Preference and Trend Analysis <br><br>

**⭐ Complete SQL Pipeline: From Raw Data to Business Insights** <br>
🔍 Exploring menu_items table <br>

-- 1. View the menu_items table
SELECT * FROM menu_items;
-- 2. Find the number of items on the menu.
SELECT COUNT(*) FROM menu_items;
-- 3. What are the least and most expensive items on the menu?
SELECT 
    *
FROM
    menu_items
ORDER BY price;

SELECT 
    *
FROM
    menu_items
ORDER BY price DESC;
-- 4. How many Itlian dishes are on the menu?
SELECT 
    COUNT(*)
FROM
    menu_items
WHERE category = 'Italian';
-- 5. What are the least and most expensive Itlian dishes on the menu?
SELECT 
    *
FROM
    menu_items
WHERE category = 'Italian'
ORDER BY price;

SELECT 
    *
FROM
    menu_items
WHERE category = 'Italian'
ORDER BY price DESC;

-- 6. How many dishes are in each category?
SELECT 
    category,
    COUNT(item_name) AS number_of_dishes
FROM
    menu_items
GROUP BY category
ORDER BY category;

-- 7. What is the average dish price within each category?
SELECT 
    category, 
    AVG(price) AS avg_price
FROM
    menu_items
GROUP BY category
ORDER BY category;






6.2.1 Rating Analysis <br>
 ![Rating 1](https://github.com/thwaythwayhtet/Airbnb-Performance-Dashboard/blob/main/Images/Rating%20Analysis%201.png) <br>
