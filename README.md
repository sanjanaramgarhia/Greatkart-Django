# 🛒 GreatKart - Django E-Commerce Application

A full-featured E-Commerce web application built with Django that simulates a real-world online shopping platform. The project includes user authentication, product management, shopping cart functionality, PayPal payment integration, order processing, product reviews, and user profile management.

---

## 🚀 Project Overview

GreatKart is a scalable e-commerce platform designed to provide a seamless online shopping experience. Users can browse products, search and filter items, add products to their cart, complete purchases using PayPal Sandbox, submit product reviews, and manage their accounts through a personalized dashboard.

This project demonstrates practical implementation of Django's MVT architecture, database design, authentication systems, payment workflows, and business logic commonly used in production-grade applications.

---

## ✨ Key Features

### 👤 User Authentication & Account Management

* User Registration
* Secure Login & Logout
* Email-Based Account Activation
* Password Reset Functionality
* User Dashboard
* Edit Profile
* Change Password
* Manage Account Details

---

### 🛍 Product Management

* Product Categories & Subcategories
* Product Listings
* Product Detail Pages
* Product Availability Management
* Product Image Gallery
* Featured Products

---

### 🔍 Search & Navigation

* Product Search
* Category-Based Filtering
* Keyword Search
* Dynamic Product Browsing

---

### 🛒 Shopping Cart System

* Add Products to Cart
* Update Product Quantity
* Remove Products from Cart
* Cart Total Calculation
* Session-Based Cart Management

---

### 💳 PayPal Payment Integration

* PayPal Sandbox Integration
* Secure Checkout Workflow
* Payment Verification
* Order Completion Process
* Payment Status Tracking

> Implemented end-to-end payment processing using PayPal Sandbox accounts to simulate real-world e-commerce transactions and checkout workflows.

---

### 📦 Order Management

* Place Orders
* Order Confirmation
* Order Summary
* Order History
* Order Tracking

---

### ⭐ Reviews & Ratings

* Product Reviews
* Product Rating System
* Review Submission
* Customer Feedback Management

---

### ⚙️ Admin Features

* Product Management
* Category Management
* User Management
* Order Management
* Review Moderation
* Inventory Monitoring

---

## 🏗 Project Structure

```text
GreatKart-Django/
│
├── accounts/          # Authentication & User Management
├── carts/             # Shopping Cart Functionality
├── category/          # Product Categories
├── orders/            # Order Processing & Payments
├── store/             # Product Management
│
├── templates/         # HTML Templates
├── static/            # CSS, JS, Images
│
├── greatcart/         # Project Configuration
├── manage.py
└── requirements.txt
```

---

## 🛠 Tech Stack

### Backend

* Python
* Django

### Database

* SQLite

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

### Payment Gateway

* PayPal Sandbox

### Version Control

* Git
* GitHub

---

## 📸 Application Screenshots

Create a folder named:

```text
screenshots/
```

Add screenshots such as:

```text
screenshots/
├── homepage.png
├── category-page.png
├── product-detail.png
├── cart.png
├── checkout.png
├── paypal-payment.png
├── dashboard.png
├── orders.png
└── reviews.png
```

Then display them in the README:

```md
## Home Page

![Home Page](screenshots/homepage.png)

## Product Detail Page

![Product Detail](screenshots/product-detail.png)

## Shopping Cart

![Cart](screenshots/cart.png)

## PayPal Checkout

![PayPal Checkout](screenshots/paypal-payment.png)
```

---

## ⚡ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/sanjanaramgarhia/Greatkart-Django.git
cd Greatkart-Django
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

---

## 🎯 Skills Demonstrated

This project demonstrates:

* Django MVT Architecture
* Database Modeling
* Django ORM
* Authentication & Authorization
* Session Management
* Payment Gateway Integration
* E-Commerce Business Logic
* CRUD Operations
* User Profile Management
* Review & Rating Systems
* Search & Filtering
* Order Processing Workflows
* Git & GitHub

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Building production-style Django applications
* Designing scalable database relationships
* Implementing secure authentication systems
* Developing shopping cart and checkout workflows
* Integrating third-party payment services
* Managing user-generated content and reviews
* Handling real-world business requirements

---

## 🔮 Future Improvements

* Django REST Framework API
* Stripe / Razorpay Integration
* Wishlist Functionality
* Coupon & Discount System
* Product Recommendation System
* Docker Support
* PostgreSQL Deployment
* CI/CD Pipeline

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit a pull request.

---

## ⭐ Support

If you found this project helpful, please consider giving it a star on GitHub.

Happy Coding! 🚀
