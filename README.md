# Chat and push notification

## Getting Started

Clone the project repository by running the command below if you use SSH

```bash
git clone https://github.com/maybinod/chat-application.git
```

After cloning,run:

```bash
composer install
```

Generate application key
````
php artisan key:generate
````
Duplicate `.env.example` and rename it `.env`

Then run:

```bash
php artisan key:generate
```

#### Seed data with some users
````
php artisan db:seed
````

#### Database Migrations

Be sure to fill in your database details in your `.env` file before running the migrations:

```bash
php artisan migrate
```

And finally, start the application:

```bash
php artisan serve
```

#### User credentials
1. Admin
    `email: admin@example.com`
    `password: admin123`

2. Employee
   `email: employee@example.com`
   `password: employee123`

3. User
   `email: user@example.com`
   `password: user123`
