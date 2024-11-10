# Task-Tracker

Task-Tracker es una aplicación web diseñada para ayudar a los usuarios a gestionar y realizar un seguimiento de sus tareas. Este proyecto está desarrollado utilizando **Django** como framework backend, y **Jinja** como motor de plantillas HTML, con un diseño responsivo y moderno gracias a **Bootstrap 5**.

## Tecnologías Usadas

- **Python**: Lenguaje de programación del proyecto.
- **Django**: Framework web para el desarrollo del lado del servidor.
- **Jinja**: Motor de plantillas utilizado para generar las páginas HTML.
- **HTML y CSS**: Estructura y estilo de la aplicación.
- **Bootstrap 5**: Framework CSS para diseño responsivo.
- **Render**: Plataforma para el despliegue de aplicaciones.
- **PostgreSQL**: Sistema de bases de datos, alojado en Render.

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/AlenSaavedra/Web-Django.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd Web-Django
    ```

3. Crea un entorno virtual y actívalo:

    ```bash
    python3 -m venv env
    source env/bin/activate  # En Windows: env\Scripts\activate
    ```

4. Instala las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

5. Configura las variables de entorno necesarias para el despliegue en Render y la conexión a PostgreSQL.

## Uso

1. Realiza las migraciones para configurar la base de datos:

    ```bash
    python manage.py migrate
    ```

2. Inicia el servidor de desarrollo:

    ```bash
    python manage.py runserver
    ```

3. Accede a la aplicación en `http://127.0.0.1:8000`.

## Despliegue en Render

Task-Tracker está diseñado para ser desplegado en Render, utilizando una base de datos PostgreSQL. Consulta la [documentación de Render](https://render.com/docs) para más detalles sobre el despliegue.

## Contribución

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza los cambios y haz commits (`git commit -am 'Agrega nueva funcionalidad'`).
4. Sube los cambios a tu repositorio (`git push origin feature/nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. 
