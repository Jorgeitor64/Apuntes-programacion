# Echo
Muestra texto o variables por pantalla
```bash
echo "Hola mundo"
------------------------------------------------------------------------
Hola mundo
```
Tiene diversas opciones
## Variables
```bash
name = Jorge
echo "Hola, $name"
------------------------------------------------------------------------
Hola, Jorge
```
## Opciones estilo
Para usar estos estilos se usa **-e**
Para imprimir múltiples líneas en una sola línea se usa **\n** y para tabularla **\t**
```bash
echo -e "Hola:\tJorge\nComo estás\nAdios"
------------------------------------------------------------------------
Hola:    Jorge
Como estás
Adios
```
## Crear archivos
Con el operador **>** se puede usar para crear un archivo en la ruta en la que lo ejecutes o para reemplazar su información si ya hay uno con el mismo nombre
```bash
echo hey > welcome.txt
```
Con el operador **>>** se añade la información extra en lugar de reemplazar la
## Información extra
[Comando Echo](https://labex.io/es/tutorials/linux-linux-echo-command-with-practical-examples-422656)