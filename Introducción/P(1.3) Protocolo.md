![Esta es una imagen de ejemplo](https://interpolados.files.wordpress.com/2017/03/16.png)

# ¿Qué es TCP/IP?

La definición de TCP/IP es la identificación del grupo de protocolos de red que hacen posible la transferencia de datos en redes, entre equipos informáticos e internet. Las siglas TCP/IP hacen referencia a este grupo de protocolos:

> TCP es el Protocolo de Control de Transmisión que permite establecer una conexión y el intercambio de datos entre dos anfitriones. Este protocolo proporciona un transporte 
fiable de datos.

> IP o protocolo de internet, utiliza direcciones series de cuatro octetos con formato de punto decimal (como por ejemplo 75.4.160.25). Este protocolo lleva los datos a otras máquinas de la red.

El modelo TCP/IP permite un intercambio de datos fiable dentro de una red, definiendo los pasos a seguir desde que se envían los datos (en paquetes) hasta que son recibidos. Para lograrlo utiliza un sistema de capas con jerarquías (se construye una capa a continuación de la anterior) que se comunican únicamente con su capa superior (a la que envía resultados) y su capa inferior (a la que solicita servicios).

## Capas del modelo TCP/IP
Dentro del modelo TCP/IP existen cuatro niveles o capas que hay que tener en cuenta.

> **Nivel de enlace o acceso a la red** 

Es la primera capa del modelo y ofrece la posibilidad de acceso físico a la red (que bien puede ser en anillo, ethernet, etc.), especificando el modo en que los datos deben enrutarse independientemente del tipo de red utilizado.

> **Nivel de red o Internet** 

Proporciona el paquete de datos o datagramas y administra las direcciones IP. (Los datagramas son paquetes de datos que constituyen el mínimo de información en una red). Esta capa es considerada la más simportante y engloba protocolos como IP,ARP, ICMP, IGMP y RARP.

> **Nivel de Transporte** 

Permiten conocer el estado de la transmisión así como los datos de enrutamiento y utilizan los puertos para asociar un tipo de aplicación con un tipo de dato.

> **Nivel de Aplicación**

 Es la parte superior del protocolo TCP/IP y suministra las aplicaciones de red tip Telnet, FTP o SMTP, que se comunican con las capas anteriores (con protocolos TCP o UDP).

 La capas del modelo TCP/IP coinciden con algunas capas del modelo teórico OSI, aunque tienen tareas mucha más diversas.

La importancia del protocolo TCP/IP es muy elevada ya que permite que los datos enviados lleguen a su destino sin errores y bajo la misma forma en la que fueron enviados.