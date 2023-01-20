

Installation Guide

    1. clone this repo to your local machine: git clone https://github.com/zhiyang446/Gym_Equipment_with-Laravel
    2. copy .example.env to .env file: cp .example.env .env
    3. create a new database and add the database credentials to your .env file
    4. run composer install
    5. run npm install && npm run dev
    6. run php artisan key:generate
    7. run php artisan ecommerce:install
    8. run php artisan serve and then visit http://127.0.0.1:8000/
    9. credentials to access admin panel (email: admin@admin.com, password: admin)
    10. go to phpmyadmin panel create database table(like a gym) and import databse file (gym.sql) to the "gym".
    11. after you login as admin, you can access the admin page from http://127.0.0.1:8000/admin

