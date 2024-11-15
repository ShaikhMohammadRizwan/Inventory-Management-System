# Inventory Management System

A web-based Inventory Management System built using Django. This application allows users to manage product data efficiently with a clean and user-friendly interface.

## Features

- **User Authentication**: Secure login and registration for authorized users.
- **Product Management**: 
  - Add, view, update, and delete product details.
  - Manage product attributes like name, SKU, price, quantity, and supplier.
- **Responsive Design**: The application uses Bootstrap to ensure device responsiveness.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap 4
- **Database**: SQLite (or PostgreSQL for production)
- **Hosting**: Deployed on [Vercel](https://vercel.com/) or another hosting service

## Installation

To get this project running on your local machine, follow these steps:

### 1. Clone the repository

bash
git clone https://github.com/yourusername/inventory-management-system.git
cd inventory-management-system

### 2. Set up the virtual environment
For Python, use venv:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Apply migrations

python manage.py migrate

### 5. Run the development server

python manage.py runserver
Now, visit http://127.0.0.1:8000/ in your browser to see the app in action.

### Usage

View Products: View a list of all products added to the system.

Update or Delete Products: You can update product details or delete them from the system as needed.
