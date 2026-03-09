# LECTONAUTA

LECTONAUTA es una aplicación web desarrollada con el framework Django que permite promocionar productos de un emprendimiento. En este proyecto se implementó una tienda de libros donde los usuarios pueden visualizar el catálogo de productos, consultar los detalles de cada libro y gestionar su interacción con el sitio.

El objetivo de la aplicación es demostrar el uso de Django para construir una aplicación web completa que utilice una base de datos, almacenamiento de imágenes y una interfaz web basada en plantillas.

## Tecnologías utilizadas

Este proyecto fue desarrollado utilizando las siguientes tecnologías:

Python  
Django  
HTML  
CSS  
SQLite  

## Descripción del funcionamiento

La aplicación permite mostrar un catálogo de libros almacenados en la base de datos. Cada libro contiene información como título, autor, descripción, precio, imagen y stock disponible.

Los libros se presentan en forma de tarjetas dentro de la página principal, permitiendo al usuario navegar entre los diferentes productos disponibles.

Cada libro cuenta con una página de detalle donde se puede visualizar información más completa del producto.

## Base de datos y almacenamiento de imágenes

La información de los libros se almacena en una base de datos SQLite, que es la base de datos incluida por defecto en Django.

Las imágenes de los productos se almacenan en la carpeta **media** del servidor. Django está configurado para guardar y servir estas imágenes automáticamente dentro de la aplicación.

## Panel administrativo

Django proporciona un panel administrativo que permite gestionar los productos del sistema sin necesidad de modificar el código.

Desde el panel administrativo es posible:

Agregar nuevos libros  
Editar información de los productos  
Eliminar productos  
Subir imágenes de los libros  

Acceso al panel administrativo:

http://127.0.0.1:8000/admin

## Funcionalidades implementadas

El sistema incluye las siguientes funcionalidades:

Visualización del catálogo de libros  
Página de detalle para cada producto  
Panel administrativo para gestión de productos  
Almacenamiento de imágenes en el servidor  
Sistema de favoritos  
Carrito de compras  
Página de pago simulada  
Buscador de libros  
Interfaz visual basada en tarjetas de productos  

Estas funcionalidades permiten mejorar la experiencia del usuario y demostrar el uso de Django para construir aplicaciones web dinámicas.

## Estructura del proyecto

El proyecto está organizado en las siguientes carpetas principales:

lectonautaweb → configuración principal del proyecto Django  
libros → aplicación donde se definen modelos, vistas y administración  
Plantillas → páginas HTML de la aplicación  
media → almacenamiento de imágenes de los libros  
db.sqlite3 → base de datos del proyecto  

## Ejecución del proyecto

Para ejecutar la aplicación se deben seguir los siguientes pasos:

1. Abrir una terminal en la carpeta del proyecto

2. Activar el entorno virtual

..\dj-env\Scripts\activate

3. Ejecutar el servidor de Django

python manage.py runserver

4. Abrir el navegador y acceder a la siguiente dirección

http://127.0.0.1:8000

## Autor

Proyecto desarrollado como práctica académica para el aprendizaje del framework Django y el desarrollo de aplicaciones web.# LECTONAUTA

LECTONAUTA es una aplicación web desarrollada con el framework Django que permite promocionar productos de un emprendimiento. En este proyecto se implementó una tienda de libros donde los usuarios pueden visualizar el catálogo de productos, consultar los detalles de cada libro y gestionar su interacción con el sitio.

El objetivo de la aplicación es demostrar el uso de Django para construir una aplicación web completa que utilice una base de datos, almacenamiento de imágenes y una interfaz web basada en plantillas.

## Tecnologías utilizadas

Este proyecto fue desarrollado utilizando las siguientes tecnologías:

Python  
Django  
HTML  
CSS  
SQLite  

## Descripción del funcionamiento

La aplicación permite mostrar un catálogo de libros almacenados en la base de datos. Cada libro contiene información como título, autor, descripción, precio, imagen y stock disponible.

Los libros se presentan en forma de tarjetas dentro de la página principal, permitiendo al usuario navegar entre los diferentes productos disponibles.

Cada libro cuenta con una página de detalle donde se puede visualizar información más completa del producto.

## Base de datos y almacenamiento de imágenes

La información de los libros se almacena en una base de datos SQLite, que es la base de datos incluida por defecto en Django.

Las imágenes de los productos se almacenan en la carpeta **media** del servidor. Django está configurado para guardar y servir estas imágenes automáticamente dentro de la aplicación.

## Panel administrativo

Django proporciona un panel administrativo que permite gestionar los productos del sistema sin necesidad de modificar el código.

Desde el panel administrativo es posible:

Agregar nuevos libros  
Editar información de los productos  
Eliminar productos  
Subir imágenes de los libros  

Acceso al panel administrativo:

http://127.0.0.1:8000/admin

## Funcionalidades implementadas

El sistema incluye las siguientes funcionalidades:

Visualización del catálogo de libros  
Página de detalle para cada producto  
Panel administrativo para gestión de productos  
Almacenamiento de imágenes en el servidor  
Sistema de favoritos  
Carrito de compras  
Página de pago simulada  
Buscador de libros  
Interfaz visual basada en tarjetas de productos  

Estas funcionalidades permiten mejorar la experiencia del usuario y demostrar el uso de Django para construir aplicaciones web dinámicas.

## Estructura del proyecto

El proyecto está organizado en las siguientes carpetas principales:

lectonautaweb → configuración principal del proyecto Django  
libros → aplicación donde se definen modelos, vistas y administración  
Plantillas → páginas HTML de la aplicación  
media → almacenamiento de imágenes de los libros  
db.sqlite3 → base de datos del proyecto  

## Ejecución del proyecto

Para ejecutar la aplicación se deben seguir los siguientes pasos:

1. Abrir una terminal en la carpeta del proyecto

2. Activar el entorno virtual

..\dj-env\Scripts\activate

3. Ejecutar el servidor de Django

python manage.py runserver

4. Abrir el navegador y acceder a la siguiente dirección

http://127.0.0.1:8000

## Autor

Proyecto desarrollado como práctica académica para el aprendizaje del framework Django y el desarrollo de aplicaciones web.
