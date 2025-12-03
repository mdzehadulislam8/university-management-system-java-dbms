# 🎓 University Management System | Java + MySQL

A complete **University Management System (UMS)** built using **Java (Swing)** and **MySQL**.  
This system manages **students, faculty, exams, fees, leave, and admin operations** in a structured and automated way.

🚀 **Ideal for educational institutions, coursework, portfolio projects, and real-world automation.**

---

## 📸 Project Preview  
> *(Replace these with your images — just upload images to GitHub and paste their links here.)*

![Admin Login](https://drive.google.com/uc?export=view&id=1OodZwzAxKeKdMOMakVTuIxJG9x6Ctjjr)
![Dashboard](https://drive.google.com/uc?export=view&id=1ErkbOShoCCvvY5IX3ucl_cE-QsrKMbfm)
![Student Form](https://drive.google.com/uc?export=view&id=1e_RZmTfAYG2qdTnyEl4Nwf6TKUcfIIQ7)

---

## ✨ Key Features

### 🔐 **Admin Panel**
- Secure admin login  
- Centralized dashboard with full control  

### 👨‍🎓 Student Management
- Add / update / view student details  
- Automatic ID generation  
- Leave request handling  
- View academic and personal information  

### 👨‍🏫 Faculty Management
- Add / update / view teacher information  
- Track faculty leave  
- Subject & course assignment  

### 📝 Examination Module
- Enter student marks  
- Auto-calculated results  
- View results using **JOIN operations**  
- Semester-wise marksheets  

### 💰 Fee Management
- Course-wise fee structure  
- Auto fee calculation  
- Generate student payment details  

### 🛢 Database Features
- Fully optimized **MySQL relational schema**  
- Triggers  
- Events  
- Primary/foreign key constraints  
- JOIN operations (left, right)  

### 🛠 Utilities
- Built-in Notepad  
- Calculator  
- About section  

---

## 🏗️ Technology Stack

| Component | Technology |
|----------|------------|
| **Frontend (GUI)** | Java Swing / AWT |
| **Backend** | Java |
| **Database** | MySQL |
| **Tools Used** | JDBC, XAMPP, NetBeans |

---

## 📂 Project Structure

```
/src
  /university.management.system
    Conn.java
    Login.java
    Dashboard.java
    Student.java
    Faculty.java
    Examination.java
    Fees.java
    ...
/database
  ums_schema.sql
  sample_data.sql
/images
  admin-login.png
  dashboard.png
README.md
```

---

## 🗄️ Database Schema (MySQL ER Diagram)
> *(Add your ER diagram image here)*  

```
![ER Diagram](images/er-diagram.png)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install Required Tools  
- MySQL  
- XAMPP / WAMP  
- NetBeans / IntelliJ IDEA  
- JDK 8+  

### 2️⃣ Import the MySQL Database  
```sql
Import `universitymanagementsystem.sql`
```

### 3️⃣ Update Database Connection  
In `Conn.java`:

```java
c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3307/universitymanagementsystem",
    "root",
    ""
);
```

### 4️⃣ Run the Project  
Open project in NetBeans → Run  
Use default admin login:

```
Username: admin
Password: admin123
```

*(Change it from the database for security)*

---

## 🧪 Features Demonstration  
### ✔ Add New Student  
### ✔ Add New Faculty  
### ✔ Update Details  
### ✔ View Records  
### ✔ Enter Marks  
### ✔ Generate Results  
### ✔ Fee Structure  
### ✔ Student Fee Submission  
### ✔ Admin Tools (Calculator / Notepad)

---

## 📊 SQL Operations Used
- **INNER JOIN**
- **LEFT JOIN**
- **RIGHT JOIN**
- **AUTO INCREMENT**
- **TRIGGERS**
- **EVENT SCHEDULER**
- **PRIMARY & FOREIGN KEYS**

---

## 🚀 Future Improvements
- Mobile App (Android)
- More secure authentication
- Cloud database integration
- Modern UI with JavaFX / Web UI
- Automated notifications
- Role-based user access (Admin/Teacher/Student)

---

## 🧑‍💻 Author
**Md. Zehadul Islam**  
CSE, Green University of Bangladesh  
ID: 222902069  

---

## ⭐ Support This Project
If you like this project, please **star this repository** ⭐ on GitHub —  
It motivates me to create more amazing projects!

