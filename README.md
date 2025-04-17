
/README.md
Elevate_labs_task_7
🧮 Task 7 - Sales Summary using SQLite and Python
📌 Objective
Analyze a sales dataset using SQL in Python and generate a basic sales summary with:

Total quantity sold per product
Total revenue per product
🛠 Tools Used
Python (Google Colab)
SQLite (sqlite3)
pandas
matplotlib
📁 Dataset
The dataset used was sales_data_sample.csv, which contains product-level sales data.

🔧 What I Did
Uploaded the CSV file to Google Colab.
Loaded the dataset into a pandas DataFrame.
Created a SQLite database and inserted the data as a table.
Ran a SQL query to calculate:
Total quantity sold (SUM(QUANTITYORDERED))
Total revenue (SUM(QUANTITYORDERED * PRICEEACH))
Printed the result and plotted a bar chart showing revenue per product.
Saved the chart as sales_chart.png.
📊 Sample Output
  product  total_qty     revenue
0  S10_1678        230     33089.80
1  S10_1949        200     30800.00
...
