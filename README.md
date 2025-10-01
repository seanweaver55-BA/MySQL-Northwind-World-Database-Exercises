# SQL Practice Projects – Northwind & World Databases

This repository contains a series of SQL exercises I completed using **MySQL Workbench** on the classic **Northwind** and **World** sample databases.  
The aim of these tasks is to simulate real-world business scenarios and data analysis problems commonly faced by analysts.

---

## Northwind Traders – Beginner SQL Tasks

### 1. Retrieve Full Customer Data
Query to select all columns from the `Customers` table.

<img width="261" height="29" alt="Query Result 1" src="https://github.com/user-attachments/assets/b277fda6-f110-4143-8c02-6a61af8655a8" />

---

### 2. Customer Names and Cities for Marketing
Query to retrieve only `CustomerName` and `City`.

<img width="287" height="59" alt="Query Result 2" src="https://github.com/user-attachments/assets/91f10e5e-ee10-4963-b4ef-6c7e0352afe1" />

---

### 3. Unique Cities for Delivery Network Expansion
Query to return distinct values from the `City` column.

<img width="233" height="59" alt="Query Result 3" src="https://github.com/user-attachments/assets/dc2265a5-d8a9-42fb-97a5-90ad9079155d" />

---

### 4. High-Value Products Report
Products from the `Products` table where `Price > 50`.

<img width="318" height="58" alt="Query Result 4" src="https://github.com/user-attachments/assets/64a1eb27-ad16-4d63-813c-f253f04de378" />

---

### 5. International Customers Targeting (USA & UK)
Customers where the `Country` is either 'USA' or 'UK'.

<img width="322" height="72" alt="Query Result 5" src="https://github.com/user-attachments/assets/3975009b-43a2-46a0-a8d7-bc5c2ab8c81a" />

---

### 6. Recent Orders Report
Orders sorted by `OrderDate` in descending order.

<img width="257" height="75" alt="Query Result 6" src="https://github.com/user-attachments/assets/78ff7539-4ed7-4413-9362-8590d46351fb" />

---

### 7. Mid-Range Products Listing
Products priced between 20 and 50, ordered by descending price.

<img width="263" height="75" alt="Query Result 7" src="https://github.com/user-attachments/assets/42345695-b6e1-46ff-b8e4-b614a1be8107" />

---

### 8. Local Marketing in the US (Portland & Kirkland)
Customers in Portland or Kirkland, ordered by `CustomerName`.

<img width="538" height="80" alt="Query Result 8" src="https://github.com/user-attachments/assets/4fd1da6d-fbc7-4e87-8bec-04569e81719f" />

---

### 9. Customers from the UK or London
Customers where `Country = 'UK'` or `City = 'London'`.

<img width="392" height="76" alt="Query Result 9" src="https://github.com/user-attachments/assets/ec4cdd5a-9b87-4dee-980b-cf9dd658948f" />

---

### 10. Product Inventory for Selected Categories
Products from Category 1 or 2, ordered by `ProductName`.

<img width="287" height="96" alt="Query Result 10" src="https://github.com/user-attachments/assets/d7ac3e34-a7dd-446b-b81d-333c0fb8731e" />

---

# Global Insights — World Database (SQL Practice)

This project demonstrates a series of SQL queries carried out on the classic **World** sample database. Each task explores population, geography, and economic data to answer analytical questions commonly encountered in real-world business and research scenarios.  

---

## Queries Completed

### 1. Counting Cities in the USA
Retrieve the total number of cities recorded in the United States.  
<img src="https://github.com/user-attachments/assets/d33b279c-dcb8-482b-880e-6818144f69ea" alt="Count Cities in USA" width="600"/>

### 2. Country with the Highest Life Expectancy
Identify which country reports the longest life expectancy.  
<img src="https://github.com/user-attachments/assets/889bd768-108d-4f65-a915-b71a65be013e" alt="Country Highest Life Expectancy" width="600"/>

### 3. Cities Containing "New"
Return all cities with the word "New" in their names.  
<img src="https://github.com/user-attachments/assets/e659db3a-62c3-40c9-b359-e70a34455da4" alt="Cities with New" width="600"/>

