# DUAL Store - Final Project

This is the final project for the Database System Application course.  
It is a web-based e-commerce system built with Django.

## Features

- 🛍️ Product listing, shopping cart, and checkout
- ✅ Real-time inventory validation to prevent over-ordering
- 📦 Backend dashboard for managing products, orders, customers, and stock transactions

## System Overview

The system includes:
- A **frontend storefront** for users to browse products and place orders
- A **backend dashboard** for admins to manage inventory and orders
- Automatic deduction of stock on purchase
- Manual stock-in interface for administrators

## How to Run

```bash
# Clone this repo
git clone https://github.com/shangsyuansuei/Grope-G-Dual-store-.git
cd Grope-G-Dual-store-

# (Optional) Create a virtual environment
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run database migrations
python manage.py migrate

# Start the development server
python manage.py runserver
