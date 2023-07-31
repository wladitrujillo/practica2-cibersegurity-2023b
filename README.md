# practica2-cibersegurity-2023b

## Práctica ETL
* scraping con selenium a un sitio web (Extract)
* conversion de datos extraidos a un objeto json (Transform)
* carga de los datos transformados a una colección en mongoDB (Load)

### Project structure

| File              | Description                   |
|-------------------|-------------------------------|
| main              | Archivo principal             |
| db                | Conexión a mongo              |
| requirements      | Dependencias externas         |
| .env              | Variables de entorno          |

### Ejemplo .env
```
MONGO_USER=username
MONGO_PASSWORD=password
MONGO_HOSTNAME=cluster.id.mongodb.net
```

