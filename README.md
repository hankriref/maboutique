# 🛍️ MaBoutique - Full-Stack E-Commerce Application

A complete e-commerce web application built with **Laravel**, featuring product catalog management, shopping cart functionality, order processing, and an administrative dashboard.

## ✨ Key Features
- **Product Management:** Browse products by categories, view detailed descriptions, and manage inventory (CRUD).
- **Shopping Cart & Orders:** Add/remove items, update quantities, and checkout seamlessly.
- **Authentication & Authorization:** Secure user registration, login, and role-based access (Admin vs. Customer).
- **Responsive UI:** Clean, modern, and mobile-friendly interface built with Blade & CSS/Bootstrap/Tailwind.

## 🛠️ Tech Stack
- **Backend:** PHP, Laravel
- **Frontend:** Blade Templates, HTML5, CSS3, JavaScript
- **Database:** MySQL

## 🚀 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/hankriref/maboutique.git
   cd maboutique
   ```
2. Install dependencies:
   ```bash
   composer install
   npm install && npm run build
   ```
3. Configure environment variables:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
4. Set up your database credentials in `.env`, then run migrations:
   ```bash
   php artisan migrate --seed
   ```
5. Start the local server:
   ```bash
   php artisan serve
   ```
