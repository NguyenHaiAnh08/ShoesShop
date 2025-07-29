# Shoes Shop - Laravel E-commerce Website

Shoes Shop is an e-commerce website for selling shoes, built with the Laravel Framework. The project provides features for product management, order management, shopping cart, reviews, promotions, and user role management.

## Technologies Used

- Laravel (PHP)
- MySQL
- Blade Template
- Bootstrap, JavaScript
- Composer, npm

## Main Features

- Manage products, shoe categories, brands, promotions
- Manage orders, shopping cart, checkout
- Product reviews
- User management, role-based access (admin, user)
- Account authentication and security

## Installation Guide

1. **Set up the environment:**
   - Install XAMPP or WAMP to have PHP and MySQL.
   - Install Laravel Framework.

2. **Clone the project:**
   ```bash
   git clone <link-repo>
   cd laravel-shoes-shop-main
   ```

3. **Install packages:**
   ```bash
   copy .env.example .env
   composer install
   # or: composer install --ignore-platform-reqs
   # or: composer update
   # or: composer update --ignore-platform-reqs
   npm install
   npm audit fix
   npm run dev
   ```

4. **Configure the database:**
   - Create a database named: `ilyoushoesshop`
   - Collation: `utf8_unicode_ci`
   - Import the `ilyoushoesshop.sql` file into the created database.

5. **Run migrations and seed data:**
   ```bash
   php artisan migrate:fresh --seed
   php artisan key:generate
   ```

6. **Start the server:**
   ```bash
   php artisan serve
   ```
   - Access the website at: [http://localhost:8000](http://localhost:8000)

## Notes

- Make sure you have installed PHP, Composer, Node.js, and npm.
- If you encounter package errors, try using `composer install --ignore-platform-reqs` or `composer update --ignore-platform-reqs`.
- Check that the `.env` file is configured with the correct database information.
- If you make changes to the frontend, run `npm run dev` again.

---

Just replace `<link-repo>` with your project's GitHub repository link. 

## Contact

For questions or support, please contact:  
**[Hải Anh]**  
Email: [haianh8102003@gmail.com]

---
