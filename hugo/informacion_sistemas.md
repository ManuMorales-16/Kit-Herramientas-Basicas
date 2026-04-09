1. Prometheus + Grafana (Métricas y Dashboards)

    ¿Qué es?: Prometheus se encarga de ir pidiendo datos (hace pull) a los servicios, y Grafana los pinta en paneles que quedan de locos.

    Para qué lo usamos: Es el estándar si trabajas con Docker. Sirve para ver el consumo de recursos de los contenedores y crear alertas si un nodo deja de responder.

2. Zabbix (El todoterreno de la red)

    ¿Qué es?: Un sistema centralizado que monitoriza de todo: servidores, switches, routers... hasta impresoras.

    Para qué lo usamos: Para gestionar toda la infraestructura desde un solo sitio. Usamos el agente de Zabbix para servidores y el protocolo SNMP para los dispositivos de red que no permiten instalar software.

3. Netdata (Para ver el "lag" del sistema)

    ¿Qué es?: Una herramienta de monitorización por segundo. Es como el administrador de tareas de Windows, pero a lo bestia y vía web.

    Para qué lo usamos: Para hacer troubleshooting (localizar fallos) rápido. Si el servidor de bases de datos va a pedales, entras aquí y ves al instante si es culpa del disco, de la CPU o de un proceso que se ha quedado colgado.

4. Nagios (El clásico de los estados)

    ¿Qué es?: La vieja escuela. Se basa en comprobar estados: si algo está UP (vivo) o DOWN (muerto).

    Para qué lo usamos: Para aprender a configurar plugins y scripts. No es el más bonito, pero es superfiable para saber si los servicios esenciales (Apache, SSH, DNS) están funcionando o si han petado.

5. Glances (El 'htop' con esteroides)

    ¿Qué es?: Una herramienta para la terminal que te da un resumen de todo el hardware.

    Para qué lo usamos: Cuando te conectas por SSH a una máquina y quieres ver en 5 segundos cómo está de carga, qué procesos están arriba y cuánta red está consumiendo sin configurar nada raro.
