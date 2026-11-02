# Biblioteca AD - Práctica JDBC

Proyecto de la asignatura de Acceso a Datos (DAM).

## Qué hace
- Conexión a PostgreSQL con JDBC
- Patrón DAO sobre la tabla `libro`
- CRUD completo: findAll, findById, insert, update y delete

## Tecnologías
- Java 21
- Maven
- PostgreSQL 18
- JDBC (driver 42.7.3)

## Cómo ejecutarlo
1. Crear la base de datos `biblioteca_ad` y la tabla `libro` en PostgreSQL.
2. Copiar `db.properties.example` a `src/main/resources/db.properties` y poner tu usuario y contraseña.
3. Ejecutar `Main` o `CrudDemo`.
