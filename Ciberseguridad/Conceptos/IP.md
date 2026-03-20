# IP (Internet Protocol)
Una **dirección IP** es un identificador numérico lógico y jerárquico asignado a cada dispositivo (host) conectado a una red que utiliza el protocolo de Internet. Su función principal es la identificación de la interfaz** y el direccionamiento de red.
## Tipos de Direccionamiento
- **IPv4 (Internet Protocol version 4):**
    
    - Formato: 32 bits, divididos en 4 octetos representados en decimal (ej. `192.168.1.1`).
        
    - Límite: Aproximadamente $2^{32}$ (4.300 millones) de direcciones.
        
- **IPv6 (Internet Protocol version 6):**
    
    - Formato: 128 bits, representados en 8 grupos de 4 dígitos hexadecimales (ej. `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
        
    - Límite: Aproximadamente $2^{128}$ direcciones (prácticamente infinitas).
## Clasificación
- **IP Pública** Visible desde todo Internet. Es asignada por el ISP (Proveedor de Internet).
- **IP Privada** No es enrutable. Utilizadas dentro de redes locales (LAN) con rangos limitados `172.16.x.x - 172.31.x.x`, `192.168.x.x`
## Asignación y Persistencia
- **Estática:** La dirección no cambia. Se usa comúnmente en servidores, firewalls o dispositivos críticos.
- **Dinámica:** Asignada temporalmente mediante el protocolo **DHCP**. Cambia cada vez que el dispositivo se conecta o expira su "concesión".