<h1 style="border: 2px solid #000; padding: 10px; text-align: center;">
  Quality Assurance Interview Questions and Answers
</h1>

### <a id="table-of-contents"></a>Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 1 | [How can you compare database data with extracted CSV data using command-line tools?](#how-can-you-compare-database-data-with-extracted-csv-data-using-command-line-tools) |
| 2 | [How can duplicates be identified in a database table using SQL?](#how-can-duplicates-be-identified-in-a-database-table-using-sql) |
| 3 | [How can you load a CSV table into a database?](#how-can-you-load-a-csv-table-into-a-database) |
| 4 | [How can I find records that are present in one table but not in another using SQL?](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql) |

---

## How can you compare database data with extracted CSV data using command-line tools?

> **To compare data from a database and a CSV file:**
> 
> - **Extract data** from the database to a CSV file.
> - Use **diff** (a command-line tool in Linux) to compare the two files.
> 
> ### Example Command:
> ```bash
> diff database_data.csv extracted_data.csv
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---
## How can duplicates be identified in a database table using SQL?

> **To identify duplicates in a database table:**
> 
> - **GROUP BY** groups the rows based on the columns you want to check for duplicates.
> - **COUNT()** counts the occurrences of each group.
> - **HAVING** filters the results to show only groups with a count greater than one, indicating duplicates.
> 
> ### Example Query:
> ```sql
> SELECT X, Y, Z, COUNT(*) 
> FROM A 
> GROUP BY X, Y, Z 
> HAVING COUNT(*) > 1;
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How can you load a CSV table into a database?

> **To load a CSV file into a database:**
> 
> - **BULK INSERT** is used to quickly load data from a file into a table.
> - **FIELDTERMINATOR** specifies the delimiter between fields (e.g., commas for CSV files).
> - **ROWTERMINATOR** specifies the delimiter that separates rows.
> 
> ### Example Query:
> ```sql
> BULK INSERT MyTable FROM 'C:\path\to\file.csv' WITH (FIELDTERMINATOR = ',', ROWTERMINATOR = '\n');
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How can I find records that are present in one table but not in another using SQL?

> **To identify records that exist in one table but not the other:**
> 
> - **MINUS** operator returns rows from the first query that do not exist in the second.
> - **UNION ALL** combines the results of both MINUS queries.
> - This approach identifies unique records that are not found in the other table.
> 
> ### Example Query:
> ```sql
> SELECT * FROM TableA MINUS SELECT * FROM TableB
> UNION ALL
> SELECT * FROM TableB MINUS SELECT * FROM TableA;
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How can you compare database data with extracted CSV data using command-line tools?

> **To compare data from a database and a CSV file:**
> 
> - **Extract data** from the database to a CSV file.
> - Use **diff** (a command-line tool in Linux) to compare the two files.
> 
> ### Example Command:
> ```bash
> diff database_data.csv extracted_data.csv
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

