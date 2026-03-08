# sql-query-generator_
# SQL Query Generator using Natural Language

## Project Overview

The SQL Query Generator is an intelligent system that converts natural language queries into SQL queries automatically. The goal of this project is to make database interaction easier for users who do not have knowledge of SQL. Users can simply type a question in plain English, and the system generates the appropriate SQL query.

This project demonstrates how artificial intelligence can bridge the gap between human language and database query languages.

## Features

* Converts natural language questions into SQL queries
* Easy-to-use web interface
* Secure query validation to avoid unsafe SQL commands
* Supports structured database schema
* Generates optimized SELECT queries for data retrieval

## Technologies Used

* Python
* Gradio
* SQLite
* Google Colab
* IBM Granite 3.3 2B Instruct

## Project Structure

```
sql-query-generator
│
├── sql_query_generator.ipynb
├── sql_query_generator.py
├── requirements.txt
└── README.md
```

## How It Works

1. The user enters a natural language query.
2. The AI model processes the input.
3. The system converts the text into a valid SQL query.
4. The generated SQL query can then be executed on the database.

## Example

User Input:

```
Show all active users from India
```

Generated SQL Query:

```
SELECT * FROM users
WHERE country = 'India'
AND status = 'active'
LIMIT 10;
```

## Installation

Clone the repository:

```
git clone https://github.com/your-username/sql-query-generator.git
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the application:

```
python sql_query_generator.py
```

## Future Improvements

* Support for multiple database types
* More advanced query understanding
* Improved UI for better user interaction
* Integration with larger AI models

## Conclusion

This project shows how natural language processing and artificial intelligence can simplify database querying. By converting human language into SQL queries, the system makes data access more accessible for beginners and non-technical users.
