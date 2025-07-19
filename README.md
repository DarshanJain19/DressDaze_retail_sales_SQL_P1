🛍️ Dressdaze Retail Sales Analysis (SQL Project)
This project is a SQL-based data analysis of retail sales for a fictional store named Dressdaze. It demonstrates how to clean, explore, and derive business insights from transactional sales data using SQL.

📂 Project Structure
Dressdaze_Retail_Sales_Analysis_SQL_project.sql: SQL file containing all queries used for table creation, data cleaning, exploration, and analysis.

Dressdaze_SQL_Retail_Sales_Analysis_utf.csv: Sample dataset used for the analysis in .csv format (UTF-8 encoded).

🧰 Tools Used
SQL (PostgreSQL)

🧼 Data Cleaning
Before analysis, the dataset is checked for and cleaned of:

NULL values across all fields

Inconsistent date/time formats

Invalid entries in categorical fields (like gender, category)

🔍 Data Exploration
Initial exploration included:

Counting total transactions

Identifying number of unique customers

Listing all available product categories

📊 Key Business Questions Answered
The following insights were derived using SQL:

-- Q.1 Write a SQL query to retrieve all columns for sales made on '2022-11-05
-- Q.2 Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 10 in the month of Nov-2022
-- Q.3 Write a SQL query to calculate the total sales (total_sale) for each category.
-- Q.4 Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.
-- Q.5 Write a SQL query to find all transactions where the total_sale is greater than 1000.
-- Q.6 Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.
-- Q.7 Write a SQL query to calculate the average sale for each month. Find out best selling month in each year
-- Q.8 Write a SQL query to find the top 5 customers based on the highest total sales 
-- Q.9 Write a SQL query to find the number of unique customers who purchased items from each category.
-- Q.10 Write a SQL query to create each shift and number of orders (Example Morning <=12, Afternoon Between 12 & 17, Evening >17)

📈 Outcome
-This project helps in understanding:
-Customer purchasing behavior
-Product category performance
-Time-based sales patterns
-Key performance metrics for business decisions

🙋‍♂️ Author
Darshan Jain
B.Tech CSE Student | Aspiring Data Analyst
📧 darshanjain1904@gmail.com
🔗 linkedin.com/in/darshanjain19

⭐️ How to Use
-Clone this repo
-Import the CSV into your local SQL database
-Run the SQL script step-by-step to see the analysis.
