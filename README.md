Mini Task Collaboration App:

Description:

This is a Mini Task Collaboration App developed for a Web Developer Internship assessment. The application allows users to manage tasks collaboratively. It features two types of users: Admin and User. The Admin can view and delete tasks, while the User can create tasks. This app includes user authentication, task management, AJAX interactivity, and a MySQL database.

Features: User Authentication: Admin and User login functionality. Admin Dashboard: Admin can view all tasks and delete tasks, but cannot assign tasks. User Dashboard: Users can create tasks and view tasks assigned to them. Task Management: Admin can manage tasks by deleting them, and users can create tasks. AJAX Interactivity: Real-time updates and seamless user experience. Preloader Animation: A custom preloader animation appears when loading the dashboard page. Technologies Used

Frontend: HTML, CSS, JavaScript, AJAX Backend: PHP Database: MySQL Libraries: GSAP for animations Preloader Animation: Custom animation showing a running figure on a progress bar with the text: "Hold Up Tight, Let's Plan Tasks.
To run this app on your local machine, follow the instructions below:

Clone the repository: git  Navigate into the project folder: cd mini-task-collaboration-app Create a MySQL database and import the schema (database.sql). Update the database connection settings in config.php: define('DB_SERVER', 'localhost'); define('DB_USERNAME', 'root'); define('DB_PASSWORD', ''); define('DB_DATABASE', 'task_collaboration'); Open the project in your browser (if using PHP's built-in server): php -S localhost:8000
