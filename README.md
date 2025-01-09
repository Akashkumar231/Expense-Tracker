# Expense Tracker

Expense Tracker is a full-stack microservices-based application designed to simplify expense management. It features AI-driven categorization, automated financial reports, and a responsive user interface. This project showcases modern software engineering practices, including microservices, AI/ML integration, and containerization.

---

## 🌟 Features

- **Expense Tracking**: Add, view, update, and delete daily expenses.
- **AI-Powered Categorization**: Automatically classify expenses into categories like Food, Travel, Utilities, etc.
- **Monthly Reports**: Generate detailed financial summaries with charts and insights.
- **Secure Authentication**: JWT-based authentication and authorization.
- **Responsive Design**: Accessible on mobile and desktop devices.
- **Scalable Architecture**: Microservices for modular, maintainable development.
- **Containerized Deployment**: Dockerized services for seamless deployment.

---

## 🛠️ Technology Stack

### **Frontend**

- **React.js**: Dynamic, responsive UI.
- **Redux**: State management.
- **TailwindCSS/Bootstrap**: Modern styling.

### **Backend**

- **Spring Boot**: RESTful APIs and business logic.
- **PostgreSQL/MySQL**: Relational database management.
- **Spring Security**: Secure authentication.

### **AI/ML**

- **Python**: ML model for categorization.
- **Scikit-learn/PyTorch**: Model training and inference.
- **Flask**: Exposes the ML model as a microservice.

### **DevOps**

- **Docker**: Containerization of services.
- **Docker Compose**: Multi-container application orchestration.
- **Postman**: API testing and debugging.

---

## 📂 Project Structure

Expense-Tracker/
│ ├── frontend/ # React.js-based frontend
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Application pages
│ │ ├── redux/ # State management files
│ │ └── styles/ # CSS/Tailwind styles
│ └── public/
│ ├── backend/
│ ├── user-service/ # User management microservice
│ ├── expense-service/ # Expense management microservice
│ ├── report-service/ # Report generation microservice
│ ├── ai-service/ # AI categorization service
│ └── common/ # Shared utilities and configs
│ ├── database/ # Database schemas and scripts
│ ├── docker/ # Docker configuration files
│ └── README.md
