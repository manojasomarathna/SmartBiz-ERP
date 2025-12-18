# SmartBiz-ERP

## 📌 Project Overview

SmartBiz-ERP is a **mini ERP (Enterprise Resource Planning) web application** built to manage basic business operations such as **products, customers, and orders**.
This project was developed as a **full-stack practice project** for internship and interview preparation.

The backend is built using **Django & Django REST Framework**, exposing RESTful APIs that can be consumed by a frontend (React planned).

---

## 🚀 Features

### 🔐 Authentication

* Django Admin authentication
* Superuser access for managing data

### 📦 Product Management

* Add products
* View product list
* Store price & quantity

### 👥 Customer Management

* Add customers
* Store contact details (email, phone)

### 🛒 Order Management

* Create orders by linking customers and products
* Auto-store order date
* Track total order amount

---

## 🛠 Tech Stack

### Backend

* Python
* Django 6.0
* Django REST Framework
* SQLite (development database)

### Version Control

* Git & GitHub

---

## 📂 Project Structure

```
SmartBiz-ERP/
│
├── backend/
│   ├── backend/          # Main Django project settings
│   ├── erp_core/         # Core ERP application (models, views, urls)
│   ├── db.sqlite3        # SQLite database
│   └── manage.py
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/manojasomarathna/SmartBiz-ERP.git
cd SmartBiz-ERP
```

### 2️⃣ Backend Setup

```bash
cd backend
pip install django djangorestframework corsheaders
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Server will start at:
👉 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🌐 API Endpoints

| Resource  | Endpoint          |
| --------- | ----------------- |
| Products  | `/api/products/`  |
| Customers | `/api/customers/` |
| Orders    | `/api/orders/`    |

---

## 🎯 Future Improvements

* React frontend integration
* JWT authentication
* Role-based access control
* Dashboard analytics
* PostgreSQL database

---

## 👨‍💻 Author

**Manoja Somarathna**
GitHub: [https://github.com/manojasomarathna](https://github.com/manojasomarathna)

---

## 📄 License

This project is for **educational and internship preparation purposes**.

# SmartBiz-ERP

Simple ERP system backend built using Django and Django REST Framework.

## Features
- Product management (CRUD)
- Customer management
- Order management
- REST APIs using Django REST Framework
- Admin panel for data management

## Tech Stack
- Python
- Django
- Django REST Framework
- SQLite

## API Endpoints
- GET /api/products/
- POST /api/products/
- GET /api/customers/
- GET /api/orders/

## Admin Panel
- URL: /admin
- Use superuser credentials to manage data

## How to Run
```bash
cd backend
py manage.py migrate
py manage.py runserver
