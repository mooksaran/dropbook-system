# DropBook - Book Donation System

DropBook is a Laravel-based web application designed to support book donations for non-profit organizations. It allows donors to give books or money, while organizations can request books based on their needs.

## Features

- Donor and Organization registration/login
- Book search and donation system
- Admin/staff management for donors, organizations, and book inventory
- Donation packages ($30 and $300)
- Gallery of available books

## Project Structure

```
dropbook-donation-system/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── ER_Diagram.jpeg
│   └── DropBook_Relational_Model.pdf
├── database/
│   └── schema.sql
├── dropbook-main/
│   ├── ... (Laravel application files)
```

## Getting Started

### 1. Clone the repository

```
git clone https://github.com/yourusername/dropbook-donation-system.git
cd dropbook-donation-system/dropbook-main
```

### 2. Install PHP dependencies

```
composer install
```

### 3. Create `.env` and setup environment

```
cp .env.example .env
php artisan key:generate
```

Edit the `.env` file to configure your local database credentials.

### 4. Run migrations (optional, if schema.sql not used directly)

```
php artisan migrate
```

### 5. Serve the application

```
php artisan serve
```

Visit `http://127.0.0.1:8000` in your browser.

## Requirements

- PHP >= 7.3
- Composer
- MySQL or MariaDB
- Node.js & NPM (for asset compilation if needed)

## Data Model

Refer to the following files in the `docs/` folder:

- ER_Diagram.jpeg
- DropBook_Relational_Model.pdf

SQL schema is available in `database/schema.sql`.

## Team Members

- Vibolrottanak S.
- Phoo Pwint Sone
- Saranya S.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
