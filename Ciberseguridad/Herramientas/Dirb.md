# Dirb
## Para qué sirve
[DIRB](https://www.kali.org/tools/dirb/) es una herramienta de escaneo de contenido web, sirve para encontrar archivos y directorios ocultos en un servidor web. Para ello lanza un [[Ataque de diccionario]] contra el servidor web y analizando las respuestas.

## Comandos
### Comando básico
Únicamente indicando la URL objetivo
```bash
dirb <URL_OBJETIVO>
```
### Con diccionario personalizado
```bash
dirb <URL_OBJETIVO> <RUTA_DICCIONARIO>
```

### Funcionalidades extra
#### Guardar resultado en un archivo
```bash
dirb <URL_OBJETIVO> <RUTA_DICCIONARIO>
```