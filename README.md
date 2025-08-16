# Online Sales Database

## 📌 Overview
This project contains a sample MySQL database **`onlinesales`** designed to demonstrate sales trend analysis using SQL aggregation functions.  
It includes a single table **`online_sales`** with data for each month of the year 2023.

---

## 📂 Dataset Structure
**Table Name:** `online_sales`  

| Column Name  | Data Type       | Description |
|--------------|----------------|-------------|
| `order_id`   | INT             | Unique order identifier |
| `order_date` | DATE            | Date when the order was placed |
| `amount`     | DECIMAL(10,2)   | Total value of the order |
| `product_id` | INT             | Product identifier |

---

## 📊 Sample Data
| order_id | order_date | amount  | product_id |
|----------|------------|---------|------------|
| 1001     | 2023-01-05 | 120.50  | 1 |
| 1002     | 2023-01-15 | 250.00  | 2 |
| ...      | ...        | ...     | ... |

---

## 📥 Importing the Dataset
1. Save the SQL file in your desired folder.
2. Open **Command Prompt** and run:
   ```bash
   mysql -u root -p your_database_name < online_sales.sql
