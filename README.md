
# SQL Retail & Sales Analysis Project

## Overview
This project was completed during a Data Technician Bootcamp and demonstrates the use of SQL to query, analyse, and extract insights from retail and sales datasets. Using databases such as Northwind, I developed SQL queries to retrieve, filter, aggregate, and combine data from multiple tables to support business reporting and decision-making.

## Project Objectives
- Analyse retail, customer, product, and sales data using SQL.
- Extract meaningful insights from relational databases.
- Apply filtering, sorting, aggregation, and table relationships to answer business questions.
- Develop practical database querying skills used in data analytics and business intelligence.

## Key Skills Demonstrated

### Data Retrieval
- Used `SELECT` statements to retrieve data from multiple database tables.
- Selected individual columns and complete datasets depending on reporting requirements.
- Applied aliases to improve query readability.

### Data Filtering
- Used `WHERE` clauses to filter records based on business criteria.
- Applied conditional operators such as:
  - `=`
  - `>`, `<`
  - `BETWEEN`
  - `IN`
  - `LIKE`
  - `AND` / `OR`
- Targeted specific customer groups, products, orders, and locations.

### Data Sorting
- Utilised `ORDER BY` to organise query results.
- Sorted sales, order, and customer data in both ascending and descending order.
- Improved report usability by ranking results based on key metrics.

### Data Aggregation
- Used `GROUP BY` to summarise business data.
- Applied aggregate functions including:
  - `COUNT()`
  - `SUM()`
  - `AVG()`
 
  COUNT() = How many things there are

  SUM() = Adds numbers together
  
  AVG() = Finds the average amount

  Examples below -

  <img width="292" height="41" alt="image" src="https://github.com/user-attachments/assets/9d3ed53b-1cc2-4d16-b103-88feff61e292" />
  <img width="258" height="38" alt="image" src="https://github.com/user-attachments/assets/c7c72089-abd6-40d7-a643-20c7f077bfe3" />
  <img width="298" height="31" alt="image" src="https://github.com/user-attachments/assets/ab10d908-06cc-4874-b0ac-536275fb608e" />



  
- Generated reports showing product counts, sales volumes, and category-level insights.

### Table Relationships & JOINs
- Worked with relational databases using table keys and relationships.
- Performed:
  - `INNER JOIN`
  - `LEFT JOIN`
  - `RIGHT JOIN`
  - `FULL JOIN`
  - `CROSS JOIN`
- Combined customer, order, product, supplier, and category data to create business-focused reports.

<img width="492" height="104" alt="image" src="https://github.com/user-attachments/assets/19aad736-1a85-41d5-86b0-988f12f0c3b9" />

This is a clear example of a left join and its breakdown

<img width="336" height="25" alt="image" src="https://github.com/user-attachments/assets/2bfa4f88-a9af-492c-90a3-4406d38f0676" />

- selects the customers name and thier order id.

<img width="116" height="32" alt="image" src="https://github.com/user-attachments/assets/b3faf99b-4969-4c62-b6f2-69115ac113c9" />
 
- selecting from the customers table.

<img width="129" height="25" alt="image" src="https://github.com/user-attachments/assets/934a7734-dd4c-4069-983b-dbb6b377cfe7" />

- connects the orders table to the customers table (a left join means to keep every customer even if they dont have an order).

<img width="332" height="24" alt="image" src="https://github.com/user-attachments/assets/3c0d385b-4e73-4d9c-ac02-16aa05fbf934" />

- this tells SQL how to connect the tables, it then matches up customers where their customerid is the same in both tables.

### Customer Order Analysis

This query identifies customers who have not placed any orders.

A `LEFT JOIN` is used to keep all customers, including those without a matching record in the `Orders` table. The `WHERE orderid IS NULL` condition then filters the results to show only customers with no orders.

The results are sorted alphabetically using `ORDER BY`.

**Conclusion:**
This query could be useful for identifying inactive customers. A business could use this information to understand which customers have not made a purchase and potentially target them with marketing or customer engagement activities.





<img width="272" height="174" alt="Screenshot 2026-08-12 141847" src="https://github.com/user-attachments/assets/46792da1-79c2-41f5-8bd6-fd69c603b15f" />

This is clear example of a full outer join and its breakdown. 





<img width="629" height="259" alt="image" src="https://github.com/user-attachments/assets/45002825-bfa0-4be5-a668-af67f8579276" />



## Example Business Questions Answered
- Which products generate the highest sales volumes?
- Which suppliers provide specific products?
- How many products exist within each category?
- Which customers placed orders during a specific period?
- Which product categories contribute most to sales activity?
- How can customer and order data be combined to create complete sales reports?

- Grouping and Summarisation
- Multi-Table Queries
- JOIN Operations
- Query Optim
