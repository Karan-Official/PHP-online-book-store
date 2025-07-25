# 📚 Online Book Store

A full-featured online book store web application built with PHP and MySQL. This project allows users to browse, search, and download books, while providing an admin interface for managing books, authors, and categories.

## 🚀 Features

- User authentication (admin login)
- Add, edit, and delete books, authors, and categories
- Book cover and file upload support
- Search functionality for books
- Organized book categories and author management
- Responsive design with custom CSS
- Secure file handling and validation

## 🗂️ Project Structure

```
online-book-store-main/
│
├── add-author.php           # Add new author (admin)
├── add-book.php             # Add new book (admin)
├── add-category.php         # Add new category (admin)
├── admin.php                # Admin dashboard
├── author.php               # Author management
├── category.php             # Category management
├── css/
│   └── style.css            # Main stylesheet
├── db_conn.php              # Database connection
├── db_SQL.sql               # SQL schema
├── edit-author.php          # Edit author details
├── edit-book.php            # Edit book details
├── edit-category.php        # Edit category details
├── img/                     # Images and icons
├── index.php                # Home page (book listing)
├── login.php                # Admin login
├── logout.php               # Logout script
├── online_book_store_db.sql # Database dump
├── php/
│   ├── add-author.php
│   ├── add-book.php
│   ├── add-category.php
│   ├── auth.php
│   ├── delete-author.php
│   ├── delete-book.php
│   ├── delete-category.php
│   ├── edit-author.php
│   ├── edit-book.php
│   ├── edit-category.php
│   ├── func-author.php
│   ├── func-book.php
│   ├── func-category.php
│   ├── func-file-upload.php
│   └── func-validation.php
├── search.php               # Book search
├── uploads/
│   ├── cover/               # Book cover images
│   └── files/               # Book files (PDF, etc.)
└── README.md
```

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/online-book-store-main.git
   ```

2. **Import the Database:**
   - Open phpMyAdmin or your preferred MySQL tool.
   - Create a new database (e.g., `online_book_store_db`).
   - Import the `online_book_store_db.sql` or `db_SQL.sql` file.

3. **Configure Database Connection:**
   - Edit `db_conn.php` and update the database credentials as needed.

4. **Set Up File Permissions:**
   - Ensure the `uploads/cover/` and `uploads/files/` directories are writable by the web server.

5. **Run the Application:**
   - Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP).
   - Access the app via `http://localhost/online-book-store-main/`.

## 👤 Admin Login

- **Username:** prajapatikaran.official@gmail.com
- **Password:** 12345

> Change the default admin credentials after first login for security.

## 📝 Usage

- **Admin:** Manage books, authors, and categories via the admin dashboard.
- **Users:** Browse and search for books, view details, and download available files.

## 🧩 Customization

- Update styles in `css/style.css`.
- Add new features or modify existing ones in the `php/` directory.

## 🛡️ Security Notes

- Always change default admin credentials.
- Validate and sanitize all user inputs.
- Restrict file uploads to safe file types.

## 📄 License

This project is for educational purposes. Please check the repository or contact the author for licensing details.

## 🙏 Credits

Developed by Prajapati Karan.