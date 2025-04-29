"# manages-task-of-employee.github.io" 
# Employee Task Management System

This is a web-based task management system developed for managing employees and assigning tasks efficiently. It is designed for administrators to register, add employees, assign tasks, and monitor progress. The application is built using *HTML, **CSS, and **JavaScript* and uses *LocalStorage* to store all data.

---

## Project Objective

The main objective of this project is to create a simple, responsive platform where:

- *Admin* can register and log in
- *Admin* can add employees
- *Admin* can assign tasks with deadlines
- Task status can be viewed as *Pending* or *Completed*
- Progress can be tracked using a visual progress bar

---

## Features

- Admin registration and login
- Admin dashboard with:
  - Total number of employees
  - Pending tasks
  - Completed tasks
- Add and manage employee details
- Assign tasks with deadline
- Task progress tracking using progress bar
- Notifications for employees
- Calendar view for tasks
- Responsive design using glassmorphism UI
- Logout functionality

---

## Technologies Used

- *HTML5* – For structuring the pages
- *CSS3* – For design, layout, and glassmorphism style
- *JavaScript* – For logic and interaction
- *LocalStorage* – To store data like employee info, tasks, and status in the browser

---

## How It Works

- The *admin panel* is used by the administrator to manage the system.
- Tasks assigned by the admin are stored in the browser using *LocalStorage*.
- The *employee panel* can access these tasks from the same browser.
- Since this system is built using LocalStorage, *both panels must run on the same browser* for full functionality.

---

## How to Run the Project

1. Clone or download the project:
   ```bash
   git clone https://github.com/shr-eeya/employee-manage-task.git

1.Open the folder and run the index.html file in your browser
2. Register  as an admin and start using the dashboard.


LIMITATIONS 
. Currently works only on the same browser (LocalStorage-based)
. No database or server backened.
. Employees cannot update task status.


FUTURE ENHANCEMENTS 
. Add backened using node.js and MongoDB or firebase
. Create separate login for employees
.Enable employees to update task status
. Sync data between different devices
. Send email notifications



 PROJECT BY 
Shreeya Patel
B.Tech - Computer Science Engineering  Lakshmi Narain College Of Technology Excellence
GitHub : shr-eeya
