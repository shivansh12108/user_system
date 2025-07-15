# user_system
# User Signup and Login System using Flask, HTML, CSS, JavaScript, and MySQL

This project is a **User Signup and Login system** built with:

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Database**: MySQL (using XAMPP server)

After signup and login, users are redirected to a **user home page (`user.html`)** upon successful authentication.

## Features

✅ User registration with form validation  
✅ User login with credential verification  
✅ User dashboard (`user.html`) after login  
✅ Password hashing for security (if implemented)  
✅ MySQL database integration  
✅ Simple, clean, and beginner-friendly structure

---

## Project Structure

project-folder/
│
├── app.py # Flask application entry point
├── db.sql # SQL file for creating the database and users table
│
├── templates/
│ ├── signup.html # User signup page
│ ├── login.html # User login page
│ └── user.html # User home page after login
│
└── static/
├── css/
│ └── styles.css # CSS styles
└── js/
└── scripts.js # JavaScript scripts if needed

---

## Prerequisites

✅ **Python 3.x**  
✅ **Flask** (`pip install flask`)  
✅ **MySQL with XAMPP**  
✅ **MySQL connector** (`pip install flask-mysqldb`)

---

## Database Setup

1️⃣ Start your **XAMPP server** (Apache and MySQL).  
2️⃣ Open **phpMyAdmin** (`http://localhost/phpmyadmin`).  
3️⃣ Create a **new database** (e.g., `user_system`).  
4️⃣ Import `db.sql` to create necessary tables:

- Click on your database > Import > Select `db.sql` > Go.

---

## Running the Project

1️⃣ Clone this repository:

```bash
git clone https://github.com/shivansh12108/user_system.git
cd user_system
## Install dependencies:

pip install flask flask-mysqldb
## Update your database connection details in app.py:
app.config['MYSQL_HOST'] = 'localhost'
app.config['MYSQL_USER'] = 'root'
app.config['MYSQL_PASSWORD'] = ''
app.config['MYSQL_DB'] = 'user_system'
## Run the Flask app:
python app.py
 Open your browser and go to http://127.0.0.1:5000.
Usage
✅ Go to /signup to create a new user account.
✅ Log in using /login.
✅ After successful login, you will be redirected to user.html (home page).




