# Refactoring a Messy Document

## Task 1: Identify Problems

| # | Issue |
|---|-------|
| 1 | No title |
| 2 | No headings or sections |
| 3 | Grammar mistakes |
| 4 | No capitalization |
| 5 | Informal language |
| 6 | Vague instructions |
| 7 | Uncertain wording |
| 8 | No step-by-step procedure |
| 9 | No error handling |
| 10 | Unclear target users |

## Task 2: Conceptual Documentation

### Student Management System

#### 1. Introduction
The Student Management System is a simple application used to manage student records. It allows users to add new students, view existing student records, and delete students who are no longer needed. All student data is stored in a database.

#### 2. Purpose of the System
The system helps schools keep student information organized in one place. It reduces paperwork and makes it faster to find, update, and remove student records.

#### 3. Key Features
- **Add Student:** Create a new student record by entering the student's name and ID.
- **View Students:** Display a list of all students saved in the system.
- **Delete Student:** Remove a student record using the student's ID.
- **Data Storage:** Save all student records in a database so they are not lost when the application is closed.

#### 4. Target Users
- **Administrators:** Manage all student records in the system.
- **Teachers:** View the list of students in their classes.
- **School Staff:** Add or update student information when needed.

## Task 3: Procedural Documentation

### Student Management System (User Guide)

#### 1. How to Open the System
1. Double click the Student Management System icon on your desktop.
2. Wait for the main screen to load.
3. The main screen shows three buttons: **Add Student**, **View Students**, and **Delete Student**.

#### 2. How to Add a Student
1. On the main screen, click **Add Student**.
2. Enter the student's full name in the **Name** field.
3. Enter a unique student ID in the **ID** field.
4. Click **Save**.

#### 3. How to View Students
1. On the main screen, click **View Students**.
2. A list of all saved students appears, showing each student's name and ID.
3. To return to the main screen, click **Back**.

#### 4. How to Delete a Student
1. On the main screen, click **Delete Student**.
2. Enter the ID of the student you want to remove.
3. Click **Delete**.
4. A confirmation message appears: "Are you sure you want to delete this student?"
5. Click **Yes** to confirm.

## Task 4: Reference Documentation

| Function | Input | Output | Description |
|----------|-------|--------|-------------|
| addStudent() | Name, ID | Success or error message | Adds a new student record to the database. |
| viewStudents() | None | List of students (Name, ID) | Displays all student records saved in the database. |
| deleteStudent() | ID | Success or "Student not found" message | Removes the student record that matches the ID. |
| searchStudent() | ID | Student details or "Student not found" message | Finds and displays one student record by ID. |

## Task 5: Before vs After Comparison

| | Before | After |
|---|--------|-------|
| Title | No title | Clear title. |
| Structure | One long paragraph with no headings | Divided into Conceptual, Procedural, and Reference sections with clear headings |
| Language | Informal words like "do stuff", "things", "click around" | Professional and clear language |
| Grammar | Grammar mistakes and no capitalization | Correct grammar, spelling, and capitalization |
| Instructions | Vague: "just click buttons and do stuff" | Numbered step by step instructions for each task |
| Certainty | Uncertain words: "maybe", "or something", "not sure" | Clear statements |
| Error Handling | "if not try again" with no explanation | Notes explain the error messages and what to do |
| Target Users | Users listed with no roles | Each user type has a clear role |
| Data Storage | "data is saved somewhere maybe database" | States clearly that data is stored in a database |
| Technical Details | No information about the system functions | Reference table shows each function, its input, output, and description |