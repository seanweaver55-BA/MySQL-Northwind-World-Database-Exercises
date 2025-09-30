# SQL Practice Projects – Northwind & World Databases

This repository contains a collection of SQL queries and exercises completed using MySQL Workbench. The projects are built on the classic **Northwind** and **World** sample databases and are designed to simulate practical business and data analysis scenarios.

---

## Northwind Traders – Core SQL Tasks

### 1. Retrieve Full Customer Data
Query returning all columns from the Customers table.  
`screenshot`

### 2. Customer Names and Cities for Marketing
Query selecting only CustomerName and City from the Customers table.  
`screenshot`

### 3. Unique Cities for Delivery Expansion
Query using `DISTINCT` to return unique city values from Customers.  
`screenshot`

### 4. High-Value Products
Query retrieving all products with a price above £50.  
`screenshot`

### 5. International Customers (USA & UK)
Query selecting customers where Country = 'USA' or 'UK'.  
`screenshot`

### 6. Recent Orders
Query retrieving all orders ordered by OrderDate descending.  
`screenshot`

### 7. Mid-Range Products
Query filtering products priced between £20 and £50, sorted by descending price.  
`screenshot`

### 8. Local Marketing in the US
Query retrieving customers in Portland or Kirkland (USA), ordered by CustomerName.  
`screenshot`

### 9. Customers from the UK or London
Query selecting customers where Country = 'UK' or City = 'London'.  
`screenshot`

### 10. Product Inventory by Category
Query retrieving products in Category 1 or 2, ordered by ProductName.  
`screenshot`

---

## Northwind – Advanced SQL Tasks

### 1. Products and Suppliers
Query joining Products with Suppliers to identify providers.  
`screenshot`

### 2. Product Categories
Query linking products to their categories.  
`screenshot`

### 3. Meat/Poultry Products
Query selecting all products in the Meat/Poultry category.  
`screenshot`

### 4. Order Overview
Query retrieving OrderID, OrderDate, Customer Name, and Employee Name.  
`screenshot`

### 5. Supply Chain Report
Query joining Product, Category, and Supplier tables.  
`screenshot`

### 6. Orders in 1996
Query retrieving all orders placed in 1996.  
`screenshot`

### 7. Product Count by Category
Query returning categories with their respective product counts.  
`screenshot`

### 8. Sales Volume
Query showing products, prices, and quantities ordered.  
`screenshot`

---

## World Database – Global Insights

### 1. Count Cities in the USA
Query counting total cities where Country = 'USA'.  
`screenshot`

### 2. Country with Highest Life Expectancy
Query selecting the top country by life expectancy.  
`screenshot`

### 3. Cities Containing 'New'
Query filtering city names containing 'New'.  
`screenshot`

### 4. First 10 Most Populous Cities
Query using `LIMIT` to show the top 10 most populous cities.  
`screenshot`

### 5. Cities Over 2 Million Population
Query returning cities with populations above 2,000,000.  
`screenshot`

### 6. Cities Beginning with 'Be'
Query filtering cities starting with 'Be'.  
`screenshot`

### 7. Mid-Sized Cities
Query returning cities with population between 500,000 and 1,000,000.  
`screenshot`

### 8. Cities Sorted Alphabetically
Query ordering cities in ascending alphabetical order.  
`screenshot`

### 9. Most Populated City
Query selecting the city with the highest population.  
`screenshot`

### 10. City Name Frequency
Query counting unique city names and their frequency.  
`screenshot`

### 11. Lowest Population City
Query identifying the city with the smallest population.  
`screenshot`

### 12. Country with Largest Population
Query selecting the most populous country.  
`screenshot`

### 13. Capital of Spain
Query identifying the capital city of Spain.  
`screenshot`

### 14. European Cities
Query selecting all cities located in Europe.  
`screenshot`

### 15. Average Population by Country
Query calculating average city population per country.  
`screenshot`

### 16. Capital City Populations
Query comparing population sizes of capital cities.  
`screenshot`

### 17. Countries with Low Density
Query returning countries with low population density.  
`screenshot`

### 18. High GDP per Capita Cities
Query selecting cities with above-average GDP per capita.  
`screenshot`

### 19. Cities Ranked 31–40 by Population
Query showing cities ranked between 31st and 40th by population.  
`screenshot`

---

## Tools Used
- MySQL Workbench  
- Northwind & World sample databases  

---
