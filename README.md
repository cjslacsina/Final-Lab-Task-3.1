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

![Image](https://github.com/user-attachments/assets/4686ff05-49ff-4b20-9160-1dcf976e9c49)

2.) Task 2

![Image](https://github.com/user-attachments/assets/5d09607e-bcbf-4750-954d-320f38158ded)
  
3.) Task 3

![Image](https://github.com/user-attachments/assets/6d279f66-a627-42b9-812b-2fd968ea1b85)

4.) Task 4

![Image](https://github.com/user-attachments/assets/aeb94b2c-d063-4493-9fd1-72dde096ea43)

5.) Task 5

![Image](https://github.com/user-attachments/assets/5b046591-9f52-401b-a256-d5c4bddc3df2)

## Output of Query Statements

1.) Task 1

![Image](https://github.com/user-attachments/assets/b475766c-e2b3-4a78-bd4b-012946ba1644)

2.) Task 2

![Image](https://github.com/user-attachments/assets/c60c0983-f88f-49dc-a49f-3103c1dd141c)

3.) Task 3

![Image](https://github.com/user-attachments/assets/7a124482-3e53-498a-a3a0-9e290dbafa5a)

4.) Task 4

![Image](https://github.com/user-attachments/assets/4e0c6412-4974-4071-9b60-b522c0a38312)

5.) Task 5

![Image](https://github.com/user-attachments/assets/3abf42c6-eba4-43a5-838d-80aa3bfb634d)
