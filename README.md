# Day7

 ##SQLite3 Analysis Project
 #Project Overview

This project demonstrates how to use SQLite3 with Python for database operations and perform Exploratory Data Analysis (EDA) using Pandas, Matplotlib, and Seaborn.
The dataset contains information about books, including their title, price, and copies sold.
The goal is to understand sales trends and relationships between variables.

## Steps Performed
1. Database Connection:
- Connected to SQLite3 database using Python.
- Created and connected to a database file.

2. Table Creation & Data Insertion:
_ Created a table to store book details.
_ Inserted records (book title, price, and number of copies sold).

3. Fetching Data with SQL Queries:
- Used SELECT queries to extract data from SQLite database.
- Loaded the extracted data into a Pandas DataFrame for analysis.

4. Data Analysis & Visualization:
- Explored the dataset using Pandas (head(), describe(), info()).
- Created visualizations to analyze sales patterns:
- Bar Plot: Showing book titles vs copies sold.
- Scatter Plot: Relationship between price and copies sold.
- Distribution Plot: Spread of book prices.


📊 Insights from Analysis:

- Some books had significantly higher sales compared to others.
- Higher price books generally had fewer copies sold, indicating a negative relationship between price and demand.
- Distribution of book prices showed clustering around mid-range values.

📚 Libraries Used:
- sqlite3 → For database connection and queries
- pandas → For handling tabular data
- matplotlib → For data visualization
- seaborn → For advanced visualizations
