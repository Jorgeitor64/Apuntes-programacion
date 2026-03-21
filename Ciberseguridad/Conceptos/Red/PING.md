# PING (Packet InterNet Groper)
El **PING** es una utilidad de diagnóstico de red utilizada para verificar la conectividad entre un host local y un destino remoto (otra computadora, servidor o router). Utiliza el protocolo ICMP (Internet Control Message Protocol).
## Funcionamiento (Mecanismo de Eco)
1. **ICMP Echo Request:** El emisor envía un paquete de datos al destino.
2. **ICMP Echo Reply:** Si el destino está activo y no hay bloqueos, responde con un paquete de confirmación.
## Datos que proporciona
- **Latencia (RTT - Round Trip Time):** El tiempo que tarda el paquete en ir y volver, medido en milisegundos (ms).
- **TTL (Time To Live):** Un valor que decrece en cada "salto" (router) que atraviesa.  Permite estimar la distancia entre el dispositivo y el servidor del destino y ayuda a identificar el Sistema Operativo del destino.
- **Pérdida de paquetes:** Si los paquetes no regresan, indican fallos en el cableado o bloqueos por firewall para descongestionar la red.
