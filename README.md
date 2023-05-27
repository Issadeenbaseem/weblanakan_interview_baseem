This is a sample CRUD (Create, Read, Update, Delete) application built using Laravel  authentication.

Getting Started
Follow the instructions below to set up and run the application on your local machine.

Prerequisites
Make sure you have the following prerequisites installed on your machine:

PHP (version 7.4 or higher)
Composer
Node.js (version 12 or higher)
NPM (version 6 or higher)
MySQL (or any other supported database)



Installation

Config file
Rename or copy .env.example file to .env 1.php artisan key:generate to generate app key.

Set your database credentials in your .env file
Set your APP_URL in your .env file.
Database
Migrate database table php artisan migrate
Install Node Dependencies



npm install to install node dependencies
npm run dev to build our javascript
Create storage link
php artisan storage:link

Run Server
php artisan serve or Laravel Homestead
Visit localhost:8000 in your browser. Create an account first and login.
![1](https://github.com/Issadeenbaseem/weblanakan_interview_baseem/assets/37994627/c7f06b5b-11fd-42e1-a571-1ff0334563ea)
![2](https://github.com/Issadeenbaseem/weblanakan_interview_baseem/assets/37994627/adb9c08d-31a7-42ce-a6ba-e50c219b0900)
![3](https://github.com/Issadeenbaseem/weblanakan_interview_baseem/assets/37994627/157403be-d787-40ef-93bf-75ba5d7a16b7)
