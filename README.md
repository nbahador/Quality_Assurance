<h1 style="border: 2px solid #000; padding: 10px; text-align: center;">
  Quality Assurance Interview Questions and Answers
</h1>

### <a id="table-of-contents"></a>Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 7 | [What are the key aspects of ETL workflow validation?](#what-are-the-key-aspects-of-etl-workflow-validation) |
| 1 | [How can you compare database data with extracted CSV data using command-line tools?](#how-can-you-compare-database-data-with-extracted-csv-data-using-command-line-tools) |
| 2 | [How can duplicates be identified in a database table using SQL?](#how-can-duplicates-be-identified-in-a-database-table-using-sql) |
| 9 | [What are the key checks for ensuring data quality in the target system after data is loaded?](#what-are-the-key-checks-for-ensuring-data-quality-in-the-target-system-after-data-is-loaded) |
| 3 | [How can you load a CSV table into a database?](#how-can-you-load-a-csv-table-into-a-database) |
| 4 | [How can I find records that are present in one table but not in another using SQL?](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql) |
| 8 | [What are the key aspects of Target Data Completeness testing?](#what-are-the-key-aspects-of-target-data-completeness-testing) |
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

## What are the key checks for ensuring data quality in the target system after data is loaded?

> **Key checks for ensuring data quality and accuracy:**
> 
> - **Ensuring numeric fields are filled correctly**: Verify that numeric fields contain appropriate values and are correctly populated.
> - **Verifying that not-null fields are populated**: Ensure that all fields that are required to be non-null are properly populated with data.
> - **Performing boundary value, case, and special character validations**: Check for proper handling of boundary values, case sensitivity, and special characters.
> - **Counting updates, inserts, and deletions of records**: Confirm that the correct number of records were updated, inserted, or deleted during the ETL process.
> - **Validating transformations against business rules**: Ensure that any data transformations applied during the ETL process comply with the defined business rules.
> - **Checking change capture logic for slowly changing dimensions (Type 2)**: Verify that Type 2 slowly changing dimensions are accurately capturing changes over time.
> - **Verifying default values and destructive updates (Type 1)**: Confirm that default values are applied correctly and that destructive updates (overwrites) follow proper logic.
> - **Ensuring correct dates, and proper validation for incorrect dates (e.g., February 30th)**: Verify that all dates are accurate and reject invalid dates.
> - **Verifying the correct date format when stored as a string (day/month/year)**: Ensure that date strings follow the correct format (day/month/year) where applicable.
> - **Ensuring no data truncation occurs**: Check that no data is being truncated, especially for fields with length restrictions.
> - **Checking for proper left and right space trimming**: Confirm that unnecessary spaces before or after data are removed.
> - **Confirming correct date format and values for DATE or TIMESTAMP types**: Ensure that DATE or TIMESTAMP fields are correctly formatted and populated.
> - **Testing both positive and negative data**: Test the system with both valid (positive) and invalid (negative) data to ensure robustness.

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

## What are the key aspects of Target Data Completeness testing?

> **Key aspects of Target Data Completeness testing:**
> 
> - **Data Completeness testing ensures that all expected data from the source has been correctly transferred to the target**: Confirm that every record expected from the source system appears in the target.
> - **Reconcile the number of records between the source and the target**: Perform a record count comparison between the source and the target to ensure no data was lost.
> - **Investigate any records that were rejected during the loading process**: Identify and analyze the reason behind any rejected records during ETL.
> - **Check for any duplicate records in the target**: Verify that there are no duplicates in the target data that could affect data integrity.
> - **Verify the integrity of relationships between primary and foreign keys, and ensure the proper formatting of natural keys**: Ensure that the relationships between keys in the target are correct, and that natural keys are properly formatted.

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

