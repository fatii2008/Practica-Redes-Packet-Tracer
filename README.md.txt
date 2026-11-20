Práctica de Redes: Diseño y configuración de una red corporativa con Cisco Packet Tracer

1. Introducción
En esta práctica hemos diseñado y configurado una red corporativa utilizando Cisco Packet Tracer.
La red está formada por cinco redes principales conectadas mediante routers. Hemos configurado subredes, direcciones IP, DHCP, Wi-Fi, servidores DNS y servidores web.
También hemos realizado pruebas para comprobar que la red funciona correctamente.
2. Diseño de la red
La infraestructura está formada por cinco redes principales, cada una con sus propios dispositivos y configuración.
* Red 1: dividida en tres subredes mediante VLSM.
* Red 2: formada por 8 ordenadores que reciben su dirección IP mediante DHCP.
* Red 3: formada por 4 ordenadores que reciben su dirección IP mediante DHCP.
* Red 4: formada por 4 ordenadores conectados por cable y 5 portátiles conectados mediante Wi-Fi.
* Red 5: formada por 5 ordenadores con direcciones IP configuradas manualmente.
Todas las redes están conectadas mediante routers.
3. Configuración de la Red 1 (VLSM)
La primera red se ha dividido en tres subredes utilizando VLSM, según el número de equipos que puede admitir cada una.
* Subred A: capacidad para 100 dispositivos.
* Subred B: capacidad para 30 dispositivos.
* Subred C: capacidad para 6 dispositivos.
Cada subred tiene sus propias direcciones IP y está aislada de las demás. Se han configurado restricciones para impedir la comunicación entre ellas y con las otras cuatro redes principales.
4. Configuración de la Red 2
La segunda red está formada por 8 ordenadores conectados a un switch y a un router.
Se ha configurado un servidor DHCP para asignar automáticamente las direcciones IP a los ordenadores, sin tener que introducirlas manualmente.
5. Configuración de la Red 3
La tercera red está formada por 4 ordenadores conectados a un switch y a un router.
Se ha configurado DHCP para asignar automáticamente las direcciones IP a los ordenadores. Esta red utiliza un rango de direcciones diferente al de la Red 2.
6. Configuración de la Red 4
La cuarta red está formada por 4 ordenadores conectados por cable y 5 portátiles conectados mediante Wi-Fi.
Los dispositivos están conectados a la misma red. Los portátiles reciben sus direcciones IP automáticamente mediante DHCP.
También se ha configurado la seguridad Wi-Fi utilizando WPA2-PSK.
7. Configuración de la Red 5
La quinta red está formada por 5 ordenadores conectados a un switch y a un router.
En esta red, las direcciones IP se han configurado manualmente (IP estática), por lo que cada ordenador tiene una dirección IP propia.
8. Conexión entre routers
Las cinco redes principales están conectadas mediante routers para permitir la comunicación entre ellas cuando está permitida.
Se ha configurado el enrutamiento para que los routers conozcan las diferentes redes. También se han utilizado listas de control de acceso (ACL) para controlar el tráfico y bloquear las comunicaciones que no están permitidas.
9. Configuración de los servidores
Se han configurado tres servidores web para crear las siguientes páginas:
* www.albacete.es: 
* www.wagner.de: 
* www.dilar.com 
También se ha configurado un servidor DNS para relacionar cada nombre de dominio con su dirección IP:
* www.albacete.es ? 192.168.50.10
* www.wagner.de ? 192.168.50.11
* www.dilar.com ? 192.168.50.12

Se han realizado pruebas de acceso a las tres páginas web y se ha comprobado que funcionan correctamente.
10. Pruebas de funcionamiento
Para comprobar que la red funciona correctamente, se han realizado las siguientes pruebas:
* Conectividad: se han realizado pruebas con el comando ping.
* DHCP: se ha comprobado que los ordenadores reciben automáticamente una dirección IP.
* Wi-Fi: se ha comprobado la conexión inalámbrica de los portátiles.
* DNS: se ha comprobado que los nombres de dominio se traducen a sus direcciones IP.
* Servidores web: se ha comprobado el acceso a las páginas de Albacete, Wagner y Dílar.
Las pruebas realizadas han permitido comprobar el funcionamiento de los servicios configurados.
A continuación se mostrara algunas comprobaciones:
Comprobación de que el ordenador puede comunicarse con su router(en este caso el de la Red 2)

Comprobación de que el ordenador puede acceder a un servidor web

Comprobación DNS



Comprobación de que un laptop esta conectado al router

Comprobación para demostrar que la seguridad de la red está bien configurada

11. Conclusión
Con esta práctica hemos diseñado y configurado una red corporativa utilizando Cisco Packet Tracer.
Hemos creado cinco redes, configurado routers, switches, direcciones IP, DHCP, Wi-Fi, servidores web y DNS.
También hemos realizado pruebas para comprobar que las redes funcionan correctamente y que las restricciones de comunicación se cumplen.
Finalmente, hemos conseguido que los usuarios puedan acceder a las páginas web mediante sus nombres de dominio.


