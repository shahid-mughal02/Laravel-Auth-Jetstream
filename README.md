## Laravel Installer Globally Setup
```
composer global require laravel/installer
```

## Install Laravel Project
```
laravel new project_name
```

## Install Laravel Jetsream
```
composer require laravel/jetstream
```

## Install Livewire for frontend
```
php artisan jetstream:install livewire
```

## Install All Packages
```
npm install
```

## Build Application
```
npm run dev
```

## Coonect with Database and make Migration
```
php artisan migrate
```

## Publish Jetstream Views
> If you install jetstream with inertia then ignore this command
```
php artisan vendor:publish --tag=jetstream-views
```

## Run Project
```
php artisan serve
```

## App Features
- [x] Can update name, email and password
- [x] Can enable two-factor authentication using QR Code
- [x] Can logout from other browsers
- [x] Can delete account