# Employee-management-system
A simple Employee Management System built with Streamlit and MySQL.
This app allows you to add, view, and search employees with a clean UI, data stored in a MySQL database.

🚀 Features
-Add new employees with details like name, email, department, position, salary, hire date
-View all employees in a structured data table with metrics:
-Total Employees
Number of Departments
Average Salary
Search employees by name, email, or department
Data stored securely in a MySQL database

🛠️ Tech Stack
-Frontend: Streamlit
-Backend: Python
-Database: MySQL
-Libraries: streamlit, mysql-connector-python, pandas

📂 Project Structure
employee_management/
│── employee_management.py   # Main Streamlit app
│── README.md                # Documentation

⚙️ Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/Amanmaurya-2724/employee-management-system.git
cd employee-management-system

2️⃣ Install Dependencies
pip install streamlit mysql-connector-python pandas

3️⃣ Configure Database
Create a MySQL database:
CREATE DATABASE company;
Update your database credentials inside employee_management.py:
db_config = {
    'host': 'localhost',
    'database': 'company',
    'user': 'root',
    'password': 'yourpassword'
}

4️⃣ Run the App
streamlit run employee_management.py

🔮 Future Improvements
Update & Delete employees
Department-wise analytics
Secure credentials using .env file

🌐 Deploy on Streamlit Cloud / Heroku

👨‍💻 Author
Developed by Aman kumar maurya
 



