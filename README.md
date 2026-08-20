# 🌸 Heavenly Blooms

## Project Overview
**Heavenly Blooms** is a web application built as an **e-commerce platform** dedicated to selling flowers and floral arrangements. The platform provides a smooth shopping experience for customers, along with a dedicated dashboard for admins to manage products, wallet recharge codes, and customer messages.

---

## Table of Contents
- [Features](#features)
- [Technical Stack](#technical-stack)
- [Database](#database)
- [Getting Started](#getting-started)
- [Authors](#authors)

---

## Features

- **Authentication & User Roles**
    - Secure login/register for customers.
    - Role-based access (Admin, User).
    - Session-based access control across all pages.

- **Product Catalog**
    - Browse all available flowers/products.
    - Product details (name, description, price, image).
    - CRUD operations for Admin (add/delete products).

- **Shopping & Checkout**
    - Add products and place orders through a dedicated checkout flow.
    - Order handling via a JSON-based API endpoint.

- **Digital Wallet**
    - Users can recharge their wallet using a unique recharge code.
    - Admin can generate new recharge codes with custom amounts.
    - Wallet balance shown directly on the user dashboard.

- **Contact & Messages**
    - "Contact Us" form for visitors and customers.
    - Admin dashboard to review all incoming customer messages.

- **User Dashboard**
    - View personal info (username, email, phone).
    - View current wallet balance.

- **Admin Dashboard**
    - Manage products (add/edit/delete).
    - Generate wallet recharge codes.
    - Review customer messages.

- **Responsive UI/UX**
    - Clean, flower-themed design across all pages.
    - Separate navigation experiences for Users and Admins.

---

## Technical Stack

| Layer            | Technologies Used                          |
|-------------------|---------------------------------------------|
| Frontend          | HTML, CSS, JavaScript                       |
| Backend           | PHP (native, `mysqli`)                      |
| Database          | MySQL / MariaDB                             |
| Icons             | Font Awesome                                |

---

## Database

The database `heavenlybloom` includes the following tables:

| Table          | Purpose                                      |
|----------------|-----------------------------------------------|
| `users`        | User accounts and wallet balances             |
| `products`     | Store products (flowers)                      |
| `messages`     | Messages submitted via the Contact Us page     |
| `transactions` | Wallet recharge / transaction history          |
| `wallet`       | Wallet-related data                            |

---

## Getting Started

This project requires a local PHP + MySQL environment such as **XAMPP** or **Laragon**.

1. Place the project folder inside your server's root directory:
   - XAMPP: `htdocs/`
   - Laragon: `www/`

2. Start **Apache** and **MySQL** from your XAMPP/Laragon control panel.

3. Open **phpMyAdmin** and create a new database named:
   ```
   heavenlybloom
   ```

4. Import the `heavenlybloom.sql` file into that database (via the Import tab in phpMyAdmin).

5. If your database credentials differ, update `connection.php`:
   ```php
   $conn = new mysqli("localhost", "root", "", "heavenlybloom");
   ```

6. Open your browser and navigate to:
   ```
   http://localhost/NTI_Graduation_Project/index.php
   ```
---

## Authors

- **Mohamed Hossam**    Mohamed_Hossam0
- **Fahd Gamal**        Fahd-Gamal
- **Sandra Azab**       Sandra-2005
- **Habiba Ayman**      1habibaa1
- **Ahmed Shaaban**

