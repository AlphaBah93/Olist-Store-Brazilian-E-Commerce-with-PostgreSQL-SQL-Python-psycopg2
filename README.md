# Olist-Store-Brazilian-E-Commerce-with-PostgreSQL-SQL-Python-psycopg2
**Dataset**: [Olist Store - Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
## 📘 Introduction

This project demonstrates how to use **Python**, the **`psycopg2` API**, and **SQL** to interact with a **PostgreSQL** database for loading, storing, and analyzing data from the Brazilian e-commerce public dataset "Olist", downloaded from Kaggle.

It highlights how Python can be combined with PostgreSQL to:
- Programmatically **create and populate a relational database**
- **Query** data using SQL
- Perform **data analysis and visualization** to extract insights about customer behavior, product performance, shipping logistics, and more.

Whether you're learning about **ETL pipelines**, **SQL joins**, or how to work with a PostgreSQL database through Python, this project serves as a complete hands-on example.

---

## 🗂️ Project Structure (Notebook Sections)

### 1. 📦 Installing and Importing the Necessary Libraries
- Import Python libraries: `psycopg2`, `pandas`, `matplotlib`, `seaborn`, etc.
- Ensure environment is ready for PostgreSQL interaction.

### 2. 🔌 PostgreSQL Connection via psycopg2
- Establish connection to a local PostgreSQL server.
- `psycopg2` is used as the **Python DB-API** for executing SQL queries and managing transactions.

### 3. 🛠️ Table Creation
- SQL `CREATE TABLE` statements executed via Python to structure the relational schema.
- Tables correspond to core CSVs such as `orders`, `customers`, `products`, `payments`, etc.

### 4. 📥 Loading CSV Data into PostgreSQL
- Clean and preprocess CSVs downloaded from Kaggle.
- Use Python + SQL to **insert data into PostgreSQL tables** efficiently.

### 5. 📊 Exploratory Data Analysis (EDA)
- Basic statistics and visualizations using `pandas` and `seaborn`.
- Explore product prices, sales volume, customer states, delivery delays, etc.

### 6. 🔍 Advanced Data Exploration Using SQL Joins and Visualizations
- Execute complex SQL JOIN queries directly from Python to combine and analyze datasets.
- Visualizations created to summarize:
  - Average prices by category
  - Monthly order volume trends
  - Delivery delays by region
  - Customer satisfaction by state

---

## 🧰 Technologies Used

| Component          | Description                                      |
|-------------------|--------------------------------------------------|
| PostgreSQL         | Relational Database Management System (RDBMS)   |
| Python             | Programming Language                            |
| psycopg2           | Python API for PostgreSQL communication         |
| SQL                | Query Language for data manipulation            |
| Pandas             | Data analysis library                           |
| Seaborn/Matplotlib | Data visualization libraries                    |

---

## 🚀 How to Run This Project

1. Clone the repo and download the dataset from Kaggle.
2. Set up a local PostgreSQL server and create a database.
3. Run the Python notebook step-by-step to:
   - Connect to the database via `psycopg2`
   - Create tables and insert data
   - Perform SQL queries and visualizations

---

## 📈 Insights You Can Explore

- Which product categories generate the highest revenue?
- Which states experience the longest delivery times?
- What payment methods are most common?
- How does customer satisfaction vary by location?

---

## 📚 Credits
- **Author**: Alpha Amadou BAH  -  amadalpha93@gmail.com
