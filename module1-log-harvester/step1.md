# Variables

Before writing our script, let's look at a simple example of declaring variables in Linux.
> Antes de escribir nuestro script, veamos un ejemplo simple de cómo declarar variables en Linux.

**Example | Ejemplo:**
```bash
PLAYER="Striker"
GOALS=2
echo "The $PLAYER scored $GOALS goals in the final match."
```{{exec}}

---

### Your Challenge | Tu Reto
Create a script named `log_harvester.sh`. Define a variable for the target log file (`app.log`) and make the script executable.
> Crea un script llamado `log_harvester.sh`. Define una variable para el archivo de registro objetivo (`app.log`) y haz que el script sea ejecutable.

`nano log_harvester.sh`{{exec}}

<details>
<summary>💡 Hint | Pista</summary>
<br>
Start your script with <code>#!/bin/bash</code>.<br>
Define your variable like this: <code>LOG_FILE="app.log"</code><br>
Make it executable using: <code>chmod +x log_harvester.sh</code>
</details>
