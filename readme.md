[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Laravel and JWT      

This is a simple implementation of JWT with Laravel. It has basic authentication features set up.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
What things you need to install the software.

- Git.
- PHP.
- Composer.
- Laravel CLI.

## Install
Clone the git repository on your computer
```
$ git clone https://github.com/fisayoafolayan/laravel-jwt.git
```
You can also download the entire repository as a zip file and unpack in on your computer if you do not have git

After cloning the application, you need to install it's dependencies.
```
$ cd laravel-jwt
$ composer install
```

## Setup
When you are done with installation, copy the .env.example file to .env
```
$ cp .env.example .env
```

Generate the application key
```
$ php artisan key:generate
```

Generate JWT secret
```
php artisan jwt:secret
```
Create sqlite file
```
touch database/database.sqlite
```

Migrate the application
```
$ php artisan migrate
``` 

Run the application
```
$ php artisan serve
```

