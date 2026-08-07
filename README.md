# ITST 302 — Laravel Development Environment Setup

## Subject
**ITST 302 — Client-Server Technologies**

## Project
**Laravel Development Environment Setup and Basic Homepage Customization**

---

# 1. Project Title

Laravel Development Environment Setup

---

# 2. Introduction

## Overview of Laravel

Laravel is a free and open-source PHP web application framework designed to simplify modern web development. It follows the Model-View-Controller (MVC) architecture, allowing developers to build secure, organized, and maintainable web applications. Laravel provides built-in features such as routing, authentication, database management, and templating through the Blade engine.

## Importance of Client-Server Technologies

Client-server technologies are the foundation of modern web applications. The client sends requests through a web browser or application, while the server processes those requests and returns the appropriate response. Understanding client-server communication is essential for developing reliable and scalable web systems.

## Purpose of the Project

The purpose of this project is to install and configure a complete Laravel development environment using PHP, Composer, Laravel, Git, MySQL, and Visual Studio Code. The project also demonstrates basic Laravel application setup, homepage customization, version control using Git, and project documentation through GitHub.

---

# 3. Objectives

The following objectives were achieved during this activity:

1. Install and configure PHP.
2. Install Composer for dependency management.
3. Install and verify the Laravel Framework.
4. Install and configure Git for version control.
5. Install and verify MySQL.
6. Install and configure Visual Studio Code.
7. Create a new Laravel project.
8. Run the Laravel development server.
9. Customize the default Laravel homepage.
10. Upload the project to GitHub.
11. Document the entire installation and setup process.

---

# 4. Development Environment

| Software | Version |
|-----------|---------|
| Operating System | Windows 11 |
| PHP | 8.5.9 |
| Laravel | 13.24.0 |
| Composer | 2.10.2 |
| Git | 2.55.0 |
| MySQL | 8.0.43 |
| Visual Studio Code | 	1.132.0 |

---

# 5. Installation Steps

### Step 1 – Install PHP

Verified the PHP installation using:

```bash
php -v
```

**Screenshot:** ![PHP Version](screenshots/Screenshot%202026-08-07%20230123.png)

---

### Step 2 – Install Composer

Verified Composer installation using:

```bash
composer -V
```

**Screenshot:** ![Composer Version](screenshots/Screenshot%202026-08-07%20230123.png)

---

### Step 3 – Install Laravel

Verified Laravel installation using:

```bash
php artisan --version
```

**Screenshot:** ![Laravel Version](screenshots/Screenshot%202026-08-07%20230304.png)

---

### Step 4 – Install Git

Verified Git installation using:

```bash
git --version
```

**Screenshot:** ![Git Version](screenshots/Screenshot%202026-08-07%20230359.png)

---

### Step 5 – Install MySQL

Verified MySQL installation.

**Screenshot:** ![MySQL Version](screenshots/Screenshot%202026-08-07%20230509.png)

---

### Step 6 – Install Visual Studio Code

Opened the Laravel project in Visual Studio Code.

**Screenshot:** ![Visual Studio Code](screenshots/Screenshot%202026-08-07%20155716.png)

---

### Step 7 – Run Laravel Development Server

Started the Laravel development server using:

```bash
php artisan serve
```

**Screenshot:** ![Laravel Development Server](screenshots/Screenshot%202026-08-07%20160201.png)

---

### Step 8 – Customize Laravel Homepage

Modified the default Laravel homepage using a Blade template.

**Screenshot:** ![Hello Laravel Homepage](screenshots/Screenshot%202026-08-07%20160500.png)

---

# 6. Project Structure

## app/

Contains the application's core business logic, controllers, middleware, models, and service classes.

## routes/

Contains route definitions that determine how URLs are handled by the application.

## resources/

Stores Blade templates, CSS, JavaScript, and localization files used by the application.

## public/

Contains publicly accessible files including the application's entry point (`index.php`) and compiled assets.

## config/

Contains configuration files for the application and installed packages.

## database/

Contains database migrations, factories, and seeders used for database management.

---

# 7. Problems Encountered

### 1. Composer was not recognized

Initially, Composer was not recognized in the terminal because it was not properly added to the system PATH.

### 2. PHP PATH configuration

PHP commands could not be executed until the PHP installation directory was added to the Windows Environment Variables.

### 3. Git branch confusion

The project was initially pushed to the `master` branch while GitHub displayed the `main` branch, causing confusion when viewing the repository contents.

---

# 8. Solutions

### Composer

Reinstalled Composer and restarted the terminal after ensuring it was added to the system PATH.

### PHP

Added the PHP installation directory to the Windows Environment Variables and restarted the computer.

### Git

Verified the local and remote branches, synchronized the repository, and pushed the Laravel project successfully to GitHub.

---

# 9. Screenshots

| Screenshot | Description |
|------------|-------------|
| ![PHP Version](screenshots/Screenshot%202026-08-07%20225716.png) | PHP version verification |
| ![Composer Version](screenshots/Screenshot%202026-08-07%20230123.png) | Composer version verification |
| ![Laravel Version](screenshots/Screenshot%202026-08-07%20230304.png) | Laravel framework version verification |
| ![Git Version](screenshots/Screenshot%202026-08-07%20230359.png) | Git version verification |
| ![MySQL Version](screenshots/Screenshot%202026-08-07%20230509.png) | MySQL installation verification |
| ![Visual Studio Code](screenshots/Screenshot%202026-08-07%20155716.png) | Laravel project opened in Visual Studio Code |
| ![Laravel Development Server](screenshots/Screenshot%202026-08-07%20160201.png) | Laravel development server running |
| ![Hello Laravel Homepage](screenshots/Screenshot%202026-08-07%20160500.png) | Customized Laravel homepage |

---

# 10. Reflection

This activity helped me understand how to set up a complete Laravel development environment from scratch. I learned how PHP, Composer, Laravel, Git, MySQL, and Visual Studio Code work together to create a modern web development workflow. Before completing this project, I had limited experience using Laravel, but through this activity I gained practical knowledge about creating a Laravel project, configuring the development environment, and running the application using Laravel's built-in development server.

One of the biggest challenges I encountered was configuring Git and understanding the difference between the `main` and `master` branches. At first, my project appeared to be missing from GitHub because it had been pushed to a different branch. I also encountered minor configuration issues while verifying software installations. These challenges improved my troubleshooting skills and taught me the importance of understanding version control and development environments.

Laravel plays an important role in client-server development because it provides a structured framework for building secure, scalable, and maintainable web applications. Its MVC architecture, routing system, Blade templating engine, and database migration features help developers organize projects efficiently while following industry best practices.

The knowledge I gained from this activity will be valuable in future software development projects. It provides a strong foundation for developing larger Laravel applications, collaborating with other developers through Git and GitHub, and understanding how client requests are processed by a web server. This experience has increased my confidence in using professional development tools that are commonly used in the software industry.

---

# 11. References

Composer. (2025). *Composer Documentation*. https://getcomposer.org/doc/

Git. (2025). *Git Documentation*. https://git-scm.com/doc

Laravel. (2025). *Laravel Documentation*. https://laravel.com/docs

PHP Group. (2025). *PHP Documentation*. https://www.php.net/docs.php