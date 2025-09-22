# 🚀 Démarrage rapide

```bash
git clone <repo-url> && cd <repo-folder>

cp .env.example .env
composer install
php artisan key:generate

# Base de données
php artisan migrate --seed

# Lancer en dev (PHP + Vite en parallèle)
npm ci
npm run dev