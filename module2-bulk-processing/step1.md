# For Loops | Bucles For

**Example | Ejemplo:**
```bash
mkdir -p matches
touch matches/match1.txt matches/match2.txt
for game in matches/*.txt; do
    echo "Processing match data: $game"
done
```{{exec}}

### Challenge | Reto
Write a loop that prints "Processing log..." 5 times.
> Escribe un bucle que imprima "Procesando log..." 5 veces.

<details>
<summary>💡 Hint | Pista</summary>
<br>
<code>for i in {1..5}; do echo "Processing log..."; done</code>
</details>
