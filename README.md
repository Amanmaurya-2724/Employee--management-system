👥 Employee Management System

A simple Employee Management System built with Streamlit and MySQL.
This app allows you to add, view, and search employees easily with a clean web-based interface.

🚀 Features

✅ Add new employees with details like name, email, department, position, salary, hire date
✅ View all employees in a structured table with statistics
✅ Search employees by name, email, or department
✅ Automatic table creation in MySQL
✅ Clean and interactive Streamlit UI

🛠 Tech Stack

Python 🐍

Streamlit (Frontend Web UI)

MySQL (Database)

Pandas (Data formatting & table display)

📂 Project Structure
employee_management.py   # Main application file

⚙️ Setup Instructions
1️⃣ Install Requirements
pip install streamlit mysql-connector-python pandas

2️⃣ Setup MySQL Database

Login to MySQL and create a new database:

CREATE DATABASE company;

3️⃣ Update Database Config in Code

In employee_management.py, update your MySQL username & password:

db_config = {
    'host': 'localhost',
    'database': 'company',
    'user': 'root',       # Change if needed
    'password': 'yourpassword'   # Enter your MySQL password
}

4️⃣ Run the App
streamlit run employee_management.py


App will open in your browser at:
👉 http://localhost:8501

📌 Future Improvements

✏️ Update / Delete employee records

📤 Export employee list to CSV/Excel

🔐 Add login system for admin access

📊 More analytics & dashboards

👨‍💻 Author

Aman Maurya
Aspiring Data Analyst | Python & SQL Enthusiast
