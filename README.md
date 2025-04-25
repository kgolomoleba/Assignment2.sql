This SQL query retrieves specific records from the ExpenseTracker database.

It demonstrates the use of:

SELECT to display specific columns (ExpenseID, Category, Description, Amount, Date)

WHERE clause to filter results based on:

Wildcards (%) for partial matching in Category and Description

Logical operators (AND, OR, NOT) for complex filtering

A comparison operator (Amount > 100) to only show higher-value expenses

ORDER BY to sort the results by most recent date first (DESC)

🧪 How to Run
Open your SQL client or database management tool (e.g., MySQL Workbench, phpMyAdmin, DBeaver).

Connect to your database that contains the ExpenseTracker table.

Run the SQL script file (Assignment2.sql) provided.

✅ Expected Output
The query should return:

All expense entries where the category contains "food" or description contains "transport"

Only entries where the amount is greater than 100

Excludes the category "Entertainment"

Sorted by the latest date on top
