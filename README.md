## 🍽️ Restaurant Order Analysis – SQL Guided Project

✨ <u>About this project</u>

**🎯 Objective** <br>
To analyze restaurant order data using SQL in order to uncover sales trends, customer preferences, and operational insights that support data-driven decision-making.  <br><br>

**🗄️ Database** 
*	SQL Platform: MySQL 
*	Key Tables: menu_items, order_details 
*	Source: Maven Analytics: [Restaurant Orders Analysis](https://mavenanalytics.io/data-playground/restaurant-orders) <br><br>


**🧰 Tools & Skills**
*	SQL (Joins, Aggregations, Suqueries) 
*	Exploratory Data Analysis (EDA)  
*	Consumer Preference and Trend Analysis <br><br>

**⭐ Complete SQL Pipeline: From Raw Data to Business Insights** <br>

**🔍 Exploring menu_items table** <br>

1. View the menu_items table <br>

2. Find the number of items on the menu.
   > Num_items = 32


3. What are the least and most expensive items on the menu?
   > The least expensive item = 'Edamame - $5' <br>
   > The most expensive item = 'Shrimp Scampi - $19.95' <br>

4. How many Itlian dishes are on the menu?
   > Num_Itlian_dishes = 9 <br>

5. What are the least and most expensive Itlian dishes on the menu?
   > The least expensive Itlian dishes = 'Spaghetti - $14.50' <br> 
   > The most expensive Itlian dishes = 'Shrimp Scampi - $19.95' <br>

6. How many dishes are in each category?
   > Num_dishes in each category
![Num_dishes](----) <br>

7. What is the average dish price within each category?
   > Avg_dish_price in each category
![Avg_price](----) <br><br>


**🔍 Exploring order_details table** <br>

1. View the order_details table. <br>
  
2. What is the date range of the table?
   > date_range = '2023-01-01 to 2023-03-31' <br>
   
3. How many orders were made within this date range? 
   > Num_orders = 5,370 <br>

4. How many items were ordered within this date range?
   > Num_order_items = '12234' <br>

5. Which orders had the most number of items? 
   > List of Orders with most number of items
  ![Order_list](----) <br><br>
 
6. How many orders had more than 12 items? 
   > Num_orders with more than 12 items = 20  <br><br>


**🔍 Analyze Customer Behaviour <br>**

1. Combine the menu_items and order_details tables into a single table. 
   > Combining two tables with LEFT JOIN
 ![Combine_two](----) <br><br>

   
2. What were the least and most ordered items? What categories were they in?
   > The least ordered item = 'Hamburger - 622'
   > The most ordered item = 'Chicken Tacos - 123'
 ![List](----) <br><br>

    
3. What were the top 5 orders that spent the most money?
   > List of Top 5 Orders with highest spending
![List](----) <br><br>

4. View the details of the highest spend order. What insights can you gather from the results? 
   > The highest spend order id = 440 <br>
   > 💡: **Italian dishes** contribute the highest order spend, positioning them as top-performing menu items that should be prioritized and consistently maintained. <br>

- Detail View <br>
![Detail_List](----) <br>

- By Category wise <br>
![List](----) <br><br>

5. View the details 0f the top 5 highest spend orders. What insights can you gather from the results? <br>
   > The Top 5 highest spend orders = 440, 2075, 1957, 330, 2675 <br>
   > 💡: Based on the top 5 orders analysis, customers with the highest spending tend to purchase **Italian dishes** despite their higher prices against other categories. This indicates strong demand, suggesting that these high-value Italian items should be retained on the menu. Expanding or promoting Italian dishes could further increase overall order value and profitability. <br>

- Detail View <br>
![Detail_List](----) <br>

👉 [*Please check out SQL Query Code!*]()







