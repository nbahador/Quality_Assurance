<h1 style="border: 2px solid #000; padding: 10px; text-align: center;">
  Quality Assurance Interview Questions and Answers
</h1>

### <a id="table-of-contents"></a>Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 7 | [What are the key aspects of ETL workflow validation?](#what-are-the-key-aspects-of-etl-workflow-validation) |
| 1 | [How can you compare database data with extracted CSV data using command-line tools?](#how-can-you-compare-database-data-with-extracted-csv-data-using-command-line-tools) |
| 2 | [How can duplicates be identified in a database table using SQL?](#how-can-duplicates-be-identified-in-a-database-table-using-sql) |
| 3 | [How can you load a CSV table into a database?](#how-can-you-load-a-csv-table-into-a-database) |
| 4 | [How can I find records that are present in one table but not in another using SQL?](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql) |
| 8 | [What are the key aspects of target data completeness testing?](#what-are-the-key-aspects-of-target-data-completeness-testing) |
| 5 | [How can you compare flat files and tables using the Linux command line?](#how-can-you-compare-flat-files-and-tables-using-the-linux-command-line) |
| 6 | [What are the key validations for testing ETL target objects structure?](#what-are-the-key-validations-for-testing-etl-target-objects-structure) |


---

## What are the key aspects of ETL workflow validation?

> **Key aspects of ETL workflow validation:**
> 
> - **Test that the workflow can run successfully**: Ensure the workflow loads data correctly from source to target, including scripts and parameter files.
> - **Test workflow execution dependencies**: Validate the proper execution order and dependencies between tasks in the workflow.
> - **Verify the generation of success or failure email notifications**: Check if email notifications are sent based on workflow success or failure.
> - **Verify ETL logs**: Ensure that logs are generated and contain the necessary details for troubleshooting and auditing.
> - **Validate ETL control tables**: Verify the accuracy and completeness of control tables used in the ETL process.
> - **Measure ETL workflow execution time**: Ensure that the ETL workflow completes within the expected time frame for efficiency.

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

## What are the key aspects of target data completeness testing?

> **Key aspects of target data completeness testing:**
> 
> - **Validate that all expected source data has been successfully loaded to the target**: Ensure all data from the source system is captured and loaded into the target.
> - **Perform records reconciliation between source and target (record counts)**: Compare the number of records in the source and target to ensure they match.
> - **Investigate and analyze rejected records**: Examine any records that were rejected during the ETL process to identify potential issues.
> - **Verify the presence of duplicate records**: Check that there are no unexpected duplicates in the target data.
> - **Check data referential integrity**: Ensure that primary and foreign key relationships are intact, and validate the format of natural keys.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How can you compare flat files and tables using the Linux command line?

> **To compare flat files and tables:**
> 
> - **Extract data** from both the database and the flat file in the same format (e.g., CSV).
> - Use **diff**, a Linux command, to compare the two files.
> 
> ### Example Command:
> ```bash
> diff extracted_file.csv flat_file.csv
> ```

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key validations for testing ETL target objects structure?

> **Key validations for testing ETL target objects structure:**
> 
> - **Verify table and column names**: Ensure the table and column names in the target match the expected names.
> - **Check column data types and lengths**: Confirm that column data types and lengths align with the source data and business requirements.
> - **Confirm "Not Null" constraints**: Ensure all required columns have the correct "Not Null" constraints applied.
> - **Validate primary key constraints**: Verify the correct primary key constraints are in place for ensuring uniqueness.
> - **Ensure foreign key constraints**: Ensure foreign key constraints are correctly implemented to maintain data relationships.
> - **Verify flat file structure**: For flat files, ensure the structure (fields, delimiters) is consistent with the expected format.
> - **Check all required data elements from the business template**: Confirm that all data elements required by the business are present and correctly mapped.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

