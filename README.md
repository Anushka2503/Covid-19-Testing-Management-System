# 🦠 COVID-19 Testing Management System

**COVID-19 Testing Management System** is a web-based application developed using PHP and MySQL to manage COVID test requests, assignments, and report tracking. It features separate modules for Admin and Users (Patients) and allows centralized handling of test data and reporting.

This project was developed for **academic purposes** to demonstrate the use of server-side scripting and relational databases for real-world healthcare use cases.

---

## 📌 Project Overview

- **Project Title:** COVID-19 Testing Management System  
- **Purpose:** Academic Project  
- **Development Type:** Web application developed during academic learning  

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery, AJAX  
- **Backend:** PHP   
- **Database:** MySQL  
- **Platform:** XAMPP  
- **Compatible Browsers:** Chrome, Firefox, Opera

---

## 👤 User Roles

### 👨‍⚕️ Admin Module
Admin has full control over the system:

- **Dashboard:** View overall test statistics — total, assigned, sample collected, and completed
- **Phlebotomist Management:** Add, update, delete phlebotomist details
- **Test Management:** Assign tests to phlebotomists and update test history
- **Report Generation:** Generate reports by date range or search by order number, name, or mobile
- **Notifications:** Get notified on every new test request
- **Profile Settings:** Update profile, change password, recover password

### 🧑‍💼 User (Patient) Module
Accessible through the website URL:

- **Testing Requests:**
  - **New Users:** Provide personal and test details
  - **Registered Users:** Only test info required; personal info is fetched
- **Report Search:** Search report using order number, name, or mobile number
- **Dashboard:** View state-wise test statistics

---

## 🧪 How to Run the Project

1. Download and unzip the project files  
2. Copy the folder `covid-tms` into your server's root directory:
   - **XAMPP:** `htdocs`
   - **WAMP:** `www`
   - **LAMP:** `var/www/html`
3. Open [phpMyAdmin](http://localhost/phpmyadmin)
4. Create a new database: `covidtmsdb`
5. Import the file `covidtmsdb.sql` from the SQL folder
6. Open your browser and run:  
   ➤ [http://localhost/covid-tms](http://localhost/covid-tms)

---

## 🔐 Admin Credentials

- **Username:** admin  
- **Password:** Test@123

---

## 📸 Screenshots

- New User Testing Page  
  (screenshots/User-Testing.png)

- Admin Dashboard  
  (screenshots/Dashboard.png)

- Test Details  
  (screenshots/Test-Details.png)

- State-wise Dashboard  
  (screenshots/Testing-Dashboard.png)

---

## 📄 Disclaimer

This project was developed purely for **academic demonstration**. It is based on open-source web development practices and is not intended for real-time deployment in healthcare environments.

---

## 👩‍💻 Contributor

- **Anushka Salve** 
