# 🛠️ Service Booking Web App

A simple and functional **Service Booking Application** built using **Flask (Python)**, **Jinja2**, **Bootstrap 5**, and **MySQL**.
This app allows users to register, browse available services, and book appointments, while admins can manage services and view bookings through a secure dashboard.

---

## 🚀 Features

### 👤 User Functionality

* Sign up and log in
* View and book available services
* Add optional notes to appointments
* View personal appointment history

### 🔐 Admin Functionality

* Secure admin login
* Add, edit, and delete services (CRUD)
* View all appointments from all users
* View list of registered users
* Access a simple, clean dashboard

---

## 🧱 Tech Stack

* **Flask** – Python micro-framework for backend and routing
* **Jinja2** – Templating engine for dynamic HTML rendering
* **MySQL** – Relational database for storing user, service, and booking data
* **Bootstrap 5** – Responsive frontend styling
* **HTML/CSS/JS** – For interface and interaction
* **Session Management** – Secure login flow for users and admins

---

## 📂 Folder Structure (Simplified)

```
/flask_app/
│
├── app.py                 # Main Flask app
├── conn.py                # DB connection
├── templates/             # Jinja2 templates
│   ├── base.html
│   ├── login_user.html
│   ├── login_admin.html
│   ├── services.html
│   ├── dashboard.html
│   ├── book_service.html
│   └── ...
├── static/
│   └── style.css          # Custom CSS
```

---

## ⚙️ How to Run

1. **Clone this repo**

   ```bash
   git clone https://github.com/yourusername/service-booking-flask.git
   cd service-booking-flask
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Setup your database**

   * Create a MySQL database (e.g., `flask_app_db`)
   * Update `conn.py` with your DB credentials

4. **Run the app**

   ```bash
   python app.py
   ```

5. Visit `http://localhost:5000` in your browser


## 📌 Useful Notes

* Admin and user roles are separated using session management.
* Template inheritance makes the UI consistent across pages.
* Bootstrap provides clean styling and mobile responsiveness.
* Flash messages provide feedback for user actions like booking or login errors.



## 💬 Contributions

Feel free to fork the project and submit PRs for enhancements!
If you're learning Flask, this can be a great base to experiment with role-based access, booking logic, email notifications, or even API integration.

