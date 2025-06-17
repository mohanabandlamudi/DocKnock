# Doc Knock - Health Rock

A web-based e-channeling and appointment management system for clinics and hospitals. This project allows patients, doctors, and administrators to manage appointments, schedules, and user accounts efficiently.

## Features

- **Patient Portal:** Register, log in, book appointments, view schedules, and manage personal information.
- **Doctor Portal:** Manage appointments, view patient lists, set up schedules, and update profile settings.
- **Admin Portal:** Oversee all users, doctors, patients, appointments, and schedules.
- **Authentication:** Secure login for patients, doctors, and admins.
- **Responsive UI:** Clean, modern interface with CSS animations.
- **Database:** MySQL/MariaDB backend for storing all data.
- **Screenshots:** See the `Screenshots/` folder for UI examples.

## Project Structure

- `index.html` — Landing page
- `login.php`, `signup.php`, `create-account.php` — Authentication and registration
- `patient/`, `doctor/`, `admin/` — Role-based dashboards and features
- `css/`, `img/` — Styles and images
- `SQL_Database_edoc.sql` — Database schema and sample data
- `Dockerfile`, `docker-compose.yml` — For containerized deployment



## Quick Start 

1. **Copy Files:**
   - Place all project files in your web server's root directory (e.g., `htdocs` for XAMPP).

2. **Database Setup:**
   - Create a database named `edoc`.
   - Import `SQL_Database_edoc.sql` using phpMyAdmin or the MySQL CLI.

3. **Configure Database Connection:**
   - Edit `connection.php` if your database credentials differ from the default:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "edoc";
     ```

4. **Access the Application:**
   - Open [http://localhost/index.html](http://localhost/index.html) in your browser.

## Screenshots

See the `Screenshots/` folder for UI examples.

## Customization

- **Styling:** Modify files in the `css/` directory.
- **Images:** Add or replace images in the `img/` directory.
- **User Roles:** Extend functionality in the `admin/`, `doctor/`, and `patient/` directories.
