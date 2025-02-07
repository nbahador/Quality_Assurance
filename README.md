<h1 style="border: 2px solid #000; padding: 10px; text-align: center;">
  Quality Assurance Interview Questions and Answers
</h1>

### <a id="table-of-contents"></a>Table of Contents - Quality Assurance

| No. | Questions |
| --- | --------- |
| 91 | [What is deliverability testing?](#what-is-deliverability-testing) |  
| 90 | [What is negative testing?](#what-is-negative-testing) |  
| 89 | [What is frontend testing?](#what-is-frontend-testing) |  
| 88 | [What is database testing?](#what-is-database-testing) |  
| 87 | [What are test artifacts in software testing?](#what-are-test-artifacts-in-software-testing) |  
| 86 | [What are the key types of software testing?](#what-are-the-key-types-of-software-testing) |  
| 85 | [What are boundary validation, range checks, threshold checks, and data truncation in data quality assurance?](#what-are-boundary-validation-range-checks-threshold-checks-and-data-truncation-in-data-quality-assurance) |  
| 84 | [What are constraint violations in databases, and how do they impact data integrity?](#what-are-constraint-violations-in-databases-and-how-do-they-impact-data-integrity) |  
| 83 | [What are the different types of testing?](#what-are-the-different-types-of-testing) |  
| 82 | [What is the purpose of Cogito SQL in reporting?](#what-is-the-purpose-of-cogito-sql-in-reporting) |  
| 81 | [How does MongoDB differ from relational databases?](#how-does-mongodb-differ-from-relational-databases) |  
| 79 | [What role does ETL play in data processing?](#what-role-does-etl-play-in-data-processing) |  
| 78 | [What are common UI issues in web applications?](#what-are-common-ui-issues-in-web-applications) |  
| 77 | [Why is regression testing crucial in software development?](#why-is-regression-testing-crucial-in-software-development) |  
| 76 | [How does workflow validation improve process execution?](#how-does-workflow-validation-improve-process-execution) |  
| 75 | [What factors affect email deliverability and user experience?](#what-factors-affect-email-deliverability-and-user-experience) |  
| 74 | [How do failed network requests impact an application?](#how-do-failed-network-requests-impact-an-application) |  
| 72 | [What are common test operations in data validation?](#what-are-common-test-operations-in-data-validation) |  
| 70 | [What should be included in test reports for analysis?](#what-should-be-included-in-test-reports-for-analysis) |  
| 69 | [What is fault tolerance in a system?](#what-is-fault-tolerance-in-a-system) |  
| 68 | [What is refactoring in software development?](#what-is-refactoring-in-software-development) |  
| 67 | [What should be included in a well-written bug report?](#what-should-be-included-in-a-well-written-bug-report) |  
| 64 | [What’s the difference between backend testing and frontend testing?](#whats-the-difference-between-backend-testing-and-frontend-testing) |  
| 63 | [What is the difference between smoke, sanity, regression, and other types of testing?](#what-is-the-difference-between-smoke-sanity-regression-and-other-types-of-testing) |  
| 61 | [What are the common HTTP methods used for retrieving, creating, and updating resources?](#what-are-the-common-http-methods-used-for-retrieving-creating-and-updating-resources) |  
| 60 | [What is the Red-Green-Refactor cycle in Test-Driven Development (TDD)?](#what-is-the-red-green-refactor-cycle-in-test-driven-development-tdd) |  
| 59 | [What steps do you follow when testing a database to ensure data accuracy and integrity?](#what-steps-do-you-follow-when-testing-a-database-to-ensure-data-accuracy-and-integrity) |  
| 58 | [What are the key types of queries used in database testing?](#what-are-the-key-types-of-queries-used-in-database-testing) |  
| 57 | [What is the difference between functional and non-functional testing in database testing?](#what-is-the-difference-between-functional-and-non-functional-testing-in-database-testing) |
| 56 | [What tool can be used to measure performance and load test web applications?](#what-tool-can-be-used-to-measure-performance-and-load-test-web-applications) |  
| 55 | [What is json-server, and how does it help with API testing?](#what-is-json-server-and-how-does-it-help-with-api-testing) |  
| 54 | [What are some open-source tools for browser automation, API testing, accessibility, security, and monitoring?](#what-are-some-open-source-tools-for-browser-automation-api-testing-accessibility-security-and-monitoring) |  
| 53 | [How do database scaling techniques like replication and sharding address performance challenges?](#how-do-database-scaling-techniques-like-replication-and-sharding-address-performance-challenges) |  
| 52 | [How does GitHub Actions automate workflows?](#how-does-github-actions-automate-workflows) |  
| 51 | [What is TestGrid and what are its key features?](#what-is-testgrid-and-what-are-its-key-features) |  
| 50 | [What is the importance of debugging emails and ensuring proper deliverability?](#what-is-the-importance-of-debugging-emails-and-ensuring-proper-deliverability) |  
| 49 | [How should UI issues be investigated to determine the root cause?](#how-should-ui-issues-be-investigated-to-determine-the-root-cause) |  
| 48 | [How should issues with the user interface be handled?](#how-should-issues-with-the-user-interface-be-handled) |  
| 47 | [How should failures be monitored over time during testing?](#how-should-failures-be-monitored-over-time-during-testing) |  
| 46 | [What is an example of negative testing?](#what-is-an-example-of-negative-testing) |  
| 45 | [What do test logs include?](#what-do-test-logs-include) |  
| 44 | [What are the steps involved in setting up a PostgreSQL database for storing data?](#what-are-the-steps-involved-in-setting-up-a-postgresql-database-for-storing-data) |  
| 43 | [What are triggers in SQL and what is the purpose of the sync changes table?](#what-are-triggers-in-sql-and-what-is-the-purpose-of-the-sync-changes-table) |  
| 42 | [What does a Test Plan include?](#what-does-a-test-plan-include) |  
| 39 | [What is a good test case?](#what-is-a-good-test-case) |  
| 38 | [What is a Test Plan?](#what-is-a-test-plan) |  
| 37 | [What is the difference between severity and priority?](#what-is-the-difference-between-severity-and-priority) |  
| 35 | [What is the bug triage process and how is it carried out?](#what-is-the-bug-triage-process-and-how-is-it-carried-out) |
| 34 | [How do you estimate the time for bug fixing?](#how-do-you-estimate-the-time-for-bug-fixing) |
| 33 | [How do you classify bug priority?](#how-do-you-classify-bug-priority) |
| 32 | [What are the key components of a test plan?](#what-are-the-key-components-of-a-test-plan) |
| 31 | [What information should be included in a test case?](#what-information-should-be-included-in-a-test-case) |
| 30 | [How do you handle bug triage and bug reports?](#how-do-you-handle-bug-triage-and-bug-reports) |
| 24 | [What to include in a bug report?](#what-to-include-in-a-bug-report) |
| 23 | [What's included in Jira and how is it used?](#whats-included-in-jira-and-how-is-it-used) |
| 22 | [What are the definitions of Backlog and Sprint?](#what-are-the-definitions-of-backlog-and-sprint) |
| 21 | [If you have three tasks that are all high priority, how will you decide which task to take on?](#if-you-have-three-tasks-that-are-all-high-priority-how-will-you-decide-which-task-to-take-on) |
| 20 | [As a first QA, what would you do?](#as-a-first-qa-what-would-you-do) |
| 19 | [If you need to start automation from scratch, what would your steps and processes be?](#if-you-need-to-start-automation-from-scratch-what-would-your-steps-and-processes-be) |
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
| 25 | [How do you develop your skills and stay up-to-date?](#how-do-you-develop-your-skills-and-stay-up-to-date) |
| 26 | [How do you ensure effective requirement management in QA?](#how-do-you-ensure-effective-requirement-management-in-qa) |
| 27 | [How do you address the failure to simulate concurrent users in testing?](#how-do-you-address-the-failure-to-simulate-concurrent-users-in-testing) |
| 28 | [What tools do you use for QA and how are they utilized?](#what-tools-do-you-use-for-qa-and-how-are-they-utilized) |
| 29 | [How did you improve the onboarding process for new employees?](#how-did-you-improve-the-onboarding-process-for-new-employees) |
| 36 | [What are the common ETL challenges and their solutions?](#what-are-the-common-etl-challenges-and-their-solutions) |  
| 40 | [What is the difference between functional and nonfunctional testing?](#what-is-the-difference-between-functional-and-nonfunctional-testing) |  
| 41 | [What are the common challenges faced by QA teams?](#what-are-the-common-challenges-faced-by-qa-teams) |
| 62 | [What would you do if you filed a bug and the developer tells you it’s not a bug?](#what-would-you-do-if-you-filed-a-bug-and-the-developer-tells-you-its-not-a-bug) |  
| 65 | [What would you do if asked to write test cases based on requirements provided?](#what-would-you-do-if-asked-to-write-test-cases-based-on-requirements-provided) |  
| 66 | [What are the steps in a bug lifecycle?](#what-are-the-steps-in-a-bug-lifecycle) |  
| 71 | [How can logs be efficiently managed when time is limited?](#how-can-logs-be-efficiently-managed-when-time-is-limited) |  
| 73 | [What is the importance of frontend and backend testing in application development?](#what-is-the-importance-of-frontend-and-backend-testing-in-application-development) |  
| 80 | [How do Unix command-line tools assist in data processing?](#how-do-unix-command-line-tools-assist-in-data-processing) |  

---

## What is deliverability testing?

> **Deliverability testing ensures that emails successfully reach recipients' inboxes without being flagged as spam or facing delivery issues. It involves:**  
>  
> - Spam Filter Testing: Checks if emails pass through spam filters.  
> - Inbox Placement: Verifies whether emails land in the primary inbox or junk folder.  
> - Content Quality Check: Ensures email content meets deliverability standards (e.g., no broken links or blocked images).  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is negative testing?

> **Negative testing involves inputting invalid or unexpected data to ensure that the application handles errors properly. For unhandled exceptions, negative testing helps by:**  
>  
> - Triggering edge cases that might cause unhandled exceptions.  
> - Verifying error messages and system behavior when inputs are incorrect or out of bounds.  
> - Ensuring graceful failure without crashes or data loss.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is frontend testing?

> **Frontend testing ensures a smooth and responsive user experience by validating:**  
>  
> - **UI Testing:** Checks layout, scaling, and clickable elements.  
> - **UX Testing:** Evaluates usability, responsiveness, and potential freezing issues.  
> - **Network & Data Handling:** Verifies API calls, database connectivity, and handles failed network requests.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is database testing?

> **Database testing ensures data integrity, consistency, and reliability through key validations:**  
>  
> - **Structure Validation:** Checks tables, schemas, constraints, and relationships (e.g., primary/foreign keys) for correctness.  
> - **Format Validation:** Ensures data types, field lengths, and formats (e.g., date, currency) follow expected standards.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are test artifacts in software testing?

> **Test artifacts are essential documents and assets in the testing process, ensuring clarity, traceability, and accountability:**  
>  
> - **Test Plan:** Outlines scope, strategy, and objectives.  
> - **Test Cases:** Detailed steps for executing tests.  
> - **Test Scripts:** Automated test execution scripts.  
> - **Test Reports:** Summarizes results, defects, and coverage.  
> - **Bug Reports:** Documents identified issues and resolutions.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key types of software testing?

> **Key types of software testing ensure software reliability and performance:**  
>  
> - **Functional Testing:** Verifies that features work as expected.  
> - **Integration Testing:** Ensures seamless interaction between components.  
> - **Interface Testing:** Validates communication between systems or APIs.  
> - **Performance Testing:** Assesses speed, scalability, and stability under load.  
> - **Regression Testing:** Confirms new updates don’t break existing functionality.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are boundary validation, range checks, threshold checks, and data truncation in data quality assurance?

> **These techniques ensure data accuracy and prevent errors:**  
>  
> - **Boundary Validation:** Verifies input values fall within expected limits.  
> - **Range Check:** Ensures numeric values stay within a predefined range.  
> - **Threshold Checks:** Flags values exceeding acceptable thresholds.  
> - **Data Truncation:** Prevents loss of information by ensuring data fits within storage constraints.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are constraint violations in databases, and how do they impact data integrity?

> **Constraint violations occur when database rules are broken, leading to data integrity issues. Common violations include:**  
>  
> - **Unique Key Violation:** Duplicate values in a column that must be unique.  
> - **Primary Key Violation:** Attempting to insert a record with a duplicate or null primary key.  
> - **Foreign Key Violation:** Referential integrity failure when a referenced record is missing.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the different types of testing?

> **Testing in software development ensures quality, performance, security, and compliance through:**  
>  
> - **Functional Testing:** Unit, integration, end-to-end, regression, UI/UX, exploratory, workflow validation.  
> - **Data & Database Testing:** Backend validation, database connectivity, source-target reconciliation, constraint checks, audit logs, ETL testing.  
> - **Performance & Security Testing:** Load, stress, fault tolerance, boundary validation, security compliance.  
> - **Test Automation & CI/CD:** Automated test cases, CI/CD pipeline execution, bug reporting.  
> - **UI & Visual Testing:** Graphical layout checks, positioning issues, clickable elements, email rendering validation.  
> - **Logging & Debugging:** Log file analysis, error handling, session tracking, workflow monitoring.  
> - **Business & Compliance Testing:** Business rule validation, regulatory compliance, release process verification.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the purpose of Cogito SQL in reporting?

> **Cogito SQL helps in reporting by:**
> 
> - Retrieving structured data from databases using predefined query templates.
> - Automating report generation with consistent and reusable SQL queries.
> - Enhancing data analysis by filtering, aggregating, and formatting results efficiently.
> - Supporting business intelligence by providing structured insights from large datasets.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How does MongoDB differ from relational databases?

> **MongoDB differs from relational databases in the following ways:**
> 
> - It is a NoSQL database that stores data in JSON-like documents instead of tables.
> - It supports flexible schema design, allowing dynamic fields and structures.
> - It scales horizontally using sharding, whereas relational databases typically scale vertically.
> - It is optimized for unstructured and semi-structured data, unlike relational databases that enforce strict schemas.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What role does ETL play in data processing?

> **ETL (Extract, Transform, Load) plays a critical role in data processing by:**
> 
> - **Extracting** data from multiple sources, such as databases, APIs, or flat files.
> - **Transforming** data through cleaning, validation, and enrichment to ensure consistency.
> - **Loading** the processed data into a target system, such as a data warehouse, for analysis and reporting.

> ETL ensures that data is structured, accurate, and ready for decision-making.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are common UI issues in web applications?

> **Common UI issues include:**
> 
> - **Broken Links:** Links that do not navigate to the correct destination.
> - **Missing Attachments:** Files or images failing to load.
> - **Unresponsive Hover Effects:** Elements that do not respond to user interactions.
> - **Misaligned UI Elements:** Components that appear incorrectly positioned on different screen sizes.

> Identifying and fixing these issues enhances user experience and accessibility.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## Why is regression testing crucial in software development?

> **Regression testing is crucial because:**
> 
> - **Prevents Breakage:** Ensures new changes do not introduce defects in existing functionality.
> - **Maintains Stability:** Validates that previous features work correctly after updates.
> - **Improves Software Quality:** Detects unintended side effects early in development.
> 
> Regular regression testing helps deliver reliable and consistent software across iterations.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How does workflow validation improve process execution?

> **Workflow validation improves process execution by:**
> 
> - **Ensuring Correct Task Sequence:** Verifies that tasks are executed in the right order, preventing logical errors.
> - **Validating Data Flow:** Confirms that data is correctly passed between steps to maintain accuracy.
> - **Meeting Performance Expectations:** Ensures execution time and resource usage align with system requirements.
> 
> Proper validation reduces errors, enhances efficiency, and improves overall process reliability.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What factors affect email deliverability and user experience?

> **Factors affecting email deliverability and user experience:**
> 
> - **Spam Triggers:** Words, phrases, or excessive links that flag emails as spam.
> - **Formatting Issues:** Incorrect HTML, missing alt text, or improper styling can affect rendering.
> - **Clipped Content:** Large emails may get clipped in certain email clients, hiding important information.
> - **Unresponsive Layouts:** Emails not optimized for mobile devices lead to poor readability.
> - **Broken Links:** Non-functional or incorrect links reduce user engagement and credibility.
> 
> Ensuring proper email design, testing across devices, and avoiding spam triggers can improve deliverability and experience.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do failed network requests impact an application?

> **Impact of failed network requests:**
> 
> - Prevent data retrieval, leading to missing or outdated information.
> - Degrade user experience by causing delays, broken UI components, or incomplete pages.
> - Cause application failures if error handling mechanisms are not in place.
> 
> Implementing robust error handling and retry mechanisms can mitigate these issues.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are common test operations in data validation?

> **Common test operations in data validation include:**
> 
> - **COUNT:** Counts all values in a field.
> - **COUNT DISTINCT:** Counts only unique values.
> - **COUNT ROWS:** Counts all rows.
> - **MIN:** Finds the lowest value in a field.
> - **MAX:** Finds the highest value in a field.
> - **AVERAGE:** Calculates the average value.
> - **SUM:** Adds up all values.
> 
> These operations help validate data quality, such as ensuring there are more than 1,000 rows or checking if a sum falls within a specific range.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What should be included in test reports for analysis?

> **Test reports for analysis should include both graphical and table formats, showing key metrics such as:**
> 
> - Tests Run vs. Tests Passed
> - Percentage of Tests Passed
> - Total Rows vs. Percentage of Bad Rows
> - Validation Failures Report
> - Bad Rows Report
> - Failed Tests Report
> 
> **Each report provides insights into data quality and helps identify areas needing attention.** For example, the Bad Rows Report details specific records that failed validation, including the Key, Bad Value, and the Test Case that caused the failure.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is fault tolerance in a system?

> **Fault tolerance is the ability of a system to continue operating even if some components fail.**

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is refactoring in software development?

> **Refactoring is the process of improving the internal structure of software without changing its external behavior.**

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What should be included in a well-written bug report?

> **A well-written bug report should include the following:**
> 
> - **A clear title** describing the issue.
> - **Steps to reproduce the issue** to help others replicate the problem.
> - **Expected vs actual results** to clarify the discrepancy.
> - **Screenshots or screen recordings** to visually demonstrate the issue.
> - **Environment details** (e.g., OS, version) for context.
> - **Relevant logs or error messages** to provide technical insights.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What’s the difference between backend testing and frontend testing?

> **The key differences between backend and frontend testing:**
>  
> - **Frontend Testing:** Focuses on the user interface and user experience, ensuring that UI elements are functional and display correctly.
> - **Backend Testing:** Focuses on server-side logic, databases, APIs, and ensuring data integrity.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the difference between smoke, sanity, regression, and other types of testing?

> **The key differences between testing types:**
>  
> - **Smoke Testing:** Verifies the basic functionality of a build to ensure that it’s stable enough for further testing.
> - **Sanity Testing:** Checks if the new changes or fixes are working as expected without causing other issues.
> - **Regression Testing:** Ensures that new code doesn’t break any existing functionality.
> - **End-to-End Testing:** Covers the entire application flow, from start to finish, to ensure the system works as a whole.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the common HTTP methods used for retrieving, creating, and updating resources?

> **The common HTTP methods for interacting with web resources:**
>  
> - **GET:** Retrieves data from the server without modifying it.  
> - **POST:** Sends data to create a new resource.  
> - **PUT:** Updates or replaces an entire resource; if it doesn’t exist, it can create one.  
> - **PATCH:** Partially updates an existing resource.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the Red-Green-Refactor cycle in Test-Driven Development (TDD)?

> **The Red-Green-Refactor cycle in TDD:**  
>  
> - **Red:** Write a test that defines the desired behavior but initially fails since the functionality is not yet implemented.  
> - **Green:** Write the minimum amount of code necessary to make the test pass.  
> - **Refactor:** Optimize and clean up the code while ensuring the test still passes, improving efficiency and maintainability.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What steps do you follow when testing a database to ensure data accuracy and integrity?

> **Steps in Database Testing:**  
>  
> - **Requirements Review:** Collaborate with business analysts to understand data expectations.  
> - **Test Planning:** Develop a test plan and cases, including negative testing, and store them centrally.  
> - **Data Profiling:** Identify anomalies and inconsistencies to improve data accuracy.  
> - **Record Verification:** Compare entered data with input sources (e.g., documents, spreadsheets).  
> - **Field-Level Validation:** Ensure data type, size, and format compliance.  
> - **Boundary Testing:** Test limits by exceeding field constraints.  
> - **Data Integrity Testing:** Verify relationships and dependencies between data.  
> - **Data Completeness Testing:** Ensure all required fields are populated correctly.  
> - **Test Execution:** Use manual testing and automation tools like Selenium to run the test plan.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key types of queries used in database testing?

> **Key Types of Queries in Database Testing:**  
>  
> - **Select Queries:** Ensure accurate data retrieval by verifying that the correct records are returned.  
>   - Example: Fetching customers who placed an order in the last 30 days.  
> - **Update Queries:** Validate that data modifications are applied correctly.  
>   - Example: Updating a customer's address and verifying that only the intended record is changed.  
> - **Delete Queries:** Test data deletion functionality.  
>   - Example: Removing inactive customer accounts and confirming successful deletion.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the difference between functional and non-functional testing in database testing?

> **Functional vs. Non-Functional Testing in Database Testing:**  
>  
> - **Functional Testing:** Ensures the database correctly performs operations like CRUD (Create, Read, Update, Delete).  
>   - Example: Verifying that an e-commerce database correctly processes orders and updates inventory.  
> - **Non-Functional Testing:** Evaluates performance, scalability, security, and reliability.  
>   - Example: Testing if the database can handle peak traffic during a holiday sale without crashing.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What tool can be used to measure performance and load test web applications?

> **Apache JMeter is a performance testing tool that can load test both static and dynamic web applications.**  
>  
> - Simulates heavy traffic to analyze server performance and scalability.  
> - Supports testing of various protocols, including HTTP, HTTPS, FTP, and databases.  
> - Provides real-time monitoring and detailed dynamic HTML reports for easy analysis.  
> - Helps identify performance bottlenecks by measuring response times and system behavior under load.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is json-server, and how does it help with API testing?

> **json-server is a free tool that allows developers to quickly create a local RESTful API for prototyping and mocking.**  
>  
> - It enables frontend developers to test applications without setting up a full backend.  
> - Supports CRUD operations (Create, Read, Update, Delete) using a simple JSON file.  
> - Provides a quick and zero-configuration way to test API calls.  
> - Helps speed up development by simulating an actual backend service.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are some open-source tools for browser automation, API testing, accessibility, security, and monitoring?

> **A variety of open-source tools exist to assist with different aspects of web development and testing. Below are some key tools categorized by their primary function:**  
> 
> **Browser Automation:**  
> - **Playwright** – An open-source tool by Microsoft for automating web browsers, similar to Selenium.
> 
> **API Testing:**  
> - **Newman** – A command-line Collection Runner for Postman that allows running and testing Postman collections from the terminal.
> 
> **Web Accessibility Evaluation:**  
> - **Wave** – A suite of tools that helps evaluate web content for accessibility compliance with WCAG standards.
> 
> **Security:**  
> - **OWASP Top 10** – A widely recognized open-source awareness document listing the top 10 security risks in web applications.
> 
> **Monitoring:**  
> - **Datadog** – An open-source monitoring and analytics platform for infrastructure, applications, and logs.
> 
> **Observability:**  
> - **Grafana** – An open-source tool for visualizing and analyzing metrics from multiple data sources.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do database scaling techniques like replication and sharding address performance challenges?

> **As systems grow, a single database might struggle with high load, leading to slow reads and writes. To address this, database scaling techniques such as replication and sharding are used.**  
> 
> **Single Database Challenges:**
> - When everything is hosted on a single machine, it may become difficult to scale as traffic increases, resulting in performance issues like slow reads and writes.
> 
> **Database Replication:**
> - Improves performance and provides fault tolerance.
> - **Master-Slave Setup:** The master database handles all write operations, while one or more slave databases handle read operations.
> - **Faster Reads:** Offloading read queries to the slave databases improves overall read performance.
> - **Fault Tolerance:** If the master database fails, a slave can be promoted to master, ensuring system availability.
> 
> **Challenges with Replication:**
> - **Replication Lag:** There may be a delay between when data is written to the master and when it is replicated to the slaves, meaning the data on the slaves may not always be up-to-date.
> - **Slower Writes:** Even though reads are offloaded to slaves, writes to the master can still become slow as the system scales.
> 
> **Database Sharding:**
> - Sharding involves partitioning data and distributing it across multiple servers to handle large volumes of data.
> - **Shards:** The database is divided into smaller pieces, called shards, and distributed across different servers.
> - **Complex Queries:** Sharding can make queries more complex, particularly when joins are required, which could lead to expensive operations.
> - **Data Denormalization:** Often, sharding requires data denormalization to optimize query performance.
> 
> **Combining Sharding and Replication:**
> - Sharding and replication can be used together. For instance, each shard can have its own replication structure, where reads are offloaded to slave databases, and data is partitioned for scalability.
> 
> So
> - **Replication** improves read performance and fault tolerance.
> - **Sharding** helps distribute large datasets across multiple servers, enabling horizontal scaling.
> - **Combining both** techniques enhances both performance and availability.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How does GitHub Actions automate workflows?
> **GitHub Actions** is an automation tool integrated directly within GitHub, enabling **continuous integration (CI) and continuous deployment (CD)** in repositories.

**How It Works:**
**Workflows**
- Automated processes that define CI/CD tasks for a repository.
- Defined in YAML files stored in `.github/workflows/` directory.
- Consist of **jobs** that perform tasks such as building, testing, and deploying code.

**Events**
- Workflows are triggered by **events** in the repository (e.g., push, pull request, release).
- Defined using the `on` keyword in the workflow file.

**Jobs**
- Individual units of work in a workflow.
- Can run sequentially or in parallel.
- Each job runs in its own virtual environment (**runner**) and can be configured for **Ubuntu, macOS, or Windows**.

**Steps**
- Tasks within a job, such as checking out code, installing dependencies, or running tests.
- Can be **individual commands** or **GitHub Actions** (predefined automation tasks).

**Actions**
- Reusable pieces of code that automate common tasks (e.g., setting up environments, deploying apps).
- Available in **GitHub Marketplace** or can be custom-built.

**Runners**
- **GitHub-hosted runners**: Pre-configured servers for Ubuntu, Windows, and macOS.
- **Self-hosted runners**: Custom servers for greater control over the environment.

**Example Workflow (YAML Format)**

1. **Trigger** → The workflow is triggered by a **push** to the `main` branch.
2. **Job** → A job named `build` runs on **Ubuntu**.
3. **Steps**:
   - **Checkout code** → Retrieves repository code.
   - **Set up Node.js** → Installs Node.js v14.
   - **Install dependencies** → Runs `npm install`.
   - **Run tests** → Executes `npm test`.
   - **Deploy** → If all previous steps succeed, runs `npm run deploy`.

**Why Use GitHub Actions?**

✅ Automates repetitive tasks (**build, test, deploy**)  
✅ Provides a **streamlined** and **efficient** workflow  
✅ Supports **parallel execution** for faster processing  
✅ Integrates seamlessly with **GitHub repositories**  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is TestGrid and what are its key features?

> **TestGrid** is a tool used to analyze test results, often presented in a grid format. It helps identify patterns and failures over time, making it easier to spot recurring issues. For example, it allows you to see consistently failing tests, flaky tests, and tests that agree or pass frequently.  

### **Key Features of TestGrid:**  
- **Sorting:** Organize tests based on specific criteria.  
- **Filtering:** Narrow down tests by selecting what you want to see or exclude.  
- **Graphing:** Visualize test results through graphs to identify trends.  
- **Grouping:** Group tests by certain patterns or categories for easy viewing.  
- **Dashboard Groups:** Organize test results into meaningful groups for easier access.  
- **Summaries:** Get summarized insights from tests to understand overall performance.  
- **Clustered Failures:** Identify tests with failures occurring in clusters, making it easier to pinpoint issues.  

> **Why is this important?**  
> These features allow teams to efficiently track and analyze test results, simplifying test performance evaluation and helping focus on areas that need improvement.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is the importance of debugging emails and ensuring proper deliverability?

> Debugging emails is the responsibility of the dev/QA team. Not all email clients support HTML and CSS in the same way, meaning certain clients, like Outlook or Gmail app for non-Google accounts, might not render background images or may display emails incorrectly. This can result in a poor user experience (UX), with the email appearing clipped, with a shifted layout, unresponsive, or containing unsupported content, which can discourage customers from returning.  

### **Key Factors in Email Debugging:**
- **Ensuring a high deliverability rate:** Measures factors like spam reports, user interactions, and bounce rates.  
- **Avoiding spam triggers:** Content should be checked to prevent emails from being flagged as spam.  
- **Rendering consistency across email clients:** Emails should be tested in multiple clients to ensure proper formatting and readability.  
- **Testing links and images:** Ensure all embedded links and images work as expected.  

> **Why is this important?**  
> If a QA or dev team ignores spam checks and deliverability testing, important emails may not reach the end-user, negatively affecting communication and engagement.  

---

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## How should UI issues be investigated to determine the root cause?
> The goal is to figure out why something is broken or not working as expected when encountering an issue in the user interface. The UI could include elements like buttons, forms, images, or navigation menus. Examples of UI issues include:  
> - A button on a web page is not clickable or looks broken (e.g., missing text or icon).  
> - A page loads with a distorted layout, or images don't display properly.   
> To resolve the issue, it's important to investigate deeply and not just fix the surface-level problem. This often requires exploring various parts of the system:  

**Network Calls:**
> Modern web apps often rely on network requests to fetch data from servers. If there's a UI issue (e.g., data not showing correctly), it might be due to a failed network request.  
> **What to do:** Open browser developer tools (like Chrome DevTools) and inspect the network tab to check if all the network requests are succeeding.  
> **Example:** If a button click is supposed to load data, but the network call fails (e.g., 404 or 500 error), you can investigate the request/response cycle to determine what went wrong.  

**Backend Service Logs:**
> The backend handles business logic, data retrieval, and data storage. If a network call to the backend fails, checking the backend service logs is crucial.  
> **What to do:** Look at the logs of the backend service (e.g., web server, API service) to identify errors or unexpected behavior during the request.  
> **Example:** If a data fetch request fails with an internal server error (500), the backend logs may show an exception explaining why (e.g., database connectivity issues, missing data).  

**Database Validation:**
> Sometimes, the issue might be due to missing, incorrect, or corrupted data in the database. If the UI relies on data from the database, the issue could be data-related.  
> **What to do:** Inspect the database directly to verify that the necessary data is available and correctly formatted.  
> **Example:** If a UI component should display user profiles but shows nothing, check the database to ensure the user records exist and contain the required fields (e.g., name, email, profile picture URL).  

So when a UI defect occurs, you should:  
> ✅ Check network calls to ensure requests to external services or APIs are not failing.  
> ✅ Inspect backend service logs to identify internal issues, such as bugs or errors.  
> ✅ Validate the database to ensure the data used by the UI is correct and available.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## How should issues with the user interface be handled?

> There are always some issues with the user interface, which includes anything the user interacts with, such as buttons, forms, images, navigation menus, etc. For example, a button might not be clickable, a link could be broken, an image might not display, or the page could load with a distorted layout.  
>  
> When such issues appear, it’s important to quickly determine why something is broken or not working as expected. However, it's crucial to investigate the issue deeply to identify the root cause, rather than just fixing the surface-level problem. This often requires exploring other parts of the system—such as the backend, frontend, and database—to find the true source of the defect.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## How should failures be monitored over time during testing?

> **Monitoring Failures Over Time:**  
> - Identify consistently failing tests.  
> - Filter tests based on what you want or don’t want to see.  
> - Narrow down tests by grouping them into specific categories.  
> - Cluster, sort, filter, and group tests for better analysis.  
> - Provide a summary for each failure type.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is an example of negative testing?

> **Example of Negative Testing:**  
> A user tries to submit a form without selecting an option from the drop-down menu.  
> This shouldn't lead to a system crash; instead, the user should be prompted to select an option.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What do test logs include?

> **Test logs include:**  
> - Details about the bugs  
> - The issues encountered  
> - Severity levels  
> - Steps to reproduce  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What are the steps involved in setting up a PostgreSQL database for storing data?

> **1. Push Data to Server:** Upload the downloaded data to the correct server paths using a push script.  
> **2. Install PostgreSQL:** Install PostgreSQL and create a new database for storing the data using the `CREATE` command.  
> **3. Set Up Database Schema:** Set up the database and create the necessary tables and schema in PostgreSQL for storing the data.  
> **4. Install Dependencies:** Create a Python virtual environment and install the necessary packages.  
> **5. Run Metadata Builder:** Add metadata to the database using the relevant command.  
> **6. Create Indexes:** Improve database performance by creating indexes on important fields (e.g., `patient_id`).  
> **7. Partition Data:** If needed, partition large tables for better query performance. This links the raw data with the metadata.  

> **Once the data is loaded, you can use SQL queries to access data.**  

> **Additional setup includes:**  
> - Commands for setting up PostgreSQL and creating the database.  
> - SQL migration scripts for database setup.  
> - Repository and setup information.  
> - Configuration file for managing settings.  
> - Code related to the server setup.  
> - Containerization with Docker if required.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What are triggers in SQL and what is the purpose of the sync changes table?

> **Triggers in SQL:** Used to automatically perform operations when certain actions (like INSERT, UPDATE, or DELETE) occur on a table.  
> **The sync_changes table:** Might store a history of changes for data consistency or auditing purposes.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What does a Test Plan include?

> A **Test Plan** outlines:  
> - **Areas to be tested** (e.g., registration, logging in, changing the language, account settings).  
> - **Areas not to be tested** (e.g., vouchers and coupons).  
> - **Types of tests** (e.g., smoke tests, exploratory sessions, regression, functional, cross-browser).  
> - **Individuals responsible** for specific activities.  
> - **Resources required** for testing.  
> - **Schedule** necessary to complete the described tasks.  

> **Example:**  
> - **Functionality Being Tested**: Logging in via email.  
> - **Goal**: Verify basic functionality and assess software quality.  
> - **Purpose**: Identify defects before delivery and confirm functionality meets expectations.  
> - **Outcome**: Test results will be documented in a report detailing performed activities.  

> **Additional components of a Test Plan:**  
> - **Test Tools**  
> - **Test Devices and Environment**  
> - **Schedule of Tests**  
> - **Priority levels** (rated from 1 = lowest to 5 = highest).  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is a good test case?

> **A good test case** clearly states parameters and expected bugs.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is a Test Plan?

> **A Test Plan** is a document outlining the details of intended testing, roles, risks, and resources.  
> It describes test design, execution, defect management, and reporting.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is the difference between severity and priority?

> **Severity:** Difficulty of fixing the issue.  
> **Priority:** Importance of fixing the issue.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is the bug triage process and how is it carried out?

> **The bug triage process involves the following steps:**  
>  
> - Evaluating bug severity and impact.  
> - Categorizing issues as Critical, Major, or Minor.  
> - Prioritizing based on customer impact and business risk.  

> **The process also includes:**  
>  
> - Working closely with developers for root cause analysis.  
> - Collaborating to identify underlying issues.  
> - Estimating fix times based on complexity and resources.  

> **Additional steps involve:**  
>  
> - Reproducing issues in multiple environments.  
> - Testing on varied platforms and browsers.  
> - Verifying reproducibility and capturing detailed logs.  

> **Clear bug documentation is maintained by:**  
>  
> - Including reproducible steps, error logs, and screenshots.  
> - Ensuring clarity to speed up developer resolution.  

> **Lastly, bug reports are managed in Jira by:**  
>  
> - Creating detailed bug tickets with priority tags.  
> - Tracking status and providing timely updates to stakeholders.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## How do you estimate the time for bug fixing?

1. **Evaluated bug complexity**:
   - Simple vs. complex bugs.
   
2. **Used past incidents as benchmarks**:
   - Referenced similar issues to gauge time.

3. **Divided the fix into subtasks**:
   - Example: investigation, coding, testing.

4. **Added buffer time for unforeseen delays**:
   - To account for potential obstacles.

5. **Adjusted estimates based on bug priority**:
   - Critical, major, or minor priority impacts time estimation.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do you classify bug priority?

### **Critical Priority:**
- System failure or security breach.
- Affects core functionality or end-user experience.

### **Minor Priority:**
- Low impact or cosmetic issues (UI glitches, small bugs).
- Does not affect core functionality or user workflow.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the key components of a test plan?

### **Test Plan:**
- **Define goals:** What the testing aims to achieve (like verifying functionality, performance).

### **Test Strategy:**
- **Manual vs. Automated:** Decide on types of tests based on complexity and frequency.
- **Test Levels:** Unit, integration, system, acceptance, regression.

### **Test Environment:**
- Define hardware, software, and network configurations required.
- Identify test devices, browsers, and OS versions for compatibility testing.

### **Test Deliverables:**
- **Test Cases:** Document specific tests for each requirement or feature.
- **Test Reports:** Bug reports, defect logs, and status updates.
- **Test Data:** Define data sets used in test execution.

### **Test Schedule & Timeline:**
- **Test phases:** Planning, execution, and reporting.
- Set deadlines for test execution and defect resolution.
- Estimate testing duration based on project milestones.

### **Risk Management:**
- **Identify potential risks:** Unclear requirements, resource limitations.
- **Define mitigation strategies** for major risks (e.g., scope creep, time delays).

### **Test Case Design:**
- Focus on positive and negative test cases.
- Include boundary tests, edge cases, and common user scenarios.

### **Resource Allocation:**
- Define roles: Testers, developers, product managers.
- Allocate resources based on testing complexity and team skills.

### **Exit Criteria:**
- Define success criteria for test completion (e.g., all high-priority bugs fixed, 95% test coverage).
- Determine when to stop testing (e.g., no major bugs remain, time constraints).

### **Test Reporting & Communication:**
- **Status updates:** Regular communication with stakeholders on progress.
- **Bug reporting:** Clear and consistent format for reporting defects.
- **Test result summaries:** Include pass/fail rates, bug severity, and testing coverage.

### **Approval & Sign-off:**
- Obtain formal sign-off from stakeholders or QA leads upon completion.
- Ensure testing meets all business requirements before release.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What information should be included in a test case?

> **Test Case ID:** Unique identifier for each test case (like TC_001). Helps track and reference test cases efficiently.  
> **Test Case Title:** Brief description of the test case purpose (like "Login functionality with valid credentials").  
> **Preconditions:** Setup steps or conditions that must be met before executing the test (like "User is logged out," "Test environment is configured").  
> **Test Data:** Specific input data required for the test (like valid username/password, date formats). Include edge cases and boundary values where applicable.  
> **Test Steps:** Step-by-step instructions to execute the test. Ensure clarity and conciseness (like "Step 1: Open the login page," "Step 2: Enter username").  
> **Expected Result:** Define the expected outcome of each step or the overall test (like "User is successfully logged in," "Error message is displayed").  
> **Actual Result:** To be filled out after test execution with actual behavior observed. Comparison with the expected result.  
> **Status:** Pass/Fail indicator based on whether the actual result matches the expected result. Include "Blocked" or "In Progress" if needed.  
> **Priority:** Assign a priority level (like High, Medium, Low) based on test case importance or impact.  
> **Test Type:** Define the type of test (like Functional, Regression, Smoke, UI). Helps categorize and target the right areas of the application.  
> **Dependencies:** List any pre-existing conditions or tests that need to run first (like "Test case TC_005 must pass before executing TC_010").  
> **Postconditions:** Define the state of the system after test execution (like "User remains logged out," "System returns to default settings").  
> **Test Case Version:** Version control for test cases, tracking changes over time. Helpful for continuous improvement and reference (like "v1.0," "v1.1").  
> **Automated vs. Manual:** Specify if the test case is to be executed manually or automated. Important for efficiency and future scalability.  
> **Comments/Notes:** Include any additional clarifications or information (like "Test only applicable for mobile version," "Check compatibility with different browsers").

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do you handle bug triage and bug reports?

> **Bug Triage:** Estimate fix times.
> 
> **Bug Reports:** Include reproducible steps, error logs, and screenshots.
> 
> Create detailed bug tickets with priority tags: Critical, Major, Minor.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What to include in a bug report?

> **Title:**  
> A brief and clear title summarizing the issue.

> **What happened:**  
> A description of what went wrong or what behavior was observed.

> **Where it happened:**  
> The location or specific module, page, or area in the system where the bug was observed.

> **Under which circumstances:**  
> Any particular conditions or actions that triggered the bug.

> **Pre-condition:**  
> Any required setup, login, or previous actions before the bug can be reproduced.

> **Environment:**  
> - **OS:** (like Windows, macOS)  
> - **Browser:** (like Chrome)  
> - **Hardware:** (like server specifications)  
> - **Network conditions:** (like Wi-Fi, VPN)  
> - **Third-party dependencies:** (like APIs)

> **Steps to reproduce:**  
> Step 1  
> Step 2  
> Step 3  
> A clear and sequential list of actions that lead to the bug occurrence.

> **Actual results vs expected:**  
> A comparison of what actually happened versus what should have happened.

> **Attachments:**  
> Screenshots, videos, log files, error dumps, or any other supporting files.

> **Severity:**  
> - **Critical:** Blocks major functionality, system crashes, or data loss.  
> - **Major:** Significant impact but with a workaround.  
> - **Minor:** Low impact or cosmetic issue.

> **Priority:**  
> - **High:** Needs to be fixed immediately.  
> - **Medium:** Needs to be fixed in the near future.  
> - **Low:** Can be fixed at a later time (rarely affects users).

> **Frequency:**  
> - **Always:** The bug occurs every time the described conditions are met.  
> - **Sometimes:** The bug occurs intermittently or randomly.  
> - **Rarely:** The bug happens under very specific or rare conditions.

> **Root cause:**  
> If identified, include the root cause of the issue.

> **Assigned to:**  
> Who is responsible for addressing the bug.

> **Status:**  
> Current state of the bug (Open, In Progress, Fixed, Verified).

> **Reproducibility:**  
> - **100% reproducible:** The issue happens every time under the stated conditions.  
> - **50% reproducible:** The issue happens intermittently under the stated conditions.  
> - **Not reproducible:** The issue cannot be reproduced despite multiple attempts.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What's included in Jira and how is it used?

> **Bug Tracking:**  
> Track and manage bugs/issues.

> **Projects:**  
> Access and manage multiple projects.

> **Scrum Board:**  
> Visualize backlog and sprint tasks.

> **Sprint Board:**  
> Track tasks in a specific sprint.

> **To Do:**  
> Tasks to be started (like design, new login page).

> **Task:**  
> Work items to be completed.

> **Ticket:**  
> Task details (description, assignee, attachments).

### QA Process:

> **QA Assignee:**  
> Person responsible for testing.

> **Check Requirements/Function:**  
> Ensure task meets requirements and works.

> **Done Status:**  
> Task is ready for release.

### Bug Reports:

> **Bug Report:**  
> Detailed issue description (e.g., "User can't login").

> **Priority:**  
> How quickly the bug needs fixing.

> **Severity:**  
> Impact level of the bug.

> **Team/Sprint:**  
> Assigned team and sprint.

> **Point Estimate:**  
> Time/effort required to fix.

> **Backlog:**  
> Current and future sprint tasks.

### Sprint Management:

> **Create Ticket in Backlog:**  
> Add summary, description, assignee.

> **Move Ticket:**  
> Move tasks across boards.

> **Add Sprint:**  
> Assign tasks to a sprint.

> **Start Sprint:**  
> Begin tracking the sprint.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the definitions of Backlog and Sprint?

> **Backlog:**  
> A list of tasks or issues that need to be worked on, but are not yet started. It can include tasks for future sprints.

> **Sprint:**  
> A set period (usually 1-2 weeks) where a team works on a specific set of tasks from the backlog. At the end of the sprint, the tasks should be completed and ready for release.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## If you have three tasks that are all high priority, how will you decide which task to take on?

> Whatever it takes, if they're all high priority, they’ve got to be tested, and as the QA engineer, I have to find a way to do so. I’d probably delegate some tasks to other team members if I can, and if we’re running short on time or resources, I’d pull in extra help to make sure everything gets done. So, I will bring more resources from the side.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## As a first QA, what would you do?

> **1. Request Documentation:**  
> The first step is to ask for all available documentation, including design tables and any tickets.

> **2. Meet with Team Members:**  
> Meet with every team member to understand their perspective on the product, what was built, and what is currently being built.

> **3. Take Responsibility for Code Review:**  
> Take responsibility for code review.

> **4. Create Basic Test Scenarios:**  
> When time is limited, create a list of basic test scenarios. These test scenarios should be enough to cover critical functionality.

> **5. Document Test Cases:**  
> Once the process is more stable, focus on documenting test cases in detail.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## If you need to start automation from scratch, what would your steps and processes be?

> **1. Resource Assessment:**  
> The first thing to ask is how many resources are available to start building automation. This means understanding the size of the team, their skill sets, and any existing tools or infrastructure already in place. A solution for which automation tools to use must also be determined. Is there a need to invest in a specific toolset or framework? What is the budget for things like cloud services (AWS, Azure, etc.) or CI/CD tools (like Jenkins, GitLab, etc.)?

> **2. Timeline Consideration:**  
> Secondly, it's crucial to consider the timeline: how urgent is the automation need? If the automation is needed quickly, quick-to-implement solutions are likely to be prioritized, even if they aren’t as scalable or sophisticated in the long term. In this case, frameworks that are more accessible or integrate better with the current tech stack may be used. If there’s more time to build out a sustainable solution, the focus can shift to selecting more robust, scalable frameworks that align with future goals.

> **3. Requirement Analysis:**  
> Next, dive into the requirements. What needs to be automated, and how are the existing processes structured? If there’s already some level of automation in place, assess what frameworks or tools have been used before. If automation has been done with other frameworks, it may be necessary to migrate or integrate them into the new approach. This also involves looking at the current tech stack and ensuring compatibility with the tools planned to be used.

> **4. Scope of Automation:**  
> After that, assess the scope of automation—deciding which areas of the application or business processes should be automated first. Typically, the most repetitive, error-prone, and high-value areas should be prioritized. Once priorities are set, the automation strategy can be designed.

> **5. Detailed Planning:**  
> Then, focus on creating a detailed plan and timeline for each phase of automation. This involves setting up environments, writing test cases or scripts, and ensuring proper integration with the development pipeline. It's also important to plan for continuous feedback and improvement—automation is not a "set it and forget it" process, so ensuring the automation is maintained and updated regularly is necessary.

> **6. Monitoring and Reporting Framework:**  
> Finally, always have a monitoring and reporting framework in place. Automation is not just about running tests; it's essential to have visibility into the success and failure of automated tasks. Monitoring tools, dashboards, and alerting mechanisms will be crucial to identify issues early and respond quickly.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

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

## How do you develop your skills and stay up-to-date?

> To stay current with industry trends, I:
> 
> - Regularly take online courses (on platforms like Coursera).
> - Attend webinars and conferences on related topics.
> - Follow industry leaders on LinkedIn and read blogs on Medium.
> - Participate in online communities like Stack Overflow and Reddit to engage with others and exchange knowledge.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do you ensure effective requirement management in QA?

> To ensure effective requirement management, I:
> 
> - Maintain detailed documentation of agreed requirements and changes.
> - Conduct collaborative requirement reviews.
> - To prevent ambiguous test cases, have clear acceptance criteria and involve stakeholders early.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do you address the failure to simulate concurrent users in testing?

> **Solution:** Use tools like JMeter to simulate realistic load patterns.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What tools do you use for QA and how are they utilized?

> **Jira:** Used for bug tracking and prioritizing issues (critical, major, minor).
> 
> **Docker:** Used to create consistent environments, ensuring reproducibility across setups.
> 
> **ETL Tools (unspecified):** Used for building and testing ETL pipelines to ensure data integrity, consistency, and accuracy.
> 
> **Parallel Processing / Partitioning / Batch Processing:** Used for optimizing ETL data processing, reducing time from days to hours.
> 
> **Test Automation Frameworks:** Used to automate testing.
> 
> **Email Automation System:** Used to send notifications and updates about onboarding requirements.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How did you improve the onboarding process for new employees?

> I created a knowledge repository to make onboarding easier for new employees. I designed standardized template documents using Google Workspace tools.
> 
> These documents cover:
> 
> - Tools and software, with manuals, tutorials, and guides
> - Information about teams and roles
> - FAQs that new hires commonly ask
> - Best practices for coding and workflows
> 
> I also set up automated email notifications to alert employees whenever the documents are updated.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the common ETL challenges and their solutions?

> **Data Inconsistency**  
> **Solution:** Implement data validation rules, use transformation scripts for standardization.  

> **Data Volume Handling**  
> **Solution:** Use partitioning, parallel processing, and batch processing.  

> **Data Quality Issues**  
> **Solution:** Apply data cleansing techniques like deduplication, error checking, and normalization.  

> **Slow ETL Process**  
> **Solution:** Optimize SQL queries, use indexing, and employ incremental loading.  

> **Schema Changes**  
> **Solution:** Use schema evolution frameworks like Apache Avro or Apache Parquet.  

> **Real-time Data Integration**  
> **Solution:** Implement change data capture (CDC) and event-driven architecture.  

> **Data Latency**  
> **Solution:** Leverage in-memory processing and stream processing engines (like Apache Kafka).  

> **Resource Management**  
> **Solution:** Use cloud-based auto-scaling, workload management tools (like Kubernetes).  

> **ETL Monitoring and Error Handling**  
> **Solution:** Implement automated alerting and logging with centralized monitoring (like ELK stack).  

> **Data Transformation Complexity**  
> **Solution:** Use modular transformation pipelines, employ SQL UDFs or custom Python functions.  

> **Dependency Management**  
> **Solution:** Use workflow orchestration tools like Apache Airflow to manage task dependencies.  

> **Data Encryption and Security**  
> **Solution:** Apply end-to-end encryption, use secure protocols (like SSL/TLS), and implement role-based access control.  

> **Data Duplication**  
> **Solution:** Use deduplication techniques within transformation scripts, enforce unique constraints.  

> **Handling Unstructured Data**  
> **Solution:** Use semi-structured formats (JSON, XML) and tools like Apache NiFi for ingestion.  

> **Version Control for ETL Jobs**  
> **Solution:** Use Git for version control, deploy with CI/CD pipelines.  

> **Poor Documentation**  
> **Solution:** Automate documentation generation, use metadata management tools.  

> **Data Integration with Multiple Sources**  
> **Solution:** Use APIs, adapters, and connectors for seamless integration (like Fivetran, Talend).  

> **Fault Tolerance**  
> **Solution:** Implement checkpointing, retry mechanisms, and fault-tolerant frameworks (like Apache Flink).  

> **Data Governance**  
> **Solution:** Implement data lineage tracking and auditing tools (like Collibra).  

> **Scalability Issues**  
> **Solution:** Use distributed computing (like Spark) and cloud-native solutions (like AWS Glue).  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What is the difference between functional and nonfunctional testing?

> **Functional Testing:** Verifies key software features meet requirements.  
> **Nonfunctional Testing:** Tests aspects like load time and performance.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---

## What are the common challenges faced by QA teams?

> - Frequent last-minute changes to project requirements.  
> - Insufficient details in user stories for clear test planning.  
> - Limited experience with test automation tools and frameworks.  
> - Poor collaboration between testers and developers.  
> - Tests failing to replicate real-world user conditions.  
> - Difficulty in prioritizing critical test cases.  
> - Challenges in managing cross-team dependencies.  
> - Complexity in testing across diverse platforms and devices.  
> - High turnover disrupting QA team stability.  
> - Application performance bottlenecks affecting user experience.  
> - Overlapping QA and development sprints causing workflow issues.  
> - Managing regression testing efficiently within tight timelines.  
> - Limited collaboration with stakeholders leading to misalignment.  
> - False positives and negatives in automated test results.  
> - Budget constraints restrict QA resources and tools.  
> - Ensuring compliance with data privacy regulations.  
> - Over-reliance on manual testing slows down processes.  
> - Frequent build failures delay testing efforts.  
> - Challenges in scaling automated testing for large projects.  
> - Limited visibility into overall test progress and outcomes.  

**[ Back to the question in the Table ⬆ ](#table-of-contents)**  

---
## What would you do if you filed a bug and the developer tells you it’s not a bug?

> **What to do in case of disagreement on a bug report:**
>  
> - Ask the developer to explain their reasoning so you can understand their perspective.
> - Review the original requirements or specifications to see if there's any documentation or user story that contradicts their reasoning. Suggest revisiting it together if necessary.
> - Present new data, logs, or examples to clarify the issue, as more context can help highlight why it might be a bug.
> - If there’s still no consensus, especially for a critical issue, escalate it to a manager, product owner, or lead for a third-party perspective.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What would you do if asked to write test cases based on requirements provided?

> **Steps to writing test cases based on provided requirements:**
>  
> - **Review Requirements:** Carefully go through the provided requirements to understand the expected functionality.
> - **Break Down Functional Scenarios:** Identify test scenarios based on functional requirements.
> - **Write Test Cases:** Create detailed test cases covering both positive and negative paths, ensuring edge cases are included for comprehensive testing.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What are the steps in a bug lifecycle?

> **The typical steps in a bug lifecycle:**
> 
> - **New:** The bug is identified and reported.
> - **Assigned:** A developer takes ownership of fixing the bug.
> - **Resolved:** The developer fixes the issue.
> - **Verified:** QA tests the fix to ensure it works.
> - **Closed:** If the issue is resolved, the bug is closed. If not, it's reopened for further investigation.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How can logs be efficiently managed when time is limited?

> **When time is limited, logs can be efficiently managed by:**
> 
> ### Retrieving Key Logs:
> - **Session Log:** Provides detailed execution information for each task.
> - **Workflow Log:** Gives insights into success/failure and task status.
> 
> ### Managing Logs Efficiently:
> - **Sorting Logs:** Filtering and sorting errors to pinpoint issues quickly.
> - **Searching Logs:** Using specific keywords to focus on critical sections without manually scanning the entire log.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## What is the importance of frontend and backend testing in application development?

> **The importance of frontend and backend testing:**
> 
> - **Frontend testing** ensures a smooth user experience by verifying UI functionality, responsiveness, and accessibility.
> - **Backend testing** validates data integrity, system security, and overall functionality to prevent critical failures.
> 
> Together, they ensure the application is both user-friendly and robust.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---

## How do Unix command-line tools assist in data processing?

> **Unix command-line tools assist in data processing by:**
> 
> - Using `awk` for pattern scanning and processing.
> - Utilizing `grep` to filter and search through text efficiently.
> - Applying `sed` for stream editing and text transformation.
> - Automating repetitive data processing tasks with minimal overhead.

**[ Back to the question in the Table ⬆ ](#table-of-contents)**

---




