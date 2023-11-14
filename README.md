# Proyecto de Administración de Usuarios

## Autor

Kevin Martínez

## Introducción

Este proyecto es una aplicación web simple para la administración de usuarios, con funcionalidades de inicio de sesión y redirección basada en roles.

## Marco Teórico

La aplicación utiliza el framework Flask para Python y una base de datos MySQL para almacenar y gestionar la información de los usuarios.

## Herramientas

- Python
- Flask
- MySQL
- HTML
- CSS
- Bootstrap

## Explicación del Código

### Estructura del Proyecto

El proyecto sigue una estructura básica de archivos y carpetas:

- `app.py`: Punto de entrada de la aplicación.
- `config.py`: Configuración de la aplicación.
- `templates/`: Carpeta que contiene las plantillas HTML.
- `static/`: Carpeta para archivos estáticos como CSS E IMAGENES
- `models/`: Carpeta que contiene los modelos de datos y la lógica de la aplicación.

### Funcionalidades

- **Login**: El usuario puede iniciar sesión proporcionando un nombre de usuario y contraseña.
- **Redirección por Roles**: Dependiendo del tipo de usuario (admin o user), se redirige a la página correspondiente.
- **Diseño Homogéneo**: Las páginas de `login.html`, `admin.html` y `home.html` tienen un diseño coherente.

### Instrucciones de Ejecución

1. Instalar las dependencias: `pip install Flask Flask-MySQLdb`.
2. Configurar las credenciales de la base de datos en `config.py`.
3. Ejecutar `app.py` para iniciar la aplicación.

## Conclusiones

El proyecto proporciona una base sólida para la gestión de usuarios, pero aún puede mejorarse añadiendo más características y mejorando el diseño.

## Contribuciones

Este proyecto es de código abierto. Si deseas contribuir, sigue las pautas en el archivo CONTRIBUTING.md.

## Licencia

Este proyecto está bajo la licencia MIT.

## Contacto

Para preguntas o colaboraciones, puedes contactarme por correo electrónico: a20490747@itmexicali.edu.mx.
