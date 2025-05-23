# Final-Lab-Task-3.1
- This portfolio uses MySQL queries to illustrate fundamental SQL skills. It includes retrieving, aggregating, and sorting data according to an existing dataset in order to manage an online course database.

# Step By Step Process:
**Step 1: Create the Database**  
- Open your MySQL environment (e.g., MySQL Workbench or phpMyAdmin).  
- Create a new database with the command:  
  `CREATE DATABASE online_courseDB;`  
  This sets up the main storage for your course data.

**Step 2: Select the Database**  
- Switch to the newly created database:  
  `USE online_courseDB;`  
  This ensures all future operations are performed within the correct database.

**Step 3: Load the Initial Data**  
- Download the `onlineCourse.l` file as instructed.  
- Run or import the file into your MySQL environment. This will:  
  - Create a `courses` table  
  - Insert 20 course records  
  - Include the following fields:  
    - `id`: auto-incremented primary key  
    - `course_name`: VARCHAR, not null  
    - `category`: VARCHAR, not null  
    - `enrollment_limit`: INTEGER, not null  
    - `students_enrolled`: INTEGER, not null  

**Step 4: Complete the SQL Tasks**

- **Task 1: Courses Below Capacity**  
  - Display courses with fewer enrolled students than the limit  
  - *SQL concept:* `SELECT` with `WHERE`

- **Task 2: Group by Category**  
  - Group courses by category and show the total enrolled students per group  
  - *SQL concepts:* `GROUP BY`, `SUM()`

- **Task 3: Fully Enrolled Courses**  
  - Show courses where enrollment meets the maximum limit  
  - *SQL concept:* `WHERE` with equality condition

- **Task 4: Total Enrollment**  
  - Calculate total enrolled students across all courses  
  - *SQL concept:* `SUM()` aggregation

- **Task 5: Sort by Enrollment**  
  - Display courses in ascending order based on number of enrolled students  
  - *SQL concept:* `ORDER BY` ascending

**Final Step: Review Outputs**  
- Confirm each query gives the correct result  
- Ensure all field names are accurate and data is consistent

# Screenshots
## Query Statements

1.) Task 1
- ![Image]()

2.) Task 2
- ![Image]()
  
3.) Task 3
- ![Image]()

4.) Task 4
- ![Image]()

5.) Task 5
- ![Image]()

## Output of Query Statements

1.) Task 1
- ![Image]()

2.) Task 2
- ![Image]()

3.) Task 3
- ![Image]()

4.) Task 4
- ![Image]()

5.) Task 5
- ![Image]()
