# Jetstream and Livewire Installation with Laravel
---
```
composer create-project laravel/laravel projectname "^12.0"
```

- After creating the laravel project that have been downgrated to laravel 12 now run this command
- If you will use the latest version of laravel you can run without the "^version" command
---
```
composer require laravel/jetstream // use this only if you're using laravel 12
composer require laravel/jetstream -W // use this if you will use jetstream with the latest version of laravel
```
- If you want to learn more you can go to <a href="https://jetstream.laravel.com/introduction.html">Jetstream Website.</a>
- Run this command to install livewire with jetstream, it's up to you if you want to use dark mode with "--dark"
```
php artisan jetstream:install livewire // without dark mode
php artisan jetstream:install livewire --dark // with default dark more
```
