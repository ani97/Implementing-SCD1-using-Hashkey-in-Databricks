# 📦 SCD Type 1 Implementation with Databricks, Delta Lake & Azure SQL

This project demonstrates an end-to-end **Slowly Changing Dimension Type 1 (SCD1)** pipeline built on **Databricks** using **Delta Lake** and **Azure SQL Database**. The pipeline handles customer order data, performs transformations, and executes an upsert (overwrite) using a hash key.

---

## 🚀 Features

- Connect to Azure SQL using JDBC
- Drop duplicates and clean null values
- Add hash key to detect changes
- Filter only "Shipped" orders
- Create Delta table if not exists
- Perform **SCD1 Merge (Upsert)** into Delta Table

---

## 🛠️ Technologies Used

- **Databricks**
- **Apache Spark (PySpark)**
- **Delta Lake**
- **Azure SQL Database**
- **JDBC Connection**
- **SQL + Python integration**
