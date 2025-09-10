# Task 6: Basic Sales Summary with SQLite and Python

## 📌 Overview
This project demonstrates how to connect Python with a small SQLite database (`sales_data.db`), run simple SQL queries to get sales information, and visualize the results using a bar chart.

## 🛠 Tools Used
- **Python** (with `sqlite3`, `pandas`, `matplotlib`)
- **SQLite** (built into Python, no extra installation needed)

## 📂 What the Script Does
1. **Creates** a SQLite database (`sales_data.db`) with a table called `sales`.
2. **Inserts** some sample data (products, quantity, price).
3. **Runs** an SQL query to calculate:
   - Total quantity sold per product  
   - Total revenue (quantity × price) per product
4. **Loads** the results into a Pandas DataFrame for easy handling.
5. **Prints** the results in a simple table format.
6. **Plots** a bar chart showing revenue by product and saves it as `sales_chart.png`.

## ▶️ How to Run
1. Save the script as `Task_6_DA.ipynb`.
2. Run it in your terminal or Jupyter Notebook:
   ```bash
   python Task_6_DA.ipynb
