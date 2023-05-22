# Laravel 8 - Quiz Application

## Screenshots

![preview img](/preview.png)
![preview img](/preview2.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/avrians/laravel-quiz.git
```

Go to the project directory

```bash
  cd laravel-quiz
```

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Login

-   email = admin@example.com
-   password = admin123
