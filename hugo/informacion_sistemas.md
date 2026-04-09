## 🛠️ Herramientas Principales

### 📊 1. Prometheus + Grafana
*El combo perfecto para la observabilidad moderna.*
*   **Definición:** Prometheus recolecta métricas (hace *scraping*) y Grafana las convierte en dashboards visuales.
*   **Uso en ASIR:** Ideal para monitorizar **contenedores Docker** y servicios web. Es lo que usamos cuando queremos gráficas de consumo de CPU/RAM que se actualicen solas.

### 🛡️ 2. Zabbix
*El "perro guardián" de la infraestructura empresarial.*
*   **Definición:** Sistema de monitorización integral basado en **agentes** y protocolo **SNMP**.
*   **Uso en ASIR:** Para controlar redes enteras. Si un switch se calienta o un servidor se queda sin espacio en disco, Zabbix te lanza un *trigger* (alerta) antes de que todo caiga.

### ⚡ 3. Netdata
*Monitorización en tiempo real a bajo nivel.*
*   **Definición:** Monitoriza el sistema segundo a segundo con un impacto mínimo en los recursos.
*   **Uso en ASIR:** Es nuestra herramienta de **troubleshooting**. Si el servidor va lento, abres Netdata y ves en el acto si es un proceso bloqueado o un cuello de botella en el disco.

### 📜 4. Nagios Core
*El estándar de la vieja escuela.*
*   **Definición:** Basado en estados (OK, Warning, Critical). Si algo falla, Nagios lo sabe.
*   **Uso en ASIR:** Perfecto para aprender a manejar **scripts y plugins**. Se usa para chequear si servicios como SSH, Apache o bases de datos están levantados.
