# Online Notes Sharing System

A web-based platform built with **PHP** and **MySQL** that lets students and teachers upload, categorize, and share notes online — removing the hassle of manually distributing study material.

## 📖 About

The Online Notes Sharing System allows users to create an account, log in securely, and upload notes (typically as PDFs) under different categories/subjects so that other users can easily browse and download relevant material. An admin panel is included to manage users and moderate uploaded content.

## ✨ Features

- 🔐 **User Registration & Login** – secure signup/login system for users
- 📤 **Upload Notes** – add notes/files under specific categories or subjects
- 📂 **Browse & Download** – search and download notes shared by other users
- ✏️ **CRUD Operations** – create, read, update, and delete your own notes
- 👤 **Profile Management** – update personal details and change password
- 🛠️ **Admin Panel** – manage users, approve/reject uploads, and oversee the system
- 📊 **Dashboard** – quick overview of uploaded notes and activity

## 🛠️ Tech Stack

| Layer      | Technology            |
|------------|------------------------|
| Frontend   | HTML, CSS, JavaScript, Bootstrap |
| Backend    | PHP                     |
| Database   | MySQL                   |
| Server     | Apache (XAMPP / WAMP)   |

## 📋 Requirements

- PHP 7.x or higher
- MySQL / MariaDB
- Apache server (XAMPP, WAMP, or similar)
- A modern web browser

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/RohitGarudkar/Online-Notes-Sharing-System.git
   ```

2. **Move the project to your server directory**
   Copy the project folder into your server's root directory, e.g.:
   ```
   C:/xampp/htdocs/online-notes-sharing-system
   ```

3. **Set up the database**
   - Open phpMyAdmin (or your preferred MySQL client)
   - Create a new database
   - Import the provided `.sql` file included in the project to set up the required tables

4. **Configure the database connection**
   Open the database connection file (commonly found at `includes/connection.php` or `config.php`) and update the credentials to match your local setup:
   ```php
   $host = "localhost";
   $username = "root";
   $password = "";
   $database = "your_database_name";
   ```

5. **Start the server**
   Start Apache and MySQL from your XAMPP/WAMP control panel.

6. **Run the application**
   Open your browser and navigate to:
   ```
   http://localhost/online-notes-sharing-system
   ```

## ▶️ Usage

1. Register a new account or log in if you already have one.
2. From your dashboard, upload notes and assign them to a category.
3. Browse notes uploaded by other users and download the ones you need.
4. Update your profile or password anytime from the profile section.
5. Admin users can log in to the admin panel to manage users and content.

## 📁 Project Structure

```
Online-Notes-Sharing-System/
├── admin/              # Admin panel files
├── includes/           # Database connection & shared includes
├── uploads/            # Uploaded notes/files
├── assets/             # CSS, JS, images
├── index.php           # Landing / login page
├── register.php        # User registration
├── dashboard.php       # User dashboard
└── database.sql        # Database schema
```
*(Folder names may vary slightly — check the repository for the exact structure.)*

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available for educational purposes. Add a license of your choice (e.g., MIT) if you plan to distribute it.

## 👤 Author

**Rohit Garudkar**
GitHub: [@RohitGarudkar](https://github.com/RohitGarudkar)
