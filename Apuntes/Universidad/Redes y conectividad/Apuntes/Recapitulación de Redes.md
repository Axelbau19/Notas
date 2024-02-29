Metodologia 
#Analisis
El proceso destinado a recabar información ayuda a aclarar e identificar cualquier problema de red actual. Esta información incluye el historial de la organización y su estado actual, el crecimiento proyectado, las políticas operativas y los procedimientos de administración, los sistemas y procedimientos de oficina y los puntos de vista de las personas que utilizarán las LAN.

Deberán formularse las siguientes preguntas al reunir la información:

- ¿Quiénes son las personas que utilizarán la red?
- ¿Cuáles son sus actitudes con respecto a las computadoras y las aplicaciones informáticas?
- ¿Cuál es el nivel de desarrollo de las políticas documentadas organizacionales?
- ¿Sólo se soportan determinados hosts de escritorio?
- ¿Quién es responsable de las direcciones, la denominación, el diseño de topología y la configuración de las LAN?
- ¿Cómo se vinculan y comparten estos recursos actualmente?
La documentación de los requisitos permite una estimación informada de los costos y líneas temporales para la implementación de diseño de LAN. (Instituto Consorcio Clavijero,2024)


#Diseño
Sistema Cableado Estructurado:es la infraestructura de cable destinada a transportar, a lo largo y ancho de un edificio, las señales que emite un emisor de algún tipo de señal hasta el correspondiente receptor. Un sistema de cableado estructurado es físicamente una red de cable única y completa, con combinaciones de alambre de cobre (**pares trenzados sin blindar UTP**), cables de fibra óptica, bloques de conexión, cables terminados en diferentes tipos de conectores y adaptadores. Uno de los beneficios del cableado estructurado es que permite la administración sencilla y sistemática de las mudanzas y cambios de ubicación de personas y equipos. El sistema de cableado de telecomunicaciones para edificios soporta una amplia gama de productos de telecomunicaciones sin necesidad de ser modificado. UTILIZANDO este concepto, resulta posible diseñar el cableado de un edificio con un conocimiento muy escaso de los productos de telecomunicaciones que luego se utilizarán sobre él. La norma garantiza que los sistemas que se ejecuten de acuerdo a ella soportarán todas las aplicaciones de telecomunicaciones presentes y futuras por un lapso de al menos diez años. Esta afirmación puede parecer excesiva, pero no, si se tiene en cuenta que entre los autores de la norma están precisamente los fabricantes de estas aplicaciones.(RackOnline,2024)

El diseño de topología LAN se puede dividir en las tres siguientes categorías únicas del modelo de referencia OSI: Capa de red. Capa de enlace de datos. Capa física. El paso final en la metodología de diseño LAN es documentar la topología física y lógica de la red. La topología física de la red se refiere a la forma en que distintos componentes de LAN se conectan entre sí. El diseño lógico de la red se refiere al flujo de datos que hay dentro de una red. También se refiere a los esquemas de nombre y dirección que se utilizan en la implementación de la solución de diseño LAN.

Tipos de Topologia:

- Topologia en Estrella
	Es el tipo de configuración más común. La red está organizada de modo que los nodos estén conectados a un dispositivo central (un hub), que actúa como servidor. El hub gestiona la transmisión de datos a través de la red. Es decir, cualquier dato enviado a través de la red viaja a través del dispositivo central antes de terminar en su destino
- Topologia en bus
	También llamada topología de red troncal, bus o línea, guía los dispositivos a lo largo de un solo cable que se extiende desde un extremo de la red hasta el otro. Los datos fluirán a lo largo del cable a medida que viaja a su destino.
- Topologia en Anillo
	Los nodos se configuran en un patrón circular. Los datos viajan a través de cada dispositivo a medida que viajan a través del anillo. En una red grande, es posible que se necesiten repetidores para evitar la pérdida de paquetes durante la transmisión. Las topologías de anillo se pueden configurar como anillo único (half-dúplex) o anillo doble (full-dúplex) para permitir que el tráfico fluya en ambas direcciones simultáneamente.
- Topologia en Malla
	Los nodos están interconectados. Los modos full-mesh conectan todos los dispositivos en la red directamente. En una topología de malla parcial, la mayoría de los dispositivos se conectan directamente. Esto proporciona múltiples rutas para la entrega de datos. Los datos se envían a la distancia más corta disponible para la transmisión.
- Topologia en CSMA/CD
	El método de acceso  _CSMA/CD se aplica en las topología BUS y ANILLO_,  este método  gestiona el acceso por parte de los terminales y que por medio de un algoritmo resuelve los conflictos causados en las colisiones de información. Cuando un nodo desea iniciar una transmisión, debe en primer lugar escuchar el medio para saber si está ocupado, debiendo esperar en caso afirmativo hasta que quede libre. Si se llega a producir una colisión, las estaciones reiniciarán cada una su transmisión, pero transcurrido un tiempo aleatorio distinto para cada estación. Esta es una breve descripción del protocolo de acceso _CSMA/CD_, pues actualmente se encuentran implementadas cantidad de variantes de dicho método con sus respectivas peculiaridades. El bus es la parte básica para la construcción de redes Ethernet y generalmente consiste de algunos segmentos de bus unidos ya sea por razones geográficas, administrativas u otras.