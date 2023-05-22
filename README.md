# EFSI 2
## Clasroom 5° a:
En proceso :construction_worker:
## Clasroom 5° b:
En proceso :construction_worker:

___
# TP1

(Template)

 ## Consigna:
 * El trabajo es por grupos de proyecto
 * Tienen que trabajar todos utilizando la metodologia del workflow de github
 * Organizar que parte del glosario/tabla hace cada uno por medio de la seccion de Issues
 * Cada alumno:
    * trabaja en su propia Branch
    * tiene que resolver por lo menos 1 issue del profesor
    * tiene que efectuar un pull request y resolver conflictos


# Tabla "Guia" =\> "Cheat-Sheet":

<table class="tg">
<thead>
  <tr>
    <th class="tg-9wq8" colspan="6">MODELO DE CAPAS (Layers)</th>
    <th class="tg-9wq8" rowspan="2">Protocolos de red </th>
    <th class="tg-9wq8" rowspan="2">Dispositivo de conexion de red</th>
  </tr>
  <tr>
    <th class="tg-9wq8">"Tipos" de Capas</th>
    <th class="tg-9wq8" colspan="2"> MODELO OSI</th>
    <th class="tg-9wq8" colspan="2">MODELO TCP/IP </th>
    <th class="tg-9wq8">Unidad de datos de protocolo (PDU)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas del anfitrion/host "Software"</td>
    <td class="tg-9wq8">7</td>
    <td class="tg-9wq8">Aplication</td>
    <td class="tg-9wq8" rowspan="3">4</td>
    <td class="tg-9wq8" rowspan="3">Process</td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="4"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">6</td>
    <td class="tg-9wq8">Presentation</td>
  </tr>
  <tr>
    <td class="tg-9wq8">5</td>
    <td class="tg-9wq8">Session</td>
  </tr>
  <tr>
    <td class="tg-9wq8">4</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas de red  "Firmware" "Hardware"</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Network</td>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Network / Internet</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Data link</td>
    <td class="tg-9wq8" rowspan="3">1</td>
    <td class="tg-9wq8" rowspan="3">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">1</td>
    <td class="tg-9wq8">Physical</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">0*</td>
    <td class="tg-9wq8">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
</tbody>
</table>

*La capa de Medio (Media) no forma parte oficial del Modelo OSI, pero esquematicamente la estudiamos ahi

# Glosario

## Contenido del Glosario:
* Definicion y/o explicacion
* En que capa TCP/IP \<=\> OSI trabajan
### Definiciones Generales
  * Server: El server es un aparato informático que almacena, suministra y distribuye la información. Este, basado en un software brinda un servicio a distintos usuarios o programas informáticos, los cuales pueden utilizarlos a nivel local o de red. El mismo opera en la capa de presentación del modelo OSI.
  * Host: Es una tecnología que ofrece distintos servicios a todos los demás equipos conectados a la red por medio de un equipo que funciona como su “huésped”. En el modelo OSI trabaja en la capa 5 mientras que en el modelo TCP/IP trabaja en la capa 4.
  * Telefono IP: Este es un aparato telefónico especial que facilita hacer llamadas por teléfono a través del Internet.Gracias a que este utiliza el Protocolo de Internet. Lo único que se necesita es una conexión a la red y al conectar el teléfono a un enrutador, estarás conectado y podrás realizar llamadas y recibirlas. Este trabaja en la capa de aplicación.
