
# 🚀 Capstone-Portal

Welcome to **Capstone-Portal**! This project combines a powerful **React.js** frontend with a robust **Spring Boot** backend to deliver a seamless experience.

## 🛠️ Project Setup

Follow these instructions to set up and run the project on your local machine.

### **Frontend Setup (React.js)**

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Access the frontend at:
   ```
   http://localhost:3000
   ```

### **Backend Setup (Spring Boot)**

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Update the database credentials in `application.properties`:
   - Set your **username** and **password** for the database.
   - Create the required database.

3. Provide your Gmail and app password for email functionality.

4. Build the project:
   ```bash
   ./mvnw clean install   # For Linux/Mac
   mvnw.cmd clean install # For Windows
   ```

5. Start the Spring Boot server:
   ```bash
   ./mvnw spring-boot:run   # For Linux/Mac
   mvnw.cmd spring-boot:run # For Windows
   ```

6. Access the backend server at:
   ```
   http://localhost:8080
   ```

## 📂 Project Structure

```
Capstone-Portal/
├── frontend/       # React.js frontend
│   ├── src/        # Source code
│   ├── public/     # Static files
│   ├── package.json
│   └── ...         
├── backend/        # Spring Boot backend
│   ├── src/        # Source code
│   ├── pom.xml     # Maven configuration
│   └── ...
└── README.md       # Project documentation
```

## ⚙️ Technologies Used

### Frontend:
- React.js
- HTML, CSS, JavaScript
- Axios for API communication

### Backend:
- Spring Boot
- Java
- Maven

### Tools:
- Visual Studio Code / IntelliJ IDEA
- Postman for API testing

## 🌟 Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add YourFeatureName"
   ```
4. Push the changes:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a Pull Request.

## 📧 Contact

- **Developer:** [Aditya Mishra](https://www.linkedin.com/in/aditya-mishra-56b26522b/)
- **GitHub:** [@adimishra16](https://github.com/adimishra16)

## 🎉 Thank You!

Thank you for checking out **Capstone-Portal**! If you find it useful, don’t forget to ⭐ the repository.
