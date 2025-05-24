# Final-Lab-Task-3.1
- This portfolio showcases SQL skills using MySQL queries. It involves retrieving, aggregating, and sorting data from an existing dataset to effectively manage an online course database.

# Step By Step Process:
**Step 1: Create the Database**

* Open your MySQL environment (e.g., MySQL Workbench or phpMyAdmin).
* Create a new database using the command:
  `CREATE DATABASE online_courseDB;`
  This will set up the primary storage for your course data.

**Step 2: Select the Database**

* Switch to the newly created database:
  `USE online_courseDB;`
  This ensures that all subsequent operations are executed within the correct database.

**Step 3: Import Initial Data**

* Download the `onlineCourse.l` file as instructed.
* Import or run the file within your MySQL environment. This will:

  * Create a `courses` table
  * Insert 20 course records
  * Include the following columns:

    * `id`: auto-incrementing primary key
    * `course_name`: VARCHAR, not null
    * `category`: VARCHAR, not null
    * `enrollment_limit`: INTEGER, not null
    * `students_enrolled`: INTEGER, not null

**Step 4: Complete the SQL Tasks**

* **Task 1: Courses Below Capacity**

  * List courses with fewer students enrolled than the enrollment limit.
  * *SQL concept:* `SELECT` with `WHERE`

* **Task 2: Group by Category**

  * Group courses by category and display the total number of students enrolled per group.
  * *SQL concepts:* `GROUP BY`, `SUM()`

* **Task 3: Fully Enrolled Courses**

  * Display courses where the number of enrolled students matches the maximum capacity.
  * *SQL concept:* `WHERE` with equality condition

* **Task 4: Total Enrollment**

  * Calculate the total number of students enrolled across all courses.
  * *SQL concept:* `SUM()` aggregation

* **Task 5: Sort by Enrollment**

  * Display courses ordered by the number of students enrolled, in ascending order.
  * *SQL concept:* `ORDER BY` ascending

**Final Step: Review Results**

* Verify that each query returns the correct result.
* Ensure the field names are correct and the data is consistent.


# Screenshots
## Query Statements

1.) Task 1
- ![Image](https://github.com/user-attachments/assets/196adc4d-fda2-498f-a748-90bcd5a8e93a)

2.) Task 2
- ![Image](https://github.com/user-attachments/assets/60457f8b-f814-440b-8045-69c65c071116)
  
3.) Task 3
- ![Image](https://github.com/user-attachments/assets/cd91bee7-8d8b-41ce-9bcb-1df1fef7a05e)

4.) Task 4
- ![Image](https://github.com/user-attachments/assets/5c78e883-12d3-48c3-b34b-a11e76efe941)

5.) Task 5
- ![Image](https://github.com/user-attachments/assets/225aacc5-85ab-41d7-9157-9231b0a7c65a)

## Output of Query Statements

1.) Task 1
- ![Image](https://github.com/user-attachments/assets/522f4c0f-33ec-4762-848f-751357991336)

2.) Task 2
- ![Image](https://github.com/user-attachments/assets/e3c2b57c-1798-489d-b0be-4ecb1f53b7dc)

3.) Task 3
- ![Image](https://github.com/user-attachments/assets/bc183082-7ec5-45fa-a6df-787c3d11fc32)

4.) Task 4
- ![Image](https://github.com/user-attachments/assets/f528e339-674a-4869-937f-3763002b1298)

5.) Task 5
- ![Image](https://github.com/user-attachments/assets/0e5a2ce5-5823-4318-bd75-461cd5a2fb52)
