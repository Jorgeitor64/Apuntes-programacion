# Grep
Busca patrones y contenido específico en archivos de texto
```bash
grep "palabra" note.txt
```
Busca una palabra dentro del archivo de texto
## Opciones adicionales
- **-i** Busca tanto la palabra en minúscula como la primera en mayúscula (perro/Perro)
- **^** Busca una expresión que comience a principio de línea
- **-E** Permite extender expresiones
```bash
grep -E "perro.*perezoso|perezoso.*perro" note.txt
```
- **-v** Sirve para excluir líneas con una palabra determinada
```bash
grep "perro" note.txt | grep -v "perezoso"
# Si una línea tiene la palabra perezoso no 
```