# Blog Website



## Description



This is a blog website built with Laravel 11. The project includes user authentication, profile management. Users can view, create, edit, and delete their posts.



## Features



### User Features

- User authentication (register, login, logout)

- User profile management (view, edit, delete)

- Ad management (create, view, edit, delete)

- Upload and update avatar

- View other users' profiles



## Technologies Used



- Laravel 11

- Tailwind CSS

- MySQL

- PHP

- Composer



## Installation



### Prerequisites

- PHP >= 8.1

- Composer

- MySQL

- Node.js & npm



### Steps



1. Clone the repository:

   ```bash

   git clone

git@github.com:7Xopencode/C-DEV-Blog-Laravel-MVC-Framework-EpitechProject-JustinGode.git

   ```



2. Navigate to the project directory:

   ```bash

   cd blogs

   ```



3. Install dependencies:

   ```bash

   composer install

   npm install

   ```



4. Copy the `.env.example` file to `.env` and configure your database and other environment variables:

   ```bash

   cp .env.example .env

   ```



5. Generate the application key:

   ```bash

   php artisan key:generate

   ```



6. Run the migrations:

   ```bash

   php artisan migrate

   ```



7. Seed the database (optional):

   ```bash
   flow this order
    
   php arsian serve

   php artisan db:seed --class=UserSeeder     
   php artisan db:seed --class=PhotoSeeder
   php artisan db:seed --class=LocationSeeder
   php artisan db:seed --class=CategorieSeeder
   php artisan db:seed --class=AdSeeder
   ```



8. Build the front-end assets:

   ```bash

   npm run dev

   ```



9. Serve the application:

   ```bash

   php artisan serve

   ```



10. Visit the application in your browser:

    ```

    http://localhost:8000

    ```



## Usage



### User Authentication

- Register a new account or log in with an existing one.

- Access your profile to view and edit your information.

- Create new ads and manage existing ones.



### Admin Dashboard

- Log in with admin credentials.

- Access the admin dashboard to manage users, categories, conditions, and locations.



## Routes



### User Routes

- `/register` - User registration

- `/login` - User login

- `/profile` - View and edit user profile

- `/ads` - View and manage ads



## Directory Structure



- `app/Http/Controllers` - Application controllers

- `app/Models` - Eloquent models

- `resources/views` - Blade templates

- `routes` - Application routes

- `database/migrations` - Database migrations

- `database/seeders` - Database seeders


## Contributing



### Steps



1. Fork the repository

2. Create a new branch (`git checkout -b feature/your-feature`)

3. Commit your changes (`git commit -m 'Add some feature'`)

4. Push to the branch (`git push origin feature/your-feature`)

5. Open a pull request





## Contact



If you have any questions, feel free to contact the project maintainer at justin.gode@epitech.eu
