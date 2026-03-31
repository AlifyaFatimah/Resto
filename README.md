# Resto Web Application 🍽️ 

## Project Overview

This project is a web-based application developed as part of a project-based application course. It is a group project where I contributed to both front-end development and back-end implementation.

The system functions as a server-side application for multiple restaurants, enabling management of menus, table availability, and transactions (when integrated with the client-side system).

---

## Features

* Manage restaurant menus.
* Handle table availability.
* Multi-restaurant support.

---

## Tech Stack

* **Front-end:** HTML, CSS, Bootstrap
* **Back-end:** PHP, Laravel
* **Database:** MySQL

---

## Installation & Setup

Follow these steps to run the project locally:

### 1. Start Server

* Run **Apache** and **MySQL** from XAMPP.

### 2. Clone Repository

```bash
git clone https://github.com/AlifyaFatimah/Resto.git
```

### 3. Move Project

Move the project folder into:

```text
C:\xampp\htdocs
```

### 4. Install Dependencies

```bash
composer install
```

### 5. Environment Setup

```bash
cp .env.example .env
php artisan key:generate
```

### 6. Configure Database

* Create a database in MySQL:

```text
tubesabp
```

* Update `.env`:

```env
DB_DATABASE=tubesabp
DB_USERNAME=root
DB_PASSWORD=
```

### 7. Run Migration

```bash
php artisan migrate
```

### 8. Run Application

```bash
php artisan serve
```

Access the app at:

```text
http://127.0.0.1:8000
```

---

Click [here](https://www.youtube.com/watch?v=3lODEEG6shs) for installation and setup tutorial.

## My Contributions

* Developed several front-end pages using HTML, CSS, and Bootstrap.
* Implemented back-end logic using PHP and Laravel.
* Integrated database with MySQL.

---

## Preview

<img width="3839" height="2147" alt="image" src="https://github.com/user-attachments/assets/ddb0f777-1070-4775-bbdf-89fe95b60b63" />

---

## License

This project is for educational purposes.
