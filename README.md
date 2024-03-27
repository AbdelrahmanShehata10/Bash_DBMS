Database Management System (DBMS) Project in Bash Shell Script

Summary: The goal of the Bash Shell Script Database Management System (DBMS) project is to create a command-line interface (CLI) programme that enables users to utilise bash scripting to save and retrieve data from the hard drive. In addition to building, listing, dropping, inserting into, selecting from, removing from, and updating rows in tables, the project will include functionality for creating, listing, connecting to, and dropping databases.

Features of the project:

Primary Menu:

Make Database: This feature lets users make new databases.
List Databases: Presents an inventory of current databases.
Link To Database: Enables users to establish a connection to a certain database.
Drop Database: Enables users to remove a database that already exists.
Database Menu: After establishing a connection to a certain database, users will be able toto the menu that follows:

Create Table: Allows users to add a new table to the database that is connected.
List Tables: Shows a list of the tables that are present in the database that is linked.
Drop Table: This feature lets users remove a table from the database that's linked.
Add Rows to Table: Enables the addition of new rows to a table.
Select From Table: Based on predetermined criteria, this method retrieves and presents rows from a table.
Delete From Table: Uses a set of criteria to remove rows from a table.
Update Row: Adjusts current rows in a table according to predetermined criteria.
Specifics of Implementation:

Database Storage: In relation to the script file's location, databases will be kept as directories. We won't rely on absolute pathways to guarantee portability.

Table Storage: Files containing tables will be kept in amay be in the file formats CSV, JSON, or XML. The table's raw data and metadata may be kept in the same file or in several files.

Metadata: Information about the table, including its name, number of columns, and column names, is kept when a table is created.


Main Key: selected by the user.

Data Types: To guarantee data integrity, user input will be checked based on the data types (digits or strings) of the columns.

Data Display: For simplicity of comprehension, the results of select queries will be displayed in a human-readable manner.

Usage: To use the DBMS, run the script file and utilise the command-line interface to browse the menu selections. Observe the instructions to establish, link to, andengage with tables and databases.

Making a contribution: We encourage your involvement in the project. You are welcome to fork the repository, edit it, and send pull requests.



Contact: [Abdelrhman Shehata] may be reached at [eng.abdelrhman.shehata1@gmail.com] with any questions or comments.

Acknowledgments: [Heba Hasan] is especially appreciated for her invaluable efforts and resources, which greatly aided in the project's progress.
# Bash_DBMS
