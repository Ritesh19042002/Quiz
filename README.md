# **Online Quiz Application**

Welcome to the **Online Quiz Application** repository! This project is a full-stack web application designed to create, manage, and take online quizzes. It is built using **Spring Boot** for the backend, **ReactJS** for the frontend, and styled using **Shad CN** for a modern and responsive UI.

## **Table of Contents**
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## **Project Overview**
This application provides an easy-to-use platform where users can:
- Create and manage quizzes.
- Take quizzes with real-time score calculation.
- View quiz results.

The backend is powered by **Spring Boot**, ensuring secure and scalable API endpoints, while the frontend uses **ReactJS** to create a dynamic user interface. **Shad CN** is used for responsive, modern UI components.

## **Features**
- **Quiz Management**: Admins can create, edit, and delete quizzes.
- **Real-Time Quiz**: Users can take quizzes and receive immediate feedback.
- **Leaderboard**: Top users based on quiz performance are displayed.
- **Responsive Design**: Fully optimized for desktop and mobile devices.

## **Technologies Used**
### **Backend**:
- **Spring Boot** - Backend framework for building Java-based applications.
- **Hibernate** - ORM framework to interact with databases.
- **MySQL** - Relational database for storing user and quiz data.
  
### **Frontend**:
- **ReactJS** - JavaScript library for building user interfaces.
- **Axios** - HTTP client for making API requests.
  
### **Styling**:
- **Shad CN** - CSS framework for creating modern, responsive designs.

## **Installation**

### **Prerequisites**
- **Java 17** or later
- **Node.js v14** or later
- **MySQL database**

### **Backend Setup**
1. Clone the repository:
   bash
   git clone https://github.com/yourusername/online-quiz-app.git

2. Navigate to the backend directory:
   bash
   cd online-quiz-app/backend

3. Set up your MySQL database and update the application properties with your database configuration:
   properties
   spring.datasource.url=jdbc:mysql://localhost:3306/yourDatabaseName
   spring.datasource.username=your-username
   spring.datasource.password=your-password

4. Run the backend:
   bash
   ./mvnw spring-boot:run
   
### **Frontend Setup**

1. Navigate to the frontend directory:
   bash
   cd ../frontend

2. Install dependencies:
   bash
   npm install   

3. Run the frontend:
   bash
   npm start

## **Usage**
1. **Open your browser and go to** [http://localhost:3000](http://localhost:3000).
2. **Sign up or log in as a user/admin.**
3. **Start taking quizzes, or if you’re an admin, create and manage quizzes.**


   
