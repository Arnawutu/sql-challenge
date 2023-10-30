This research project involves the creation of a database to store information about individuals employed by Pewlett Hackard during the 1980s and 1990s, with data sourced from six CSV files. The project comprises the following key steps and methods:

Data Modeling:

The initial step involves inspecting the provided CSV files and creating an Entity-Relationship Diagram (ERD) to outline the structure of the database.
Data Engineering:

A table schema is designed for each of the six CSV files, encompassing considerations like data types, primary keys, foreign keys, and constraints.
The uniqueness of primary keys is ensured, or composite keys are created if needed to uniquely identify rows.
Tables are created in the appropriate order to handle foreign key relationships.
CSV files are imported into their respective SQL tables.
Data Analysis:

Several queries are constructed to extract meaningful information from the database. These queries address various aspects of employee data and department management.
Queries include listing employee details, identifying individuals hired in specific years, retrieving manager information, and more.
Tools and Methods Used:

SQL: SQL is used extensively for database creation, data import, and querying.
Jupyter Notebooks: Jupyter Notebooks are employed as a coding environment for running SQL queries.
ERD: An Entity-Relationship Diagram is used to visualize the structure of the database.
Primary Keys: Primary keys are utilized to ensure data integrity and unique identification of records.
Additionally, the project extends beyond data retrieval and includes data visualization and report generation:

Data Visualization:

A histogram is created to visualize common employee salary ranges.
A bar chart illustrating the average salary by job title is generated.
Documentation and Output:

An image file of the ERD is produced to provide a visual representation of the database structure.
.sql files are generated to document the table schemata and SQL queries for future reference and reproducibility.
The overall goal of this project is to effectively manage and analyze Pewlett Hackard's historical employee data to gain insights into the workforce during the 1980s and 1990s. The use of SQL, ERD modeling, and data visualization tools enhances the project's ability to draw meaningful conclusions from the data.
