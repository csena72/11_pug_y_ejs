# Desafío #11 Pug y Ejs

### Consigna:  
Sobre el proyecto entregable de la clase anterior, realizar las siguientes adaptaciones

1) Manteniendo la misma funcionalidad reemplazar el motor de plantillas handlebars por pug.
2) Manteniendo la misma funcionalidad reemplazar el motor de plantillas handlebars por ejs.
3) Por escrito, indicar cuál de los tres motores de plantillas prefieres para tu proyecto. Justificar tu respuesta.


## Aspectos a incluir en el entregable:
- Puedes utilizar branches para las consignas 1) y 2) (Optativo) o simplemente hacer dos commits.
- La justificación puede ir escrita al subir la entrega. Si utilizaste branches, puedes enviar al máster la opción seleccionada.


## Ejemplo para consumir el EP que actualiza un producto:

```
curl --location --request PUT 'localhost:8080/api/productos/2' \
--header 'Content-Type: application/json' \
--data-raw '[
    {
        "title": "manzana",
        "price": "222",
        "thumbnail": "dsafwea"        
    }
]'
```

## Ejemplo para consumir el EP que borra un producto:

```
curl --location --request DELETE 'localhost:8080/api/productos/2'
```