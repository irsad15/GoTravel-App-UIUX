Cara menjalankan
```

-   Copy .env.example dan ubah jadi .env and edit database/nama database travel 

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

untuk admin http://127.0.0.1:8000/Login

-   email = admin@admin.com
-   password = 123
