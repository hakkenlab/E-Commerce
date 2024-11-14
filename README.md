# E-Commerce Website

This is a full-stack eCommerce application built using Django Rest Framework (DRF) for the backend, Next.js for the frontend, and TypeScript for type safety on the client side. This project aims to create a scalable, modern, and robust online store with features like product browsing, user authentication, a shopping cart, and order management.

# Table of Contents

  # Features
  # Tech Stack
  # Installation
  # Configuration
  # Usage
  # Project Structure
  # API Documentation
  # Contributing
  # License

## Features

  User Authentication: Registration, login, and authentication with JWT tokens.
  Product Catalog: View, filter, and search products.
  Shopping Cart: Add products to the cart, adjust quantities, and proceed to checkout.
  Order Management: View and manage orders.
  Admin Panel: Manage products, orders, and users (using Django’s admin interface).
  Responsive Design: Optimized for mobile and desktop devices.

## Tech Stack

- **Frontend**:
  - HTML5, CSS3, JavaScript
  - next.js (or any other frontend framework/library)
  - Bootstrap (for responsive design)
  
- **Backend**:
  - Node.js with Express (or Django, Laravel, etc. depending on your backend framework)
  - MongoDB (or any other database like MySQL, PostgreSQL)
  
- **Payment Gateway**:
  - Integrated with Stripe, PayPal, or any other payment service for processing payments.

## Setup and Installation

Follow these steps to set up the project locally:

### Prerequisites

- Node.js installed (for a Node-based backend)
- npm or yarn (for managing packages)
- MongoDB or other database setup (if you're using a database)
- Any other dependencies (based on your tech stack)

### 1. Clone the repository

```bash```
git clone https://github.com/owayo-cloud/E-Commerce.git
cd E-Commerce

### 2. Set up a virtual environment

```bash```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# 3. Install backend dependencies:

```bash```
pip install -r requirements.txt

### 4. Configure environment variables:

Create a .env file in the backend folder with the following variables:

```env```
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=your_database_url

### 5. Run migrations and start the development server:

```bash```
python manage.py migrate
python manage.py runserver


## Frontend Setup
### 1. Navigate to the frontend directory:

```bash```
cd ../frontend

### 2. Install frontend dependencies:

```bash```
npm install
# or
yarn install

### 3. Configure environment variables:

## Create a .env.local file in the frontend folder with the following variables:

```env`
NEXT_PUBLIC_BACKEND_URL=http://localhost:8000
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

### 4. Start the Next.js development server:

```bash`
npm run dev
# or
yarn dev


# Configuration

## 1. Backend Configuration:

Edit the settings.py file in the Django project to configure the database, JWT settings, and CORS.

## 2. Frontend Configuration:

Configure Axios to use NEXT_PUBLIC_BACKEND_URL for API requests.

# Usage

## Access the frontend:

Visit http://localhost:3000 in your browser to access the application.
API:

# Contributing
Contributions are welcome! Please submit a pull request or open an issue to get started.

License
This project is licensed under the MIT License. See the LICENSE file for more information.

