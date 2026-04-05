# 📝 Todo Application (Spring Boot)

A simple and clean **Todo Application** built using **Spring Boot, MySQL, and Thymeleaf**.
This project allows users to manage daily tasks with features like adding, deleting, and toggling completion.

---

## 🚀 Features

* ➕ Add new tasks
* ✅ Mark tasks as completed / not completed
* ❌ Delete tasks
* 📋 View all tasks in a clean UI

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Frontend:** Thymeleaf, Bootstrap
* **Database:** MySQL
* **Build Tool:** Maven

---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/todo-app.git
cd todo-app
```

### 2️⃣ Configure MySQL

Create a database:

```sql
CREATE DATABASE todo_app;
```

Update your `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todo_app
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Run the application

```bash
mvn spring-boot:run
```

OR run from IntelliJ

---

## 🌐 Access the App

Open in browser:

```
http://localhost:8080/
```

---

## 📂 Project Structure

```
src/
 ├── main/
 │   ├── java/com/app/todo/
 │   │   ├── Controller/
 │   │   ├── Service/
 │   │   ├── Repository/
 │   │   └── Entity/
 │   └── resources/
 │       ├── templates/
 │       └── application.properties
```

---

## 🔮 Future Improvements

* ✨ Add user authentication (Login/Signup)
* 🌍 REST API version + React frontend
* 📅 Due dates & task priorities
* 📱 Mobile-friendly UI

---

## ⭐ Contribute

Feel free to fork this repo and improve it!
Pull requests are welcome.

---

## 📄 License

This project is open-source and available under the MIT License.
