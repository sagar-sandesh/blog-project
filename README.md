# 📝 My Personal Blog – Flask Web App

Welcome to **My Blog**, a fully functional blog platform built with **Flask**, **SQLAlchemy**, and **WTForms**. It supports admin authentication, blog post management (CRUD), categories, image uploads, and static pages like About and Contact.

---

## 🚀 Features

- 🏠 Homepage listing all blog posts with images and excerpts
- 🔍 Post detail view with full content and publication info
- 🛠 Admin dashboard to manage posts (Create, Edit, Delete)
- 🔐 Admin login/logout functionality
- 🖼️ Image upload support for blog posts
- 🗃️ Categories for classifying posts
- 📄 Static pages: About, Contact
- 🌐 Responsive Bootstrap 5 frontend

---

## 🛠 Technologies Used

- Python 3.x
- Flask
- Flask-SQLAlchemy
- Flask-WTF
- Flask-Login
- Jinja2 Templates
- SQLite (default DB)
- Bootstrap 5

---

## 📁 Project Structure

myblog/
-│
- ├── app.py
- ├── config.py
- ├── models.py
- ├── forms.py
- ├── static/
- │ ├── css/
- │ │ └── style.css
- │ └── images/
- │ └── uploaded blog images
- ├── templates/
- │ ├── base.html
- │ ├── index.html
- │ ├── post_details.html
- │ ├── login.html
- │ ├── dashboard.html
- │ ├── post_form.html
- │ ├── contact.html
- │ └── about.html
- ├── requirements.txt
- └── README.md

---

## ⚙️ Installation
---
## 📌 Prerequisites

- Python 3.8+
- pip (Python package manager)
- Virtual environment (optional but recommended)
---
## 🧩 Steps

---
#### Clone the repository
```bash
git clone https://github.com/yourusername/myblog.git
cd myblog
```
---
####  Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate     # On Windows use: venv\Scripts\activate
```
---
#### Install dependencies
```bash
pip install -r requirements.txt
```
---
#### Run the app
```bash
python app.py
```
---
---

## 🔐  Admin Login Credentials

Username: admin

Password: adminpass

## ✏️ Usage
Visit the homepage to see latest blog posts.

Admins can:

- Login via /admin/login

- Create/edit/delete posts via the dashboard.

- View individual post details by clicking "Read More".

-Static pages like /about and /contact are always accessible.

### 🧪 Future Improvements
✅ Pagination on homepage

🔍 Search functionality

🧾 Rich-text or Markdown editor for posts

🧑‍🤝‍🧑 Multi-user support with roles

📬 Contact form with Flask-Mail

🧼 XSS protection & content sanitization

## 🙋 Contributing
- Contributions are welcome!

- Fork the repository

- Create a new branch (feature/new-feature)

- Commit your changes

- Open a Pull Request

## 📝 License
This project is licensed under the MIT License.
## 👤 Author
Mr. Sagar Sandesh Oli
📧 olisagarsandesh@gmail.com
📍 Based in Finland 🇫🇮 | Originally from Nepal 🇳🇵
