# JDBC
A simple Java JDBC project for database connectivity and basic CRUD operations.

# JDBC Project

A simple Java project that demonstrates database connectivity using JDBC.

## Overview
This project shows how to connect a Java application to a relational database and perform CRUD operations using JDBC.  
It helps understand how Java interacts with databases through SQL queries and JDBC drivers.

## Features
- Connect Java application to database.
- Insert new records.
- Retrieve records from database.
- Update existing records.
- Delete records.
- Use of `PreparedStatement` and `ResultSet`.

## Technologies Used
- Java
- JDBC
- MySQL / PostgreSQL / Any Relational Database
- SQL

## Prerequisites
- Java JDK installed
- Database installed and running
- JDBC driver added to the project
- IDE like IntelliJ IDEA or Eclipse

## Project Structure
```bash
src/
 └── Main.java
```

## How It Works
1. Load the JDBC driver.
2. Create a database connection.
3. Create SQL statements.
4. Execute queries.
5. Process the results.

## Example
```java
Connection con = DriverManager.getConnection(url, user, password);
Statement stmt = con.createStatement();
ResultSet rs = stmt.executeQuery("SELECT * FROM students");
```

## Setup and Run
1. Clone the repository.
2. Add the database driver JAR to the project.
3. Update database credentials in the code.
4. Run the Java program.

## Learning Outcome
- Understand JDBC architecture.
- Learn database connectivity in Java.
- Practice SQL with Java.
- Build CRUD-based applications.

## License
This project is for learning and educational purposes.
