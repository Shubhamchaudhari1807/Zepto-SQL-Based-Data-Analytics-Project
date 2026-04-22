<div align="center">

# 🛒 Zepto SQL Data Analysis Project

<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=amazondynamodb&logoColor=white" />
<img src="https://img.shields.io/badge/pgAdmin-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

<br/>

> **A real-world e-commerce data analytics project** — cleaning, exploring, and extracting business insights from a Zepto-inspired inventory dataset using advanced SQL.

<br/>

[📊 View Queries](#-data-analysis--business-insights) · [🚀 Quick Start](#-quick-start) · [📬 Connect](#-connect-with-me)

</div>

---

## 👨‍💻 About the Author

Hi, I'm **Shubham Chaudhari** — an aspiring **Data Analyst & Full Stack Developer** with a passion for turning raw data into actionable business intelligence. I love crafting optimized SQL queries, uncovering hidden patterns, and thinking like a data-driven problem solver.

---

## 🎯 Project Objective

This project simulates a real-world analytics workflow on an e-commerce inventory dataset modeled after **Zepto** — one of India's fastest-growing quick-commerce platforms.

The goals were to:

- ✅ Design and build a structured SQL database from raw CSV data
- ✅ Perform thorough **data cleaning & transformation**
- ✅ Conduct in-depth **Exploratory Data Analysis (EDA)**
- ✅ Solve **business-critical problems** using advanced SQL queries

---

## 📊 Dataset Overview

Each row in the dataset represents a unique product SKU in Zepto's inventory system.

| Column | Description |
|---|---|
| `sku_id` | Unique Product Identifier |
| `name` | Product Name |
| `category` | Product Category |
| `mrp` | Original / Listed Price (₹) |
| `discountPercent` | Discount Applied (%) |
| `discountedSellingPrice` | Final Selling Price (₹) |
| `availableQuantity` | Units Available in Stock |
| `weightInGms` | Product Weight (grams) |
| `outOfStock` | Stock Availability Status |
| `quantity` | Units per Package |

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐘 **PostgreSQL** | Core database engine |
| 🖥️ **pgAdmin 4** | Database management & query execution |
| 📄 **Excel / CSV** | Raw data handling & initial exploration |
| 🔤 **SQL** | Data cleaning, transformation & analysis |

---

## 🔧 Project Workflow

```
📥 Raw CSV Data
      │
      ▼
🏗️  Database Design & Table Creation
      │
      ▼
📤  Data Import (UTF-8 Encoded)
      │
      ▼
🔍  Data Exploration (EDA)
      │
      ▼
🧹  Data Cleaning & Transformation
      │
      ▼
📊  Business Analysis & Insights
```

### 1️⃣ Database Creation
- Designed relational table structure with appropriate data types
- Applied constraints to ensure data integrity

### 2️⃣ Data Import
- Imported CSV into PostgreSQL via pgAdmin
- Resolved UTF-8 encoding issues for smooth ingestion

### 3️⃣ Data Exploration
- Checked total record count and schema structure
- Identified null values, duplicates, and data inconsistencies
- Analyzed category distribution and stock status

### 4️⃣ Data Cleaning
- Removed entries with zero or null pricing
- Standardized price representation into Indian Rupees (₹)
- Fixed data type mismatches and column anomalies

### 5️⃣ Business Analysis
- Translated stakeholder questions into optimized SQL queries
- Generated category-wise, price-wise, and inventory-based insights

---

## 📈 Data Analysis & Business Insights

Here's a snapshot of the business questions solved through SQL:

| # | Business Problem | SQL Technique Used |
|---|---|---|
| 🔝 | Top discounted products | `ORDER BY`, `LIMIT` |
| 📦 | Out-of-stock high-value items | `WHERE`, filtering |
| 💰 | Revenue estimation by category | `SUM`, `GROUP BY` |
| 🏷️ | Expensive products with low discounts | Conditional filtering |
| 📊 | Category-wise average discount | `AVG`, `GROUP BY` |
| ⚖️ | Price-per-gram analysis | Derived columns, arithmetic |
| 📦 | Inventory distribution insights | Aggregations, `HAVING` |

---

## 🚀 Quick Start

### Prerequisites
- PostgreSQL installed
- pgAdmin 4 (or any SQL client)
- Git

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/shubhamchaudhari1807/zepto-sql-data-analysis.git
cd zepto-sql-data-analysis
```

```sql
-- 2. Create the database in pgAdmin
CREATE DATABASE zepto_analysis;
```

```bash
# 3. Import the dataset
# Open pgAdmin → Select database → Import CSV using the Import/Export tool
```

```sql
-- 4. Run the SQL scripts in order
-- Step 1: table_creation.sql
-- Step 2: data_cleaning.sql
-- Step 3: eda_queries.sql
-- Step 4: business_insights.sql
```

---

## 🧠 Key Learnings

- 🔍 Writing **optimized, production-style SQL** queries
- 🧹 Handling **real-world messy datasets** end-to-end
- 📐 Applying **data cleaning** and transformation best practices
- 💼 Thinking in a **business-first, data-driven** mindset
- 📊 Translating raw numbers into **meaningful insights**

---

## 💼 Why This Project Matters

This project is a testament to practical data analytics skills, not just theoretical knowledge:

- 📌 Real dataset — not a toy problem
- 📌 Business-framed questions — not just queries for the sake of it
- 📌 End-to-end pipeline — from raw CSV to actionable insight
- 📌 Clean, readable SQL — production-grade code quality

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shubham_Chaudhari-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubhamchaudhari1807/)
[![Email](https://img.shields.io/badge/Email-chaudharishubham1807@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chaudharishubham1807@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-shubhamportfoliosite.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://shubhamportfoliosite.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-shubhamchaudhari1807-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shubhamchaudhari1807)

</div>

---

<div align="center">

### ⭐ Found this useful? Give it a star — it keeps me motivated to build more!

*Made with ❤️ and lots of SQL by Shubham Chaudhari*

</div>
