Muestra el nombre de usuario de la sesión actual
```
whoami
------------------------------------------------------------------------
jorgemd64
```
Esto tiene diversas aplicaciones como comprobar si el usuario es el esperado por un script
```
#!/bin/bash
echo "El usuario actual es: $(whoami)"
if [ "$(whoami)" == "jorgemd64" ]; then
	echo "Eres el usuario deseado, comenzando tarea"
	#######
else
	echo "No eres este usuario"
	exit 1
fi
```