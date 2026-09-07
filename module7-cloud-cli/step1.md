# GCP SDK Container

Instead of installing heavy cloud tools locally, you can run them directly via Docker.
> En lugar de instalar pesadas herramientas en la nube localmente, puedes ejecutarlas directamente mediante Docker.

```bash
docker run --rm google/cloud-sdk gcloud --version
```{{exec}}

**Challenge | Reto:**
Try running a mock cloud storage command to list buckets.
> Intenta ejecutar un comando simulado de almacenamiento en la nube para listar buckets.

```bash
docker run --rm google/cloud-sdk gsutil help ls
```{{exec}}
