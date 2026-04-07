# Ls
Se utiliza para listar el contenido de un directorio, proporciona información como sus nombres, permisos o propietarios.
```
ls

file1.txt  file2.txt  folder1  folder2
```
## -l
Se utiliza para obtener información más detallada
```
total 8
-rw-r--r-- 1 labex labex 0 Apr 12 12:34 file1.txt
-rw-r--r-- 1 labex labex 0 Apr 12 12:34 file2.txt
drwxr-xr-x 2 labex labex 4096 Apr 12 12:34 folder1
drwxr-xr-x 2 labex labex 4096 Apr 12 12:34 folder2
```
## -a
Muestra archivos ocultos que empiecen por "."
```
.hidden_file .cache file1.txt  file2.txt  folder1  folder2
```
Usando **-la** se consigue una mezcla de los dos anteriores
## Otros comandos útiles
Usando **-lh** los archivos muestran un tamaño más legible
```
drwxr-xr-x 2 labex labex 4.0K Apr 12 12:34 folder2
```
Usando **-lr** la lista sale inversa

Esto se puede combinar reiteradamente para obtener una lista detallada reversa **-lra**
## Listar otros directorios
Para listar el contenido de un directorio concreto se usa **~**
```
ls ~/project/new_folder
```
Si se quieren agregar sus subdirectorios se combina con **-R**
#### Información extra
[Comando Ls](https://labex.io/es/tutorials/linux-linux-ls-command-with-practical-examples-422776)