### Elementos de una red
#### y en que capa de los modelos TCP/IP \<=\> OSI trabajan ==>> se completa en la tabla
  *  Router: Es el responsable de interconectar los equipos o clientes de una red interna a una red de datos. Funciona como un dispositivo de unión entre dos o más redes. Se encuentra en la capa 3 del modelo OSI, es decir, la capa de red. En TCP/IP también se encuentra en la capa 3, conocida como la capa de transporte.
  *  Switch: El switch o conmutador es el dispositivo digital lógico de interconexión de equipos que opera en la capa de enlace de datos del modelo OSI. El mismo busca conectar equipos en red formando lo que se conoce como una red de área local (LAN) y cuyas especificaciones técnicas siguen el estándar conocido como Ethernet.
   *  Switch Capa 2 (=): Funciona en la capa de enlace de datos y utiliza direcciones de control de acceso a medios del dispositivo de red para determinar dónde reenviar las tramas.
   *  Switch Capa 3:Este es un switch y un router al mismo tiempo, puede considerarse un router con múltiples puertos Ethernet y con función de conmutación. El Switch capa 3 permite la conmutación de paquetes inspeccionando sus direcciones IP y sus direcciones MAC. El mismo opera en la capa dos del modelo OSI, (data link).
  *  Hub: Es un dispositivo de red que conecta diferentes nodos. En el modelo de referencia OSI, los hubs se clasifican como elementos de la capa 1 que operan en la capa física. Su principal cometido es conectar varios ordenadores entre sí y reenviar inmediatamente los datos recibidos. 
  *  Wireless Access-point: Se trata de un dispositivo de red que en una red de computadoras, su función es interconectar equipos de comunicación inalámbricos, formando una red inalámbrica que conecta dispositivos móviles o tarjetas de red. Este se encuentra en la capa de transporte (4) del modelo OSI.
  *  Wireless Router: Los routers inalámbricos son dispositivos de hardware que los proveedores de servicios de Internet utilizan para conectarse a la red de Internet por cable o xDSL que ofrecen. Un router o enrutador trabaja en la capa 3 del modelo OSI, es decir, la capa de red, la cual se encarga de la identificación del enrutamiento de paquete y por tanto unión entre dos o más redes.
  *  WAN: Se trata de una red de computadoras que interconecta varias redes de ámbito geográfico menor, por ejemplo redes de área local, aunque sus miembros no estén todos en una misma ubicación física.Las WAN se utilizan para conectar redes LAN y otros tipos de redes. Así los usuarios se pueden comunicar con los usuarios y equipos de otros lugares. Opera en la capa 1 y en la 2 del modelo OSI.
  *  LAN: LAN o Local Area Network (Red de Área Local), consiste en cierta red de comunicación entre ordenadores situados uno cercano al otro , de forma que permite a sus usuarios el intercambio de datos y la compartición de recursos. Esta se encuentra en la capa 3, denominada también capa de red.
  *  VLAN: VLAN es una colección de computadoras en una o varias LAN que se agrupan en un solo dominio de difusión. Esto permite agrupar dispositivos de acuerdo con patrones de tráfico en lugar de proximidad física. Esta tecnología trabaja en la capa 2 del modelo OSI y es capaz de aislar el tráfico, para que de esta manera la eficiencia de la red entera se incremente.
  *  WLAN: Es una red inalámbrica de comunicación que funciona mediante ondas de radio o infrarrojas para distancias cortas. Esto minimiza las conexiones cableadas por lo que le facilita la movilidad al usuario. Además se encuentra en la capa 3 del modelo OSI.
  *  Media (Medio de Transporte): Esta  permite transportar información de uno o varios usuarios desde un punto a otro u otros puntos de forma bidireccional o unidireccional. Transfiriendo diversas clases de información de control de red, tales como la señalización e información de operaciones y mantenimiento. Esta se encuentra en la capa media del modelo TCP/IP, dentro de las capas de red.
