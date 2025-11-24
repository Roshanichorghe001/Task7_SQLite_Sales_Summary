# Task7_SQLite_Sales_Summary
Task 7 – Data Analyst Internship | Sales summary using SQLite &amp; Python (SQL + Pandas + Bar Chart)
# Task 7 – Sales Summary from SQLite Database using Python

This task uses a small SQLite database (`sales_data.db`) and Python to generate a basic sales summary.  
The purpose is to practice SQL queries inside Python and visualize simple results.

## ✔ Steps Completed

1. **Created SQLite database** with a "sales" table.
2. **Inserted sample data** (product, quantity, price).
3. **Connected Python to the database** using sqlite3.
4. **Ran SQL query** to calculate:
   - Total quantity sold per product  
   - Total revenue (quantity × price)
5. **Loaded the SQL result into pandas.**
6. **Printed the summary table.**
7. **Plotted a simple bar chart** showing revenue by product.
8. **Saved the chart as `sales_chart.png`.**

## ✔ Files in this Repository

- `Task7_SalesSummary.ipynb` – Jupyter Notebook with all Python code  
- `sales_data.db` – SQLite database file  
- `sales_chart.png` – Generated bar chart  
- `README.md` – Task explanation  

## ✔ Requirements

- Python  
- sqlite3  
- pandas  
- matplotlib  

## ✔ Output

The SQL query outputs a table with:  
- Product  
- Total Quantity  
- Revenue  

The bar chart visualizes revenue for each product.
