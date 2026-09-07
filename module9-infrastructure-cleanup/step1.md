# Pruning Resources | Podando Recursos

**Example | Ejemplo:**
First, let's create a dummy stopped container.
> Primero, creemos un contenedor detenido de prueba.

```bash
docker run ubuntu echo "I am finished"
docker ps -a
```{{exec}}

### Challenge | Reto
Use the system prune command to force-remove all stopped containers and unused data.
> Usa el comando system prune para forzar la eliminación de todos los contenedores detenidos y datos no utilizados.

```bash
docker system prune -f
docker ps -a
```{{exec}}
