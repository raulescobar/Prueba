# Prueba técnica - Gestor Productos
Esta es una aplicación web para gestionar productos (CRUD) construida con Laravel


## Requisitos

*   Docker
*   Docker Compose

## Instalación y ejecución

1.  Clona el repositorio:
    ```bash
    git clone [URL_DE_TU_REPO]
    cd Prueba
    ```

2.  Laravel Sail utiliza un archivo `docker-compose.yml` que ya está incluido. Levanta los servicios con Sail:
    ```bash
    ./vendor/bin/sail up -d
    ```

3.  Ejecuta las migraciones de la base de datos para crear la tabla `products`:
    ```bash
    ./vendor/bin/sail artisan migrate
    ```

4.  ¡Listo! La aplicación está corriendo.
    *   **API Endpoint:** `http://localhost/api/products`

