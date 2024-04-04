## QUICK START


La instalación y configuración de Graphene-Django-Cruddals es un proceso rápido y sencillo, ¡listo en cuestión de segundos!



## PREREQUISITOS

Tener  un proyecto Django, con al menos un modelo.

* &gt;=2.2

## INSTALACION

En la raiz de tu proyecto Django installa Graphene-Django-Cruddals.

```python

pip install graphene-django-cruddals

```

## USO BASICO 

En una de tus aps de Django  **crea un archivo schema.py** al lado del archivo **models.py** que quieras *Crudalizar*
en este archivo copia este contenido. 



Al importar **crudadals.models**, convertimos tu modelo en los campos y tipos necesarios para tu esquema de Graphene. Luego, pasamos el modelo como un metatributo para obtener nuestro esquema completo, listo para usar en tu URL GraphQL.
