# 🚀 Capstone-Portal

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React.js-61DBFB?logo=react&logoColor=white" alt="React Badge"/>
  <img src="https://img.shields.io/badge/Backend-Spring%20Boot-6DB33F?logo=springboot&logoColor=white" alt="Spring Boot Badge"/>
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL Badge"/>
  <img src="https://img.shields.io/badge/Build-Maven-C71A36?logo=apachemaven&logoColor=white" alt="Maven Badge"/>
</p>

<p align="center">
  <b>Capstone-Portal</b> is a full-stack web platform built with <b>React.js</b> (frontend) and <b>Spring Boot</b> (backend) 
  to streamline project management, evaluation, and communication for academic or enterprise capstone initiatives.
</p>

---

## 🧭 Table of Contents
- [🌟 Features](#-features)
- [🛠️ Project Setup](#️-project-setup)
  - [Frontend (React.js)](#frontend-reactjs)
  - [Backend (Spring-Boot)](#backend-spring-boot)
- [📁 Project Structure](#-project-structure)
- [⚙️ Technologies Used](#️-technologies-used)
- [🤝 Contributing](#-contributing)
- [📧 Contact](#-contact)
- [⭐ Acknowledgments](#-acknowledgments)

---

## 🌟 Features

✅ Modern React.js-based UI with responsive design  
✅ Secure RESTful APIs built with Spring Boot  
✅ Email notifications via Gmail SMTP  
✅ Separate local dev servers for frontend & backend  
✅ Easy configuration and modular architecture  
✅ Ready for containerization and CI/CD setup  

---

## 🛠️ Project Setup

### 🧩 Frontend (React.js)

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install all dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Visit the frontend at:
   ```
   http://localhost:3000
   ```

---

### ⚙️ Backend (Spring Boot)

1. Navigate to the backend folder:
   ```bash
   cd backend
   ```

2. Update your database configuration in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/<your_database_name>
   spring.datasource.username=<your_username>
   spring.datasource.password=<your_password>
   ```

3. Add your Gmail and App Password for email functionality:
   ```properties
   spring.mail.username=<your_gmail>
   spring.mail.password=<your_app_password>
   ```

4. Build the backend:
   ```bash
   ./mvnw clean install   # Linux/Mac
   mvnw.cmd clean install # Windows
   ```

5. Run the application:
   ```bash
   ./mvnw spring-boot:run   # Linux/Mac
   mvnw.cmd spring-boot:run # Windows
   ```

6. Access the backend API:
   ```
   http://localhost:8080
   ```

---

## 📂 Project Structure

```
Capstone-Portal/
├── frontend/                # React.js Frontend
│   ├── src/                 # React source code
│   ├── public/              # Static assets
│   ├── package.json
│   └── vite.config.js
│
├── backend/                 # Spring Boot Backend
│   ├── src/                 # Java source code
│   ├── pom.xml              # Maven configuration
│   └── application.properties
│
└── README.md                # Project Documentation
```

---

## ⚙️ Technologies Used

### 🖥️ Frontend:
- **React.js**
- **Vite**
- **Axios**
- **React Router**
- **Bootstrap / Tailwind CSS**

### ⚙️ Backend:
- **Spring Boot**
- **Spring Data JPA**
- **MySQL Database**
- **Java 17+**
- **Maven Build System**

### 🧰 Tools & Utilities:
- **VS Code / IntelliJ IDEA**
- **Postman** for API testing
- **Git + GitHub** for version control

---

## 🤝 Contributing

We welcome contributions!  
To contribute, follow these steps:

1. **Fork** the repository  
2. **Create a new branch**  
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make your changes and commit**
   ```bash
   git commit -m "Add YourFeatureName"
   ```
4. **Push to your branch**
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open a Pull Request**

> 💡 *Make sure your code follows project style guidelines and passes all build tests.*

---

## 📧 Contact

👤 **Developer:** [Aditya Mishra](https://www.linkedin.com/in/aditya-mishra-56b26522b/)  
💻 **GitHub:** [@adimishra16](https://github.com/adimishra16)  
📩 **Email:** aditya.mishra@example.com  

---

## ⭐ Acknowledgments

Thanks for checking out **Capstone-Portal**!  
If you find it useful, consider giving the repo a ⭐ and sharing it with others 🚀  
