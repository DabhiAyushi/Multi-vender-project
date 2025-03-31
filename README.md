
Overview

This project is a Multi-Vendor E-Commerce Platform built using Django for the backend and React for the frontend. The platform allows multiple vendors to list their products, manage inventory, and process orders while customers can browse, purchase, and review products seamlessly.

Features

For Vendors:
Vendor Registration & Login
Product Management (Add, Edit, Delete)
Order Management
Inventory Tracking
Sales Reports

For Customers:
Customer Registration & Login
Product Browsing & Search
Add to Cart & Checkout
Order History & Tracking
Reviews & Ratings

Tech Stack

Backend:
Django
PostgreSQL/MySQL

Frontend:

HTML, CSS
Javascript
Installation & Setup

Backend Setup:
# Clone the repository
git clone https://github.com/DabhiAyushi/Multi-vender-project.git
cd Multi-vender-project

# Create virtual environment & activate it
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start the server
python manage.py runserver

Frontend Setup:
# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Start the development server
npm start

API Endpoints

GET:-   /api/products/ - Get all products
GET:-   /api/products/{id}/ - Get a single product
POST:-  /api/vendors/ - Register a vendor
GET:-   /api/orders/ - Get all orders
POST:-  /api/orders/ - Place an order

