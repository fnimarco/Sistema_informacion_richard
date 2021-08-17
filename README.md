## Sistema_informacion_richard

## Instalación

`git clone https://github.com/fnimarco/Sistema_informacion_richard.git`

`cd Sistema_informacion_richard`

`composer install`

`cp .env.example .env`

`php artisan key:generate`

Registrar las credenciales de la base de datos, reconpilar, y luego ejecuar las migraciones

`php artisan cache:clear`

`php artisan config:cache`

`php artisan migrate:fresh --seed`

Ejecutar la aplicación web

`php artisan serv`

## Demo

https://afternoon-woodland-93527.herokuapp.com/

## Power BI
https://app.powerbi.com/reportEmbed?reportId=7aff522e-a27c-42a7-b464-884eeb7f4be3&autoAuth=true&ctid=75b0567a-be11-461a-9c74-17e3a5f96741&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXVzLW5vcnRoLWNlbnRyYWwtcmVkaXJlY3QuYW5hbHlzaXMud2luZG93cy5uZXQvIn0%3D

## Acerca de...

- Desarrollado por: Marco Antonio Mamani
- Email: fnimarco@gmail.com
