# Dirección MAC (Media Access Control)
La **dirección MAC** es un identificador único de 48 bits asignado por el fabricante a una tarjeta de red (Network Interface Controller/NIC). Se considera el identificador físico de un dispositivo pues no puede ser alterado.
## Formato y Estructura
Se representa en formato hexadecimal, dividido es seis grupos de dos dígitos (ej. `00:1A:2B:3C:4D:5E`)
1. **OUI (Organizationally Unique Identifier):** Los primeros 6 dígitos. Identifican al fabricante del dispositivo.
2. **NIC Specific:** Los últimos 6 dígitos. Es el identificador único asignado a cada tarjeta por el fabricante.
## Obtención en consola
- En Windows: `getmac` o `ipconfig /all`
- En Linux/macOS: `ip link show` o `ifconfig`
## Ciberseguridad
La dirección MAC puede ser enmascarada para engañar a un firewall mediante el método 