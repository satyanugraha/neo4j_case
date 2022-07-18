# neo4j_case


### 1. Data Modelling in Arrows - Northwind.json
Implement exploration process to determine Nodes and Relationships. From observation, I found 6 key-join between tables.

Nodes:
1. Product 
2. Category
3. Supplier
4. Customer
5. Order
6. Employee

Relationship
1. PART_OF
2.SUPPLIES
3. PURCHASED
4. ORDERS
5. CASHIER
6. REPORTS_TO

![Northwind](https://user-images.githubusercontent.com/9002772/179548331-99ebec85-6c6e-4853-83a0-2830afe82754.png)

### 2. Import Northwind Data to Neo4j with Python - Neo4j-Northwind.ipynb

1. Setup Connection to local Neo4j Browser
2. Load table into Pandas Dataframe
3. Import Nodes with each Properties
4. Import Relationships
5. Convert date string to date

### 3. Exploratory Cypher Query in Neo4j Browser

Business questions:
1. What is the best selling product?
2. Who is selling most of the products?
3. Which employee have the most subordinate?
