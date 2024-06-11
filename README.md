<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
# Laravel RESTful API for Customers and Invoices

This project is a Laravel-based RESTful API for managing customers and their invoices. It includes functionality for creating, reading, updating, and deleting customer and invoice records.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features
- RESTful API endpoints for customers and invoices
- CRUD operations for customers and invoices
- Database seeding for initial data
- Comprehensive API documentation available via Postman

## Requirements
- PHP 7.4 or higher
- Composer
- Laravel 8.x
- MySQL or any other supported database

## Installation
1. **Clone the repository**
    ```sh
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Install dependencies**
    ```sh
    composer install
    ```

3. **Configure the environment**
    - Copy the `.env.example` file to `.env`
    - Update the `.env` file with your database credentials and other configurations

4. **Generate application key**
    ```sh
    php artisan key:generate
    ```

## Running the Project
1. **Run database migrations and seeders**
    ```sh
    php artisan migrate:fresh --seed
    ```

2. **Start the development server**
    ```sh
    php artisan serve
    ```

## API Documentation
All API routes and request details are available in the Postman collection linked below:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://api.postman.com/collections/28087875-7a617646-52df-4c25-8664-9dbd5d9264e1?access_key=PMAT-01J03R2JK5Q6XM4GC7NM8T4JVQ)
