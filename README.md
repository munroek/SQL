# SQL
Covering topics related to SQL

Here, I will be keeping track of my progess in regards to refreshing myself with SQL.

The topics that will be covered are:

Uses cases/design of relational databases and SQL
Setting up a local database
Creating, modifying, and deleting databases and their tables
SQL Data types and their constraints(primary key, foreign key)
Create, Read, Update, and Delete(CRUD) operations
Exporting and importing  data from relational databases

# What is a Relational Database?

As defined by [Oracle](https://www.oracle.com/database/what-is-a-relational-database/#:~:text=A%20relational%20database%20is%20a%20type%20of%20database%20that%20stores%20and%20provides%20access%20to%20data%20points%20that%20are%20related%20to%20one%20another.%20Relational%20databases%20are%20based%20on%20the%20relational%20model%2C%20an%20intuitive%2C%20straightforward%20way%20of%20representing%20data%20in%20tables.), a relational database stores and provides access to data points that are related to one another.

* The data is stored in tables where each table contains a set of columns used to specify the type of data. 
* The data is stored as rows inside the database tables. This can also be referred to as records.
* Create, Read, Update and Delete, also referred to as CRUD are operations that are supported by the tables. We are able to create the data, have access to it in order to read it, update or edit the data, 
* and to also delete it. 
* Tables can be connected to other tables utilizing relationship constraints.
* We use the Structured Query Language (SQL) to retrieve information from the database

# Installing the MySQL Server and Workbench

## Windows

[MySQL Community Download](https://dev.mysql.com/downloads/windows/installer/8.0.html)

Under the Setup Type, we'll want to select "Custom". 

!()

Next, we'll want to select the workbench and server. Make sure, they're the most recent ones. Expand MySQL Servers by selecting the plus, and keep expanding them until you come across MySQL Server 8.0.33 - X64. The version might be different in the future. Once you have it selected, select the arrow pointing towards the empty box. 

You will do the same thing for the Workbench. Scroll down the list in the left box until you get to where it says Applications. Keep expanding the list until you come across MySQL Workbench 8.0.33 - X64. Select it, and press the right arrow once more. The right box should now be populated with the workbench and server.

Click Next.

## Mac/Linux

