---
layout: post
title: Anonimato en internet
image: 
  path: \assets\img\anonimato-en-internet\Anonimato.jpg
description: >
  Entendiendo como conservar la privacidad y el anonimato en internet.
sitemap: false
---

0. this unordered seed list will be replaced by toc as unordered list
{:toc}

El anonimato en internet se refiere a la capacidad de ocultar la identidad real de un usuario al navegar por la red. Esto se puede lograr utilizando diferentes herramientas y técnicas, como el uso de pseudónimos, el uso de redes privadas virtuales (VPN) o el uso de servicios de navegación privada.{:.lead}

El anonimato en internet puede ser utilizado con diversos fines, algunos positivos como proteger la privacidad de los usuarios, permitir la libre expresión de opiniones y proteger a los usuarios de posibles amenazas o acosadores en línea. Sin embargo, también puede ser utilizado con fines negativos, como el ciberacoso, la difusión de información falsa o dañina, el hacking o la distribución ilegal de contenido protegido por derechos de autor.

Es importante destacar que el anonimato en internet no es sinónimo de impunidad. Aunque un usuario puede mantener su identidad oculta, sigue siendo responsable de las acciones que lleve a cabo en línea y puede ser rastreado y sancionado si viola las leyes o los términos de uso de una plataforma en línea.




<!-- El anonimato en internet es la capacidad de navegar en línea sin revelar tu identidad o información personal. Es importante tener en cuenta que, aunque es posible mantenerse en gran medida anónimo en línea, es casi imposible hacerlo completamente. Algunas formas de proteger tu privacidad incluyen ser cuidadoso con la información personal que compartes en línea y configurar la privacidad en tus cuentas de redes sociales.
{:.lead} -->

<!-- When making changes to `_config.yml`, it is necessary to restart the Jekyll process for changes to take effect.
{:.note} -->
<!-- 
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

Para comenzar explicaremos de forma general algunos conceptos básicos sobre redes e internet.

# Peer to Peer (P2P)

Es un tipo de red de comunicación que permite compartir información de forma descentralizada entre individuos, lo que significa que no necesitamos un servidor central, de esta forma los clientes quedan conectados directamente entre si por los diferentes nodos. Peer to peer permite a cada cliente funcionar como usuario y como servidor.

![image](https://wh04m1r00t.github.io/assets/img/anonimato-en-internet/Ambos.png "Estructuras") 

Para conectarse a esta red se utilizara algún software que realice el enlace entre los nodos de la red P2P.

Algunos ejemplos de estos tipos de red son BitTorrent, Skype, Bitcoin, incluso Spotify en sus inicios utilizaban este tipo de red por la poca inversion que se necesitaba considerando que no se realiza la compra de un servidor.

Si bien puede ser complejo imaginar la posibilidad de anonimato usando red P2P, es cierto que para cada nodo de la red que tiene una "dirección" se pueden utilizar pseudónimos para estas conexiones. Por lo que la idea de anonimato en P2P reside en que no se tiene certeza de quien en especifico requiere la información. Puede ser un nodo entre la comunicación con algún otro usuario o para si mismo, siempre considerando que el usuario funciona como emisor y receptor de datos.

**NOTE**: Es importante mencionar que cada usuario deberá voluntariamente evitar la entrada de malware a la red P2P, en consecuencia podría provocar la existencia de archivos infectados.
{:.message}

# Virtual Private Network (VPN)

Una [Virtual Private Network](2022-10-23-virtual-private-network.md){:.heading.flip-title} es una red que se utiliza como intermediario entre el usuario y el internet.

Al conectarnos a una VPN tendremos un túnel cifrado y directo con las peticiones que realicemos en internet las cuales serán a traves de la dirección IP del servidor VPN, entregando una capa extra de protección a los usuarios.

![image](https://wh04m1r00t.github.io/assets/img/vpn/VPN.png "VirtualPrivateNetwork") Arquitectura general de VPN
{:.figure}

De manera general se debe entender que al tener una VPN que cifre nuestro trafico tanto la compañía de internet que tengamos, como las redes wifi no podrán ver lo que estamos haciendo en internet. Pero si tendrá esta información la empresa que gestione la VPN.

Entre otras utilidades que tiene usar una conexión VPN es que enruta todos los servicios que tenga el usuario hacia internet, a diferencia de los [proxy](2022-10-23-proxy.md){:.heading.flip-title} que son utilizados unicamente en navegadores web. Incluyendo la evasion del geobloqueo para evitar la censura y poder acceder a contenido bloqueado o limitado en la region que nos encontremos.

Si quieres conocer a detalle como funciona una VPN reciba el siguiente post:
[Virtual Private Network](2022-10-23-virtual-private-network.md)

**NOTE**: Con respecto a las VPN gratuitas estas pueden generar un gran riesgo dado que los proveedores de estos servicios requieren de una gran inversion, por lo que deberán generar ganancias de alguna otra forma. En general pueden vender tu información, lo que provocara que tu conexión debe de ser anónima.
{:.message}

# Proxy

Un proxy funciona como un intermediario que filtra toda la informacion entre el usuario y un servidor web de destino, por lo que el servidor [Proxy](2022-10-23-proxy.md){:.heading.flip-title} es el que recibira las peticiones HTTP y es el encargado de establecer la conexion con el servidor web, de esta forma el servidor recibira la peticion del proxy.

Si el servidor proxy se encuentra en EEUU, el servidor web recibira la peticion desde esa localizacion y no desde el lugar que nos encontremos.

![image](https://wh04m1r00t.github.io/assets/img/proxy/Proxy.png "Proxy") Arquitectura general de Proxy
{:.figure}

## Tipos de Proxy

* Proxy Anónimo, utilizado para enmascarar la dirección IP, algunos casos es encriptada.
* Proxy de Alto Nivel de Anonimato, es presentado como un usuario comun, no como un servidor proxy.
* Proxy Transparente, No realiza enmascaramiento de IP, unicamente es representado como un nodo de paso.
* Proxy Inverso, el obejtivo es evitar que otros usuarios accedan a tu computador.

**NOTE**: Existen muchos Servidores proxy publicos en internet, pero siempre se debe tener en cuenta que deben ser servicios confiables y con una rapida conexion.
{:.message}


# Red TOR

Tor es una red de anonimato en línea que te permite navegar de forma anónima y privada. Funciona enrutando tu tráfico a través de varios nodos en la red, lo que hace difícil determinar tu ubicación o identidad. Cuando usas Tor, tu tráfico se encripta y se envía a través de varios nodos de la red antes de llegar a su destino final. Cada nodo desencripta solo una capa de encriptación, lo que hace que sea difícil rastrear el tráfico de vuelta a su origen.

![image](https://wh04m1r00t.github.io/assets/img/Tor/Tor.png "ToR") Arquitectura general de ToR
{:.figure}
 -->
