# PHP School Management System

A school management system built with PHP and MySQL. It manages students, parents, teachers, classes and results.

## Screenshot

_Screenshot coming soon._

## Features

- Faculty login, sign-up, and username and password recovery pages
- Admin page
- Add, update, view and delete students and parents
- Add, update and view classes and teachers
- Add, update, view and search results
- MySQL tables: `admission_office`, `class`, `parents`, `result`, `student`, `teacher`

> **Security note:** this is a student project and isn't safe for production use. Login queries put user input straight into the SQL (open to SQL injection), and passwords are stored as plain text.

## Tech stack

PHP (mysqli), MySQL, HTML, CSS, Bootstrap

## Getting started

1. Install a local PHP and MySQL server, such as XAMPP.
2. Create a database called `school_management_system` and import `database/school_management_system.sql`.
3. Check the database settings in `connection.php`. The defaults are host `localhost`, user `root` and an empty password.
4. Put the project folder in your web root (for example `htdocs/`) and open `http://localhost/php-school-management-system/`.

## Project structure

```
connection.php       Database connection
database/*.sql       Database schema and data
*.html               Forms (insert, update, delete, search)
*.php                Form handlers and views (view_*.php, update_*.php, ...)
*.jpg / *.png        Images
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
