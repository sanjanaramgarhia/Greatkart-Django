# 🛒 GreatKart - Django E-Commerce Application

A full-featured E-Commerce web application built with Django that simulates a real-world online shopping platform. The application includes user authentication, product management, shopping cart functionality, PayPal payment integration, order processing, product reviews, ratings, and user profile management.

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
* Account Management

### 🛍 Product Management

* Product Categories
* Product Listings
* Product Detail Pages
* Product Image Gallery
* Featured Products

### 🔍 Search & Navigation

* Product Search
* Category Filtering
* Keyword Search
* Dynamic Product Browsing

### 🛒 Shopping Cart System

* Add Products to Cart
* Update Product Quantity
* Remove Products from Cart
* Cart Total Calculation
* Session-Based Cart Management

### 💳 PayPal Integration

* Secure Checkout
* PayPal Sandbox Integration
* Payment Verification
* Order Completion Workflow

### ⭐ Reviews & Ratings

* Product Ratings
* Customer Reviews
* Feedback Management

---

# 📸 Application Screenshots

## 🏠 Homepage

The homepage provides featured products, categories, and promotional content to help users quickly explore the store.

<img src="images/homepage.png" width="900" alt="Homepage">

---

## 🛍 Store Page

Users can browse products, explore categories, and search for items efficiently.

<img src="images/store.png" width="900" alt="Store Page">

**Features Shown:**

* Product Listings
* Category Navigation
* Search Functionality
* Product Cards

---

## 👤 User Dashboard

The dashboard allows users to manage profiles, view order history, and update account information.

<img src="images/dashboard.png" width="900" alt="Dashboard">

**Features Shown:**

* User Profile Management
* Order History
* Account Settings
* Personal Dashboard

---

## 📄 Billing & Checkout

Customers can review their order details and enter billing information before completing payment.

<img src="images/billing-page.png" width="900" alt="Billing Page">

**Features Shown:**

* Billing Information
* Shipping Details
* Order Summary
* Checkout Workflow

---

## 💳 PayPal Payment Gateway

Integrated PayPal Sandbox enables secure payment processing and simulates real-world transactions.

<img src="images/paypal-payment.png" width="900" alt="PayPal Payment">

**Features Shown:**

* Secure Payment Processing
* PayPal Integration
* Transaction Verification
* Order Confirmation

---

## ⭐ Ratings & Reviews

Customers can leave reviews and ratings for products, helping future buyers make informed decisions.

<img src="images/rating-review.png" width="900" alt="Ratings and Reviews">

**Features Shown:**

* Product Ratings
* Customer Reviews
* Review Submission
* Feedback Management

---

## 🏗 Project Structure

```text
GreatKart-Django/
│
├── accounts/
├── carts/
├── category/
├── orders/
├── store/
│
├── templates/
├── static/
├── images/
│
├── greatcart/
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

## ⚡ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/sanjanaramgarhia/Greatkart-Django.git
cd Greatkart-Django
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
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

* Django MVT Architecture
* Django ORM
* Authentication & Authorization
* Session Management
* Payment Gateway Integration
* E-Commerce Business Logic
* CRUD Operations
* Search & Filtering
* User Profile Management
* Order Processing Workflows

---

## 🔮 Future Improvements

* Django REST Framework API
* Stripe / Razorpay Integration
* Wishlist Functionality
* Coupon & Discount System
* Product Recommendation Engine
* Docker Support
* PostgreSQL Deployment
* CI/CD Pipeline

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit a pull request.
