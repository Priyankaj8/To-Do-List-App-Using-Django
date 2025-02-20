# 📌 Django To-Do List App

## **📖 Overview**
This is a **Django-based To-Do List application** that allows users to **create, edit, delete, and mark tasks as complete**. It also includes **user authentication (login, register, logout)** and ensures that users can only access their own tasks. The application is styled using **CSS** for a clean and user-friendly interface.

## **🚀 Features**
- ✅ **CRUD Operations** (Create, Read, Update, Delete tasks)
- ✅ **User Authentication** (Login, Register, Logout)
- ✅ **User-Specific Task Management** (Users can only see their own tasks)
- ✅ **Task Completion Tracking** (Mark tasks as complete/incomplete)
- ✅ **Security Measures** (Login required to access tasks)
- ✅ **Responsive Design with CSS**

## **🛠️ Technologies Used**
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** SQLite (default, can be changed to PostgreSQL/MySQL)
- **Authentication:** Django's built-in authentication system

---

## **📂 Project Structure**
```
todo_list/
│── base/                 # Django App
│   ├── migrations/       # Database Migrations
│   ├── templates/base/   # HTML Templates
│   │   ├── main.html
│   │   ├── task_list.html
│   │   ├── task_form.html
│   │   ├── task_confirm_delete.html
│   │   ├── login.html
│   │   ├── register.html
│   ├── static/css/       # CSS Files
│   ├── models.py         # Task Model
│   ├── views.py          # CRUD & Authentication Views
│   ├── urls.py           # URL Routing
│── todo_list/            # Project Settings
│   ├── settings.py
│   ├── urls.py
│── manage.py             # Django Management Script
│── db.sqlite3            # SQLite Database (default)
```

---

## **⚙️ Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/todo-list-django.git
cd todo-list-django
```

### **2️⃣ Create and Activate a Virtual Environment**
```bash
python -m venv env
source env/bin/activate  # For Mac/Linux
env\Scripts\activate    # For Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Apply Migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

### **5️⃣ Create a Superuser (Optional for Admin Access)**
```bash
python manage.py createsuperuser
```

### **6️⃣ Run the Development Server**
```bash
python manage.py runserver
```

✅ **Now, open `http://127.0.0.1:8000/` in your browser!** 🚀

---

## Screenshots
**Login Page**  
![image](https://github.com/user-attachments/assets/bf32e5af-e43a-4e43-b747-c809c1d86cbd)  

**Invalid Login**  
![image](https://github.com/user-attachments/assets/3fffecec-f182-416e-bedd-501f5de49468)  


**Register Page**  
![image](https://github.com/user-attachments/assets/b3f0d1a8-23c2-4c8c-a27e-c5132067ac5e)  

**To-Do List Page**  
![image](https://github.com/user-attachments/assets/d1d5e378-f0e7-4f6c-8d93-fab59d1fade8)  

---

## **📌 Usage Guide**
1️⃣ **Register an account** (or log in if you already have one).  
2️⃣ **Create a new task** by clicking the **“Add Task”** button.  
3️⃣ **Edit or delete** tasks using the provided buttons.  
4️⃣ **Mark tasks as complete** to keep track of progress.  
5️⃣ **Logout securely** using the logout button.  

---

## **🚀 Future Enhancements**
- ✅ **Task Filtering & Search** (By completion status or title)
- ✅ **Due Dates & Reminders**
- ✅ **Priority Levels for Tasks**
- ✅ **Drag-and-Drop Task Reordering**

---

## **📜 License**
This project is licensed under the **MIT License**.

---

## **💡 Contributing**
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to improve.
