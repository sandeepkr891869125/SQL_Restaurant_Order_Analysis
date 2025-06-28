# SQL_Restaurant_Order_Analysis using MySQL

## Overview
This project aimed to analyze
1. Sales pattern, revenue generation & identify top selling items
2. customer preferences, ordering habits, and identify popular menu categories.

## Steps Taken:
1. **Database Creation**: A new database named `restaurant_db` is created.

2. **Table Creation**: Two tables - `menu_items`, and `order_details` - are defined within the database. Two tables are designed to store information about menu, and order details respectively.

3. **Enabling Local File Loading**: The script sets a system variable to enable the loading of data from local files into the database tables.

4. **Data Loading**: Data is loaded from local CSV files into the corresponding database tables. The script specifies the delimiters used in the CSV files to correctly parse the data.

## Insights
* Menu items range in price from $5 to $19.95, accommodating various budget preferences
* Despite a richer varities of Mexican and Italian dishes, the most popular choices belong to the American and Asian categories
* Edamame is the least expensive and shrimp scampi is the most expensive menu item
* Items like chicken tacos, potstickers, cheese lasagna, and steak tacos are among the least ordered items
* Items like hamburgers, edamame, Korean beef bowl, cheese burger and French fries are most ordered items
* Highest spend orders tend to be spending a lot on Italian food.
