
# Pizza Sales Analysis

This project analyzes pizza sales data using SQL and Power BI to extract insights into sales performance and customer preferences.

## Tools Used
- **SQL** for data extraction, cleaning, and analysis.
- **Power BI** for data visualization.

## SQL Highlights
- Data cleaning and preprocessing.
- Revenue and sales trend analysis.
- Identifying best-selling pizzas.
- Customer behavior insights using aggregation and joins.

### Example Query
```sql
-- Calculate Total Revenue by Pizza Type
SELECT p.pizza_type, SUM(o.quantity * p.price) AS total_revenue
FROM orders o
JOIN pizzas p ON o.pizza_id = p.pizza_id
GROUP BY p.pizza_type
ORDER BY total_revenue DESC;
```

## How to Run
1. Clone the repository.
2. Execute the SQL scripts on your database.
3. Import the dataset into Power BI.
4. Visualize the insights using dashboards.



