

# Microservices ERP System

A comprehensive Enterprise Resource Planning (ERP) system built using a microservices architecture. This application was developed as a capstone graduation project during the Full-Stack Engineering Internship at Konecta. 

## 📖 Project Overview

This ERP system is designed to handle complex business logic and ensure scalable, cross-functional data flow across various departments. Built to mimic real-world enterprise environments, the project was developed in an agile setting through close collaboration with a large, cross-functional team comprising technical, AI, finance, and marketing interns.

## 🚀 Tech Stack

### Frontend
*   **Framework:** Angular
*   **Language:** TypeScript
*   **Styling:** HTML5, CSS3 / SCSS (Add specific UI library if applicable, e.g., Angular Material or Bootstrap)

### Backend (Microservices)
*   **Java Service(s):** Spring Boot
*   **C# Service(s):** .NET Core
*   **Architecture:** Microservices pattern enabling independent scaling, deployment, and maintenance of different business domains.

## ✨ Key Features

*   **Microservices Architecture:** Backend functionality is decoupled into independent services (managed via Spring Boot and .NET) to ensure high availability and scalable cross-functional data flow.
*   **Dynamic Frontend:** A robust Angular SPA (Single Page Application) providing a seamless, interactive dashboard for enterprise users.
*   **Cross-Departmental Integration:** Designed to mimic real corporate workflows, integrating requirements gathered from finance, marketing, and AI teams.
*   **Robust API Design:** Secure and optimized RESTful communication between frontend interfaces and backend services.

## 🤝 Team & Collaboration

This project was built in a simulated corporate environment, requiring active cross-departmental communication. 
*   **Engineering Team:** Responsible for system architecture, database integration, API design, and full-stack implementation.
*   **Cross-Functional Partners:** Worked alongside AI, Finance, and Marketing interns to define business requirements, integrate predictive models, and structure financial data flows.

## 🛠️ Local Development Setup

### Prerequisites
*   [Node.js](https://nodejs.org/) and Angular CLI
*   [Java Development Kit (JDK)](https://www.oracle.com/java/)
*   [.NET SDK](https://dotnet.microsoft.com/)

### Running the Frontend (Angular)
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
ng serve

```


The application will be available at `http://localhost:4200/`.

### Running the Backend Services

**Spring Boot Service:**

1. Navigate to the Spring Boot directory.
2. Build and run the application using Maven or Gradle:
```bash
./mvnw spring-boot:run

```



**.NET Service:**

1. Navigate to the .NET service directory.
2. Build and run the application:
```bash
dotnet build
dotnet run

```

