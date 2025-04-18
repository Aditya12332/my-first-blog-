# 📝 My First Blog – Django Girls Tutorial Project

This is a beginner-friendly blog web app built by following the [Django Girls tutorial](https://tutorial.djangogirls.org/). It introduces the core concepts of Django web development such as models, views, templates, and the admin interface.

## 🌟 Features

- View all blog posts
- Create, edit, and delete posts using the admin panel
- Basic template styling with HTML & CSS
- User-friendly interface for writing blog entries

## 🚀 Getting Started

These instructions will help you run the project locally.

### 1. Clone the repository

bash
git clone https://github.com/Aditya12332/my-first-blog-.git
cd my-first-blog-
2. Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
3. Install dependencies

pip install -r requirements.txt
4. Apply migrations and start the server
bash
Copy
Edit
python manage.py migrate
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to view the blog.

🛠 Tech Stack
Python

Django

SQLite (default Django database)

HTML & CSS

🧑‍💻 Admin Panel
To access the Django admin panel:


python manage.py createsuperuser
Then go to http://127.0.0.1:8000/admin/ and log in.

📦 Requirements
You can generate the requirements.txt with:

bash

pip freeze > requirements.txt
Typical contents:

shell

Django>=5.0,<6.0
📄 License
This project is for educational purposes, inspired by the awesome Django Girls community.

