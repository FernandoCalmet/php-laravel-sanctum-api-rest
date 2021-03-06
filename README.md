# PHP Laravel Sanctum API RESTFUL

[![Github][github-shield]][github-url]
[![Kofi][kofi-shield]][kofi-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Khanakat][khanakat-shield]][khanakat-url]

## 馃敟 ACERCA DEL PROYECTO

馃 Este proyecto es una muestra de una aplicaci贸n b谩sica API REST utilizando Laravel Sanctum.

## 鉁旓笍 CARACTER脥STICAS

- [x] Auth Login
- [x] Create User
- [x] Get User Authenticated

## 鈿欙笍 INSTALACI脫N

Clonar proyecto

```bash
gh repo clone FernandoCalmet/php-laravel-sanctum-api-rest
```

Ejecutar proyecto

```bash
php artisan serve
```

### COMANDOS UTILIZADOS

Crear proyecto

```bash
composer create-project laravel/laravel myproject-name
```

Instalar laravel sanctum

```bash
composer require laravel/sanctum
```

Publicar la configuraci贸n y migraci贸n de los archivos de sanctum

```bash
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
```

Migrar base de datos

```bash
php artisan migrate
```

Crear controlador de autenticaci贸n de usuario

```bash
php artisan make:controller AuthController
```

## 馃搫 LICENCIA

Este proyecto est谩 bajo la Licencia (Licencia MIT) - mire el archivo [LICENSE](LICENSE) para m谩s detalles.

## 猸愶笍 DAME UNA ESTRELLA

Si esta Implementaci贸n le result贸 煤til o la utiliz贸 en sus Proyectos, d茅le una estrella. 隆Gracias! O, si te sientes realmente generoso, [隆Apoye el proyecto con una peque帽a contribuci贸n!](https://ko-fi.com/fernandocalmet).

<!--- reference style links --->
[github-shield]: https://img.shields.io/badge/-@fernandocalmet-%23181717?style=flat-square&logo=github
[github-url]: https://github.com/fernandocalmet
[kofi-shield]: https://img.shields.io/badge/-@fernandocalmet-%231DA1F2?style=flat-square&logo=kofi&logoColor=ff5f5f
[kofi-url]: https://ko-fi.com/fernandocalmet
[linkedin-shield]: https://img.shields.io/badge/-fernandocalmet-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernandocalmet
[linkedin-url]: https://www.linkedin.com/in/fernandocalmet
[khanakat-shield]: https://img.shields.io/badge/khanakat.com-brightgreen?style=flat-square
[khanakat-url]: https://khanakat.com
