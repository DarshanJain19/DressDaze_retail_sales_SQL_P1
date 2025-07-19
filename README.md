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

Sales on a specific date
→ All transactions on '2022-11-05'

Category-based filtering
→ Clothing category sales with quantity > 4 in November 2022

Category-wise total sales
→ SUM of total_sale grouped by category

Average age of Beauty category buyers

High-value transactions
→ Sales where total_sale > 1000

Gender & Category-based transaction count

Monthly average sale & best-selling month per year

Top 5 customers by total sales

Unique customers by category

Sales shifts analysis
→ Categorized by Morning, Afternoon, and Evening shifts based on sale_time

✅ Sample Query Highlight
sql
Copy
Edit
SELECT category, SUM(total_sale) as total_sales
FROM retail_sales
GROUP BY category;
This returns the total sales generated per product category.

📈 Outcome
This project helps in understanding:

Customer purchasing behavior

Product category performance

Time-based sales patterns

Key performance metrics for business decisions

🙋‍♂️ Author
Darshan Jain
B.Tech CSE Student | Aspiring Data Analyst
📧 [Add your email]
🔗 [Add your LinkedIn or Portfolio]

⭐️ How to Use
Clone this repo

Import the CSV into your local SQL database

Run the SQL script step-by-step to see the analysis

Let me know if you'd like a project thumbnail image, badges, or Markdown formatting tips for GitHub.
