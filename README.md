# User Management System 🚀
A full-featured User Management System built with **Laravel** framework, supporting complete CRUD operations with image upload functionality.

---

## 📋 Features

- ✅ Create new users with profile picture upload
- ✅ View all users in a responsive table
- ✅ Edit and update user information
- ✅ Delete users with confirmation popup
- ✅ Search users by email
- ✅ Clean and modern UI with Bootstrap 5

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Laravel 12 | Backend Framework |
| PHP 8.2 | Server Language |
| MySQL | Database |
| Bootstrap 5 | Frontend UI |
| Bootstrap Icons | Icons |

---

## ⚙️ Installation Guide

### 1. Clone the repository
```bash
git clone https://github.com/YourUsername/user-management.git
cd user-management
```

### 2. Install dependencies
```bash
composer install
```

### 3. Configure environment
```bash
cp .env.example .env
php artisan key:generate
```

### 4. Setup database
- Create a MySQL database named `user_management`
- Update `.env` file:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=user_management
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Run migrations
```bash
php artisan migrate
```

### 6. Create uploads folder
Create a folder named `uploads` inside the `public` directory.

### 7. Start the server
```bash
php artisan serve
```

Visit: `http://127.0.0.1:8000`

---

## 📁 Project Structure
