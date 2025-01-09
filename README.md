# Scalable-Inventory-Management-System
An overview of the project with a breakdown of the repositories that follow

Project Title:

Scalable Inventory Management System

Overview:

This project provides a comprehensive solution for managing inventory in small businesses, addressing key challenges such as overstocking, understocking, and inefficiencies in order tracking and invoicing. The system leverages both relational and NoSQL databases for optimal performance, scalability, and flexibility.

Features:

Entity Design: Conceptualized with EER and UML class diagrams to model entities and relationships, ensuring robust database design.
Relational Database Implementation: Built in MySQL with normalized tables and data integrity maintained through primary/foreign keys.
Data Analysis and Visualization: Python scripts with Matplotlib and Seaborn provide insights into inventory trends and supplier performance.
NoSQL Integration: Implemented MongoDB collections for hierarchical data representation and fast query processing.
Real-World Sample Data: Populated with realistic datasets generated using Python’s Faker library to test and validate functionalities.
Technical Stack:

Programming Languages: Python, SQL
Libraries and Tools: Pandas, Matplotlib, Seaborn, Faker, PyMongo
Databases: MySQL, MongoDB
Key Functionalities:

Relational Database:
Designed relational tables for entities like Suppliers, Products, Sales Orders, and Customers.
Addressed many-to-many relationships through associative tables.
SQL queries to validate database structure and retrieve actionable insights.
Data Visualization:
Histogram of low-stock products.
Pie chart of product categories in inventory.
Bar chart of average purchase prices by supplier.
NoSQL Implementation:
Created collections for core entities in MongoDB.
Used aggregation pipelines and lookups for data analysis.
Challenges and Considerations:

Ensuring referential integrity and data uniqueness across relational and NoSQL databases.
Balancing query performance with complex relationships in NoSQL.
Future Enhancements:

Automating stock alerts based on thresholds.
Incorporating supplier review mechanisms.
Index optimization for faster query execution.

Diagram Links


[EER Diagram](https://drive.google.com/file/d/14V0hYe_WkELJt8NoJ3BoR70lky1WEs6m/view?usp=sharing)

[UML Class Diagram](https://drive.google.com/file/d/1Ywtvez0WN6AF_KvXJBlyTlepOMPY1DO-/view?usp=sharing)

Repository Structure:

/SIMS-sql_scripts: SQL queries for creating and populating MySQL tables.

/SIMS-data_generation: Python scripts using Faker for sample data.

/SIMS-visualizations: Python scripts for data analysis and visualizations.

/SIMS-nosql: MongoDB collection setup and queries.
