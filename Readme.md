# Company Employee Portal

## Project Overview

The Company Employee Portal is a simple Django web application that demonstrates the fundamentals of the Django framework using the MVT (Model-View-Template) architecture.

This project includes multiple web pages with navigation, HTML templates, and CSS styling.

---

## Features

* Home Page
* About Page
* Contact Page
* Multi-page Navigation
* Django Templates
* Static CSS Files
* Responsive Navigation Menu
* Django MVT Architecture

---

## Technology Stack

* Python 3
* Django
* HTML5
* CSS3

---

## Project Structure

```text
company_portal/
│
├── manage.py
├── requirements.txt
├── README.md
│
├── company_portal/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── __init__.py
│
├── employees/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   ├── apps.py
│   ├── templates/
│   │   └── employees/
│   │       ├── home.html
│   │       ├── about.html
│   │       └── contact.html
│   │
│   └── static/
│       └── employees/
│           └── css/
│               └── style.css
│
└── venv/
```

---

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project

```bash
cd company_portal
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

---

## URLs

| Page    | URL       |
| ------- | --------- |
| Home    | /         |
| About   | /about/   |
| Contact | /contact/ |
| Admin   | /admin/   |

---

## Project Screens

* Home Page
* About Page
* Contact Page

---

## Learning Objectives

* Understand Django MVT Architecture
* Create Django Applications
* Configure URL Routing
* Create Views
* Render Templates
* Use Static Files
* Implement Multi-page Navigation
* Apply CSS Styling

---

## Future Improvements

* Employee CRUD Operations
* User Authentication
* Database Integration
* Bootstrap UI
* Search Functionality
* Admin Dashboard

---
