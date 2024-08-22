<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# SSLaiss API

1. Clonar el proyecto
```
git clone https://github.com/jhon78963/ssl-backend.git
```
2. Instalar dependencias
```
composer install
```
3. Levantar postgresql con docker
```
docker-compose up --build -d
```
4. Clonar el archivo ```.env.example``` y renombrar a ```.env```
5. Cambiar las variables de entorno
6. Ejecutar migraciones y/o seeders
```
php artisan migrate --seed
```
7. Levantar servidor
```
php artisan serve
```
