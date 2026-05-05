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
user-management/
├── app/
│   ├── Http/Controllers/UserController.php
│   └── Models/UserRegistration.php
├── database/migrations/
├── public/uploads/
├── resources/views/
│   ├── index.blade.php
│   ├── create.blade.php
│   └── edit.blade.php
└── routes/web.php
---

## 📌 Routes

| Method | URL | Action |
|--------|-----|--------|
| GET | / | Show all users |
| GET | /create | Show create form |
| POST | /store | Save new user |
| GET | /edit/{id} | Show edit form |
| POST | /update/{id} | Update user |
| GET | /delete/{id} | Delete user |
| GET | /search | Search by email |

---

## 📷 Screenshots

### User Listing
> *(<img width="1488" height="912" alt="W2" src="https://github.com/user-attachments/assets/d4883ac5-7281-44a2-b9f9-33d3c04f4102" />
)*

### Registration Form
> *(<img width="1210" height="905" alt="W1" src="https://github.com/user-attachments/assets/ed76078b-270d-4eba-8951-b7c0c85462a1" />
)*

### Edit Form
> *(<img width="1485" height="912" alt="W3" src="https://github.com/user-attachments/assets/29a6a583-2878-4bec-bbd3-0e14df0f5290" />
)*

---

## 👨‍💻 Developer

**Moiz Ahmad**
COMSATS University Islamabad
Web technologies

---

## 📄 License
This project is for educational purposes only.
