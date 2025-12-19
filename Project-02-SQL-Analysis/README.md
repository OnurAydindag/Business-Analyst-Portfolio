# Project 2: E-commerce SQL Analysis

## 📊 Project Overview
SQL analysis of 31,235 UK retail transactions using PostgreSQL to extract business insights and identify growth opportunities.

## 🎯 Objectives
- Design and populate PostgreSQL database
- Write complex SQL queries for business analysis
- Extract actionable insights from sales data

## 🛠️ Tools Used
- **PostgreSQL 18** - Database management
- **pgAdmin 4** - Query execution  
- **DBeaver** - Data import
- **SQL** - Data analysis

## 📁 Dataset
- **Records:** 31,235 transactions
- **Period:** 2010-2011
- **Customers:** 973 unique
- **Revenue:** £17.8M total

## 🗄️ Database Schema
```sql
CREATE TABLE sales (
    id SERIAL PRIMARY KEY,
    invoice_no VARCHAR(50),
    stock_code VARCHAR(50),
    description VARCHAR(500),
    quantity INTEGER,
    invoice_date VARCHAR(50),
    unit_price NUMERIC(10,2),
    customer_id VARCHAR(50),
    country VARCHAR(100),
    total_price NUMERIC(10,2)
);
```

## 📈 Key Findings

**Top Products:**
- Best Seller: WORLD WAR 2 GLIDERS (5,763 units)
- Top Revenue: CREAM HEART CARD HOLDER (£515,896)

**Customer Insights:**
- 973 total customers
- Top customer: £196,362 lifetime value
- Avg order: £571.41

**Market Analysis:**
- Primary market: United Kingdom
- Total revenue: £17.8M
- Units sold: 381,404
- Most common order: £100-500 range

## 🔍 SQL Analysis (10 Queries)

1. Data validation and quality checks
2. Product performance analysis
3. Geographic sales distribution
4. Customer spending patterns
5. Order value segmentation
6. Monthly sales trends
7. Business metrics dashboard

## 📂 Files
- `ecommerce_analysis.sql` - All queries with documentation
- `ecommerce_cleaned_data.csv` - Cleaned dataset (31,235 records)
- `screenshots/` - Query result visualizations

## 💡 Skills Demonstrated
- PostgreSQL database design
- Complex SQL (GROUP BY, aggregations, CASE statements)
- Business intelligence & insights
- Data analysis & reporting

## 🚀 Business Recommendations
1. Stock priority: High-volume products (WORLD WAR 2 GLIDERS)
2. VIP program: Target customers spending £100K+
3. Market focus: Strengthen UK presence
4. Revenue optimization: Promote high-margin items (CREAM HEART CARD HOLDER)

---

**Completed:** December 19, 2024
