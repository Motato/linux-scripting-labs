# Extracting Data | Extrayendo Datos

Let's look at a filtering example. Imagine filtering a running log to find all half-marathon pacing times.
> Veamos un ejemplo de filtrado. Imagina filtrar un registro de entrenamiento para encontrar los tiempos de medio maratón.

**Example | Ejemplo:**
```bash
echo -e "5K: 0:25:00\n21K: 1:56:48\n10K: 0:52:10" > pacing.txt
grep "21K" pacing.txt
```{{exec}}

---

### Your Challenge | Tu Reto
Open your `log_harvester.sh` script. Add a command to extract only the "ERROR" lines from your `$LOG_FILE` and save them to a new file called `errors.txt`.
> Abre tu script `log_harvester.sh`. Añade un comando para extraer solo las líneas con "ERROR" de tu `$LOG_FILE` y guárdalas en un nuevo archivo llamado `errors.txt`.

<details>
<summary>💡 Hint | Pista</summary>
<br>
Use the syntax: <code>grep "ERROR" "$LOG_FILE" > errors.txt</code>
</details>
