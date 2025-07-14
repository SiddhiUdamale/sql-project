# E-Commerce Data Analysis Using Python & MySQL

This project performs end-to-end data analysis on an e-commerce dataset using Python, MySQL, and Jupyter Notebook. It includes SQL queries for data aggregation and Python for data manipulation and visualization.

---

## Project Overview

- Imported and cleaned multiple CSV datasets using `pandas`
- Created tables and inserted data into a MySQL database
- Performed basic to advanced SQL queries for insights
- Visualized key metrics using Seaborn and Matplotlib

---

## Tech Stack

| Tool/Tech         | Purpose                     |
|-------------------|-----------------------------|
| Python            | Data processing, scripting  |
| Pandas            | Data manipulation           |
| MySQL             | Database and SQL queries    |
| Seaborn/Matplotlib| Data visualization          |
| Jupyter Notebook  | Development environment     |

---

## Features

- Load and transform CSV data into MySQL
- Analyze customer behavior and sales trends
- Generate insights using complex SQL queries
- Visualize cumulative revenue, customer growth, and product category performance

---

## Sample Queries

- Total revenue by product category
- Average products per order per city
- Customer retention rate (within 6 months)
- Moving average of order value over time
- Year-over-year growth rate

---

## Files

- `ecommerce_analysis.ipynb` – Notebook containing data loading, SQL execution, and visualizations
- `.csv` files – Raw datasets -https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv
- `README.md` – This file

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/SiddhiUdamale/sql-project.git
   cd sql-project
2. Make sure MySQL server is running, and create a database:
CREATE DATABASE ecommerce;

3. Run the Jupyter notebook:
jupyter notebook ecommerce_analysis.ipynb

4. Install dependencies (if needed):
pip install pandas mysql-connector-python matplotlib seaborn
