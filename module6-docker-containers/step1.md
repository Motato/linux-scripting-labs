# Building Images | Construyendo Imágenes

**Challenge | Reto:**
Create a simple Python script and a Dockerfile to run it.
> Crea un script de Python simple y un Dockerfile para ejecutarlo.

```bash
echo 'print("Hello from the Container!")' > app.py
echo -e "FROM python:3.9-slim\nCOPY app.py /app.py\nCMD [\"python\", \"/app.py\"]" > Dockerfile
docker build -t my-python-app .
docker run my-python-app
```{{exec}}

<details>
<summary>💡 Hint | Pista</summary>
<br>
The `docker build` command reads the Dockerfile to create the image, and `docker run` executes it.
<br>
<em>El comando `docker build` lee el Dockerfile para crear la imagen, y `docker run` la ejecuta.</em>
</details>
