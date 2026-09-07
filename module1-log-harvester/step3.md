# Conditionals | Condicionales

Scripts need logic to prevent crashing if a file is missing.
> Los scripts necesitan lógica para evitar fallos si falta un archivo.

**Example | Ejemplo:**
```bash
if [ -f "pacing.txt" ]; then
    echo "File exists! | ¡El archivo existe!"
else
    echo "File not found. | Archivo no encontrado."
fi
```{{exec}}

### Your Challenge | Tu Reto
Wrap your `grep` command inside an `if` statement that checks if the log file exists first.
> Envuelve tu comando `grep` dentro de una declaración `if` que compruebe primero si el archivo de registro existe.
