# 📝 Django To-Do List with User Authentication  

A **To-Do List Web Application** built using **Django** that allows users to **register, log in, and manage their tasks** securely. Each user has a **personalized dashboard** where they can create, update, mark as complete, and delete tasks. The system ensures that **users can only see their tasks** by implementing authentication and user-specific task filtering.  

---

## 📌 Table of Contents  

- [📖 Introduction](#-introduction)  
- [✨ Features](#-features)  
- [🛠 Technologies Used](#-technologies-used)  
- [🚀 Getting Started](#-getting-started)  
  - [📋 Prerequisites](#-prerequisites)  
  - [⚙️ Setting Up the Project](#-setting-up-the-project)  
- [📌 Usage](#-usage)  
  - [🔐 User Authentication](#-user-authentication)  
  - [📌 Managing Tasks](#-managing-tasks)  
- [🔮 Next Steps](#-next-steps)  
- [💡 Contributing](#-contributing)  
- [📝 License](#-license)  

---

## 📖 Introduction  

This Django project provides a **secure and user-friendly** to-do list application with **user authentication**.  
Each user can:  
✅ **Register, log in, and log out securely**  
✅ **Create, update, delete, and view their own tasks**  
✅ **Mark tasks as completed or pending**  

---

## ✨ Features  

- 🔐 **User Authentication:** Secure registration, login, and logout with Django's built-in authentication system.  
- 🏷 **User-Specific Tasks:** Each user can see only their tasks.  
- 📜 **CRUD Operations:** Create, read, update, and delete tasks.  
- ✅ **Task Status Tracking:** Mark tasks as completed or pending.  
- 📱 **Responsive UI:** Mobile-friendly design using **Bootstrap**.  
- 🔑 **Secure Password Handling:** Passwords are stored using **Django’s built-in hashing**.  

---

## 🛠 Technologies Used  

| **Technology** | **Purpose** |
|--------------|------------|
| 🐍 Python (v3.8+) | Backend programming language |
| 🌐 Django | Web framework |
| 🗄 SQLite / PostgreSQL | Database management |
| 🎨 HTML, CSS, Bootstrap | Frontend styling |
| 🔐 Django Authentication | Secure user authentication |
| ⚡ Django ORM | Database interaction |

---

## 🚀 Getting Started  

### 📋 Prerequisites  

Make sure you have the following installed:  

- **Python (3.8 or higher)**  
- **pip (Python package manager)**  
- **Django (latest version)**  

---

### ⚙️ Setting Up the Project  

#### **1️⃣ Create a Virtual Environment**  
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows

2️⃣ Install Django
bash
Copy
Edit
pip install django
3️⃣ Create a Django Project
bash
Copy
Edit
django-admin startproject todoproject
cd todoproject
4️⃣ Create a Django App for Tasks
bash
Copy
Edit
python manage.py startapp tasks
5️⃣ Add 'tasks' to Installed Apps in settings.py
python
Copy
Edit
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'tasks',  # Add the tasks app
]
6️⃣ Run Initial Migrations
bash
Copy
Edit
python manage.py migrate
7️⃣ Create a Superuser for Admin Panel
bash
Copy
Edit
python manage.py createsuperuser
Follow the prompts to set up the admin user.

8️⃣ Run the Development Server
bash
Copy
Edit
python manage.py runserver
📌 Open http://127.0.0.1:8000/ in your web browser.

📌 Usage
🔐 User Authentication
Register: Users can create an account via a registration form.
Login: Users can log in and access their tasks.
Logout: Users can securely log out.
📌 Managing Tasks
➕ Create Tasks: Users can add new tasks by providing a title and description.
👀 View Tasks: Users can see their tasks categorized as pending or completed.
✏️ Update Tasks: Users can edit tasks or mark them as completed.
🗑 Delete Tasks: Users can delete tasks when they are no longer needed.
🔮 Next Steps
🚀 Future improvements for the project:

⏳ Task Due Dates & Notifications: Add due dates for tasks with reminders or notifications.
📌 Task Priority Levels: Implement task priorities (High, Medium, Low).
📱 API Support: Use Django REST Framework (DRF) to create an API for mobile support or external integrations.
💡 Contributing
🔹 Contributions are welcome!

Fork the repository
Create a new branch (feature-branch)
Commit changes
Push to your fork
Open a pull request
📝 License
📜 This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Developed with ❤️ using Django

⭐ If you like this project, consider giving it a star on GitHub! ⭐
