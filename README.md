# 🏪 Superstore Sales Data Warehouse

Transform raw Superstore sales data into a normalized PostgreSQL database for analytics and business intelligence.

## 🚀 Project Overview

This project implements an **ETL pipeline** that extracts data from a CSV dataset, transforms it into a structured format, and loads it into PostgreSQL using **Python** and **SQLAlchemy**. The goal is to enable fast, reliable analytics and create a foundation for BI dashboards.

## 🛠 Tech Stack

- **Python**: Pandas, SQLAlchemy, Jupyter Notebook  
- **PostgreSQL**: Relational Database  
- **SQL**: Data Modeling, Queries, Views  

## 📌 Workflow

### 1. Database Setup
- Create PostgreSQL database: `superstore_db`  
- Establish Python → PostgreSQL connection via SQLAlchemy  

### 2. Data Modeling
- Identify core entities:
  - `Orders`
  - `Customers`
  - `Products`
  - `Categories`
  - `Regions`
- Define tables, primary keys, and foreign keys  
- Apply normalization (1NF → 2NF → 3NF)  

### 3. ETL Process
- Clean and split CSV data into normalized tables  
- Load data into PostgreSQL using SQLAlchemy  
- Verify integrity and relationships of inserted data  

### 4. Analytics & Transformations
- Calculate business metrics:
  - Total Sales per Product / Category / Region  
  - Average Profit per Order / Customer  
- Create SQL views for fast reporting and analysis  

### 5. Visualization Preparation
- Ensure all relevant data is in the database  
- Confirm relational integrity for smooth joins  

## 📊 Key Metrics
- **Total Sales per Product**  
- **Total Sales per Category**  
- **Total Sales per Region**  
- **Average Profit per Order**  
- **Average Profit per Customer**  

## 📂 Project Files
| File | Description |
|------|-------------|
| `superstore.csv` | Original raw dataset |
| `SQLALCHEMY_PROJECT.ipynb` | ETL pipeline and database operations |
| `documentation.pdf` | Project documentation |

## 🎯 Objective

Build a structured, **normalized database** from raw sales data to enable business analysis, reporting, and dashboard creation.

---
