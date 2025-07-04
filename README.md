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
│
-├── app.py
-├── config.py
-├── models.py
-├── forms.py
-├── static/
-│ ├── css/
-│ │ └── style.css
-│ └── images/
-│ └── uploaded blog images
-├── templates/
-│ ├── base.html
-│ ├── index.html
-│ ├── post_details.html
-│ ├── login.html
-│ ├── dashboard.html
-│ ├── post_form.html
-│ ├── contact.html
-│ └── about.html
-├── requirements.txt
-└── README.md



---

## ⚙️ Installation

### 📌 Prerequisites

- Python 3.8+
- pip (Python package manager)
- Virtual environment (optional but recommended)
---
### 🧩 Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/myblog.git
cd myblog

# Create a virtual environment
python -m venv venv
source venv/bin/activate     # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```
###🔐 Admin Login Credentials
Username: admin
Password: adminpass
---
###✏️ Usage
