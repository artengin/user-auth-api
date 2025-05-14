# Laravel API Project

REST API for user registration, authentication, and profile management in Laravel

## Features

- User registration, login, logout and profile

## Endpoints

### Authentication
- `POST api/register` - register
- `POST api/login` - login
- `Get api/logout` - logout (requires authentication)
- `Get api/profile` - Returns data of the currently authenticated user (requires authentication)

## Installation

1. Clone the repository
2. `composer install`
3. Configure `.env` file
4. `php artisan migrate`
5. `php artisan serve`

[![API Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/40470359/2sB2qUo5RM)