# SQLite-Sales-Summary
Basic Sales Summary using SQLite in Python
# Task 7: Basic Sales Summary using SQLite in Python

## 📌 Objective
To create a basic sales summary by calculating total quantity sold and total revenue for each product using SQL inside Python.

---

## 🛠 Tools Used
- Python
- SQLite (sqlite3)
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Files
- Task7_SQLite_Sales_Summary.ipynb
- sales_data.db
- sales_chart.png

---

## 📊 SQL Query Used

SELECT product,
SUM(quantity) AS total_qty,
SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;

---

## 📈 Output
- Calculated total quantity sold for each product
- Calculated total revenue for each product
- Created bar chart showing revenue by product

---

## 📝 Observations
- Mobile has highest quantity sold.
- Laptop generated highest revenue.
- Tablet has moderate sales performance.

---

## 📌 Conclusion
This project demonstrates how SQL can be integrated with Python to extract, analyze, and visualize data using SQLite database.
