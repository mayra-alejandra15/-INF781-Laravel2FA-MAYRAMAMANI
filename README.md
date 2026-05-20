# INF781 Laravel 2FA

Aplicación web desarrollada en Laravel con autenticación de dos factores (2FA) usando Google Authenticator.

## Características

- Registro de usuarios
- Inicio de sesión
- Generación de QR para 2FA
- Activación y desactivación de autenticación en dos pasos
- PostgreSQL como base de datos

## Requisitos

- PHP 8+
- Composer
- PostgreSQL
- Laravel 13

## Instalación

Clonar repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

Entrar al proyecto:

```bash
cd INF781-Laravel2FA
```

Instalar dependencias:

```bash
composer install
```

Copiar archivo .env:

```bash
cp .env.example .env
```

Generar clave:

```bash
php artisan key:generate
```

Ejecutar migraciones:

```bash
php artisan migrate:fresh
```

Iniciar servidor:

```bash
php artisan serve
```

## Autor

Mayra Alejandra
