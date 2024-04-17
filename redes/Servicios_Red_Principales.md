# TCP/IP y los servicios de red



## Los servicios de red principales

Son servicios que se encargan de la comunicacion entre los dispositivos de una red.

### HTTP (Hypertext Transfer Protocol)

Es un protocolo de transferencia de hipertexto de capa de aplicacion, que se utiliza en la World Wide Web (WWW) para la transferencia de archivos, como podrian ser HTML.

### DNS (Domain Name System)

El DNS es un sistema de nomenclatura jerarquico descentralizado para dispositivos conectados a redes IP (Internet). Su funcion principal es traducir nombres de dominio a direcciones IP.

*El nombre de dominio funciona como un link a la dirección IP.*

### Servicio de correo

El servicio de correo en una red se encarga de la transmisión de mensajes de correo electrónico. Los protocolos más comunes para este servicio son SMTP para el envío de correos y POP3 o IMAP para la recepción.

#### SMTP (Simple Mail Transfer Protocol)

SMTP es el protocolo estándar para el envío de correos electrónicos a través de Internet. Los clientes de correo electrónico utilizan SMTP para enviar correos electrónicos a los servidores de correo.

## Otros servicios de red importantes

### FTP (File Transfer Protocol)

FTP es un protocolo de red estándar utilizado para la transferencia de archivos entre un servidor y un cliente en una red TCP/IP. FTP utiliza una arquitectura cliente-servidor y conexiones de control y de datos separadas.


### DHCP (Dynamic Host Configuration Protocol)

DHCP es un protocolo que permite a los servidores asignar automáticamente una dirección IP a los dispositivos en una red. El DHCP es importante porque reduce el trabajo manual y el potencial de errores en la configuración de dispositivos en una red.

# Conceptos adicionales de redes

## Capas en los servicios de red

Los servicios de red operan en diferentes capas del modelo OSI. Por ejemplo:

- HTTP y SMTP son protocolos de la capa de aplicación. Esta capa se encarga de la interacción con el software del usuario final.
- DNS opera en la capa de aplicación pero también interactúa con la capa de transporte para enviar y recibir datos.
- FTP utiliza tanto la capa de aplicación (para los comandos de control) como la capa de transporte (para la transferencia de datos).
- DHCP opera en la capa de aplicación pero también interactúa con las capas inferiores para asignar direcciones IP.
- SMB opera en la capa de aplicacion y interactua con la capa de transporte para la transferencia de archivos.

## Puertos en los servicios de red

Los puertos son utilizados por los protocolos de la capa de transporte (TCP y UDP) para identificar procesos específicos en un dispositivo. Algunos servicios de red tienen puertos estándar asignados. Por ejemplo:

- HTTP utiliza el puerto 80 para las conexiones no seguras y el puerto 443 para las conexiones seguras (HTTPS).
- DNS utiliza el puerto 53.
- SMTP utiliza el puerto 25.
- FTP utiliza los puertos 20 y 21.
- DHCP utiliza los puertos 67 y 68.
- SMB utiliza el puerto 445.

## Protocolos de red y sus falencias

Cada protocolo de red tiene sus propias fortalezas y debilidades. Por ejemplo, HTTP es fácil de usar pero no es seguro por defecto. DNS es esencial para la navegación en la web, pero puede ser explotado para redirigir a los usuarios a sitios maliciosos. SMTP es eficiente para el envío de correos electrónicos, pero no tiene mecanismos de seguridad robustos incorporados. FTP es útil para la transferencia de archivos, pero transmite los datos en texto plano, lo que puede ser un problema de seguridad. DHCP es conveniente para la configuración de la red, pero puede ser explotado para asignar direcciones IP maliciosas.