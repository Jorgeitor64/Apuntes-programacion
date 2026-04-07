# Echo
Muestra texto o variables por pantalla
```
echo "Hola mundo"
------------------------------------------------------------------------
Hola mundo
```
Tiene diversas opciones
## Variables
```
name = Jorge
echo "Hola, $name"
------------------------------------------------------------------------
Hola, Jorge
```
## Opciones estilo
Para usar estos estilos se usa **-e**
Para imprimir múltiples líneas en una sola línea se usa **\n**
```
echo -e "Hola, Jorge\nComo estás\nAdios"
------------------------------------------------------------------------
Hola, Jorge
Como estás
Adios
```
Para tabular una línea se usa **\t**
Para ponerla en negrita \e