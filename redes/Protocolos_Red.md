# Protocolos

## Descripcion general de protocolos de red

Los protocolos de red definen un conjunto común de reglas que se pueden implementar en dispositivos de software, hardware o ambos. Cada protocolo tiene sus propios formatos, funciones y mediciones.

|Tipo de protocolo|Descripcion|
|----|-----|
|Comunicación de red|Permite que dos o más dispositivos se comuniquen a través de una o más redes.|
|Seguridad de redes|Proporciona autenticación, integridad de datos y cifrado de datos para garantizar la seguridad de la red.|
|Tabla|Permite que los routers intercambien información de ruta, comparen información y seleccionen la mejor ruta.|
|Detección de servicios|Utilizado para la detección automática de dispositivos o servicios.|

## Funciones de protocolo de red

- Los dispositivos usan protocolos acordados para comunicarse.
- Los protocolos pueden tener una o funciones.

|Funcion|Descripcion|
|---|---|
|Direccionamiento|Permite identificar y localizar dispositivos en una red mediante direcciones IP o MAC.|
|Confianza|Garantiza la integridad y autenticidad de los datos transmitidos en la red.|
|Control de flujo|Regula la velocidad de transmisión de datos para evitar la congestión de la red.|
|Secuenciacion|Ordena los paquetes de datos para que sean recibidos en el orden correcto.|
|Deteccion de errores|Detecta y corrige errores en la transmisión de datos para garantizar la integridad de la información.|
|Interfaz de la aplicacion|Proporciona una interfaz para que las aplicaciones puedan acceder a los servicios de red.|

## Interaccion de protocolos 

- las redes requieren el uso de varios protocolos.
- cada protocolo tiene su propia funcion y formato.

## Suites de protocolos

Los protocolos deben poder trabajar con otros protocolos.

Suite de protocolos:
- Un grupo de protocolos interrelacionados que son necesarios para realizar funciones de comunicacion.
- conjuntos de reglas que funcionan conjuntamente para ayudar a resolver un problema.
  
Los protocolos se ven en terminos de capas:
- caoas superiores
- capas inferiores: se preocuoan por mover datos y proporcionar servicios a las capas superiores.

## Evolución de conjuntos de protocolos

Existen varios conjuntos de protocolos utilizados en redes de comunicación. Algunos de los más conocidos son:

- **Suite de protocolos de internet o TCP/IP**: Es el conjunto de protocolos más comúnmente utilizado en Internet. Está compuesto por una serie de protocolos interrelacionados, como IP (Internet Protocol), TCP (Transmission Control Protocol) y UDP (User Datagram Protocol). Este conjunto de protocolos es mantenido por la Internet Engineering Task Force (IETF) y ha sido ampliamente adoptado en todo el mundo.

- **Protocolos de interconexión de sistemas abiertos (OSI)**: Fue desarrollado por la Organización Internacional de Normalización (ISO) y la Unión Internacional de Telecomunicaciones (UIT). El modelo OSI define una arquitectura de red en siete capas, cada una con sus propios protocolos específicos. Aunque no es tan ampliamente utilizado como TCP/IP, el modelo OSI sigue siendo una referencia importante en el diseño de redes.

- **AppleTalk**: Fue el conjunto de protocolos propietario desarrollado por Apple Inc. para sus productos. Fue ampliamente utilizado en entornos de red de Apple, pero ha sido reemplazado por TCP/IP en la mayoría de los casos.

- **Novell NetWare**: Fue un conjunto de protocolos propietario desarrollado por Novell Inc. para su sistema operativo de red NetWare. NetWare fue muy popular en la década de 1990, pero ha perdido relevancia con el tiempo debido a la adopción generalizada de TCP/IP.

## Solicitud de IP

Para solicitar una dirección IP, un dispositivo debe generar una solicitud de difusión (broadcast) para solicitar que el dispositivo que tenga el protocolo de asignación de direcciones IP le responda.

## Suite de protocolo TCP/IP

El conjunto de protocolos TCP/IP es uno de los más comúnmente utilizados en Internet. Está compuesto por cuatro capas:


