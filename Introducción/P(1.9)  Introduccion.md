### Introducción 

![Texto alternativo](https://www.ingenieros.es/files/noticias/Protocolo_ipv6.jpg)

IPv6 es el protocolo de Internet versión 6 (IP, Internet Protocol) que permite conectar diversos dispositivos a internet, identificándolos con una dirección única. Este protocolo viene a sustituir al IPv4 mucho más limitado en cuanto al número de direcciones IPs disponibles.

El protocolo IPv6 se empezó a desarrollar en el año 1998 y su lanzamiento oficial fue en junio de 2012. El principal problema a la hora de que IPv6 pueda sustituir por completo a IPv4 es la convivencia entre ambos. Muchos servidores y routers actuales no son compatibles con IPv6 lo que hace muy difícil la conexión entre dispositivos utilizando ambos protocolos. 

* ¿Qué es una dirección IPv6?

Una dirección IPv6 es una etiqueta numérica que se utiliza para identificar un ordenador o red. Estas direcciones, únicas para cada equipo, permiten encaminar paquetes de información entre los distintos hosts.

Una dirección IPv6 se representa en ocho grupos de 4 dígitos hexadecimales (cada uno de estos grupos representa 16 bits). Un ejemplo de una dirección IPv6 sería:

4021:0000:240E:0000:0000:0AC0:3428:121C

Hay algunas reglas que se aplican en esta nomenclatura de la dirección IPv6: no distinguen entre mayúsculas y minúsculas lo que disminuye los errores o los 0 a la izquierda se pueden eliminar, por ejemplo.

* Para qué sirve IPv6

Con la actualización del protocolo IPv4 al IPv6 se conseguirán una serie de mejoras que influyen en muchos aspectos como la seguridad, la sencillez a la hora de unirse a una red, etc.

Su aporte de una mayor cantidad de direcciones, hará posible que internet crezca y permitirá por ejemplo, el desarrollo del internet de las cosas.

* Características IPv6

Las principales características IPv6 son:

> Mayor número de direcciones IP: al cambiar el tamaño de 32 bits en IPv4 a 128 bits en IPv6, soporta más niveles de jerarquía de direccionamiento. Esto repercute en un aumento del número de IPs disponibles.

> Incluye mejoras en aspectos de seguridad.
No será necesario utilizar NAT debido al gran número de direcciones disponibles.

> IPv6 incluye en su estándar un “plug and play” que facilita a los usuarios la conexión a la red ya que, al conectar una máquina a la misma, se le puede asignar automáticamente una o varias direcciones IPv6.

> Paquetes IP eficientes: los paquetes contienen una cabecera más simple de una longitud fija, que acelera el procesado por parte del router.

> Header más sencillo: algunos campos del header IPv4 se han eliminado o se han hecho opcionales.

> Paquetes con carga útil de datos superiores a 62.355 bytes.
Autoconfiguración: la autoconfiguración de direcciones es más sencilla, ya que al ser de 128 bits se dividen en 64 bits superiores e inferiores, los superiores se separan desde el Router y los segundos 64 separados en dirección MAC. El largo del prefijo de la subred es 64 por lo que no es necesaria la máscara de subred. Esta autoconfiguración facilitará el uso de la red al usuario, que no deberá preocuparse por la configuración de red o la dirección IP.

> Multihoming: se puede cambiar el formato de numeración, conservando la misma dirección IP. Esto facilita el cambio entre proveedores de servicio.

>Mejora de la calidad del servicio y mejora en la capacidad de autenticación y privacidad.
