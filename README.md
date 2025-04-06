# Larafila Starter Kit

A Laravel starter kit with Filament for panels, persian language, persian validation, vazirmatn font, and essential features for rapid application development.

Inspired from [vest-kits (laravel)](https://github.com/vest-kits/laravel) by [Nuno Maduro](https://github.com/nunomaduro)

## 🚀 Features

- **Laravel 12.x**
- **Filament 3.x**
- **Livewire 3.x**
- **Tailwind CSS 4.x**
- **Pest PHP**
- **PHPStan**
- **Rector**
- **Laravel Pint**
- **Laravel Persian Language**
- **Laravel Persian Validation**
- **Vazirmatn Font**

## 📦 Requirements

- PHP 8.2 or higher
- Composer
- Node.js & NPM
- MySQL/PostgreSQL
- Web Server (Apache/Nginx)

## 🛠 Installation

1. Clone the repository:
```bash
git clone https://github.com/sadegh19b/larafila-starter.git
```

2. Install PHP dependencies:
```bash
composer install
```

3. Install NPM dependencies:
```bash
npm install
```

4. Create environment file:
```bash
cp .env.example .env
```

5. Generate application key:
```bash
php artisan key:generate
```

6. Run migrations:
```bash
php artisan migrate
```

7. Start the development server:
```bash
php artisan serve
```

**Note**: For better performance, suggest to use the below commands to cache icons and components:
```bash
php artisan icons:cache
php artisan filament:cache-components
```

## 🏗 Project Structure

```
app/
├── Actions/         # Business logic actions
├── Enums/           # Enums
├── Fields/          # Model field constants
├── Filament/        # Filament admin panel resources
├── Http/
│   ├── Controllers/
├── Icons/           # Blade ui kit icons (heroicons)
├── Models/          # Eloquent models
├── Services/        # Service classes
└── Support/         # Support classes
```

## 🧪 Testing

Run tests using Pest PHP:
```bash
composer test
```

Run code style checks:
```bash
composer lint
```

Run refactoring with Rector:
```bash
composer refactor
```

## 📚 Documentation

- [Laravel Documentation](https://laravel.com/docs)
- [Laravel Pint Documentation](https://laravel.com/docs/12.x/pint)
- [Filament Documentation](https://filamentphp.com/docs)
- [Livewire Documentation](https://livewire.laravel.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Pest PHP Documentation](https://pestphp.com/docs)
- [Rector Documentation](https://getrector.com/documentation)
- [Rector Laravel Documentation](https://github.com/driftingly/rector-laravel)
- [PHPStan Documentation](https://phpstan.org)
- [Laravel Persian Validation](https://github.com/sadegh19b/laravel-persian-validation)
- [Heroicons](https://heroicons.com/)

## 📄 License

This project is licensed under the MIT License.