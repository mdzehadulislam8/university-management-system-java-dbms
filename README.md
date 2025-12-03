# 🎓 University Management System (Java + MySQL)

A complete **University Management System** developed using **Java (Swing GUI)** and **MySQL**.  
This system streamlines university operations such as student & faculty management, examination control, fee processing, and leave tracking.

This project is created for **Database System Lab (CSE-210)** at  
**Green University of Bangladesh**.

---

## Features

### Admin Module
- Secure Admin Login
- Admin Dashboard with full controls
- Add/Edit/Delete Students
- Add/Edit/Delete Teachers
- View all student & teacher details

### Student Management
- Add new student  
- Update student info  
- View student details  
- Manage semester fees  
- Track semester drop/leave

### Teacher Management
- Add new faculty  
- Update teacher info  
- View faculty details  
- Teacher leave handling  

### Examination System
- Insert student marks  
- Fetch results using JOIN operations  
- Subject-wise marks display

### Leave Management
- Student leave submission  
- Teacher leave submission  
- Leave details shown using JOIN queries  

### Fee Management
- View fee structure  
- Auto-calculate semester fee  
- Store all fees in database

### Utilities
- Built-in Notepad  
- Built-in Calculator  
- About System section  

---

## Tech Stack

| Component | Technology |
|----------|------------|
| Language | Java (Swing + AWT) |
| Database | MySQL |
| Connectivity | JDBC |
| IDE Used | NetBeans |
| Server | XAMPP MySQL |

---

## System Architecture

### ER Diagram  
🔶 **Add Image Here** (Example format)  

![ER Diagram](https://drive.google.com/uc?export=view&id=1VDSPsICZrpHKpo8uxWMGwJcDgjOBUGbj)




### Database Schema  
Includes:
- Student Table  
- Teacher Table  
- Leave Tables  
- Fee Structure  
- Marks Table  
- Triggers  
- Join Operations  
- Auto-Increment PKs & FK Relationships  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/University-Management-System-Java-MySQL.git
```

### 2️⃣ Import Database
- Open **phpMyAdmin**
- Create a new database:
```sql
CREATE DATABASE universitymanagementsystem;
```
- Import the provided `.sql` file

### 3️⃣ Configure JDBC  
Inside `Conn.java`:
```java
c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3307/universitymanagementsystem", 
    "root", 
    ""
);
---

### 4️⃣ Run the Project
- Open project in **NetBeans**
- Clean & Build  
- Run  

---

## Screenshots

### Admin Login  
🔶 **Add Image Here**
---
![Admin Login](https://drive.google.com/uc?export=view&id=1OodZwzAxKeKdMOMakVTuIxJG9x6Ctjjr)

---

### Admin Dashboard  
🔶 **Add Image Here**
---
![Admin Dashboard](https://drive.google.com/uc?export=view&id=1ErkbOShoCCvvY5IX3ucl_cE-QsrKMbfm)

---

### Add New Student  
🔶 **Add Image Here**
---
![Add Student](https://drive.google.com/uc?export=view&id=1oZN7ac73Xrw-XXeIe9qcqSLcFFnt_5rc)

---

### Add New Faculty  
🔶 **Add Image Here**
```
![Add Faculty](https://drive.google.com/uc?export=view&id=1HQxCH3bE4KJR_jp_wH9FphKd6zmUjqsh)

---

### Insert Marks  
🔶 **Add Image Here**
```
![Insert Marks](https://your-image-link)
---

### Fee Structure  
🔶 **Add Image Here**
---
![Fee Structure](https://your-image-link)
---

### Leave Details  
🔶 **Add Image Here**

---

## Results & Discussion

The system improves university workflow by:
- Centralizing academic and administrative data  
- Reducing human error through automation  
- Enhancing data accuracy using triggers & joins  
- Ensuring faster access to student/faculty records  
- Providing a full admin-controlled environment  

---

## Future Enhancements
- Mobile App for admin panel  
- Cloud-based database  
- Role-based login (Admin / Teacher / Student)  
- JavaFX modern UI  
- Analytics dashboard  

---

## Developer

**Md. Zehadul Islam**  
Department of Computer Science & Engineering  
Green University of Bangladesh  

