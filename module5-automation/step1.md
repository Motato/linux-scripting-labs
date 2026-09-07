# Scheduling | Programación

**Example | Ejemplo:**
This syntax runs a backup every Sunday at midnight (0 0 * * 0).
> Esta sintaxis ejecuta una copia de seguridad cada domingo a medianoche.

```bash
echo "0 0 * * 0 /root/backup.sh" > mycron
crontab mycron
crontab -l
```{{exec}}

### Challenge | Reto
Write a cron expression that runs every minute (`* * * * *`).
> Escribe una expresión cron que se ejecute cada minuto (`* * * * *`).
