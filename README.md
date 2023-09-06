# Laravel-Docker-With-PHP8.2-Apache-MySQL

Welcome to the Laravel-PHP8.2-Apache-MySQL development environment repository. This project provides a Dockerized setup for Laravel development, equipped with PHP 8.2, Apache, and MySQL.

## Getting Started

Follow these steps to set up your development environment:

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/avnsh1111/laravel-docker-with-php8.2-apache-mysql.git
   ```
2. Navigate to the project directory:
    ```
    cd laravel-docker-with-php8.2-apache-mysql
    ```
3. Place your Laravel project within the `laravel` directory in this repository. You can do this by copying or cloning your existing Laravel project into the `laravel` directory.

4. Start the Docker containers:
    ```
    docker-compose up -d
    ```
5. Access your Laravel application in your web browser at `http://localhost:8080`.

If your Laravel project is not running after the above steps, follow these additional instructions:

6. Access the terminal within the `laravel-php` container:
    ```
    docker-compose exec laravel-php bash
    ```

7. Run `composer install` to install Laravel's dependencies.

8. After the installation is complete, exit the container's terminal:
    ```
    exit
    ```

Now, your Laravel project should be up and running on port 8080. You can access it in your web browser at `http://localhost:8080`.

## Features

- Laravel Framework: Utilize the power of Laravel to build modern web applications.
- PHP 8.2: Benefit from the latest PHP features and improvements.
- Apache Web Server: Host your Laravel project with the Apache web server.
- MySQL Database: Manage your application's data with MySQL.
- Dockerized Environment: Ensure consistency and easy setup across different systems.
- Database Seeding and Migrations: Simplify database management during development.
- Sample Application: Start with a sample Laravel application or build from scratch.
- Composer Dependencies: Easily add and manage Composer packages for your Laravel app.

## Contributing

We welcome contributions! If you have suggestions, bug fixes, or new features to add, please submit a pull request or open an issue on this repository.

## License

This project is open-source and licensed under the GNU General Public License (GNU GPL). Feel free to use, modify, and distribute it in accordance with the terms of the GNU GPL.

Happy coding with Laravel, PHP 8.2, Apache, and MySQL!


