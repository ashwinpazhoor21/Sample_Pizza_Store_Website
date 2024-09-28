# 🍕 Django Food Ordering System

This project is a **Django-based food ordering system**, inspired by the seamless online ordering experience of major pizza chains like **Domino's**. It enables users to browse a restaurant's menu, customize orders, and track their order status—all through an intuitive and responsive web interface. Built with Django and Bootstrap 4, this system provides a smooth user experience, without relying on JavaScript, while offering powerful administrative tools for restaurant owners.

## 🚀 Key Features

### 🍽️ **Full Menu and Cart System**
- Users can browse an interactive menu and customize items (similar to adding toppings to a pizza).
- The contents of a user’s cart are preserved across sessions, ensuring a seamless ordering experience.

### 🔐 **User Authentication**
- **Register**, **Login**, and **Logout** functionality ensures secure access to personalized features like order history and status tracking.

### 🛒 **Shopping Cart & Order Placement**
- Users can add items to their cart, customize their order, and place an order with just a few clicks.
- The system calculates the total cost, making checkout straightforward and efficient.

### ✅ **Order Tracking**
- Users can view the status of their orders (e.g., pending or completed).
- Restaurant administrators can manage orders by marking them as complete.

### 💼 **Admin Panel for Restaurant Owners**
- **Django Admin** allows restaurant owners to easily add, update, or remove items from the menu and view all placed orders.

### 💳 **Stripe Integration**
- Integrated with **Stripe API** to allow users to securely pay for their orders using credit cards during checkout.
- Ensures fast and secure transactions, with no sensitive data stored in the system itself.

### ✨ **Personal Touch**
- Inspired by Domino's online order tracking, users can see real-time updates on their order status.
- Additionally, an automatically generated superuser account simplifies first-time setup for restaurant owners.

## 🛠️ Technologies Used
- **Python** (Django Framework)
- **Bootstrap 4** for responsive design
- **Django ORM** for efficient database management
- **Stripe API** for payment processing
- **HTML/CSS** for frontend styling

## 📂 Project Structure
- **`models.py`**: Defines the database schema, including user, menu items, and orders.
- **`views.py`**: Contains the core logic for rendering templates and processing user actions like placing orders.
- **`urls.py`**: Maps the routes for various views in the application.
- **HTML Templates**: Includes `index.html`, `menu.html`, `orders_manager.html`, etc., which extend a common base layout for consistent design.

## 🎯 Inspiration
This project is heavily inspired by the streamlined user interface of **Domino's Pizza**, focusing on ease of ordering and order management. My goal was to create a user-friendly web application that brings that same simplicity to any restaurant’s online ordering experience.

## 💡 Getting Started
1. Clone the repository: `git clone https://github.com/your-repo-url`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the server: `python manage.py runserver`
4. Log into the **Django Admin** (superuser is auto-generated) and start managing menu items!
5. Set up your Stripe API keys for secure payment integration.