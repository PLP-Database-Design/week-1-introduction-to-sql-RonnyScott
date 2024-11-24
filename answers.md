1. State and Explain the components of a DBMS(Database Management System)
	A Database Management System is a software system that enables users to define, create, maintain and control access to databases

	Components:
Database Engine:
The core component responsible for managing and accessing the data stored in the database. It handles tasks like storage, retrieval, and updating of data.

Database Schema:
The structure that defines the organization of data, including tables, views, indexes and relationships.

Query Processor:
Interprets and executes SQL queries. It translates user queries into a format that the DBMS can understand and execute, optimizing the queries for faster performance.

Data Dictionary:
A repository of metadata which includes details about the structure, constraints, relationships and properties of the data stored in the database.

Transaction Management:
Ensures that all database operations are executed in a consistent, isolated and durable manner, handling operations like commits and rollbacks.

Security Management:
Controls access to the database, ensuring only authorized users can access or modify the data. This includes authentication and authorization.

Backup and Recovery:
Provides mechanisms for creating backups and restoring the database in case of system failure or data loss.


2. What is a relational database? Give 4 examples.
A Relational Database is a type of database that stores data in tables known as relations, where each table consists of rows called tuples and columns with attributes. These tables can be related to each other through primary keys and foreign keys, allowing the data to be queried and manipulated efficiently 

Examples of Relational Databases:

	1. MySQL
	2. PostgreSQL
	3. Oracle Database
	4. Microsoft SQL Server


3. State and Explain three classifications of SQL?
Data Definition Language:
DDL is used to define and manage the structure of a database, such as creating, altering, and deleting tables and schemas.
Examples: CREATE, ALTER, DROP, TRUNCATE

Data Manipulation Language (DML):
DML is used to manage and manipulate the data within the tables. It allows inserting, updating, and deleting data.
Examples: SELECT, INSERT, UPDATE, DELETE

Data Control Language (DCL):
DCL is used to define the permissions and access control for the database and its objects.
Examples: GRANT, REVOKE


4. What is the difference between a Primary Key and a Foreign Key?
Primary Key:
A primary key is a field in a table that uniquely identifies each record. It must be unique and cannot contain NULL values.

Foreign Key:
A foreign key is a field in one table that refers to the primary key in another table, establishing a relationship between the two tables.


5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram is a visual representation of the relationships between entities in a database. It helps in designing and understanding the structure of a database. It consists of entities, relationships, and attributes.


6. What are the advantages of relational databases?
- Data Integrity: Relational databases use constraints like primary keys, foreign keys, and unique keys to ensure data consistency and integrity.
- Flexibility: SQL provides a powerful query language that allows users to retrieve, update, and manage data flexibly and efficiently.
- Normalization: Data is normalized in relational databases to reduce redundancy and improve data integrity.
- Scalability: Relational databases can handle large volumes of data and are scalable to accommodate growing datasets.
- Security: Advanced security features allow for user-level access control, ensuring that only authorized users can access or modify data.


7. State four types of data type used to store data in tables?
- Integer
- Varchar
- Date/Time
- Boolean


8. What is the purpose of a database management system (DBMS)?
The purpose of a Database Management System is to provide a systematic and efficient way to store, manage, and retrieve data. A DBMS ensures that data is organized in a structured manner, supports multi-user access, provides mechanisms for data security, backup, and recovery and allows for data manipulation using queries. 