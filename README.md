# API DE DISPOSITIVOS TECNOLOGICOS

API desarrollada con FastAPI para consultar dispositivos tecnológicos.

## Documentación interactiva
- **[Swagger UI](https://api-lista-tech.onrender.com/docs)**
- **[ReDoc](https://api-lista-tech.onrender.com/redoc)**

- ## Endpoints principales
- `GET /tech/search?category=X&subcategory=Y&name=Z`: Búsqueda filtrada.
- `GET /tech`: Todos los dispositivos.
- `GET /tech/{id}`: Dispositivo por ID.
- `GET /tech/category/{cat}`: Dispositivo(s) por Categoria.
- `GET /tech/subcategory/{sub}`: Dispositivo(s) por Subcategoria.
- `GET /tech/name/{name}`: Dispositivo por Nombre.
- `GET /tech/{cat}/{sub}`: Dispositivo por Categoria y Subcategoria.
- `GET /tech/{cat}/{sub}/{name}`: Dispositivo por Categoria, Subcategoria y Nombre.
- `GET /tech/sub/{sub}/name/{name}`: Dispositivo por Subcategoria y Nombre

## Ejemplo de uso
```bash
curl -X 'GET' 'https://api-lista-tech.onrender.com/tech/1'
