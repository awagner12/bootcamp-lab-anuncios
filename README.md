# bootcamp-lab-anuncios

En este lab vamos a crear una página web de anuncios. 
Objetivo:
- Aprender a paginar un listado largo de objetos (anuncios en este caso)
- Implementar búsqueda
- Implementar filtro por categoías y país
- Implementar formulario para crear anuncios con validaciones.

## Iteración 1
Hacer un fork del repositorio y clonar el repositorio en local.
## Iteración 2
Crear virtual environment 

`conda create --name bootcamp-lab-anuncios python=3.8`
## Iteración 3
Instalar Django

`pip install Django`
## Iteración 4
Crear proyecto de Django

`django-admin startproject anuncios`

## Iteración 5
Crear modelo anuncio con los siguientes atributos:

- Nombre
- Descripción
- País
- Categoría (Electrónica, Mascotas, Muebles, Bricolaje, Inmuebles, otros)
- Email 
- Teléfono
- Nombre del anunciante

## Iteracion 6
Crear panel administrativo (Django admin) y añadir el modelo Anuncio. 

Esto nos permitirá comprobar que vamos bien y podremos crear anuncios de prueba.
## Iteración 7
- Instalar Bootstrap
- Crear página principal con el listado de anuncios


## Iteración 8
Crear página de creación de anuncios, donde cualquier usuario podrá añadir anuncios.

## Iteración 9
Añadir paginación al listado de anuncios.

## Iteración 10
Añadir filtros por categoría y país