|Capa de red|Protocolo|
|---|---|
|Capa de aplicación|HTTP, FTP, SMTP|
|Capa de transporte|TCP, UDP|
|Capa de red|IP, ICMP|
|Capa de enlace de datos|Ethernet, Wi-Fi|

- Capa de Aplicación: Esta capa proporciona servicios de red a las aplicaciones, como HTTP, FTP y SMTP.

- Capa de Transporte: Aquí se encuentran los protocolos TCP (Transmission Control Protocol) y UDP (User Datagram Protocol), que se encargan de la entrega confiable y no confiable de datos, respectivamente.

- Capa de Internet: Esta capa utiliza el protocolo IP (Internet Protocol) para enrutar los paquetes de datos a través de la red.

- Capa de Acceso a la Red: Aquí se encuentran los protocolos que se encargan de la transmisión física de los datos, como Ethernet y Wi-Fi.

## Estandares abiertos

Los estandares abiertos fomentan:
- Interoperabilidad
- La competencia
- Empresarial
Las organizaciones estandares son:
- Vendedor-neutral
- Organizaciones sin fines de lucro
- Establecido para desarrollar y promover el concepto de normas abiertas.

## Modelos de referencia

### Beneficio de modelo de capas

conceptos complejos, como el funcionamiento de una red, pueden ser dificiles de explicar y comprender. por esta razon se usa un modelo en capas.

Dos modelos en capas describen las operaciones de red:
- modelo de referencia de interconexiones de sistemas abiertos.
- Modelo de referencia TCP/IP

### Apstref

1. Aplicación: Capa que proporciona servicios de red a las aplicaciones, como HTTP, FTP y SMTP.
2. Presentación: Capa que se encarga de la representación y conversión de datos para que puedan ser interpretados por las aplicaciones.
3. Sesión: Capa que establece, mantiene y finaliza las conexiones entre las aplicaciones.
4. Transporte: Capa que se encarga de la entrega confiable y no confiable de datos, utilizando los protocolos TCP y UDP.
5. Red: Capa que utiliza el protocolo IP para enrutar los paquetes de datos a través de la red.
6. Enlace de datos: Capa que se encarga de la transmisión física de los datos, utilizando protocolos como Ethernet y Wi-Fi.
7. Físico: Capa que se encarga de la transmisión de bits a través del medio físico de la red.


**Los errores se manejan de abajo hacia arriba siendo primero capa fisica, a apliacion.**

## Segmentacion de mensaje

La segmentación de mensajes es un proceso que consiste en dividir un mensaje en unidades más pequeñas. Esto proporciona beneficios como el aumento de la velocidad, ya que se pueden enviar grandes cantidades de datos a través de la red sin saturar el canal de comunicación. Además, aumenta la eficiencia, ya que solo los segmentos que no llegan al destino necesitan ser retransmitidos, en lugar de tener que retransmitir todo el flujo de datos.

### Secuenciación

La secuenciación de datos es responsabilidad del protocolo TCP (Transmission Control Protocol). TCP se encarga de ordenar los segmentos de datos para que sean recibidos en el orden correcto por el destinatario.

### Encapsulamiento de datos

El encapsulamiento de datos es el proceso en el cual los protocolos agregan su información a los datos. Durante este proceso, cada protocolo agrega su propia cabecera al mensaje original, formando así una estructura en capas. Esta encapsulación permite que los datos sean transmitidos de manera eficiente y que los protocolos de red puedan interpretar y procesar la información correctamente.

### Des-encapsulamiento

El desencapsulamiento es el proceso en el cual los datos se descomponen a medida que se mueven hacia arriba en la pila de protocolos. Cada capa del modelo de referencia de protocolos elimina su encabezado correspondiente después de completar su proceso.

Este proceso de desencapsulamiento ocurre en el receptor, donde los datos recibidos se descomponen capa por capa hasta llegar a la capa de aplicación, donde los datos originales son entregados a la aplicación de destino.

El desencapsulamiento es esencial para el correcto funcionamiento de la comunicación en redes, ya que permite que los protocolos de cada capa interpreten y procesen la información adecuadamente.


