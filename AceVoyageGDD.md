# Ace Voyage

## Índice
1. [Historial de versiones](#1historial-de-versiones)
2. [Introducción](#2introducción)
    1. [Concepto del juego](#21-concepto-del-juego)
    1. [Características principales](#22características-principales)
    1. [Género](#23género)
    1. [Propósito y público objetivo](#24propósito-y-público-objetivo)
    1. [Jugabilidad](#25jugabilidad)
    1. [Estilo visual](#26estilo-visual)
    1. [Alcance](#27alcance)
    1. [Plataforma](#28plataforma)
    1. [Licencia](#29licencia)
    1. [Requisitos](#210-requisitos)
3. [Mecánicas del juego](#3-mecánicas-de-juego)
   1. [Jugabilidad](#31-jugabilidad)
   1. [Flujo de juego](#32-flujo-de-juego)
   1. [Personajes](#33-personajes)
   1. [Movimiento e interacción](#34-movimiento-e-interacción)
4. [Interfaz](#4-interfaz)
5. [Modelo de negocio y monetización](#5-modelo-de-negocio-y-monetización)
   1. [Modelo de negocio](#51-modelo-de-negocio)
   1. [Monetización](#52-monetización)
6. [Análisis MDA](#6-análisis-mda)
   1. [Estéticas](#61-estéticas)
   1. [Dinámicas](#62-dinámicas)
   1. [Mecánicas](#63-mecánicas)

***
***
# 1.	Historial de versiones
## 1.1 Versión 1.0
- Primera versión de GDD.
## 1.2 Versión 1.1
- Añadido el apartado "2.2.1 Aprendizaje computacional"
## 1.3 Versión 2.0
- Añadidas mecánicas de juego.
- Explicadas uso de cartas y ataque. Idea general del resto
- Añadidos personajes y enemigos
## 1.4 Versión 2.1
- Agregadas descripciones y conceptos visuales de los personajes
- Correcciones menores
## 1.5 Versión 2.2
- Ampliación de detalles sobre el apartado "2.6. Estilo Visual"
## 1.6 Versión 2.3
- Ampliación de mecánicas
- Correcciones menores
## 1.7 Versión 2.4
- Correcciones menores
## 1.8 Versión 2.5
- Desarrollo de la mecánica de movimiento
## 1.9 Versión 2.6
- Añadido un índice
- Correcciones en movimiento (movido de apartado Mecánicas a Movimiento e interacción)
## 1.10 Versión 2.7
- Explicación de mecánicas de recogida de cartas, recogida de piezas y salida.
- Correción menores.
## 1.11 Versión 2.8
- Añadido el apartado de requisitos mínimos
## 1.12 Versión 3.0
- Añadido el apartado "4. Modelo de negocio y monetización"
- Incluidas imágenes del apartado 4.1
- Correcciones menores
## 1.13 Versión 3.1
- Añadida la explicación de flujo de juego
## 1.14 Versión 3.2
- Modificada la expliacación de pensamiento computacional
## 1.15 Versión 3.3
- Añadida la interfaz
## 1.16 Versión 3.4
- Correcciones menores
- Mejoras en la redacción
## 1.17 Versión 4.0
- Añadido el apartado "6. Análisis MDA"
## 1.18 Versión 4.1
- Añadida la descripción del apartado "3.1.1. Quitar niebla"
- Añadidos los dos tipos de cartas que faltaban (dash y reparación del avión) en el apartado "3.1.3. Uso de cartas"
- Correcciones ortográficas y de redacción menores

# 2.	Introducción
## 2.1. Concepto del juego
*Ace Voyage* es un videojuego narrativo que basa su mecánica principal en el uso de cartas y exploración. Cuenta la historia de Patt, un aviador que en una de sus misiones sufre un accidente con su avioneta y trata de volver a su ciudad. Para ello, deberá encontrar las piezas de recambio para poder arreglar su avioneta, investigando en diversos biomas y enfrentándose a una gran variedad de enemigos.

## 2.2.	Características principales
El juego se caracteriza por:

### 2.2.1. Aprendizaje computacional
En la actualidad, la educación en programación y la evaluación de habilidades computacionales forman parte del plan de estudios en centros educativos españoles y en muchos otros países, incluso desde la etapa de educación infantil. Por otro lado, los niños comienzan a jugar videojuegos a edades cada vez más tempranas. Por esta razón, resulta sumamente interesante desarrollar videojuegos que fomenten el desarrollo de estas habilidades, ya sea en una sola dimensión o en varias. Un amplio abanico de videojuegos podría encajar en esta categoría, como, por ejemplo, juegos de rompecabezas que desafíen a encontrar rutas y superar obstáculos, juegos de estrategia que requieran la gestión de recursos, o juegos de plataformas con desafíos diversos. Con la motivación de poder desarrollar un videojuego que propicie la mejora de esta habilidad, ciertos aspectos de este proyecto, especialmente las mecánicas, están orientadas a este fin. 
Entre las destrezas que se asocian al uso de un PC y el juego pretende desarrollar se encuentran:
-	Abstracción: el reconocimiento de patrones está presente en este apartado. Nuestro juego proporciona situaciones para el desarrollo de esta habilidad, por ejemplo, con las pautas de movimiento de los distintos enemigos. En este caso, el murciélago ataca desplazándose en una única dirección, mientras que el lobo persigue al jugador por el mapa. 
-	Pensamiento algorítmico: el niño deberá centrar su atención en crear algoritmos, que pueden consistir en jugar algunas cartas en cierto orden, o en derrotar a ciertos enemigos de diferentes formas, dependiendo del tipo de estos. Se puede ejemplificar con la necesidad de usar cartas para despejar la niebla si se pretende desplazarse a una casilla cubierta por la misma.
-	Evaluación: en este caso, el niño deberá intentar gestionar de la manera más eficiente los distintos recursos y herramientas del videojuego. Quizá es en este aspecto donde mayor desarrollo puede notarse, debido a las distintas mecánicas que potencian esta destreza. El niño deberá gestionar el uso de cartas durante todo el nivel, ya que estas son limitadas, y sus funciones son imprescindibles para completar la pantalla. Además, con las mecánicas de estamina y exploración, el niño debe evaluar la situación y decidir si es asumible, negativo o incluso positivo para su personaje el desplazamiento a según qué casilla. 
Así, el videojuego recogerá datos, como el número de casillas exploradas, el número de cartas empleadas por el niño para completar cada nivel, o las veces en las que el niño pierde la partida de una u otra forma. Esto permitirá, accediendo a estos datos almacenados en una base de datos, que los profesores o responsables de estos niños puedan evaluar su evolución en el aprendizaje computacional. 


## 2.3.	Género
Ace Voyage posee una mezcla de los siguientes géneros:
-	Aventura/exploración: el objetivo principal del jugador será explorar los escenarios de cada nivel en busca de recursos, y, sobre todo, la casilla de salida.
-	Puzzle/estrategia: para conseguir superar los niveles, el jugador deberá jugar las cartas de las que dispone estratégicamente.

## 2.4.	Propósito y público objetivo
El propósito principal del videojuego se centra en la enseñanza de pensamiento computacional en niños de edades comprendidas entre 3 y 12 años, como ya se ha desarrollado en el apartado "2.2.1". Por ello, y teniendo en cuenta que ya existen numerosos videojuegos de enseñanza que no resultan divertidos para los niños, se ha de centrar también en hacer un videojuego de aprendizaje, pero que a su vez resulte entretenido y divertido para niños.
Por otro lado, para lograr dicho propósito se ha optado por un sistema de niveles cortos y rejugables, que mantengan al usuario jugando sin llegar a cansarle a causa de largas sesiones.

## 2.5.	Jugabilidad
En Ace Voyage, cada nivel tendrá lugar en un bioma diferente, en el que el escenario se mostrará en forma de tablero con casillas cuadradas. Estas casillas, en su mayoría, se encontrarán ocultas bajo nubes o niebla.
El objetivo principal en cada nivel será explorar el escenario, despejando estas nubes, tratando de encontrar la pieza del avión correspondiente a ese nivel, y, posteriormente, la casilla de salida para desbloquear el siguiente nivel. Para ello, el jugador hará uso de las siguientes acciones:
-	Movilidad: el jugador podrá moverse por el escenario deslizando en la dirección en la que quiera y le permita el propio tablero.
-	Juego de cartas: estas permitirán descubrir casillas ocultas, regenerar estamina (que se irá gastando con el movimiento) y salud, o atacar a enemigos.
-	Obtención de cartas: el jugador podrá obtener cartas en casillas recién descubiertas, o explorando las casillas ya descubiertas (en el caso de que se haya quedado sin cartas previamente).
-	Combate: el combate con enemigos consistirá en dos fases: una de esquiva, en la que el enemigo atacará unas determinadas casillas, y el jugador deberá evitar posicionarse en estas y recibir daño; y otra de ataque, en la que el jugador jugará una carta que le permitirá hacer daño a enemigos que estén posicionados en las casillas en las que se realice el ataque.

## 2.6.	Estilo Visual
El estilo artístico y visual del videojuego se enfoca en crear un mundo visualmente atractivo y coherente, donde los personajes y el entorno se combinen de manera armoniosa para ofrecer a los jugadores una experiencia única y memorable. Para lograrlo, se ha optado por utilizar una paleta de colores vibrantes, pero no estridentes, con tonos suaves que transmitan una sensación de calma y diversión al mismo tiempo, además de emplear estilos cercanos a los cell-shading y cartoon.

Los personajes principales del juego presentarán formas redondeadas y amigables, lo que les hará fácilmente identificables y simpáticos para los jugadores. Sus rasgos faciales serán suaves y expresivos.

Por otro lado, el escenario del juego también seguirá este estilo artístico. Los paisajes contarán con elementos naturales como árboles, ríos y montañas, pero aportándoles un toque fantástico y mágico. Además, los edificios y estructuras del juego presentarán diseños únicos que combinen elementos tradicionales con un toque moderno y creativo, lo que creará un mundo coherente y cautivador.

Los personajes del juego y los entornos serán diseñados y modelados en 3D, mientras que las cartas serán una mezcla de 2D y 3D.

Se tomarán como referencias, entre otros títulos:
 	 
![Mail mole (colores suaves, diseños redondos)](/images/Imagen1.jpg)

> *Mail mole (colores suaves, diseños redondos)*

![Animal crossing (colores, anatomía de los personajes)](/images/Imagen2.jpg)

> *Animal crossing (colores, anatomía de los personajes)*
 	 
![Tunic (isométrico, aventura, diseño general)](/images/Imagen3.jpg)

> *Tunic (isométrico, aventura, diseño general)*

![Death’s door (isométrico, escenarios)](/images/Imagen4.jpg)

> *Death’s door (isométrico, escenarios)*

## 2.7.	Alcance
Aunque no hay planes concretos para próximas expansiones o secuelas en este momento, el juego está diseñado de manera que pueda considerarse dicha posibilidad en el futuro. En caso de que sea necesario, se podrían desarrollar expansiones que incluyan más niveles o nuevas historias en el mismo universo para futuras entregas.

## 2.8.	Plataforma
El juego será desarrollado para navegadores web, siendo jugable tanto en PC como en tablets (principal herramienta de aprendizaje con nuevas tecnologías en colegios).

## 2.9.	Licencia
La premisa del juego es totalmente original y única, sin estar basada en ninguna propiedad intelectual previa ni en conceptos preexistentes en el mundo de los videojuegos. El equipo de desarrollo ha trabajado en la creación de un mundo, mecánicas de juego y personajes que son innovadores y no se derivan de ninguna fuente externa. El enfoque principal es ofrecer a los jugadores una experiencia fresca y emocionante que no se asemeje a ningún otro juego existente.

## 2.10. Requisitos
Dependiendo del dispositivo en el que se desea jugar a *Ace Voyage* son necesarios una serie de requisitos mínimos:
- PC/Itch.io: es necesario dsponer de uno de los siguientes navegadores: Chrome o Mozilla Firefox (recomendado tenerlos actualizados a la última versión).
- Android: es necesario disponer de la versión 7.0 Nougat u otra posterior. También se recomienda tener una pantalla suficientemente grande (aproximadamente 10 pulgadas o mayor).

# 3. Mecánicas de juego
## 3.1. Jugabilidad
En este juego, se explora un escenario que cambia con cada bioma y en el los jugadores encontrarán distintos obstáculos, como enemigos y niebla, que reduce la visión del tablero. Para avanzar por el escenario, se deberán usar las cartas con las que los usuarios podrán defenderse de los enemigos y despejar la niebla. Además, cada movimiento cuenta, ya que la estamina se consume con cada paso que se da.

### 3.1.1. Quitar niebla
Como se ha explicado anteriormente, algunas de las casillas del tablero tendrán niebla encima de ellas, lo que impide que el personaje pueda ir a esas casillas o atravesarlas. Por ello, el jugador ha de utilizar las correspondientes cartas de niebla, que le permitirán despejarla y seguir explorando el nivel.

### 3.1.2. Estamina
En cada casilla que el jugador mueve al protagonista, se consume un porcentaje de su estamina máxima. Si la estamina se agota por completo, el jugador perderá la partida, por lo que es fundamental administrar cuidadosamente los recursos y movimientos. Es importante destacar que es posible recuperar estamina mediante el uso de cartas.

### 3.1.3. Uso de cartas
Nuestro protagonista empieza cada partida con una mano de cartas, y podrá conseguir más a lo largo de la partida. Estas cartas se mostrararán en la parte inferior de la pantalla.
Habrá varios tipos de cartas: de ataque, de exploración, de estamina, de dash y de reparación del avión. Las cartas podrán seleccionarse de manera que la carta sobresaldrá de la mano y se iluminará en el escenario el área de efecto de dicha carta, informando visualmente al jugador.
- Las cartas de ataque muestran un área frente al jugador, y, una vez se hace click en la dirección en la que se quiere usar la carta, esta se gasta y hará daño a los enemigos que se encuentren en ese área.
- Las cartas de exploración mostrarán el área de niebla, que se despejará frente al jugador. Al usar la carta, se gastará y eliminará la niebla del escenario, permitiendo al jugador moverse por la casilla y ver lo que esta contiene.
- Las cartas de estamina muestran como área de efecto la casilla del jugador, puesto que esta recupera la estamina del jugador para que pueda moverse de nuevo. Al usarse la carta, se gasta inmediatamente.
- Las cartas de dash permiten al jugador esquivar de manera rápida los ataques de los enemigos.
- La carta de reparación del avión se utiliza atan solo al final del juego, como conclusión de la historia.
Dentro de cada categoría de las cartas (excepto dash y reparación del avión), existen distintos tipos dependiendo del área de efecto.

### 3.1.4. Recolección de cartas
Cada casilla puede tener sobre ella una carta. Cuando el jugador desplaza su personaje hasta la propia casilla, recoge la carta, y esta pasa a formar parte de su mano. 

### 3.1.5. Ataque
El jugador tiene distintas cartas de ataque que puede usar para hacer daño a los enemigos. Para que el ataque tenga éxito, tiene que conseguir que los enemigos se encuentren en las casillas en las que hará efecto el ataque. Esto provoca daño en los enemigos matándolos, en caso de que su vida sea menor que el daño ejercido.
Cartas de ataque:
- Carta de ataque débil: El área de efecto del ataque es de 2x1 en la dirección del jugador. Quita 25 puntos de salud.
- Carta de ataque fuerte: El área de efecto del ataque es en forma de T, siendo de 2x1 frente al jugador, más dos casillas más una a cada lado del final del primer área mencionada. Este ataque quita 50 puntos de salud en el área principal y 25 en los dos extremos.

### 3.1.6. Carga de exploración
Por cada casilla que el jugador mueve al protagonista, se carga un porcentaje de la exploración máxima. Cuando esta llega al máximo, se puede solicitar una nueva carta. Esto fomenta la exploración del jugador por el mapa, recompensándolo por dicha acción.

### 3.1.7. Encontrar piezas y salida
En cada nivel hay dos casillas únicas, la que posee la pieza y la de salida. Para superar el nivel, el jugador deberá encontrar la pieza correspondiente a ese nivel, y buscar (si no la ha encontrado ya) la casilla de salida para poder pasar al siguiente. Es decir, el jugador no podrá salir por dicha casilla si no ha recogido previamente la pieza mencionada anteriormente.

## 3.2. Flujo de juego
La experiencia del jugador en una partida de *Ace Voyage* no difiere significativamente en términos de la forma en que se desarrolla una partida en un videojuego convencional, especialmente en lo que respecta al tipo de pantallas que se encuentran.

Lo primero que se encuentra el jugador es la pantalla con el menú principal. Se le dan las opciones de jugar y de configurar las opciones del juego. Al pulsar en jugar se muestra una pantalla de selección del bioma, en la que se deberá elegir el grupo de niveles en el que se quiere avanzar.

Como se ha mencionado previamente, *Ace Voyage* se estructura en biomas. Cuando el jugador selecciona un bioma por primera vez, se presenta una breve cinemática que narra una parte de la historia. Esta narración tiene como objetivo proporcionar contexto y enriquecer la inmersión del jugador en la trama del juego.

Cada bioma está conformado por niveles independientes. Para avanzar al siguiente, el jugador debe completar el nivel anterior. Los niveles que se completan son guardados para que este continúe el progreso por donde lo dejó cuando vuelva al juego. Además, al entrar a un nivel, el jugador se encuentra con un terreno dividido en casillas y la interfaz, en la que se muestran las barras de energía y exploración y la mano de cartas actual. También se le indica el objetivo del nivel, el cual siempre es recoger una de las piezas del avión de *Patt*.

Por el terreno, el jugador debe lidiar con la niebla (que oculta partes de la superfice) y los enemigos que obstaculizan el camino, así como con una posible escasez de cartas y de energía. Para conseguir más cartas el jugador puede recogerlas del suelo (si las hay), eliminar enemigos o avanzar por las casillas. Esto último significa gastar energía para llenar la barra de exploración. Cuando esta se llena completamente, se le proporciona una nueva carta.

Si consigue alcanzar la pieza y llegar a la salida sin haber perdido toda la energía, el nivel se completa exitosamente y se presenta una pantalla de victoria, dando la opción de regresar al menú. Cada vez que se completa el último nivel de un bioma, se muestra una cinemática en la que se cuenta un poco más de la historia del protagonista.

Por el contrario, si el jugador pierde toda la energía antes de haber alcanzado la pieza, se muestra una pantalla de derrota, dando la posibilidad de reintentarlo o volver al menú principal.

El jugador puede iniciar todos los niveles desbloqueados las veces que desee.

## 3.3. Personajes
### 3.3.1. Patt (Protagonista)
Nuestro pequeño pero valiente protagonista es un cartero que hace uso de las cartas para defenderse y explorar el terreno.

Lleva un abrigo largo, confeccionado en un llamativo color azul verdoso que contrasta con su piel pálida y amarronada. La bufanda que rodea su cuello está tejida en lana de punto inglés con un color amarillo anaranjado llamativo que no pasará desapercibido.

En sus pies, lleva unas botas de goma amarillas a juego con la bufandita que llegan hasta la mitad de la pantorrilla. Estas son prácticas y cómodas, ideales para aventurarse en cualquier terreno.

El toque más llamativo de su atuendo es el gorro de aviador que adorna su cabeza. Este gorro es de cuero marrón con una visera de ante, y unas gafas de aviador apoyadas sobre el mismo. Las lentes de las gafas son redondas y tintadas en un tono azul profundo, dándole un aire misterioso y enigmático.

### 3.3.2. Murciélago
Un enemigo volador que se caracteriza por pequeño tamaño y su velocidad. Precisamente por sus rápidos movimientos no es capaz de cambiar de dirección fácilmente por lo que se mueve en línea recta. El daño que puede causar es bajo y no dispone de mucha vida.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |     25     |
|    Daño    |     10     |
| Movimiento | 3 Casillas |
|   Ataque   | 3 casillas |

### 3.3.3. Lobo
Un enemigo que tiene un gran olfato que le permite perseguir al jugador allá a donde vaya. Es muy rápido, aunque debe acercarse mucho para poder atacar. Por suerte para él, dispone de bastante vida, lo que le podría permitir resistir algún golpe. Aunque no siempre se le brinde la oportunidad de atacar, cuando la tiene, la aprovecha bien, causando bastante daño.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |     50     |
|    Daño    |     25     |
| Movimiento | 4 Casillas |
|   Ataque   | 1  Casilla |

### 3.3.4. Araña
Un enemigo que acecha a sus víctimas y espera a que caigan en su trampa. Se mueve muy lentamente para evitar ser detectado mientras prepara sus trampas de telaraña por el camino. Cuando su presa se encuentra a su alcance ataca causando mucho daño a su alrededor y ralentizando su marcha, si es que consigue escapar. Además tiene una armadura de telaraña la cual le proporciona una fuerte protección frente a los ataques.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |     75     |
|    Daño    |     25     |
| Movimiento | 1  Casilla |
|   Ataque   | 8 Casillas |

## 3.4. Movimiento e interacción
### 3.4.1. Interacción entre elementos
Los mapas están formados por bloques que se toman como casillas a la hora de realizar cualquier acción en el entorno (desplazamiento, ataques y consumibles).
Para moverse, el jugador debe pulsar sobre la casilla destino, y si es accesible, el personaje recorrerá una ruta calculada mediante el algoritmo de A estrella hasta allí.
De la misma manera, los consumibles y ataques muestran su efecto en el entorno en base a las casillas que abarcan.

### 3.4.2. Controles
Prácticamente la totalidad del tiempo de juego el jugador estará usando el ratón (si se juega en ordenador), pues todas las acciones principales se realizan con este: marcar una casilla para moverse, arrastrar cartas y abrir menús. Así se consiguen unos controles más unificados entre plataformas (ordenador y dispositivos tablets), facilitando el desarrollo y brindando precisión al jugador en la toma de decisiones.

# 4. Interfaz
A continuación, se muestrán las cuatro pantallas básicas de la interfaz del videojuego.

![Pantalla del menú principal](/images/Menú_principal.png)

> *Pantalla del menú principal*

![Pantalla de contacto y créditos](/images/Contacto_y_créditos.png)

> *Pantalla de contacto y créditos*

![Pantalla de juego](/images/Juego.png)

> *Pantalla de juego*

![Pantalla de partida perdida](/images/Partida_perdida.png)

> *Pantalla de partida perdida*

# 5. Modelo de negocio y monetización
## 5.1. Modelo de negocio
Nuestra empresa sigue un modelo de negocio que resulta de la fusión del modelo de eliminación de intermediarios y la venta directa. Esta estrategia implica que nosotros mismos nos acerquemos y trabajemos directamente con y para nuestros clientes, que en este caso son centros educativos, sin necesidad de recurrir a intermediarios externos. Para desarrollar y definir este modelo de negocio, hemos utilizado varias metodologías que nos han proporcionado una comprensión más profunda y una base sólida:
- Información sobre el Usuario: Hemos llevado a cabo una investigación exhaustiva para comprender a fondo a nuestro cliente, en este caso, los centros, y su entorno.

![Información sobre el Usuario](/images/informacionSobreElUsuario.png)

> *Información sobre el Usuario*

- Mapa de Empatía: Utilizamos el mapa de empatía para profundizar en la perspectiva de nuestros clientes, comprender sus opiniones y preocupaciones con respecto a nuestros productos y servicios.

![Mapa de Empatía](/images/mapaDeEmpatia.png)

> *Mapa de Empatía*

- Caja de Herramientas: Hemos empleado una caja de herramientas que describe nuestro modelo de negocio a través de una serie de componentes que representan las diferentes partes afectadas por las actividades de nuestra empresa, así como las distintas acciones y relaciones que se establecen entre ellas.

![Caja de Herramientas](/images/cajaDeHerramientas.png)

> *Caja de Herramientas*

- Modelo de Lienzo: Para obtener una representación visual y clara de nuestra infraestructura, oferta, tipo de clientes y aspectos financieros de nuestra empresa.

![Modelo de Lienzo](/images/modeloDeLienzo.png)

> *Modelo de Lienzo*

## 5.2. Monetización
En términos de monetización, hemos optado por un modelo de "pay-to-play" que implica una suscripción trimestral. Esta estrategia permite a los centros educativos adquirir nuestro producto anualmente, durante los trimestres en los que lo necesiten, de modo que puedan aprovechar al máximo su inversión y no sientan que están desperdiciando recursos.

# 6. Análisis MDA
## 6.1. Estéticas
Se pretende que las estéticas principales que presente *Ace Voyage* sean DESAFÍO, NARRATIVA y DESCUBRIMIENTO. Para ello, se desarrollan, en función de cada una de estas estéticas, varias dinámicas que las fomenten, de manera que el usuario las experimente a la hora de jugarlo.

## 6.2. Dinámicas
Así, por cada estética, estas dinámicas serían:
1.	Para DESAFÍO: el juego propone un reto al jugador, siendo este terminar el nivel habiendo gestionado correctamente tanto las cartas que ha obtenido a lo largo de la partida como la energía del protagonista. Todo ello mientras ha de lidiar con diversos obstáculos como huecos entre casillas, diversos objetos, enemigos y la niebla que cubre parte del mapa.
2.	Para NARRATIVA: *Ace Voyage* presentará una historia emocionante, en la que Patt, piloto de aviones y cartero, intentará entregar una carta. En su viaje sufrirá un accidente que hará que su avión se estrelle en una zona desconocida, llena de enemigos que intentarán quitarle la vida. Patt deberá buscar las piezas de su avión esparcidas a lo largo de los niveles, y así arreglar su avión y poder retomar su misión.
3.	Para DESCUBRIMIENTO: el jugador irá encontrando nuevos tipos de enemigos conforme avanza a través de los niveles, que poseerán diferentes comportamientos (tanto en los patrones de movimiento como en los de ataques). Por otro lado, también hallará diferentes tipos de cartas, que podrá combinar de diversas maneras para conseguir superar el nivel. Por último, en un momento concreto de la partida, el jugador se encontrará a un compañero, su mascota, que le ayudará en diversas funciones, como atacar enemigos o recoger ítems para llevárselos al jugador.

## 6.3. Mecánicas
En cuanto a la mecánica, esta gira en torno al juego de cartas como forma de explorar el mapa (descubriéndolo) y combatir enemigos (tanto para atacar como para esquivar o curarse). El jugador dispone de una mano de cartas de diferentes tipos (ataque, quitar niebla, recargar estamina, dash y reparar el avión). Este deberá jugarlas a lo largo del nivel para conseguir superar el mismo, pero a su vez tratando de utilizar el menor número de cartas posibles. Por otro lado, existen dos barras que miden dos aspectos importantes del personaje: la estamina, que se pierde al andar o al recibir daño (al estilo de una barra de salud) y se puede recuperar consumiendo una carta del tipo correspondiente (como se ha mencionado anteriormente); y la de exploración, que se va llenando conforme el personaje se va moviendo, y puede otorgar una carta si el jugador desea, evitando que el jugador se quede sin cartas y por tanto no pueda avanzar en el nivel.
