## capas de los protocolos de red

### Modelo OSI

1. Capa Física: Se encarga de las conexiones físicas de la computadora a la red, incluyendo los aspectos de hardware.
2. Capa de Enlace de Datos: Proporciona la transferencia de datos entre dos sistemas directamente conectados.
3. Capa de Red: Se encarga de la dirección IP y el enrutamiento de paquetes.
4. Capa de Transporte: Proporciona la transferencia de datos de extremo a extremo.
5. Capa de Sesión: Gestiona la conexión entre los sistemas.
6. Capa de Presentación: Se encarga de la representación de los datos, incluyendo la codificación y el cifrado.
7. Capa de Aplicación: Es la capa que interactúa con el software o aplicación.
s
### Modelo TCP/IP

1. Capa de Aplicación: Combina las funciones de las capas de Aplicación, Presentación y Sesión del modelo OSI. Incluye protocolos como HTTP, SMTP, FTP, etc.
2. Capa de Transporte: Similar a su contraparte en el modelo OSI, utiliza protocolos como TCP y UDP.
3. Capa de Internet: Equivalente a la Capa de Red en el modelo OSI, se encarga de la dirección IP y el enrutamiento de paquetes.
4. Capa de Acceso a la Red: Combina las funciones de las capas Física y de Enlace de Datos del modelo OSI. Se encarga de cómo los datos se envían y reciben en la red.


# Orden de los protocolos Modelo OSI

| Capa de Aplicación | Capa de Presentación | Capa de Sesión | Capa de Transporte | Capa de Red | Capa de Enlace de Datos | Capa Física |
| --- | --- | --- | --- | --- | --- | --- |
| HTTP | - | - | TCP | IP | Ethernet | Cobre |
| FTP | - | - | TCP | IP | Ethernet | Cobre |
| SMTP | - | - | TCP | IP | Ethernet | Cobre |
| POP3 | - | - | TCP | IP | Ethernet | Cobre |
| IMAP | - | - | TCP | IP | Ethernet | Cobre |
| SMB | - | - | TCP | IP | Ethernet | Cobre |
| FTPS | - | - | TCP | IP | Ethernet | Cobre |
| SSH | - | - | TCP | IP | Ethernet | Cobre |
| DNS | - | - | UDP | IP | Ethernet | Cobre |
| DHCP | - | - | UDP | IP | Ethernet | Cobre |
| SNMP | - | - | UDP | IP | Ethernet | Cobre |

# Orden de los protocolos Modelo TCP/IP

| Capa de Aplicación | Capa de Transporte | Capa de Internet | Capa de Acceso a la Red |
| --- | --- | --- | --- |
| HTTP | TCP | IP | Ethernet |
| FTP | TCP | IP | Ethernet |
| SMTP | TCP | IP | Ethernet |
| POP3 | TCP | IP | Ethernet |
| IMAP | TCP | IP | Ethernet |
| SMB | TCP | IP | Ethernet |
| FTPS | TCP | IP | Ethernet |
| SSH | TCP | IP | Ethernet |
| DNS | UDP | IP | Ethernet |
| DHCP | UDP | IP | Ethernet |
| SNMP | UDP | IP | Ethernet |