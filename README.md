# BinaryDBConsole
# My Simple Binary File Database

My Simple Binary File Database is a simple database implementation that uses binary files to store and manage data. It allows users to define tables with desired columns and a primary key, and perform various operations on the data stored in these tables.

## Project Overview

The project consists of the following components:

1. **Metadata File:** This binary file stores information about the table structure, such as column names, data types, and the primary key.

2. **Records File:** This binary file stores the actual records of the table. Each record corresponds to a row in the table and contains values for each column.

3. **Index File:** This binary file stores index information based on the primary key. It allows for efficient searching and retrieval of records based on the primary key.

## Project Operations

The following operations can be performed on a table:

a. **Create/Insert a Record:** Allows the user to insert a new record into the table.

b. **Read/Search a Record (without using index):** Retrieves a record based on a given primary key without utilizing the binary index file.

c. **Read/Search a Record (with using index):** Retrieves a record based on a given primary key using the binary index file.

d. **Update a Record (without using index):** Updates a record based on a given primary key without utilizing the binary index file.

e. **Update a Record (with using index):** Updates a record based on a given primary key using the binary index file.

f. **Delete a Record (without using index):** Deletes a record based on a given primary key without utilizing the binary index file.

g. **Delete a Record (with using index):** Deletes a record based on a given primary key using the binary index file.

i. **Order Records (without using index):** Orders all records in the table according to the given primary key without utilizing the binary index file.

j. **Order Records (with using index):** Orders all records in the table according to the given primary key using the binary index file.



## Guidelines and Restrictions

- Reading and writing the entire object into a file is not allowed to minimize the file size.
- The project aims to keep the file sizes as minimal as possible while ensuring efficient data storage and retrieval.

## Getting Started

To get started with the My Simple Binary File Database project, follow these steps:



```shell
1. Clone the repository:

git clone https://github.com/theprelior/BinaryDBConsole.git

2.Compile and run the project using your preferred Java development environment.

3.Follow the instructions displayed on the console to create tables and perform various operations on the data.

Compile and run the project using your preferred Java development environment.

Follow the instructions displayed on the console to create tables and perform various operations on the data.
