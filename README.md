# Retail_sales_Analysis
🛒 Retail Sales Analysis using SQL  This project focuses on analyzing retail sales data using MySQL. It covers data import, cleaning, exploration, and answers key business questions using SQL queries.

📁 Project Structure.
- `SQL - Retail Sales Analysis_utf.csv`: Raw dataset file used in this project.
- `project.sql`: Contains all SQL commands used for database creation, data checks, and analysis.

## 🗂️ Dataset Overview
The dataset contains retail transaction data with the following fields:

- `transactions_id`
- `sale_date`
- `sale_time`
- `customer_id`
- `gender`
- `age`
- `category`
- `quantiy`
- `price_per_unit`
- `cogs`
- `total_sale`

🔧 Steps Performed
1. **Database Setup**
   - Create and use the `RETAIL` database.
   - Create the `RETAIL` table schema.

2. **Data Import**
   - Load data from the CSV file into MySQL.
   - Verify successful data import.

3. **Data Cleaning**
   - Check for `NULL` values in all columns.

4. **Data Exploration**
   - Total sales records
   - Unique customers
   - Unique product categories

📊 Business Questions Answered

- 🗓️ Retrieve all sales made on a specific date
- 👕 Sales in specific categories with filters (e.g. quantity, month)
- 💰 Total sales per category
- 👤 Average age of customers by category
- 💵 High-value transactions (above ₹1000)
- 👨‍👩‍👧‍👦 Transactions grouped by gender and category
- 📈 Best-selling months each year (using `RANK()` window function)
- 🥇 Top 5 customers by total sales
- 🔍 Unique customers by category
- 🕓 Orders per shift: Morning, Afternoon, Evening

⚠️ Notes
- Ensure you are using **MySQL 8.0+** for window functions like `RANK()`.
- Date and time parsing depends on proper format in CSV file.
