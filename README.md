## Installation

1. Install dependencies:

```
composer install
npm install
```

2. Copy **env.example** and update **.env** with your settings (DB_DATABASE, DB_USERNAME, DB_PASSWORD, etc.):
```
copy .env.example .env
```

3. Generate laravel encryption key:
```
php artisan key:generate
```

4. Migrate database:
```
php artisan migrate
```

5. Serve project:
```
php artisan serve
```