* ### Protocolos
  *  VOIP: Se trata de una tecnología con la cual se puede hacer llamadas de voz a través de la red. Para que esto se logre, se toma el audio que es captado por el micrófono y se convierte en datos digitales, que se transmiten por la red a otro dispositivo donde se interpretan para que se escuche de nuevo la voz. Se encuentra en la capa 4 del modelo OSI.
  *  DNS: Este es un servicio distribuido globalmente que convierte los nombres legibles de las personas en direcciones IP numéricas,  que utilizan los equipos para conectarse entre sí. El sistema DNS de Internet funciona como una agenda telefónica donde se administra el mapeo entre los nombres y los números. Los servidores DNS convierten las solicitudes de nombres en direcciones IP, con lo que se controla a qué servidor se dirigirá un usuario final cuando escriba un nombre de dominio en su navegador web. Estas solicitudes se denominan consultas. Este trabaja en la capa OSI de aplicación.
  *  FTP: El FTP o Protocolo de transferencia de archivos es un protocolo de red para la transferencia de archivos entre sistemas conectados a una red TCP, el mismo basado en la arquitectura cliente-servidor.Como su nombre indica, se trata de un protocolo que permite transferir archivos directamente de un dispositivo a otro. Trabaja en la capa FTP (TCP/IP) o como lo denominariamos en su equivalente de capa OSI, en la de aplicación, sesión y presentación.
  *  SSH: SSH o en inglés Secure Shell. Comprende a un  protocolo que tiene como función ofrecer acceso remoto a un servidor. Este cuenta con  acceso  seguro, ya que toda la información va cifrada. Lo que evita filtraciones.Siendo uno de los protocolos que tenemos para conectarnos de forma remota a un servidor más eficaz.El mismo reside en la capa 7 (Aplicación) del Modelo OSI.
  *  SMTP: Es un protocolo TCP/IP que utiliza los servidores de correo electrónico para enviar y recibir e-mails. Se encuentra en la capa de aplicación del modelo OSI, es decir, en la séptima.
  *  POP: Post Office Protocol (Protocolo de Oficina Postal), es un protocolo que nos permite sincronizar el correo electrónico de Gmail con cualquier cliente de correo compatible.Este protocolo está pensado para recuperar mensajes de correo accediendo al servidor en forma dinámica desde una workstation.El mismo trabaja en la capa de aplicación que utiliza TCP como protocolo de capa de enlace.
  *  SNMP: Este consiste en un protocolo de nivel de aplicación diseñado para supervisar la infraestructura de red y proporcionar a los administradores visibilidad centrada en el dispositivo. El mismo opera en la capa de aplicación del conjunto de protocolos de Internet (capa 7 del modelo OSI).
  *  DHCP:  Hace referencia a un modelo que permite la configuración fluida de las interfaces de red y que resulta de gran utilidad cuando se manejan grandes redes o gran cantidad de usuarios móviles. A su vez, asigna direcciones IP dinámicas y de forma automática. Esto sumado a que también permite la administración de red reducida a través de herramientas como la configuración TCP/IP de manera centralizada y automatizada, así como su definición desde una ubicación central.Se encuentra en la capa 7 del modelo OSI.
  *  HTTP/S: HTTP/S es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML.Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor. Este trabaja en la capa de aplicación (capa 7 del modelo OSI).
  *  TCP / UDP: Se trata de dos protocolos básicos de nivel de transporte para realizar conexiones entre sistemas principales de Internet, ya que estos dos protocolos se sitúan en la capa de transporte del modelo TCP/IP, y es la primera capa donde origen y destino se comunican directamente.
  *  IPv4: Es el formato de dirección estándar que permite que todas las máquinas en Internet se comuniquen entre sí. Consiste en un protocolo de Internet utilizado actualmente para las direcciones IP de los dominios. Estas direcciones IP se asignan automáticamente cuando se registra un dominio. Este protocolo funciona en la capa de red del modelo OSI y en la capa de Internet del modelo TCP/IP.
  *  IPv6: Es la sexta versión del Protocolo de Internet que conecta dispositivos en Internet, identificándolos con una dirección única. Esta surge a través del agotamiento del espacio de direcciones disponibles en IPv4. Funciona en la capa 3 del modelo OSI.
  *  ARP: Es el encargado de establecer una correspondencia entre la dirección IP y la dirección MAC, el cual transmite datos específicos mediante un paquete. A su vez, lleva a cabo un proceso de mapeo, funcionando como traductor para que dos sistemas con longitudes diferentes como la dirección IP y la dirección MAC puedan reconocerse entre sí. Se encuentra en la segunda capa del modelo OSI.
  *  MAC: Se trata de un identificador único que cada fabricante le asigna a la tarjeta de red de sus dispositivos conectados. Está formada por 48 bits representados generalmente por dígitos hexadecimales. Como son identificadores únicos, las MAC pueden ser utilizadas por un administrador de red para permitir o denegar el acceso de determinados dispositivos a una red. Se encuentra en la capa dos del modelo OSI.
  *  IEEE 802.11 (WIFI): Hace referencia al conjunto de estándares que definen la comunicación para LAN inalámbricas (redes de área local inalámbricas o WLAN). La tecnología detrás de 802.11 está marcada para los consumidores como Wi-Fi. Se encuentra en la capa 1 del modelo OSI.
  *  IEEE 802.3 (ETHERNET): Es una tecnología para redes de datos por cable que vincula software y hardware entre sí. Así, distintos dispositivos conectados en una red local, establecen conexiones mediante el protocolo Ethernet y pueden intercambiar paquetes de datos entre sí. Se encuentra en la capa 3 del modelo OSI y en la 4 del modelo TCP/IP.
  *  Fibra OPTICA: Se trata de un medio de transmisión de datos mediante impulsos fotoeléctricos a través de un hilo construido en vidrio transparente u otros materiales plásticos con la misma funcionalidad. Se encuentra en la capa 1 del modelo OSI.
  *  "Firewall": Se trata de un dispositivo de seguridad de la red que monitorea el tráfico de red que entra y sale y a partir de reglas de seguridad decide si permite o bloquea tráfico. Se encuentra en la capa 3 del modelo OSI.
   

