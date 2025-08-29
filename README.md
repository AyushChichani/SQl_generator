# SQl_generator
SQL_generator from plain english

🔍 SQL Query Generator

Convert plain English statements into SQL queries instantly!

📌 Overview
The SQL Query Generator is a lightweight web application built using HTML, CSS, and JavaScript. It helps users—especially beginners—translate natural English queries into valid SQL statements like SELECT, INSERT, UPDATE, and DELETE.

Example:
Input: “Show all users where age is greater than 25”
Output:
SELECT * FROM users WHERE age > 25;

🚀 Features

Transform plain English → SQL queries.
Supports SELECT, INSERT, UPDATE, DELETE.
Handles conditions (WHERE, ORDER BY, AND/OR).
Copy-to-clipboard functionality.
Responsive, modern UI with example queries.
Fully browser-based (no server required).

🛠️ Technologies Used

HTML5 – Structure of the interface
CSS3 – Modern styling with responsive design
JavaScript (Regex + Logic) – Query parsing and generation

📖 How to Use

Open index.html in your browser.
Enter a table name, choose a query type, and type your query in plain English.
Click Generate SQL Query to see the result.
Copy the query using the Copy button.

📂 Project Structure
├── sql_generator.html   # Main application file
└── README.md    # Project documentation

🎯 Future Improvements

Add support for JOIN queries & aggregate functions (SUM, COUNT, AVG).
Voice-to-query input for accessibility.
Direct connection with a database (MySQL/PostgreSQL).
Export generated queries.
