<h1>laravel-berita</h1>
laravel=berita is Laravel v10 starter template with AdminLTE 3 and Bootstrap 5. 

![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/3bda3d0b-4220-4b8a-8265-210b685a6611)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/a34a22e0-d4c8-4b26-bc13-92f9022b9fe0)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/b81e959e-359b-4594-b0da-7695f7cfedda)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/ae8f8903-31ad-4714-9b71-4c7b45fee3c3)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/f5e8ed7e-2c82-47b8-9438-e8a3df3ecb64)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/acdc3894-f88d-4b3e-868b-e344c9de7a50)


<h2>Features</h2>
<ul>
    <li>Laravel Breeze (Blade)</li>
    <li>Spatie Permission v6 with multi role</li>
    <li>Indonesian Region by Laravolt include: Province, City, District, Village</li>
    <li>Dashboard Admin: CRUD Post, Category, Tag, User, Navigation, Permission, Role</li>
    <li>Dashboard Author: CRUD Post, Edit Profile</li>
</ul>

<h3>Layout</h3>
Frontend: Bootstrap 5, Backend: AdminLTE 3

<h3>Packages</h3>
<ul>
    <li>Yajra Datatable</li>
    <li>SweetAlert</li>
    <li>Select2</li>
    <li>Bootstrap Datepicker</li>
    <li>Fontawesome 6</li>
</ul>

Or you can see all package that i've used in this repo from plugins in public > assets folder and composer.json file. But the plugins and packages are not all used, so you can see the actual one from layouts > app.blade.php and script.blade.php.

<h2>How to Install</h2>
<ul>
    <li>Make sure you are connected to internet and PHP 8.1 installed.</li>
    <li>Open your terminal / cmd / powershell to this project and run these commands:
        <ul>
            <li>composer install / composer update</li>
            <li>cp .env.example .env</li>
            <li>php artisan migrate</li>
            <li>php artisan db:seed</li>
        </ul>
    </li>
    <li>Setup SMTP Mail Credential (optional)
        <ul>
            <li>MAIL_MAILER=</li>
            <li>MAIL_HOST=</li>
            <li>MAIL_PORT=</li>
            <li>MAIL_USERNAME=</li>
            <li>MAIL_PASSWORD=</li>
            <li>MAIL_ENCRYPTION=</li>
            <li>MAIL_FROM_ADDRESS=""</li>
        </ul>
    </li>
</ul>

<h2>User Login Credential</h2>
<ul>
    <li>Admin: email and password; dinahariyanti48@gmail.com</li>
    <li>Author: email and password; alexandra22@gmail.com</li>
</ul>

Do you have another suggestions? Star, fork, and create PR for this repo. Let's make this repo better!

