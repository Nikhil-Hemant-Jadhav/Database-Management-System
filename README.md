# Database Management System (DBMS) Replica - Java

## Overview

This Java project aims to replicate the features of a Database Management System (DBMS) with a Command User Interface. It focuses on one specific database as an example, providing implementations for various queries to perform operations on that database. The project serves as an educational tool to enhance understanding of the internal workings of a DBMS.

## Technology: Java Programming

The entire project is developed using the Java programming language.

## User Interface: Command User Interface (CUI)

The project employs a Command User Interface to interact with users, providing a text-based interface for input and output.

## Features

- Replication of DBMS functionalities.
- Implementation of various queries.
- Operations performed on a specific example database.

## How to Use

1. **Compile Java Files:**
   - Compile the Java files before executing the project.

   ```bash
   javac DBMSMain.java QueryProcessor.java
   ```

2. **Run the Application:**
   - Execute the project using the appropriate Java command.

   ```bash
   java -cp . DBMSMain
   ```

3. **Interact with the Command User Interface:**
   - Follow the on-screen instructions to input queries and interact with the simulated DBMS.

## Example Queries

- Various types of SQL queries are implemented, including SELECT, INSERT, UPDATE, DELETE, etc.

```sql
-- Example SELECT query
SELECT * FROM employees WHERE department = 'IT';

-- Example INSERT query
INSERT INTO employees VALUES (101, 'John Doe', 'IT', '2022-01-24');

-- Example UPDATE query
UPDATE employees SET salary = 60000 WHERE employee_id = 101;

-- Example DELETE query
DELETE FROM employees WHERE employee_id = 101;
```

## Notes

- This project is intended for educational purposes to provide insight into DBMS functionalities.
- The example database used in this project is for illustrative purposes.

## Contributors

- Nikhil Hemant Jadhav
## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

## Support

For any questions or issues, please contact [nj820201@gmail.com].

Thank you for using the DBMS Replica in Java!