### 4. Top 10 Most Populous Cities
Use `LIMIT` to display the ten largest cities by population.  
<img src="https://github.com/user-attachments/assets/892a4175-7ec5-4a99-b5bd-f1f721146283" alt="Top 10 Cities" width="600"/>

### 5. Cities Above 2 Million Population
List cities where the population exceeds 2,000,000.  
<img src="https://github.com/user-attachments/assets/31c882ed-f7d6-4d29-8983-0376f85ec946" alt="Cities Over 2M" width="600"/>

### 6. Cities Beginning with "Be"
Retrieve all cities whose names start with the prefix "Be".  
<img src="https://github.com/user-attachments/assets/30a6fcf9-ad66-46b3-ad8f-5bfb639a1aac" alt="Cities Beginning with Be" width="600"/>

### 7. Mid-Sized Cities (500K–1M)
Identify cities with populations ranging between 500,000 and 1,000,000.  
<img src="https://github.com/user-attachments/assets/6a3eb898-7c2b-4396-a5db-7959b337fbb5" alt="Mid-Sized Cities" width="600"/>

### 8. Cities in Alphabetical Order
Display the complete list of cities sorted A–Z.  
<img src="https://github.com/user-attachments/assets/9de9c106-dc1e-43f1-bb55-fcf6835e45f6" alt="Cities Alphabetical" width="600"/>

### 9. Most Populated City
Return the single most populated city in the database.  
<img src="https://github.com/user-attachments/assets/04f6a7b1-13ea-4726-8d9d-67fc17c4b4e0" alt="Most Populated City" width="600"/>

### 10. Frequency of City Names
List unique city names and show how many times each occurs.  
<img src="https://github.com/user-attachments/assets/0b9a25f6-406f-4bb6-85a4-a9ff2b87284d" alt="City Name Frequency" width="600"/>

### 11. City with the Smallest Population
Identify the city with the lowest population value.  
<img src="https://github.com/user-attachments/assets/fe470c40-3441-4ceb-b400-c33332bc2d10" alt="Lowest Population City" width="600"/>

### 12. Country with the Largest Population
Retrieve the country with the highest national population.  
<img src="https://github.com/user-attachments/assets/2f3bcbb8-0c88-4b10-a564-99ec14aa7fcf" alt="Country with Largest Population" width="600"/>

### 13. Capital of Spain
Query the capital city of Spain.  
<img src="https://github.com/user-attachments/assets/0a903232-dff8-40aa-8ad0-ea4739b71523" alt="Capital of Spain" width="600"/>

### 14. Cities in Europe
Return all cities located within European countries.  
<img src="https://github.com/user-attachments/assets/df5786fe-fa4a-4a35-884a-60f0e38cd122" alt="Cities in Europe" width="600"/>

### 15. Average Population per Country
Calculate the mean city population for each country.  
<img src="https://github.com/user-attachments/assets/caf38d40-926c-4f8c-adc3-49ef8d30cb00" alt="Average Population by Country" width="600"/>

### 16. Comparing Capital City Populations
Compare the populations of capital cities across all countries.  
<img src="https://github.com/user-attachments/assets/3e1efc25-b4a0-4ec0-b285-2f9dbdc0b488" alt="Capital Populations" width="600"/>

### 17. Countries with Low Population Density
Identify countries where population density is relatively low.  
<img src="https://github.com/user-attachments/assets/6265648a-b6c6-43cc-bc91-43f51b43db0d" alt="Low Population Density" width="600"/>

### 18. Cities with High GDP per Capita
List cities with GDP per capita values above the global average.  
<img src="https://github.com/user-attachments/assets/d84400eb-6300-4283-9693-1c2a452f5b3a" alt="Cities with High GDP" width="600"/>

### 19. Cities Ranked 31–40 by Population
Display the cities ranked between 31st and 40th in terms of population size.  
<img src="https://github.com/user-attachments/assets/0091eb4f-68fb-4d45-a1c4-e3602e685f30" alt="Cities 31–40 by Population" width="600"/>

---

## Tools Used
- **MySQL Workbench** — for running and testing queries  
- **World Sample Database** — dataset containing countries, cities, and population/economic statistics  


## Tools Used
- **MySQL Workbench** – query writing and execution.  
- **Northwind & World Databases** – structured sample datasets for practice.  

---
