# 🧾 freeCodeCamp SQL Bash Script Part 2

## 📘 Overview
This Bash script connects to a `students` PostgreSQL database** and executes a series of SQL queries to retrieve detailed information about students, majors, and courses.  
It uses the `psql` command-line tool to query data and display formatted results directly in the terminal.

---

## ⚙️ Requirements
Before running this script, ensure that you have:

- 🐘 **PostgreSQL** installed and running  
- A database named **`students`** (created in the FreeCodeCamp Relational Database course)  
- A PostgreSQL user named **`freecodecamp`** with access to the database  
- The following tables present and populated:
  - `students`
  - `majors`
  - `majors_courses`
  - `courses`

---

## 🚀 How to Run

1. Save the script as `students_info.sh`
2. Make it executable:
   ```bash
   chmod +x students_info.sh
   ````
3. Run the script:
   ./students_info.sh
4. The script will connect to the PostgreSQL database and display results for each query.

## 👨‍💻 Author

Created by: Hugo Rocha
