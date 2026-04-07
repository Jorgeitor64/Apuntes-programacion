Muestra el nombre de usuario de la sesión actual
```
whoami
------------------------------------------------------------------------
jorgemd64
```
Esto tiene diversas aplicaciones como comprobar si el usuario es el esperado por un script
```
#!/bin/bash
echo "The current user is: $(whoami)"
if [ "$(whoami)" == "labex" ]; then
	echo "You are the labex user."
else
	echo "You are not the labex user."
fi
```