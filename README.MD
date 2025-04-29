# Employee Task Management System

This is a web-based project designed to help administrators manage employees and assign tasks efficiently. The system provides two main panels: one for the *Admin (Administrator)* and one for the *Employee. It is built using **HTML, **CSS, and **JavaScript, and it stores data using the browser's **LocalStorage*.

---

## Project Objective

The main objective of this project is to create a task management system that allows:

- Admin to log in securely
- Admin to add employees with their details
- Admin to assign tasks and track progress
- Tasks to be viewed by employees in their panel

---

## How It Works

- The *Admin Panel* is only accessible by the *administrator*. From here, the admin can:
  - Register/Login
  - Add employees
  - Assign tasks
  - View the number of pending and completed tasks
  - Monitor employee task progress using a progress bar
  - See tasks in a calendar view

- The *Employee Panel* is designed for employees. It is used to:
  - View tasks assigned by the admin
  - (In future versions) update task progress/status

> *Important Note:*  
> This project uses *LocalStorage, so both the admin and employee panels must run in the **same browser/device* for the data to be shared correctly. In future versions, backend integration will allow real-time, multi-device support.

---

## Features

- Admin registration and login
- Dashboard showing total employees, pending & completed tasks
- Add and manage employees
- Assign tasks with deadlines
- Task progress shown via progress bar
- Notifications for new tasks
- Calendar view for task scheduling
- Responsive and modern design with glassmorphism effect
- Logout with redirect to login page

---

## Technologies Used

- *HTML5* – For webpage structure
- *CSS3* – For design and layout (glassmorphism)
- *JavaScript* – For interactivity and logic
- *LocalStorage* – For saving data within the browser

---

## Limitations

- No backend or database; all data stored in LocalStorage
- Only works properly when admin and employee panels are opened in the same browser/device
- Employees cannot yet update task status themselves

---

## Future Enhancements

- Add backend (Node.js + MongoDB or Firebase)
- Employee login system
- Employee ability to update task status
- Email notifications
- Allow multi-device access with real-time syncing

---

## How to Run the Project

1. *Download or Clone* the repository:
   ```bash
   git clone https://github.com/shr-eeya/employee-manage-task.git

 PROJECT BY 
Shreeya Patel
B.Tech - Computer Science Engineering  Lakshmi Narain College Of Technology Excellence
GitHub : shr-eeya

