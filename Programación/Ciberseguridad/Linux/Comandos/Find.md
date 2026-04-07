# Find
Permite buscar archivos y directorios basándonos en los criterios que le pasemos
```
find [path] [expression]
```
Si no indicamos [path] tomará en el que nos encontremos
## Ejemplo
- Buscar todos los archivos en el directorio actual (Como ls -a)
```
find .
```
## Expresiones
- **-name** Buscar todos los archivos con una extensión determinada o una palabra en común
```
find . -name "*.txt"
```
- **-type** 