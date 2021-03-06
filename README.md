# **Laravel Vue Blog**


## Installation
1. Clone the project `git clone https://github.com/sukanta7660/laravel-vue-blog.git`

2. Go to project folder by entering `cd laravel-vue-blog` command

3. Install composer following by this command: `composer install --ignore-platform-reqs`

4. Install npm following by this command: `npm install`

5. Compile the vue components by this command: `npm run watch`


6. Copy `.env.example` file to `.env` on the root folder. You can type `copy .env.example .env` or `cp .env.example .env` using terminal in laravel-vue-blog directory.

7. Open your database ***XAMPP / LAMP / HeidiSQL*** (Whatever you use).
    Create a new database with any database name. `For Example:  blog`
    Open your `.env` file and change the database name `DB_DATABASE` to whatever you have, username `DB_USERNAME` and password `DB_PASSWORD` field correspond to your configuration. By default, the username is `root` and you can leave the **password field empty**. *(This is for Xampp)*. By default, the username is `root` and password is also `root`. *(This is for Lamp)*.

8. Now run following commands on terminal: 
```
php artisan key:generate
php artisan optimize:clear
```

9. You need to run following command for migrating the databases.

------------
>  **For Migrating Database:**
```
php artisan migrate --seed
```
------------

10. Now run this command `php artisan serve`. Then open browser and go to `http://localhost:8000`
