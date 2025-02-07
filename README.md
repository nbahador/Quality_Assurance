<h1 style="border: 2px solid #000; padding: 10px; text-align: center;">
  Quality Assurance Interview Questions and Answers
</h1>

### <a id="table-of-contents"></a>Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 18 | [What’s the difference between a test case and a bug report, and how do you write a good bug report?](#whats-the-difference-between-a-test-case-and-a-bug-report-and-how-do-you-write-a-good-bug-report) |
| 17 | [What is the difference between a good test case and a bad test case?](#what-is-the-difference-between-a-good-test-case-and-a-bad-test-case) |
| 16 | [Why should tasks be automated?](#why-should-tasks-be-automated) |
| 14 | [What are the key checks for ensuring target data quality and accuracy?](#what-are-the-key-checks-for-ensuring-target-data-quality-and-accuracy) |
| 13 | [What are the key checks for ensuring target data completeness?](#what-are-the-key-checks-for-ensuring-target-data-completeness) |
| 12 | [What is the purpose of checking ETL logs?](#what-is-the-purpose-of-checking-etl-logs) |
| 11 | [What is the purpose of testing success/failure emails in a process?](#what-is-the-purpose-of-testing-successfailure-emails-in-a-process) |
| 10 | [What is the purpose of testing dependencies in workflows?](#what-is-the-purpose-of-testing-dependencies-in-workflows) |
| 7 | [What are the key aspects of ETL workflow validation?](#what-are-the-key-aspects-of-etl-workflow-validation) |
| 1 | [How can you compare database data with extracted CSV data using command-line tools?](#how-can-you-compare-database-data-with-extracted-csv-data-using-command-line-tools) |
| 2 | [How can duplicates be identified in a database table using SQL?](#how-can-duplicates-be-identified-in-a-database-table-using-sql) |
| 9 | [What are the key checks for ensuring data quality in the target system after data is loaded?](#what-are-the-key-checks-for-ensuring-data-quality-in-the-target-system-after-data-is-loaded) |
| 3 | [How can you load a CSV table into a database?](#how-can-you-load-a-csv-table-into-a-database) |
| 4 | [How can I find records that are present in one table but not in another using SQL?](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql) |
| 8 | [What are the key aspects of Target Data Completeness testing?](#what-are-the-key-aspects-of-target-data-completeness-testing) |
| 5 | [How can you compare flat files and tables using the Linux command line?](#how-can-you-compare-flat-files-and-tables-using-the-linux-command-line) |
| 6 | [What are the key validations for testing ETL target objects structure?](#what-are-the-key-validations-for-testing-etl-target-objects-structure) |
| 15 | [What are Slowly Changing Dimensions (SCD), and how can they be managed?](#what-are-slowly-changing-dimensions-scd-and-how-can-they-be-managed) |

---

## What’s the difference between a test case and a bug report, and how do you write a good bug report?

> **A test case** is used to verify the steps for testing a specific functionality to ensure it works as expected.  
> **A bug report**, on the other hand, focuses on reproducing the steps to identify and describe a bug.

> **Writing a good bug report**:
> - **Be clear and concise**: Start with a descriptive but short title, such as "Menu button doesn’t work on the home screen." This title tells the team exactly what’s wrong and where it happens.
> - **Provide a brief explanation**: Include a short description if necessary to clarify the issue.
> - **List the steps to reproduce**: Clearly describe the steps needed to recreate the bug.
> - **Include visuals**: Add short GIFs (6-7 seconds), screenshots with arrows, or a video clip (15-20 seconds) to demonstrate the steps if they are complex.
> - **Make the bug easy to understand and reproduce**: The goal is to ensure that the team can easily replicate the issue to troubleshoot effectively.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the difference between a good test case and a bad test case?

> **A bad test case** is one that is difficult to follow. If you give it to someone else, they should be able to repeat the steps exactly and get the same result. If they can't, the test case is poorly written.

> **A good test case** is clear, detailed, and easy to follow. It should be structured in a way that anyone can execute it with minimal confusion and get consistent results.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## Why should tasks be automated?

> **Tasks should be automated** because manual, repetitive tasks consume a lot of time and are prone to human error. Automation increases efficiency and reduces the chances of mistakes. Some examples of tasks that should be automated include:

> - **Data Entry**: Automating tasks like copying and pasting or moving data.
> - **Email Responses**: Automatically sending similar responses to customers.
> - **Report Generation**: Automating the creation of regular reports or the analysis of data trends.
> - **Inventory Updates**: Automatically updating stock levels or order statuses.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key checks for ensuring target data quality and accuracy?

> **Key checks for ensuring target data quality and accuracy:**
> 
> - **Ensuring that the loaded data meets quality standards**: Validate that there is no invalid data, such as "John Doe" in numeric fields.
> - **Verifying that not-null fields are populated**: Ensure required fields, such as the "Email" field, are filled for every customer.
> - **Checking numeric data accuracy**: Confirm that fields like "Total_Sales" contain accurate numbers without rounding errors.
> - **Ensuring there are no unnecessary spaces in data values**: Remove spaces before or after data values, such as "John Doe".
> - **Verifying that date fields have the correct format and values**: Ensure fields like "Order Date" follow the "YYYY-MM-DD" format.
> - **Performing boundary value testing**: Test extreme values like ensuring the "Age" field can handle values like 0 and 120.
> - **Ensuring case sensitivity is handled correctly**: Check that case sensitivity works, such as distinguishing "John" from "john".
> - **Verifying that special characters are properly loaded**: Ensure that characters like "$" and "%" are accurately handled.
> - **Checking for data truncation**: Ensure no data is truncated, such as verifying that a 15-digit phone number is fully loaded.
> - **Testing both valid and invalid data**: Test with both valid and invalid data to ensure correct system behavior, like rejecting invalid emails.
> - **Validating that data transformations follow business rules**: Ensure transformations, like calculating "Amount" as "Quantity * Unit Price", are accurate.
> - **Ensuring default values are applied when data is missing**: Confirm that default values, like "Unknown" for missing "Region", are correctly applied.
> - **Checking that update logic works**: Ensure the system properly updates old records, like replacing a customer's old email with a new one.
> - **Ensuring slowly changing dimensions add new records and mark old ones as expired**: Verify that updates to customer details, like address changes, are handled correctly.
> - **Verifying the number of records inserted, updated, or deleted**: Ensure the record count matches the expected number of changes.
> - **Ensuring all dates are accurate and correctly formatted**: Reject invalid dates, such as "2022-02-29".

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key checks for ensuring target data completeness?

> **Key checks for ensuring target data completeness:**
> 
> - **Verifying that all source data is loaded into the target system**: Ensure that all records, like "Sales" data, are correctly transferred to the "Reporting" system.
> - **Comparing record counts between the source and target systems**: Confirm that the record count in both systems match, such as having 1000 records in both source and target.
> - **Investigating rejected records**: Examine why records were rejected and not loaded, like missing customer information in "Order" records.
> - **Checking for duplicate records**: Ensure no duplicates are present, such as making sure each "Customer_ID" appears only once in the target system.
> - **Ensuring data integrity by verifying relationships between tables**: Check the integrity of relationships, like ensuring every "Order_ID" in the "Order Details" table has a matching "Order_ID" in the "Orders" table.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the purpose of checking ETL logs?

> **The purpose of checking ETL logs:**
> 
> - To review the logs and ensure no errors occurred during the ETL process.
> - For example, checking for any failed rows, missing data, or unexpected issues that might have occurred during the load.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the purpose of testing success/failure emails in a process?

> **The purpose of testing success/failure emails in a process:**
> 
> - To ensure that appropriate emails are sent when the process finishes, whether it succeeds or fails.
> - For example, if the data load fails, an error email should be sent to the team to notify them of the issue.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the purpose of testing dependencies in workflows?

> **The purpose of testing dependencies in workflows:**
> 
> - To ensure that tasks in the workflow run in the correct order, with dependent tasks completed first.
> - For example, ensuring that the "Data Cleaning" step runs before the "Data Load" step to maintain data integrity.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

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

## What are Slowly Changing Dimensions (SCD), and how can they be managed?

> **Slowly Changing Dimensions (SCD)** refer to data that does not change frequently, such as a customer’s address or name.

> There are three ways of SCD management:

> - **Overwriting Old Data**: Use this when you only need the most recent data and do not need to keep the historical record.
>   When data changes, the old value is replaced with the new one, with no record of the old value.  
>   *Example*: If a customer moves, the old address is replaced with the new one, and no trace of the old address remains.

> - **Creating a New Record**: Best when you need to preserve the complete history of changes over time.
>   When data changes, a new record is created, and both the old and new values are stored, often with dates showing when each value was valid.  
>   *Example*: If a customer moves, a new record is added with the new address, and the old address remains in the system along with the valid dates.

> - **Tracking Old and New Values**: Useful if you need to store both the current and previous values but not the entire history.
>   The old and new values are stored in the same record. The old value is saved in one field, while the new value is kept in the main field.  
>   *Example*: If a customer changes their email, the old email is stored in a separate column, and the new email is placed in the main email field.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---
