# Laravel CRUD Generator

Este proyecto utiliza **Laravel CRUD Generator**, lo que simplifica la creación de aplicaciones CRUD (Crear, Leer, Actualizar, Eliminar) mediante comandos automáticos. Algunas características clave del generador incluyen:

- **Generación automática de migraciones** para la base de datos.
- **Generación de controladores**, vistas y rutas para facilitar la administración de recursos.
- **Interfaces de usuario listas para usar**, con diseños limpios y funcionales.
- Soporte para personalización avanzada de las vistas y controladores generados.

## Instalación

### 1. Clonar el repositorio
git clone https://github.com/tu_usuario/tu_repositorio.git

### 2. Instalar dependencias
cd tu_repositorio
composer install

### 3. Configuración del entorno
Copia el archivo .env.example a .env:
cp .env.example .env

### 4. Generar claves
php artisan key:generate

### 5. Migración de la base de datos
php artisan migrate

### 6. Crear un CRUD
php artisan crud:generate NombreModelo

https://github.com/awais-vteams/laravel-crud-generator