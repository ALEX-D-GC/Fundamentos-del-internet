### Formatos de dirección de IPv6

![Texto alternativo](https://docs.oracle.com/cd/E19957-01/820-2981/images/basic-IPv6-address.gif)


El tamaño y el formato de la dirección IPv6 amplían la capacidad del espacio para direcciones.

El tamaño de las direcciones de IPv6 es de 128 bits. La representación preferente de direcciones de IPv6 es x:x:x:x:x:x:x:x, donde cada x es el valor hexadecimal de las 8 partes de 16 bits de la dirección. 
> Las direcciones IPv6 abarcan desde 0000:0000:0000:0000:0000:0000:0000:0000 a ffff:ffff:ffff:ffff:ffff:ffff:ffff:ffff.

Además de en este formato preferente, las direcciones IPv6 pueden especificarse en otros dos formatos abreviados:
Omitir ceros iniciales
Especifique las direcciones IPv6 omitiendo los ceros iniciales.
> Por ejemplo, la dirección IPv6 1050:0000:0000:0000:0005:0600:300c:326b puede escribirse como 1050:0:0:0:5:600:300c:326b.

Dos signos de dos puntos
Especifique las direcciones IPv6 con dos signos de dos puntos (::) en lugar de una serie de ceros.

> Por ejemplo, la dirección IPv6 ff06:0:0:0:0:0:0:c3 puede escribirse como ff06::c3.

 Los dos signos de dos puntos sólo pueden utilizarse una vez en una dirección IP.
Un formato alternativo para las direcciones IPv6 combina la notación de dos puntos y un punto, de forma que la dirección IPv4 puede incrustarse en la dirección IPv6. Se especifican valores hexadecimales para los 96 bits de más a la izquierda, y valores decimales para los 32 bits de más a la derecha que indican la dirección IPv4 incrustada. Este formato garantiza la compatibilidad entre los nodos IPv6 y los nodos IPv4 cuando se está trabajando en un entorno de red mixto.

La dirección IPv6 correlacionada con IPv4 utiliza este formato alternativo. Este tipo de dirección se utiliza para representar los nodos IPv4 como direcciones IPv6. Permite que las aplicaciones de IPv6 se comuniquen directamente con las aplicaciones de IPv4. 
>Por ejemplo, 0:0:0:0:0:ffff:192.1.56.10 y ::ffff:192.1.56.10/96 (formato abreviado).

Todos estos formatos son formatos de dirección IPv6 válidos. Puede especificar estos formatos de dirección IPv6 en System i Navigator, excepto la dirección IPv6 correlacionada con IPv4.

