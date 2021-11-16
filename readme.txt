SIPERAS

Repository Link

* Main Repo
  - https://github.com/Richie-Z/siperas-backend
* Backend Repo
 - DVD commit head 8e270729db6f83cd2d89a3024f7cb0caeb25992b
 - https://github.com/Richie-Z/siperas-backend
* Frontend Repo
 - DVD commit head ac542fb075ee9f46006141b6e5a60a3bc1dc792c
 - https://github.com/Richie-Z/siperas-frontend 

Framework and Component used

- Lumen v.8.0
  - JWT-Auth v.1.0
  - Laravel-Cors v.2.0
- Vue Js v.3.0
  - Vuex v.4.0
  - Vue Router v.4.0.5
  - Tailwindcss v.2.0.3
  - Postcss v.7.0
  - Sweetalert2 v.10.15.5
  - Echarts v.5.0.2
  - Vue Echarts v.6.0

Requirement

1.  Node JS v.14 up
2. Composer v.1 up (v.2 is much Recommended)
3. Git (Optional)

Installation

* Backend
 - Go inside the siperas-backend folder then open a terminal inside it
 - Execute composer install
 - Rename .env.example to .env
 - Execute php artisan key:generate
 - Configure your DB info in .env
 - Import db_siperas.sql (This is highly not recommended)
 - if you want this app can support for long term skip import db_siperas step 
 - then execute php artisan migrate (if you skip import step)
 - then execute php artisan db:seed (if you skip import step)
 - Developing server can be access using php -S 127.0.0.1:8000 -t public command

* Frontend
 - Go inside the siperas-frontend folder then open a terminal inside it
 - Execute npm install
 - Developing server can be access using npm run serve

Updating Guide

 - Make sure git is intalled properly on your device 
 - Go to siperas-frontend/siperas-backend then open terminal inside it
 - Execute git pull origin master
 
