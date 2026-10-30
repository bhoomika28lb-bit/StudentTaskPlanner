# Student Task Planner

## About the Project
Student Task Planner is a web-based application developed to help students organize their academic tasks, manage deadlines, and track their task completion status.

Students can register, log in, add tasks, view their tasks, update task status, and delete tasks.

## Features
- User Registration
- User Login and Logout
- Add New Tasks
- View All Personal Tasks
- Manage Task Deadlines
- Mark Tasks as Completed
- Delete Tasks
- User-specific Task Management

## Technologies Used

**Frontend:**
- HTML
- CSS
- JSP

**Backend:**
- Java
- Servlet API
- JDBC API

**Database:**
- MySQL

**Tools:**
- Eclipse IDE
- Apache Tomcat
- Git and GitHub

## Project Structure

```text
StudentTaskPlanner/
├── src/
│   └── com/studentplanner/
│       ├── connection/
│       ├── dao/
│       ├── dto/
│       └── servlet/
├── WebContent/
│   ├── css/
│   ├── index.jsp
│   ├── register.jsp
│   ├── login.jsp
│   ├── addTask.jsp
│   └── viewTasks.jsp
└── README.md
```

*Adjust the structure above if your actual Eclipse project uses different folders.*

## Database Configuration
1. Create a MySQL database named `student_planner_db`.
2. Create the required `users` and `tasks` tables.
3. Configure your database connection in `DBConnection.java`.
4. Run the application using Apache Tomcat.

## How to Run
1. Clone or download this repository.
2. Import the project into Eclipse.
3. Configure Apache Tomcat.
4. Configure the MySQL database.
5. Run the project on the server.
6. Open the application in your browser.

## Author
Developed as a Java Full Stack project.

## Future Enhancements
- Task search and filtering
- Task priority management
- Study progress tracking
- Dashboard with task statistics
