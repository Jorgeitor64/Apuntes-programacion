# Find
Permite buscar archivos y directorios basándonos en los criterios que le pasemos
```bash
find [path] [expression]
```
Si no indicamos [path] tomará en el que nos encontremos
## Ejemplo
- Buscar todos los archivos en el directorio actual (Como ls -a)
```bash
find .
```
## Expresiones
- **-name** Buscar todos los archivos con una extensión determinada o una palabra en común
```bash
find . -name "*.txt"
find . -name "file1.txt"
```
- **-type** Buscar todos los archivos de cierto tipo o todos los directorios
	- **f** Archivo normal
	- **d** Directorio
```bash
find . -type d
```
- **-size** Buscar todos los archivos de cierto tamaño
```bash
find . -size +1M
```
- **-delete** Elimina los archivos encontrado
```bash
find . -type f -name "*.tmp" -delete
```
## Información extra
[Comando Find](https://labex.io/es/tutorials/linux-linux-find-command-with-practical-examples-422682)