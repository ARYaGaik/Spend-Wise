Spendwise - Personal Finance Tracker
Spendwise is a modern, full-stack personal finance application designed to help users track their income, expenses, and savings goals. Built with a robust Spring Boot backend and a dynamic React frontend, it features secure authentication, a dark mode aesthetic, and interactive dashboards.

🚀 Features
User Authentication: Secure Signup and Login using JWT (JSON Web Tokens) and BCrypt password encryption.
Dashboards: Interactive visualization of Total Balance, Income, and Expenses.
Transaction Management: Add and delete transactions (Income/Expenses) with ease.
Savings Goals: Create and track progress towards financial goals with visual progress bars.
Dark Mode: Fully responsive UI with a toggleable Dark/Light theme.
Profile Management: View user details and secure logout.
Responsive Design: Built with Tailwind CSS to look great on desktop and mobile.
🛠️ Tech Stack
Frontend
React.js: Component-based UI library.
Vite: Fast build tool and development server.
Tailwind CSS: Utility-first CSS framework for styling.
Lucide React: Beautiful icons.
Axios: For API requests.
React Router: For client-side routing.
Backend
Java Spring Boot: Robust REST API framework.
Spring Security: For authentication and authorization.
Spring Data JPA: For database interaction.
MySQL: Relational database for data persistence.
JWT (io.jsonwebtoken): For stateless security.
Lombok: To reduce boilerplate code.
⚙️ Setup & Installation
Prerequisites
Node.js & npm
Java JDK 17+
Maven
MySQL Server
1. Database Setup
Open MySQL Workbench or CLI.
Create a database named spendwise_db.
CREATE DATABASE spendwise_db;
Update backend/src/main/resources/application.properties with your MySQL username and password.
2. Backend Setup
Navigate to the backend directory.
cd backend
Build the project.
mvn clean package
Run the application.
mvn spring-boot:run
The backend will start on http://localhost:8080.
3. Frontend Setup
Navigate to the frontend directory.
cd frontend
Install dependencies.
npm install
Run the development server.
npm run dev
The frontend will start on http://localhost:5173.
📸 Usage
Open your browser and search for http://localhost:5173.
Sign Up for a new account.
You will be redirected to the Dashboard where you can start adding transactions and goals.
Toggle Dark Mode in the top navigation bar.
🤝 Contributing
Contributions are welcome! Please fork the repository and submit a Pull Request.
