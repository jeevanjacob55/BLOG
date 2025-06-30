# BlogMaster - Flask Blogging Platform

A full-featured blogging platform built using Flask, SQLAlchemy, Flask-Login, Flask-WTF, and CKEditor. This project allows users to register, log in, create and edit blog posts, comment on posts, and manage user accounts with secure authentication.

---

## Features

* 🧾 Create, edit, and delete blog posts
* 🔐 Secure user authentication with hashed passwords
* 🧑 Admin-only post creation and editing
* 💬 Comment on blog posts (users only)
* 💻 Responsive UI using Bootstrap 5
* 🎨 Rich-text editing via Flask-CKEditor
* 👤 Profile avatars via Gravatar
* 📆 Auto-stamped post creation dates
* 📄 RESTful routing and clean architecture

---

## Technologies Used

* Python 3.11+
* Flask
* SQLAlchemy
* Flask-Login
* Flask-Bootstrap
* Flask-WTF
* Flask-CKEditor
* Flask-Gravatar
* Werkzeug (for password hashing)
* SQLite

---

## Installation

1. **Clone the repository**

```bash
https://github.com/your-username/blogmaster.git
cd blogmaster
```

2. **Create a virtual environment and activate it**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the app**

```bash
python main.py
```

Open `http://127.0.0.1:5002` in your browser.

---

## Usage

* Register a new account (first user is admin)
* Create new blog posts (admin only)
* Comment on blog posts (users only)
* Edit or delete your posts (admin only)
* Logout securely

---

## Admin Access

* The first user to register becomes the admin (ID = 1).
* Only the admin can create, edit, or delete blog posts.

---

## Future Improvements

* Profile pages for users
* Like/dislike functionality for comments
* Pagination and tags for blog posts
* Email verification and password reset
* Dockerize the application

---

## License

This project is open-source and available under the MIT License.

---
