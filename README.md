# 🔐 Digital Locker System

![React](https://img.shields.io/badge/React-18-blue)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Backend-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Jest](https://img.shields.io/badge/Tested%20with-Jest-red)
![License](https://img.shields.io/badge/license-MIT-green)

A full-stack document management web application built with **React.js** (frontend), **Spring Boot** (backend REST API), and **MySQL** (local database). Users can securely upload, view, and manage their digital documents in one place — no third-party storage, no complexity.

---

## 🔗 Live Demo
🎥 Demo Video: [Watch Demo](#)

---

## ✨ Features

* Upload and securely store digital documents
* View and manage all uploaded documents
* Seamless page navigation via React Router
* Fast API communication using Axios
* Clean, responsive user interface
* Dynamic rendering with React state management

---

## 🛠️ Tech Stack

* **Frontend:** React.js, React Router DOM, Axios, CSS
* **Backend:** Spring Boot, REST APIs
* **Database:** MySQL (local)
* **Testing:** Jest, React Testing Library

---

## 📂 Project Structure

```
digital-locker-system/
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── UploadDocument.jsx
│   │   │   └── DocumentList.jsx
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── backend/
│   └── src/main/java/
│       ├── Controller/
│       ├── Service/
│       ├── Entity/
│       └── Repository/
└── README.md
```

---

## ⚙️ Setup & Installation

### 🗄️ 1. Database Setup (MySQL)

```sql
CREATE DATABASE digital_locker_db;
```

Update `backend/src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/digital_locker_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 🖥️ 2. Backend (Spring Boot)

```bash
cd backend
mvn spring-boot:run
```

Backend runs at: `http://localhost:8080`

### 🌐 3. Frontend (React)

```bash
cd frontend
npm install
npm start
```

Frontend runs at: `http://localhost:3000`

---

## 🔭 Future Enhancements

* JWT Authentication & Role-Based Access Control
* Document download and deletion from UI
* File type validation and size limits
* Cloud storage integration (AWS S3 / Firebase)
* Docker containerization for easy deployment
* Global error handling and input validation

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