* ###   Unidad de Datos de protocolo (PDU)(Encapsulamiento)
  * Datos: Son representaciones simbólicas de un determinado atributo o variable.Los mismos residen en las capas 4,5,6 y 7 (Transporte, Sesión, Presentación y Aplicación), aquí se manejan, transportan y comparten recursos, entre otras acciones.
  * Segmento: Se conoce como segmento a  la parte de una rutina de un ordenador digital lo bastante corta como para ser completamente almacenada en la memoria interna. Este se asocia con la capa Transporte (Host layers), en donde se genera la transmisión de segmentos de datos entre puntos de red, incluyendo la segmentación.
  * Paquete: El paquete es la unidad de información básica que se transfiere a través de una red. Este mismo reside también en la capa de red (Media) aquí es en donde se dividen los segmentos de la capa de transporte en unidades más pequeñas, llamadas paquetes; en el dispositivo del emisor, y vuelve a juntar estos paquetes en el dispositivo del receptor.
  * Trama: Una trama es una unidad de envío de datos. Es una serie sucesiva de bits, organizados de una forma determinada, que transportan información. Esta reside en la capa Media Layers, en la parte de enlace de datos; transmitiendo los datos confiables entre dos nodos conectados mediante una capa física.
  * Bits: Es la unidad de información más pequeña y puede contener una unidad de información, pero no constituye un conjunto de datos. El mismo reside en la capa física (OSI) codificando los datos de la trama de enlace de datos en un patrón de unos y ceros (bits) para su transmisión a través del medio.
  * Señal (dbm): Es una unidad relativa que se utiliza para representar la potencia y la fuerza del voltaje de diferentes dispositivos y equipos electrónicos. Estas son muy importantes porque también se encargan de medir la señal. La misma reside en la capa 0 (capa física - medio) funcionando como un medio físico de transmisión

* ###   Medios
  * #### Conectores
    * (con foto) Conector RJ45 Hembra (Jack RJ45): Los conectores RJ45 son los más utilizados para conectar un dispositivo con acceso a Internet con otro dispositivo de red.La conexión por cable que proporcionan estos conectores permite una mayor velocidad de datos, una mayor estabilidad y una mayor seguridad. Haciendo que estas conexiones sean atractivas tanto para el uso profesional como para el personal.
    * (con foto) Conector RJ45 Macho (ficha RJ45): El RJ45 es un conector que se utilizada para redes de cableado estructurado. Contando con hasta 8 pines de conexión, resulta válido tanto para cables de datos (8 hilos), como para cables telefónicos (2 hilos).
    * (con foto) Norma T568A y T568B (ficha RJ45 y JackRJ45): Ambos, el T568A y el T568B se utilizan para normalizar la disposición de cables, estos proporcionan esquemas de cableado para la terminación de los cables de red en enchufes, así como enchufes RJ45 de ocho posiciones.
    * Cable Cruzado vs Cable Derecho: El cable cruzado se usa para conectar dos dispositivos del mismo tipo, mientras que el cable directo conecta dos dispositivos diferentes entre sí, como por ejemplo un PC a un switch.
  * #### CABLE UTP (CAT5 CAT5e y CAT6)
    * Colores de los pares del cable UTP:
    * Diferencias Constructivas:
    * Velocidades Maximas:
    * Distancias Maximas:
  * #### IEEE 802.3 (ETHERNET)
    * 10BASE-T (802.3i):
        1. cantidad de pares en uso
        2. Velocidad Maxima
        3. Tipo de cable
    * 100BASE-TX (802.3u)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * 1000BASE-T (802.3ab)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * Full Duplex (802.3x)
    * Auto-negociación
      * velocidad
      * Full Duplex vs Half Duplex\
    * POE (802.3af)
