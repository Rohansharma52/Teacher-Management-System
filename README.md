# 📚 Teacher Management System (Spring Boot + JDBC)

A **college-level CRUD web application** developed using **Java Spring Boot**, **JDBC**, **Thymeleaf**, and **Bootstrap**.
This project allows managing teachers' records such as **Add, View, Edit, and Delete** with a clean UI.

---

## 🔥 Features

* Add New Teacher
* View All Teachers
* Update Teacher Details
* Delete Teacher
* Clean & responsive UI (Bootstrap)
* JDBC-based database interaction (No JPA)
* MVC Architecture

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** H2 (In-Memory)
* **Frontend:** HTML, Thymeleaf, Bootstrap
* **Build Tool:** Maven
* **Architecture:** MVC (Model–View–Controller)

---

## 📂 Project Structure

```
teacher-management-system
├── pom.xml
├── src/main/java/com/college/tms
│   ├── TeacherManagementSystemApplication.java
│   ├── controller
│   │   └── TeacherController.java
│   ├── model
│   │   └── Teacher.java
│   └── repository
│       └── TeacherRepository.java
│
├── src/main/resources
│   ├── templates
│   │   ├── index.html
│   │   └── form.html
│   ├── application.properties
│   ├── schema.sql
│   └── data.sql
```

---

## ▶️ How to Run the Project

### Prerequisites

* Java 17+
* Maven
* IDE (IntelliJ / Eclipse / STS)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
```

2. Open project in IDE
3. Run:

```
TeacherManagementSystemApplication.java
```

4. Open browser:

```
http://localhost:8080
```

---

## 🗄️ Database Details (H2)

* **Console URL:** [http://localhost:8080/h2-console](http://localhost:8080/h2-console)
* **JDBC URL:** jdbc:h2:mem:testdb
* **Username:** sa
* **Password:** (empty)

---

## 🧪 Sample Data

The application loads sample teachers automatically using `data.sql`:

* Dr. Sarah Smith – Physics – 8 years
* Mr. John Doe – Mathematics – 5 years

---

## 🎓 College Viva Explanation (Short)

* **Why Spring Boot?**
  → Auto-configuration, easy setup, no XML configuration

* **Why JDBC instead of JPA?**
  → Direct SQL queries, syllabus-friendly, better understanding of DB operations

* **Architecture Used:**
  → MVC (Controller → Repository → Database → View)

---

## 👨‍🎓 Project Type

* College Mini Project
* Suitable for:

  * BCA
  * B.Tech
  * MCA
  * Diploma

---

## ✍️ Author

**Name:** Ritesh Sir
**Project:** Teacher Management System
**Technology:** Spring Boot + JDBC

---

## ✅ Future Enhancements

* MySQL Integration
* REST API Version
* Authentication (Login/Signup)
* Pagination & Search

---

⭐ If you like this project, give it a star on GitHub!
