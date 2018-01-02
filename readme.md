# Sco Admin Demo

[Sco Admin](https://github.com/ScoLib/admin "Sco Admin") Demo，Permission use [laravel-permission](https://github.com/spatie/laravel-permission)


# Install

```bash
git clone https://github.com/ScoLib/admin-demo-by-laravel-permission.git
cd admin-demo-by-laravel-permission
composer install -vvv
copy .env.example .env
php artisan key:generate
```
Open `.env` file, write database info.

run the command, import tables:

```bash
php artisan migrate --seed
```

If you want change VueJS component 

First install js package

```javascript
npm install
```

```javascript
npm run prod
```