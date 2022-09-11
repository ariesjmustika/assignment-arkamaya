<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Project

This is Mini Project Assestment with PT. Arkamaya:

## Account
email    : admin@gmail.com
password : admin


## Setting Configuration
1. running apache, mysql in Xampp/Mamp for starting activate local server
2. create new database 'db_project_aries' in http://localhost/phpmyadmin/
3. import file this file ['db_project_aries.sql'](https://drive.google.com/file/d/11ja3mpUJrY5JAJSf-ka0HjDqtkK9t7q9/view?usp=sharing).
4. Download Zip file and Extract
5. open project in text editor (Visual Studio) running project using 'php artisan serve' in terminal
6. project successfully running


## Route List
1. http://127.0.0.1:8000/login                -> login page
2. http://127.0.0.1:8000/register             -> register page
3. http://127.0.0.1:8000/api/project/project  -> dashboard page


# Notes 
> Create Account
  - name -> required
  - email -> required|email
  - password -> required 
  - password2 -> required|equalto:password

> JWT Auth
 - Every post request need tocken to access
 - token expired 15 meanutes in backend, and would refresh token every 15 meanutes in frontend tho

> Main Jquery/javascript located in public/assets/js/custom.js


> Technology 
- Backend : Laravel (PHP)
- Frontend : Jquery, Ajax, Datatable, Bootstrap
- CRUD Form : Pop up modal
- Validation Form : Jquery validation
- Alert : basic alert, sweetalert2
- Icon : Font-awesome
- Template Admin : AdminLte 3.20
- Store loggin user : Localstorage

> Database Migrations
Actually you can create database in project directly by typing 'php artisan migrate' in cmd/terminal on root project


