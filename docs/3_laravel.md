Laravel project létrehozása
`composer create-project --prefer-dist laravel/laravel . "^12.0"`

Laravel verzió ellenőrzés
`php artisan --version`

backend/ .env fileban
- APP_URL=http://localhost:8001
- DB_CONNECTION=mysql
- DB_HOST=db
- DB_PORT=3306
- DB_DATABASE=todo_db
- DB_USERNAME=todo
- DB_PASSWORD=todo_secret

API támogatás telepítése
`php artisan install:api`

API útvonalak listázása
`php artisan route:list --path=api`

Migráció futtatása (adatbázis szerkezet kialakítása)
`php artisan migrate`

Amiket a migráció hozott létre
`php artisan migrate:status`

Fejlesztői szerver indítása
`php artisan serve --host=0.0.0.0 --port=8000`