# Environment Variables | Variables de Entorno

**Example | Ejemplo:**
We can inject a target database name or SQL query directly into a container at runtime.
> Podemos inyectar el nombre de una base de datos o consulta SQL directamente en un contenedor durante la ejecución.

```bash
docker run -e TARGET_DB="sales_data" ubuntu bash -c 'echo "Connecting to database: $TARGET_DB"'
```{{exec}}

### Challenge | Reto
Write a shell command that runs an Ubuntu container and passes a variable `QUERY="SELECT * FROM users"`, then prints it.
> Escribe un comando shell que ejecute un contenedor Ubuntu y pase una variable `QUERY="SELECT * FROM users"`, y luego la imprima.
