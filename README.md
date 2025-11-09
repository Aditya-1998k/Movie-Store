# 🎬 Movie Store — Full Stack Django Application

A full-stack **Movie Store web application** built using **Python (Django)** and **Bootstrap**.  
It allows users to browse movies, view details, add them to cart, and place orders — with user authentication, session-based cart management, and responsive UI design.

---

## 🚀 Features

- 🎥 **Movie Listings:** Browse available movies with dynamic images and details  
- 🛒 **Shopping Cart:** Add movies, manage quantities, and view cart summary  
- 👤 **User Authentication:** Signup, login, and logout using Django’s built-in auth system  
- 🧾 **Order Management:** Simple flow for simulating movie purchase  
- 📱 **Responsive Design:** Built with Bootstrap for smooth UX across devices  
- ⚡ **Pagination & Query Optimization:** Efficient movie listing with scalable backend structure  

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Backend** | Python, Django |
| **Frontend** | HTML5, CSS3, Bootstrap |
| **Database** | SQLite |
| **Session & Auth** | Django built-in session framework |
| **Deployment** | PythonAnywhere |
| **Version Control** | Git, GitHub |

---

## 📂 Project Structure
```
Movie-Store/
├── accounts/ # Authentication views and templates
├── cart/ # Cart management logic
├── home/ # Homepage and static content
├── movies/ # Movie models, views, templates
├── moviesstore/ # Project settings, URLs, static and base templates
├── media/ # Uploaded movie images
├── staticfiles/ # Collected static files for production
├── db.sqlite3 # Database file
└── manage.py # Django management script
```

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Aditya-1998k/Movie-Store.git
cd Movie-Store
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Now visit 👉 [http://127.0.0.1:8000/movies/](http://127.0.0.1:8000/movies/  
Live Demo: [pythonanywhere](https://gaditya.pythonanywhere.com/movies/)  

## Key Learning Highlights

- Working with **Django Models, Views, Templates (MVT)** pattern  
- Using **Django sessions** to manage cart and user state  
- Handling **user authentication and form validation**  
- Managing **static and media files** (with `collectstatic` and Pillow image handling)  
- Deploying Django apps on **PythonAnywhere**  


Model Class Diagram
---
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/081c41f2-27a7-49f5-bd4b-18dd7eb90c02" />

MVT Architecture
------
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/570de012-21e4-4ca9-bcd2-dea023e7dba6" />



---

## Author

**Aditya Gupta**  
[aditya98gupta@gmail.com](mailto:aditya98gupta@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/aditya-gupta1998)  
[GitHub](https://github.com/Aditya-1998k)  

