# Laravel Simple CRUD

A beginner-friendly Laravel application that demonstrates basic CRUD (Create, Read, Update, Delete) operations with product image upload, local storage, pagination, and database seeding.

---

## Features

- Create, view, edit, and delete products
- Upload and display product images (stored locally)
- Paginated product listing in HTML table layout
- Database seeder with fake products and images
- Clean UI using plain HTML + CSS (no frameworks)
- Organized structure with separate Form Request validation and Resourceful controllers

---

## Setup Instructions

Clone this repo and set it up on your local machine:

```bash
git clone https://github.com/pradeeptiwari-nickelfox/laravel-simple-crud.git
cd laravel-simple-crud
composer install
cp .env.example .env
php artisan key:generate
