
# Basic Sales Summary from SQLite Database

## Overview
This project demonstrates how to use **Python** with **SQLite** to:
- Create a sample sales database (if not already existing).
- Insert sample sales records.
- Run SQL queries to retrieve total quantity sold and total revenue per product.
- Display results using print statements.
- Plot a simple bar chart for revenue by product.

## Features
1. **Table Creation**: Creates `sales` table if it doesn't exist.
2. **Sample Data Insertion**: Inserts multiple rows of sample data if the table is empty.
3. **SQL Queries**:
   - `SELECT COUNT(*) FROM sales;` → Check if table has data.
   - `SELECT product, SUM(quantity) AS total_qty, SUM(quantity * price) AS revenue FROM sales GROUP BY product ORDER BY revenue DESC;` → Sales summary.
4. **Visualization**: Generates a bar chart showing revenue by product.
5. **Data Output**: Prints total sales summary and breakdown by product.

## Requirements
- Python 3.x
- pandas
- matplotlib





