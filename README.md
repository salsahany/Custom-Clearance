## Quick Start

```bash
git clone https://github.com/salsahany/Custom-Clearance
cd project-name

composer install
npm install

cp .env.example .env
php artisan key:generate

php artisan migrate --seed

npm run dev
php artisan serve
```

Configure your database settings in `.env` before running migrations.
