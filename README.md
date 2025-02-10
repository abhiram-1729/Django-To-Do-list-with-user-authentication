# Django To-Do List with User Authentication

A **To-Do List Web Application** built using **Django** that allows users to **register, log in, and manage their tasks** securely. Each user has a **personalized dashboard** where they can create, update, mark as complete, and delete tasks. The system ensures that **users can only see their tasks** by implementing authentication and user-specific task filtering.

## Table of Contents  

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Setting Up the Project](#setting-up-the-project)  
5. [Usage](#usage)  
   - [User Authentication](#user-authentication)  
   - [Managing Tasks](#managing-tasks)  
6. [Next Steps](#next-steps)  

---

## 1. Introduction  

This Django project provides a secure and user-friendly to-do list application with **user authentication**. Each user can create, update, delete, and view their own tasks.

---

## 2. Features  

- **User Authentication:**  
  - Secure user registration, login, and logout.  
  - Passwords are hashed for security.

- **User-Specific Tasks:**  
  - Each user has their own task list.  
  - Tasks are only visible to the logged-in user.

- **CRUD Operations on Tasks:**  
  - Create, read, update, and delete tasks.

- **Task Status Tracking:**  
  - Mark tasks as completed or pending.

- **Responsive UI:**  
  - A mobile-friendly design using **Bootstrap**.

---

## 3. Technologies Used  

- **Backend:** Django  
- **Database:** SQLite / PostgreSQL  
- **Frontend:** HTML, CSS, Bootstrap  
- **Security:** Django’s built-in authentication, CSRF protection  
- **Other:** Django Class-Based Views (CBVs), Django Forms  

---

## 4. Getting Started  

### 4.1 Prerequisites  

Make sure you have the following installed:  

- **Python (3.8 or higher)**  
- **pip (Python package manager)**  
- **Django (latest version)**  

### 4.2 Setting Up the Project  

1. **Create a Virtual Environment:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate  # For Windows
