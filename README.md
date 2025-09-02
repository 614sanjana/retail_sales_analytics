# Retail Sales Trend and Performance Analysis – Python & SQL

**Technologies:** Python, Pandas, SQL, SQLAlchemy  

This repository showcases an **end-to-end data analytics project** on a Kaggle retail orders dataset. The project demonstrates the full workflow of data extraction, cleaning, transformation, SQL-based analysis, and actionable business insights generation.

---

## Project Overview

- Extracted datasets from Kaggle using the **Kaggle API**.
- Processed CSV files using **Pandas**: handled null values, renamed columns, and created derived features like discount, sale price, and profit.
- Converted string date columns into **datetime objects** for analysis.
- Loaded cleaned and transformed data into **SQL Server** using **SQLAlchemy**.
- Performed SQL-based analysis to answer key business questions.

---

## Key Business Questions Answered

- **Top Revenue Products:** Identified the top 10 highest revenue-generating products.  
- **Regional Sales Analysis:** Top 5 selling products per region.  
- **Month-over-Month Growth:** Compared sales trends across months and years.  
- **Category Analysis:** Determined highest selling categories and highest growth subcategories.  

---

## Workflow / Process

1. **Data Extraction:** Downloaded datasets from Kaggle using API commands.  
2. **Data Cleaning & Transformation:**  
   - Handled missing and inconsistent values.  
   - Renamed columns to snake_case.  
   - Derived new columns: discount, sale price, profit.  
3. **Data Loading:** Loaded processed data into SQL Server for query-based analysis.  
4. **SQL Analysis:** Ran queries to answer business questions on revenue, sales trends, and product performance.  
5. **Insights Generation:** Analyzed query results to identify actionable insights for business decisions.  

---

## Repository Structure

- `orders.csv` – Original dataset downloaded from Kaggle.  
- `data_cleaning.ipynb` – Python notebook for cleaning, transforming, and preparing data for SQL.  
- `sql_queries.sql` – SQL queries answering business questions.  
- `README.md` – Project overview and workflow.  

---

## Insights / Results

- Top-selling products and categories identified.  
- Month-over-month sales growth highlighted key trends.  
- Regional sales performance comparison for strategic planning.  
- Profit and revenue analysis for business decision-making.

---

## How to Run

1. Clone this repository.  
2. Install required Python packages: `pandas`, `sqlalchemy`, `kaggle`.  
3. Run the Python notebook to clean and transform the dataset.  
4. Load the cleaned dataset into SQL Server.  
5. Execute SQL queries in `sql_queries.sql` to reproduce business insights.


