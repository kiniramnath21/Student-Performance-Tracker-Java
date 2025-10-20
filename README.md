# 🎓 Student Performance Tracker (Java + MySQL)

A console-based project built in **Java** that connects to **MySQL** using JDBC to manage student performance records.

---

## 🚀 Features
- Add Students
- Add Courses
- Enroll Students in Courses
- Assign Grades (Exam/Assignment)
- Generate Student Reports

---

## 🧠 Tech Stack
- **Language:** Java SE 25
- **Database:** MySQL
- **Connector:** MySQL Connector/J 9.4.0
- **IDE:** IntelliJ IDEA

---

## ⚙️ How to Run

1. Create the database:
   ```bash
   mysql -u root -p < sql/create_tables.sql
2. Open the project in IntelliJ IDEA.

3. Update credentials in DatabaseManager.java:
   ```bash
    private static final String URL = "jdbc:mysql://localhost:3306/student_db";
    private static final String USER = "root";
    private static final String PASSWORD = "your_password";

4. Run Main.java and follow the menu.

📁 Project Structure

    StudentPerformanceTracker/
    ├── src/
    │   ├── Main.java
    │   ├── DatabaseManager.java
    │   ├── Student.java
    │   ├── Course.java
    │   └── Grade.java
    ├── sql/
    │   └── create_tables.sql
    ├── README.md
    └── LICENSE

🧩 Sample Output

Database connected successfully!

--- Student Performance Tracker ---
1. Add Student
2. Add Course
3. Enroll Student in Course
4. Assign Grade
5. Generate Student Report
0. Exit

🧑‍💻 Author

Developed by K Ramanath

Final Year B.E Student | Focus: Data Science & AI/ML
