# 🎯 Quality Assurance Interview Questions and Answers 🎯

### Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 1 | [How can duplicates be identified in a database table using SQL?](#how-can-duplicates-be-identified-in-a-database-table-using-sql) |
| 2 | [How can I find records that are present in one table but not in another using SQL?](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql) |

---

## <a id="how-can-duplicates-be-identified-in-a-database-table-using-sql"></a>How can duplicates be identified in a database table using SQL?

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

**[ Back to the question in the Table ⬆ ](#how-can-duplicates-be-identified-in-a-database-table-using-sql)**

---

## <a id="how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql"></a>How can I find records that are present in one table but not in another using SQL?

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

**[ Back to the question in the Table ⬆ ](#how-can-i-find-records-that-are-present-in-one-table-but-not-in-another-using-sql)**
