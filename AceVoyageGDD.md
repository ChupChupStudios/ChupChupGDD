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
   1. [Escenarios](#34-escenarios)
   1. [Movimiento e interacción](#35-movimiento-e-interacción)
4. [Interfaz](#4-interfaz)
5. [Modelo de negocio y monetización](#5-modelo-de-negocio-y-monetización)
   1. [Modelo de negocio](#51-modelo-de-negocio)
   1. [Monetización](#52-monetización)
6. [Análisis MDA](#6-análisis-mda)
   1. [Estéticas](#61-estéticas)
   1. [Dinámicas](#62-dinámicas)
   1. [Mecánicas](#63-mecánicas)
7. [Post-mórtem](#7-post-mórtem)
   1. [Qué ha ido bien](#71-qué-ha-ido-bien)
   1. [Qué se puede mejorar](#72-qué-se-puede-mejorar)
   1. [Desarrollo de ideas](#73-desarrollo-de-ideas)
8. [Plan de Marketing](#8-plan-de-marketing)
    1. [Dónde estamos](#81-dónde-estamos)
    1. [Objetivos](#82-objetivos)
    1. [Estrategias y tácticas](#83-estrategias-y-tácticas)
    1. [Plan](#84-plan)
    1. [Análisis](#85-análisis)
***
***
# 1.	Historial de versiones
## 1.1 Versión 1.0
- Primera versión de GDD.
## 1.2 Versión 1.1
- Añadido el apartado "2.2.1 Aprendizaje computacional".
## 1.3 Versión 2.0
- Añadidas mecánicas de juego.
- Explicadas uso de cartas y ataque. Idea general del resto.
- Añadidos personajes y enemigos.
## 1.4 Versión 2.1
- Agregadas descripciones y conceptos visuales de los personajes.
- Correcciones menores
## 1.5 Versión 2.2
- Ampliación de detalles sobre el apartado "2.6. Estilo Visual".
## 1.6 Versión 2.3
- Ampliación de mecánicas.
- Correcciones menores
## 1.7 Versión 2.4
- Correcciones menores.
## 1.8 Versión 2.5
- Desarrollo de la mecánica de movimiento.
## 1.9 Versión 2.6
- Añadido un índice
- Correcciones en movimiento (movido de apartado Mecánicas a Movimiento e interacción).
## 1.10 Versión 2.7
- Explicación de mecánicas de recogida de cartas, recogida de piezas y salida.
- Correción menores.
## 1.11 Versión 2.8
- Añadido el apartado de requisitos mínimos.
## 1.12 Versión 3.0
- Añadido el apartado "4. Modelo de negocio y monetización".
- Incluidas imágenes del apartado 4.1.
- Correcciones menores.
## 1.13 Versión 3.1
- Añadida la explicación de flujo de juego.
## 1.14 Versión 3.2
- Modificada la explicación de pensamiento computacional.
## 1.15 Versión 3.3
- Añadida la interfaz.
## 1.16 Versión 3.4
- Correcciones menores.
- Mejoras en la redacción.
## 1.17 Versión 4.0
- Añadido el apartado "6. Análisis MDA".
## 1.18 Versión 4.1
- Añadida la descripción del apartado "3.1.1. Quitar niebla".
- Añadidos los dos tipos de cartas que faltaban (dash y reparación del avión) en el apartado "3.1.3. Uso de cartas".
- Correcciones ortográficas y de redacción menores.
## 1.19 Versión 5.0
- Cambiadas las descripciones y estadísticas de los enemigos.
- Añadidos los concepts de los personajes y escenarios.
- Añadido el apartado "3.1.8. Mascota".
## 1.20 Versión 5.1
- Reescrito el apartado "3.2. Flujo de juego".
- Añadidas las pantallas de pérdida y victoria.
- Añadido el diagrama de flujo en el apartado "4. Interfaz".
## 1.21 Versión 6.0
- Añadido el apartado "7. Post-mórtem".
## 1.22 Versión 7.0
- Añadido el apartado "8. Plan de Marketing".
## 1.23 Versión 7.1
- Corrección de formato en el apartado "8. Plan de Marketing".
## 1.24 Versión 7.2
- Corrección de errores menores de formato del apartado "8. Plan de Marketing".
## 1.25 Versión 7.3
- Añadido el apartado "8.2. Objetivos"
- Corrección de errores menores de formato.
## 1.26 Versión 7.4
- Añadidos apartado 8 y subapartados del mismo en el índice.
- Corrección de errores menores.
## 1.27 Versión 7.5
- Añadido apartado "8.3. Estrategias y tácticas".
- Corrección de errores menores.
## 1.28 Versión 7.6
- Añadido apartado "8.4. Plan".
- Corrección de errores menores.
## 1.29 Versión 7.7
- Corrección de errores de formato y referencias.
## 1.30 Versión 7.8
- Corrección de errores menores.
## 1.31 Versión 7.9
- Ampliación del contenido del apartado "8.4. Plan".
- Corrección de errores menores.
## 1.32 Versión 7.10
- Ampliación del contenido del apartado "8.4. Plan".
## 1.33 Versión 7.11
- Corrección de errores menores.
## 1.34 Versión 7.12
- Corrección de errores menores.
- Añadido el apartado "8.5. Análisis".
## 1.35 Versión 7.13
- Corrección imagen calendario semana apartado "8.4.3. Planificación semana del lanzamiento".
- Correcciones menores en el mismo apartado.
## 1.36 Versión 7.14
- Corrección imagen calendario semana apartado "8.4.3. Planificación semana del lanzamiento".
- Correcciones menores en el mismo apartado.
## 1.37 Versión 7.15
- Corrección de errores menores.
  
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

### 3.1.8. Mascota
Como se detallará en el apartado de personajes (3.3.) la mascota, Perky, ayudará al jugador por su cuenta a lo largo de los niveles. Podrá atacar enemigos y recoger cartas para traérselas a Patt.

## 3.2. Flujo de juego
La experiencia del jugador en una partida de *Ace Voyage* no difiere significativamente en cómo se desarrolla en una partida en un videojuego convencional, especialmente en lo que respecta al tipo de pantallas que se encuentran.

Lo primero que se encuentra el jugador es la pantalla con el menú principal. Al pulsar en jugar por primera vez, aparecerán 3 opciones: jugar el tutorial, omitir el tutorial y volver al menú.

Si el jugador decide jugar el tutorial, este será guiado a través de todas las mecánicas del videojuego. Una vez completado, comenzará el nivel 1 (si el jugador omite el tutorial, empezará desde aquí).

Para avanzar entre niveles, el jugador debe completar el nivel anterior. Al entrar a un nivel el jugadr tendrá ante él un terreno dividido en casillas con recursos y enemigos varios, y la interfaz, en la que se muestran las barras de energía y exploración (arriba a la izquierda), la mano de cartas actual (abajo), los botones de pausa (abajo a la izquierda) y de giro (abajo a la derecha) y la info de la mascota (arriba a la derecha). En el escenario además habrá un cartel en una casilla concreta, que el jugador podrá leer y que añadirá contrexto a la hisotria de Patt. Al igual que el cartel, cuando Patt recoja la pieza correspondiente a cada nivel, este recordará también parte del contexto que rodea la historia.

En el menú de pausa aparecen las opciones: reanudar, bestiario y salir al menú.

Por el terreno, el jugador debe lidiar con la niebla (que oculta partes de la superfice) y los enemigos que obstaculizan el camino, así como con una posible escasez de cartas y de energía. Para conseguir más cartas el jugador puede recogerlas del suelo (si las hay), eliminar enemigos o avanzar por las casillas. Esto último significa gastar energía para llenar la barra de exploración. Cuando esta se llena completamente, se le proporciona una nueva carta.

Si consigue alcanzar la pieza y llegar a la salida sin haber perdido toda la energía, el nivel se completa exitosamente, a diferencia del último nivel, que no se superará hasta que el jugador utilice la carta de reparación del avión sobre este. Además, una vez completado el último nivel, aparecerá una pantalla dando la enhorabuena al jugador por haber completado el juego.

Por el contrario, si el jugador pierde toda la energía antes de haber alcanzado la pieza, se muestra una pantalla de derrota, dando la posibilidad de reintentarlo o volver al menú principal.

## 3.3. Personajes
### 3.3.1. Patt (Protagonista)
![Patt](/images/Patt.jpg)

Nuestro pequeño pero valiente protagonista es un cartero que hace uso de las cartas para defenderse y explorar el terreno.

Lleva un abrigo largo, confeccionado en un llamativo color azul verdoso que contrasta con su piel pálida y amarronada. La bufanda que rodea su cuello está tejida en lana de punto inglés con un color amarillo anaranjado llamativo que no pasará desapercibido.

En sus pies, lleva unas botas de goma amarillas a juego con la bufandita que llegan hasta la mitad de la pantorrilla. Estas son prácticas y cómodas, ideales para aventurarse en cualquier terreno.

El toque más llamativo de su atuendo es el gorro de aviador que adorna su cabeza. Este gorro es de cuero marrón con una visera de ante, y unas gafas de aviador apoyadas sobre el mismo. Las lentes de las gafas son redondas y tintadas en un tono azul profundo, dándole un aire misterioso y enigmático.

### 3.3.2. Perky (Mascota)
![Perky](/images/Mascota.JPG)
Perky tiene diversos intereses y atenderá solo uno simultáneamente, entre ellos está su instinto protector, si se centra en él irá hacia el enemigo más cercano, entrando en combate con él. La mascota puede también querer mostrar su afecto al protagonista, si esto se junta con una escasez de cartas en el mazo del jugador, Perky comenzará un ciclo en el que primero buscará algún recurso (cartas por el escenario), después irá a recogerlo, momento en el que queda a la espera de que el jugador le dé la señal para llevárselo.

El tiempo que pase Perky moviéndose o combatiendo, así como el recibir ataques, mermará su energía. Si esta decae mucho abandonará la actividad que esté realizando para ir a una casilla concreta a descansar, lo que incluye abandonar combates y búsquedas. Si un enemigo se acerca mientras está durmiendo y ya ha recuperado sufiente energía, la mascota pasará a cubrir otros intereses. Perky ignorará a cualquier enemigo que esté en su ruta siempre y cuando no sea su objetivo de instinto  protector, incluso si llega a darle algún golpe y restarle algo de energía. La característica anterior se repite de igual manera para los objetos que pueda encontrar en su ruta si no está recolectando para el jugador.

### 3.3.3. Murciélago
![Murciélago](/images/Murciélago.jpg)

El murciélago es un pequeño y veloz enemigo. Su simpleza hace que sea el primer enemigo que el jugador enfrentará, y por ello su dificultad residirá en la aparición de otros 2 murciélagos extra una vez los invoque.

Por la velocidad que le caracteriza, su movimiento consiste en avanzar 3 casillas seguidas por cada acción del jugador. Así, si el jugador se encuentra en una de las tres casillas que se encuentran enfrente, el murciélago atacará.

Por otro lado, tendrá la capacidad de invocar a otros 2 murciélagos tras su muerte, que aparecerán en las casillas que se encuentren a ambos lados de este, para evitar que invoque murciélagos indefinidamente solo el primer murciélago (el murciélago invocador) podrá hacerlo.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |      1     |
|    Daño    |     2.5    |
| Movimiento | 3 Casillas |
|   Ataque   | 3 casillas |

### 3.3.4. Lobo
![Lobo](/images/Lobo.jpg)

Se trata de un enemigo que tiene un gran olfato que le permite perseguir al jugador vaya a donde vaya. Es muy rápido, aunque debe acercarse mucho para poder atacar. Por suerte para él, dispone de bastante vida, lo que podría permitirle resistir algún golpe y, aunque no siempre se le brinde la oportunidad de atacar cuando la tiene, la aprovecha bien causando bastante daño.

En cuanto a su movimiento, el lobo se desplaza en casillas de cuatro en cuatro, siempre yendo a las últimas ubicaciones del protagonista. Cada vez que realiza un movimiento, espera un tiempo variable para descansar y volver a tener energía y seguir con su persecución. Si en su tarea de ir tras Patt, llega a estar en su rango de interacción, el lobo atacará al jugador con un potente mordisco. Además, si Patt se encuentra en un estado de baja salud, el lobo olerá la situación y aumentará su ritmo para cazar al protagonista.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |      2     |
|    Daño    |      5     |
| Movimiento | 4 Casillas |
|   Ataque   | 1  Casilla |

### 3.3.5. Araña
![Araña](/images/Araña.JPG)

La araña se desplaza en un patrón impredecible, moviéndose una casilla a la vez a una velocidad notablemente reducida mientras acecha a sus presas. Siempre desea mantener activas dos trampas elaboradas con tela de araña en su territorio. Si alguien cae en una de ellas, verá reducida su velocidad y la telaraña se romperá. Si no se encuentra con ningún objetivo, la reactivará y continuará con su comportamiento habitual, y si encuentra al objetivo, lo atacará.

Por otra parte, está envuelta en una armadura confeccionada con su misma tela de araña, lo que le otorga la capacidad de soportar un golpe adicional. Sin embargo, esta defensa se desintegra al recibir un impacto, momento en el cual la araña priorizará alejarse para reconstruir su armadura. Cuando alguien se encuentra dentro de su radio de alcance, desencadena un ataque de área, focalizando las ocho casillas circundantes con cada una de sus patas.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |      2     |
|    Daño    |     2.5    |
| Movimiento | 1  Casilla |
|   Ataque   | 8 Casillas |

### 3.3.6. Topo
![Topo](/images/Topo.JPG)

El topo es un enemigo que no tiene mucha vida y tiene un movimiento bastante limitado. A pesar de estas desventajas, no es un enemigo sencillo de derrotar, ya que tiende a escapar cuando se encuentra en peligro y ataca sin ser detectado fácilmente. Además, puede recuperar salud si está herido y se siente a salvo, o aumentar su capacidad de ataque si se siente amenazado mientras intenta relajarse.

Por tanto, cuando el topo esté en la superficie, comprobará si hay alguna criatura cerca de él. Si no hay nadie, y tiene toda la vida, se moverá por el escenario. Sin embargo, si se cruza con alguna otra criatura, se enterrará para ocultarse. Si esa criatura es el jugador, el topo la atacará, y si no es el jugador, simplemente permanecerá escondido en su lugar. Una vez que no se sienta en peligro porque las criaturas que lo rodeaban se han alejado, saldrá a la superficie, y si ha perdido algo de vida, desenterrará una raíz. Con la raíz en su posesión, volverá a comprobar si hay alguien cerca. En este caso, si detecta al jugador, lo atacará con la raíz causando más daño. Si no hay nadie cerca, se sentirá seguro y consumirá la raíz para regenerar algo de vida.
|  Cualidad  |  Cantidad  |
|------------|------------|
|    Vida    |      2     |
|    Daño    |1 (con raíz)/5(sin raíz)|
| Movimiento | 2 Casillas |
|   Ataque   | 2 Casillas |

## 3.4. Escenarios
En el videojuego aparecen dos biomas principalmente: pradera y cueva.

### 3.4.1. Pradera
![Pradera](/images/Pradera.png)

### 3.4.2. Cueva
![Cueva](/images/Cueva.png)

## 3.5. Movimiento e interacción
### 3.5.1. Interacción entre elementos
Los mapas están formados por bloques que se toman como casillas a la hora de realizar cualquier acción en el entorno (desplazamiento, ataques y consumibles).
Para moverse, el jugador debe pulsar sobre la casilla destino, y si es accesible, el personaje recorrerá una ruta calculada mediante el algoritmo de A estrella hasta allí.
De la misma manera, los consumibles y ataques muestran su efecto en el entorno en base a las casillas que abarcan.

### 3.5.2. Controles
Prácticamente la totalidad del tiempo de juego el jugador estará usando el ratón (si se juega en ordenador), pues todas las acciones principales se realizan con este: marcar una casilla para moverse, arrastrar cartas y abrir menús. Así se consiguen unos controles más unificados entre plataformas (ordenador y dispositivos tablets), facilitando el desarrollo y brindando precisión al jugador en la toma de decisiones.

# 4. Interfaz
A continuación, se muestrán el diagrama de flujo y las cuatro pantallas básicas de la interfaz del videojuego.

![Diagrama de flujo](/images/DiagramaDeFlujo.jpg)

> *Diagrama de flujo*

![Pantalla del menú principal](/images/Menú_principal.png)

> *Pantalla del menú principal*

![Pantalla de contacto y créditos](/images/Contacto_y_créditos.png)

> *Pantalla de contacto y créditos*

![Pantalla de juego](/images/Juego.png)

> *Pantalla de juego*

![Pantalla de partida perdida](/images/Pantalla_perdida.png)

> *Pantalla de partida perdida*

![Pantalla de victoria](/images/Pantalla_victoria.png)

> *Pantalla de victoria*

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

# 7. Post-mórtem
A continuación se desarrolla el post-mórtem correspondiente a la versión beta del videojuego. Primero cada mmiembro del equipo mencionarán un par de ideas por cada apartado ("Qué ha ido bien" y "Qué se puede mejorar"), teniendo en cuenta tanto la experiencia personal en el desarrollo del proyecto como el feedback externo obtenido de las pruebas de Beta Testing. Posteriormente se hará una puesta en común de estas ideas, en donde cada miembro desarrollará las que haya propuesto, y se desarrollará un breve texto destacando las que se consideren más importantes en base al consenso de todos los miembros.

## 7.1. Qué ha ido bien
- Desarrollador 1: Comunicación y relación entre miembros; reparto de tareas y colaboración.
- Desarrollador 2: Comunicación de ideas entre miembros y reparto de trabajo aprovechando fortalezas.
- Desarrollador 3: Reparto de trabajo; comunicación en casos de estancamientos de tareas.
- Desarrollador 4: Sobreposición a problemas y adversidades (gracias a la comunicación y compromiso); reparto de tareas y responsabilidades.
- Artista 1: Comunicación entre miembros; coordinación y reparto del trabajo.
- Artista 2: Materialización de la idea; puesta en común del trabajo.

## 7.2. Qué se puede mejorar
- Desarrollador 1: Adecuación del tamaño del proyecto al tiempo disponible; diseño inicial de las características del videojuego.
- Desarrollador 2: Continuidad en el trabajo; pruebas de los avances en el desarrollo.
- Desarrollador 3: Organización para evitar acumulación de tareas; testings en general, destacando los últimos niveles.
- Desarrollador 4: Desarrollo inicial sólido del GDD (incluyendo planificación y descripción de la estructura del código en TDD o similas; revisión profunda de fallos y búsqueda de soluciones profundas.
- Artista 1: Pruebas y control de calidad; gestión de crisis y planificación de contingencias.
- Artista 2: Planificación de las dimensiones del proyecto; pruebas de testing más frecuentes en etapas tempranas.

## 7.3. Desarrollo de ideas
En el apartado de "Qué ha ido bien", el acertado reparto de tareas al inicio del proyecto ha sido fundamental para el éxito del equipo. La consideración de las fortalezas individuales de cada miembro permitió una asignación equitativa de responsabilidades, dividiéndose eficientemente en dos bloques clave: arte y programación. Este enfoque estratégico no solo optimizó el rendimiento, sino que también demostró sensibilidad ante las necesidades específicas de cada área. La ponderación de la carga de trabajo fue una prioridad, asignando un mayor número de colaboradores al bloque que exigía mayor atención, como fue el caso de la programación con un equipo conformado por cuatro personas, mientras que el bloque de arte contó con dos talentosos integrantes.

La comunicación interna se destacó como otro pilar del éxito, utilizando herramientas como Microsoft Teams para reuniones planificadas y Whatsapp para interacciones menos urgentes. Esta diversificación en canales aseguró una conectividad constante, adaptándose a las demandas tanto en tiempo real como de manera más asincrónica. Además, la apertura a la colaboración y la puesta en común de ideas propiciaron un ambiente creativo y productivo. La materialización de estas ideas resultó en un producto final que no solo cumplió con las expectativas iniciales, sino que también satisfizo las visiones individuales de cada miembro del equipo.

Por otro lado, al abordar "Qué se puede mejorar", se evidenció una oportunidad de crecimiento en el área de testing. La limitada ejecución de esta fase, impulsada principalmente por restricciones temporales, generó dificultades en la detección de fallos, especialmente aquellos que se manifiestan en sesiones de juego prolongadas o en niveles más avanzados. Esta reflexión destaca la importancia de otorgarle a la fase de testing la atención y el tiempo necesario para garantizar la calidad y estabilidad del producto final.

Asimismo, la planificación del proyecto emergió como otro punto crítico a mejorar. A pesar de alcanzar los objetivos fundamentales y lograr un producto jugable y atractivo, la falta de tiempo impidió la inclusión de aspectos esenciales que, en un principio, se consideraban cruciales. Una gestión más efectiva del tiempo habría permitido la integración de estas características, contribuyendo a un resultado aún más completo y satisfactorio.

Finalmente, se identificó la falta de continuidad en el trabajo como un desafío. La distribución desigual de las cargas laborales, concentrándose especialmente en las semanas previas a las fechas de entrega, evidenció la necesidad de un balance más equitativo a lo largo del proceso de desarrollo. Un enfoque más uniforme y sostenible en el tiempo contribuiría a evitar picos de estrés y garantizaría una mayor consistencia en la calidad del trabajo entregado.

# 8. Plan de Marketing
A continuación, se presenta el Plan de Marketing estratégico diseñado para nuestro videojuego, Ace Voyage, un juego educativo de gran envergadura.
Este documento detalla una estrategia integral que abarca desde la consolidación de nuestra presencia en redes sociales hasta la implementación de campañas pagadas durante los próximos 2 años.
Cabe destacar que este plan está concebido como una guía adaptable destinado a mantener el ímpetu y la visibilidad de Ace Voyage, respondiendo a las dinámicas cambiantes del mercado y las expectativas de la audiencia.

## 8.1. Dónde estamos
### 8.1.1. Análisis DAFO (Debilidades, Amenazas, Fortalezas y Oportunidades)
 *- Debilidades (D):*
 
1. Recursos Limitados: Ace Voyage se enfrenta a la realidad de recursos financieros y humanos limitados. Este desafío podría influir en el ritmo de desarrollo y la profundidad de ciertos aspectos del juego. La gestión eficiente de estos recursos será clave.
2. Competencia en el Mercado: Ingresar al mercado de videojuegos, el cual, actualmente, es altamente competitivo, plantea el desafío de destacar entre una gran variedad de títulos similares. La diferenciación efectiva y estrategias de marketing creativas serán esenciales para captar la atención de la audiencia.

 *- Amenazas (A):*
   
1. Rápidos Cambios Tecnológicos: La rápida evolución de la tecnología puede hacer que Ace Voyage quede obsoleto rápidamente si no se mantiene actualizado. La adaptabilidad a los avances tecnológicos será fundamental para mantener la relevancia a lo largo del tiempo.
2. Expectativas del Público: Las altas expectativas de los jugadores pueden convertirse en una amenaza si no se cumplen. La calidad y coherencia en el juego serán cruciales para evitar la decepción de la audiencia.

 *- Fortalezas (F):*
 
 1. Concepto Único: La combinación de acción, puzles y elementos educativos en Ace Voyage constituye una fortaleza única. Este enfoque innovador tiene el potencial de atraer a una audiencia diversa, desde jugadores casuales hasta aquellos interesados en la educación.
2. Enfoque en Pensamiento Computacional: La orientación educativa del juego puede ser una ventaja distintiva. En un mercado donde el desarrollo de habilidades cognitivas es valorado, Ace Voyage puede destacar al proporcionar una experiencia de juego que también estimula el pensamiento computacional.

 *- Oportunidades (O):*
 
1. Mercado en Crecimiento de Juegos Educativos: Con el creciente interés en los juegos educativos, Ace Voyage tiene la oportunidad de posicionarse como una opción atractiva para padres y educadores. Aprovechar este mercado en expansión podría ser clave para el éxito del juego.
2. Colaboraciones y Asociaciones: Explorar colaboraciones con instituciones educativas o asociaciones con influencia en el ámbito educativo puede ampliar la visibilidad y aceptación de Ace Voyage, fortaleciendo así la credibilidad del juego y permitiendo llegar a audiencias específicas.

![Análisis DAFO](/images/analisis_DAFO.png)

> *Análisis DAFO*

### 8.1.2. Público objetivo
Ace Voyage tiene un público objetivo muy específico: niños entre 3 y 12 años que buscan una experiencia de juego estimulante y divertida mientras desarrollan y mejoran sus habilidades de pensamiento computacional. Este grupo demográfico abarca un espectro clave de desarrollo cognitivo y educativo, donde la atención a la diversión y el aprendizaje se entrelazan de manera armoniosa.

 *- Niños de 3 a 12 años:* El núcleo de nuestro público objetivo son los niños de edades comprendidas entre 3 y 12 años. Este rango abarca desde los primeros años de la infancia hasta la preadolescencia, etapa crucial para el desarrollo cognitivo. Ace Voyage está diseñado para ser tanto educativo como emocionante, adaptándose a distintos niveles de habilidad y proporcionando desafíos graduales para impulsar el pensamiento lógico y las habilidades de resolución de problemas.

 *- Padres de los Niños:* Aunque los niños son la audiencia principal, Ace Voyage reconoce la influencia fundamental de los padres en las decisiones de entretenimiento de sus hijos. Los padres buscan, no solo juegos atractivos, sino también experiencias educativas que aporten valor al desarrollo de sus hijos. Ace Voyage ofrece un equilibrio único entre diversión y aprendizaje, proporcionando a los padres la tranquilidad de que sus hijos están participando en una actividad beneficiosa.

 *- Profesores y Escuelas:* Ace Voyage se presenta como una herramienta educativa valiosa para profesores y escuelas que buscan enriquecer el aprendizaje de sus estudiantes a través de la tecnología. Al proporcionar una plataforma que fomenta el pensamiento computacional, el juego se convierte en un recurso didáctico atractivo que complementa los métodos de enseñanza tradicionales. La adaptabilidad del juego a diferentes niveles de habilidad lo convierte en un recurso versátil para la integración en entornos educativos.

### 8.1.3. Propuesta de valor
*¿Qué es Ace Voyage?*

Ace Voyage no es simplemente un juego, es una puerta de entrada a un medio donde la diversión y el aprendizaje convergen de manera única. Diseñado para niños de 3 a 12 años, Ace Voyage ofrece una experiencia envolvente que va más allá del entretenimiento convencional.

*¿Por qué es especial?*

1. Aventuras Educativas: Ace Voyage te sumerge en emocionantes desafíos mientras desarrollas habilidades clave de pensamiento computacional. Cada misión estimula la lógica y la resolución de problemas de manera divertida y accesible.
2. Juego Adaptativo: Desde pequeños exploradores hasta jóvenes genios, Ace Voyage se adapta a todos los niveles de habilidad. Los niños avanzan a su propio ritmo, brindándoles una experiencia personalizada que se ajusta a sus necesidades y desafíos individuales.
3. Participación de los Padres: Ace Voyage no solo involucra a los niños, sino que también incluye a los padres en la experiencia. Con herramientas para el seguimiento del progreso, los padres pueden estar seguros de que sus hijos están aprendiendo de manera significativa mientras se divierten.
4. Colaboración con Escuelas: Ace Voyage se presenta como una herramienta educativa efectiva para aulas digitales. Profesores y escuelas pueden integrar el juego en sus planes de estudio para enriquecer el aprendizaje y fomentar el pensamiento computacional.

#### 8.1.3.1. Lienzo de Propuesta de valor
La Propuesta de Valor de Ace Voyage se define a través de un lienzo estratégico que fusiona dos elementos cruciales: el perfil del cliente y el mapa de valor. Este enfoque integral nos permite comprender a nuestros jugadores y destacar cómo creamos valor a través de nuestros productos y servicios.

![Lienzo Propuesta de valor](/images/propuestaDeValor.png)

> *Lienzo Propuesta de valor*

1. Perfil del Cliente: Descubriendo a nuestros jugadores

El perfil del cliente se divide en tres áreas fundamentales:
   - Los Trabajos del Cliente:
        1. Funcionales: Nuestros jugadores desempeñan roles de exploradores y solucionadores de desafíos, utilizando el juego como herramienta de aprendizaje.
        2. Sociales: Buscan destacarse entre amigos al convertirse en héroes de la historia educativa que están construyendo.
        3. Emocionales: Experimentan alegría, satisfacción y éxito al enfrentar y superar desafíos educativos.
    
   - Frustraciones del Cliente:
        1.	Características, Problemas y Resultados no deseados: Evitar el aburrimiento en actividades educativas es crucial para mantener el interés.
        2.	Obstáculos: La falta de desafíos interesantes puede conducir a la desconexión del aprendizaje.
        3.	Riesgos: Existe el riesgo de perder la conexión emocional con el proceso educativo.
        
   - Alegrías del Cliente:
        1.	Necesarias: Buscan un aprendizaje significativo y divertido.
        2.	Esperadas: Desean el desarrollo de habilidades cognitivas a través de experiencias educativas y divertidas.
        3.	Deseadas: Anhelan el reconocimiento por los logros educativos.
        4.	Inesperadas: Disfrutan de la colaboración con amigos durante el juego.

        
2. Mapa de Valor: Creando Experiencias Únicas
   
El mapa de valor se compone de tres áreas estratégicas:
   - Productos o Servicios:
        1. Ace Voyage: Un juego educativo inmersivo y emocionante que fusiona aprendizaje y entretenimiento.
        2. Módulos de Aprendizaje Personalizados: Contenidos adaptados a la edad y habilidades de cada jugador.
           
   - Aliviadores de Frustraciones:
        1.	Desafíos Educativos: Misiones intrigantes que evitan el aburrimiento y mantienen el interés.
        2.	Progresión Adaptable: Sistema que se adapta a diferentes niveles de habilidad para una superación personal continua.
           
   - Creadores de Alegrías:
        1.	Recompensas Educativas: Logros que refuerzan el aprendizaje y reconocen los esfuerzos educativos.
        2.	Interacción Social: Posibilidad de colaborar y competir con amigos en tiempo real.

        
3. Encaje: Donde Nuestra Oferta Coincide con sus Necesidades

    1. Desafíos Importantes: Nuestra oferta aborda desafíos educativos cruciales para mantener la relevancia y el interés del jugador.
    2. Alivio de Frustraciones: Adaptamos Ace Voyage para abordar diferentes niveles de habilidad y preferencias de aprendizaje.
    3. Generación de Alegrías: Ace Voyage busca, no solo satisfacer, sino superar las expectativas de nuestros jugadores, ofreciendo reconocimiento social y logros educativos.

### 8.1.4. Competencia
Ace Voyage se enfrenta a un mercado educativo y de entretenimiento diverso, entre los que destacan:
1. Aplicaciones Educativas Convencionales: Plataformas ampliamente utilizadas en el ámbito educativo que ofrecen contenido educativo, pero con enfoque menos lúdico y atractivo para los niños.
2. Plataformas de Streaming de Contenido Infantil: Ofrecen una variedad de programas educativos para niños, pero carecen de la interactividad y la personalización presentes en Ace Voyage.
    
*Ventajas Competitivas de Ace Voyage:*

1. Enfoque holístico: Integración de educación y entretenimiento de manera equilibrada, adaptada a las habilidades individuales de cada jugador.
2. Gamificación innovadora: Uso creativo de la gamificación para hacer que el aprendizaje sea divertido y motivador, incentivando la participación continua.
3. Narrativa inmersiva: Una historia cautivadora que envuelve a los jugadores en un viaje educativo único, fomentando la participación a largo plazo.
4. Personalización educativa: Módulos de aprendizaje adaptativos que se ajustan al progreso y nivel de habilidad de cada jugador, asegurando un aprendizaje efectivo.
5. Recompensas significativas: Reconocimiento y recompensas educativas que refuerzan positivamente el progreso y los logros de los jugadores.

Así, con este análisis se destacan las fortalezas distintivas de Ace Voyage en el mercado educativo y de entretenimiento, proporcionando una propuesta única que se destaca entre la competencia.

## 8.2. Objetivos
### 8.2.1. Comunidad
Uno de los objetivos de nuestro proyecto es la creación y consolidación de una comunidad comprometida compuesta por jugadores, educadores y padres, todos ellos unidos por la experiencia única ofrecida por Ace Voyage. Para lograr este propósito, debemos destacar diversos aspectos clave que giran en torno a la interacción social, el aprendizaje y la participación activa.

*Estrategias:*

1. Establecer canales de comunicación abiertos, como foros en línea y redes sociales (X, Instagram, Youtube, Itch.io), para facilitar la interacción entre la comunidad.
2. Organizar eventos y desafíos comunitarios para incentivar la participación y el intercambio de experiencias.
3. Colaborar con educadores para ampliar la visibilidad y la participación en la comunidad.

*Métricas de éxito:*

1. Crecimiento mensual de usuarios activos en la comunidad.
2. Participación en eventos comunitarios y desafíos.
3. Nivel de interacción en las redes sociales y foros.

### 8.2.2. Leads
Es muy importante para nosotros establecer y expandir una base sólida de leads cualificados que muestren interés en Ace Voyage. Este propósito abarca tanto a los usuarios directos como a educadores y padres, reconociendo la diversidad de nuestra audiencia y buscando crear conexiones significativas con cada segmento. Para lograr este objetivo, implementamos estrategias específicas:

*Estrategias:*

1. Implementar campañas de marketing digital que destaquen los aspectos educativos y de entretenimiento del juego.
2. Ofrecer demostraciones gratuitas y contenido exclusivo para educadores y padres.
3. Establecer programas de afiliados que incentiven a los usuarios a referir a otros.

*Métricas de éxito:*

1. Tasa de conversión de visitantes a leads.
2. Crecimiento mensual de leads a través de campañas y afiliados.
3. Participación en eventos educativos y colaboraciones con instituciones.

### 8.2.2. Ventas (Compra, Backer)
Nuestra meta es maximizar las ventas de Ace Voyage, empleando una estrategia integral que abarque tanto las compras directas como las campañas de financiamiento colectivo con backers. Para alcanzar este objetivo, hemos desarrollado un plan estratégico que se enfoca en varios aspectos clave:

*Estrategias:*

1. Ofrecer promociones y descuentos para la adquisición directa del juego.
2. Diseñar campañas de Kickstarter u otras plataformas de crowdfunding para financiar nuevas funciones y expansiones.
3. Colaborar con minoristas y plataformas de distribución para ampliar la disponibilidad del juego.

*Métricas de Éxito:*

1. Volumen de ventas directas e indirectas.
2. Financiamiento exitoso de campañas de crowdfunding.
3. Retención de backers a largo plazo y participación en actualizaciones y expansiones.
    
Estos objetivos estratégicos hacen que Ace Voyage sea una experiencia educativa y de entretenimiento integral, buscando no solo crecer en términos de usuarios, sino también en términos de participación y compromiso de la comunidad.

## 8.3. Estrategias y tácticas
En un mundo digitalmente interconectado, la promoción efectiva de un estudio y su proyecto es fundamental para alcanzar el éxito. En este contexto, nos enfocamos en dos objetivos claves: dar a conocer nuestro estudio y dirigir a los usuarios hacia una campaña crucial en Kickstarter. Nuestra estrategia se centra en aprovechar el poder de las redes sociales como un vehículo dinámico para la difusión y participación.

### 8.3.1. Objetivo 1: Dar a Conocer el Estudio

*¿Cómo lo hacemos?*

Para lograr este objetivo, se ha trazado una estrategia integral que comienza con el establecimiento de perfiles en plataformas clave como Instagram, X e Itch.io. Estas plataformas no solo sirven como puntos de contacto directo con la audiencia, sino que también ofrecen un espacio valioso para compartir insights sobre nuestro proceso de desarrollo, avances del juego y detalles detrás de escena. La creación de contenido atractivo, incluyendo imágenes y vídeos impactantes, jugará un papel esencial para captar la atención y generar una conexión significativa con nuestra audiencia.

### 8.3.2. Objetivo 2: Llevar usuarios a la campaña de Kickstarter

*¿Cómo lo hacemos?*

Una vez establecida una presencia sólida en redes sociales, la atención se centra en el segundo objetivo: dirigir a los usuarios hacia nuestra campaña en Kickstarter. Se implementarán campañas publicitarias pagadas en redes sociales, segmentando anuncios para llegar específicamente a nuestro público objetivo, que incluye padres, educadores y jugadores ávidos. El contenido exclusivo creado específicamente para redes sociales generará expectación y curiosidad en torno a la campaña de Kickstarter.

En conjunto, estas estrategias y tácticas están diseñadas para construir una presencia sólida en redes sociales, al tiempo que canalizan de manera efectiva la atención de la audiencia hacia nuestra campaña en Kickstarter. La combinación de contenido relevante y publicidad contriburá en alcanzar estos objetivos de manera efectiva.

## 8.4. Plan
ChupChup Studios busca destacar en la educación infantil, específicamente en el desarrollo del pensamiento computacional para niños de 8 a 12 años. Queremos proporcionar una herramienta educativa innovadora y emocionante, garantizando que cada niño tenga acceso a una educación tecnológica de alta calidad, por lo que nos comprometemos a fomentar el pensamiento computacional desde temprana edad, creando así las bases para un futuro digital inclusivo y equitativo.
El plan que se detalla a continuación está diseñado para cumplir con cada una de nuestras metas durante los dos próximos años, siendo el reflejo de nuestro compromiso con este proyecto.

### 8.4.1. Año 1 (2024): Consolidación y Comunidad

![Calendario 2024](/images/marketing_2024.png)

> *Calendario planificación de marketing 2024*

#### 8.4.1.1. Trimestre 1: Meses 1-3

- Qué:
1. Consolidación en Plataformas de Juego: Obtener reseñas y retroalimentación de los primeros usuarios. Ofrecer actualizaciones y mejoras según los comentarios.
2. Comunicación Constante: Mantener a la comunidad informada sobre futuras actualizaciones, eventos y contenido adicional.
3. Expansión de la Comunidad: Implementar programas de referidos y recompensas para aumentar la base de usuarios.
4. Colaboraciones: Explorar colaboraciones con otros estudios indie para promover la comunidad de juegos.
 
- Cómo:
1. Utilizar encuestas y comentarios directos de los usuarios para identificar áreas de mejora.
2. Publicar regularmente en redes sociales y enviar boletines informativos.
3. Lanzar incentivos atractivos para programas de referidos.
4. Iniciar conversaciones y colaboraciones a través de eventos y plataformas especializadas.
   
- Medio:
Plataformas de juego, redes sociales, correos electrónicos.
   
- Quién:
Equipo de desarrollo, gestor de comunidad, especialistas en marketing y relaciones públicas.

- Dónde:
Plataformas de juego, redes sociales (Facebook, Twitter, Instagram), eventos de la industria.

- Cuándo:
Desde el lanzamiento del juego hasta el tercer mes.

- KPIs:
1. Número de reseñas y calificaciones positivas.
2. Tasa de participación en programas de referidos.
3. Crecimiento mensual de la base de usuarios.
4. Número de colaboraciones establecidas.
   
#### 8.4.1.2. Trimestre 2: Meses 4-6

- Qué:
1. Eventos y Ferias Virtuales: Participar en eventos de la industria para aumentar la visibilidad.
2. Contenido Exclusivo: Desarrollar contenido exclusivo para jugadores leales, como desafíos, eventos en el juego y recompensas.
3. Expansión de Plataformas: Lanzar versiones del juego para nuevas plataformas según la demanda de la audiencia.
   
- Cómo:
1. Diseñar stands virtuales para eventos y participar en charlas y paneles.
2. Crear contenido adicional atractivo y recompensar a los jugadores activos.
3. Evaluar la demanda de nuevas plataformas y adaptar el juego en consecuencia.
   
- Medio:
Plataformas de juego, eventos virtuales, redes sociales.

- Quién:
Equipo de desarrollo, gestor de eventos, especialistas en contenido y adaptación.

- Dónde:
Eventos de la industria, plataformas de juego existentes, nuevas plataformas.

- Cuándo:
Desde el cuarto hasta el sexto mes.

- KPIs:
1. Participación y visibilidad en eventos virtuales.
2. Número de jugadores activos participando en eventos exclusivos.
3. Éxito de la expansión a nuevas plataformas.
   
#### 8.4.1.3. Trimestre 3: Meses 7-9

- Qué:
1. Contenido de Temporada: Introducir actualizaciones de temporada con contenido temático.
2. Competiciones y Torneos: Organizar competiciones en el juego para mantener el interés y la participación.
3. Campañas en Redes Sociales: Ejecutar campañas creativas en redes sociales para fomentar la participación de la comunidad.
   
- Cómo:
1. Planificar actualizaciones temáticas y eventos estacionales.
2. Diseñar competiciones y torneos emocionantes con recompensas significativas.
3. Desarrollar campañas interactivas en redes sociales para incentivar la participación.
   
- Medio:
Plataformas de juego, redes sociales, eventos en el juego.

- Quién:
Equipo de desarrollo, gestor de redes sociales, organizadores de eventos.

- Dónde:
Plataformas de juego, redes sociales.

- Cuándo:
Desde el séptimo hasta el noveno mes.

- KPIs:
1. Participación en eventos de temporada.
2. Número de jugadores participando en competiciones.
3. Impacto y participación en campañas de redes sociales.

#### 8.4.1.4. Trimestre 4: Meses 10-12

- Qué:
1. Aniversario del Juego: Celebrar el primer aniversario con eventos especiales, regalos y contenido exclusivo.
2. Encuestas de Satisfacción: Obtener comentarios detallados a través de encuestas para mejorar la experiencia del usuario.
3. Preparación para Año 2: Evaluar el rendimiento del primer año y planificar estrategias para el próximo año.

- Cómo:
1. Organizar eventos festivos y recompensas especiales para los jugadores.
2. Enviar encuestas detalladas a la comunidad para obtener comentarios específicos.
3. Revisar el rendimiento del primer año y establecer metas para el próximo.
   
- Medio:
Plataformas de juego, encuestas en línea, eventos en el juego.

- Quién:
Equipo de desarrollo, gestor de comunidad, analistas de datos.

- Dónde:
Plataformas de juego, encuestas en línea.

- Cuándo:
Desde el décimo hasta el duodécimo mes.

- KPIs:
1. Participación y satisfacción en eventos de aniversario.
2. Respuestas y comentarios recopilados en las encuestas.
3. Planificación estratégica para el próximo año.

### 8.4.2. Año 2 (2025): Expansión y Monetización

![Calendario 2025](/images/marketing_2025.png)

> *Calendario planificación de marketing 2025*

#### 8.4.2.1. Trimestre 1: Meses 13-15

**1. Expansión Global:**
- Qué: Localizar el juego para llegar a audiencias internacionales.
- Cómo: Identificar mercados clave, traducir contenido y adaptar estrategias de marketing.
- Medio: Plataformas de distribución internacional, servicios de traducción, estrategias de marketing global.
- Quién: Equipo de localización, marketing internacional y desarrollo.
- Dónde: Mercados internacionales identificados.
- Cuándo: Durante el trimestre 1.
- KPIs: Número de descargas en nuevos mercados, aumento en la base de usuarios global.

**2. Incorporación de Elementos In-App:**
- Qué: Introducir elementos cosméticos y funciones premium para la monetización.
- Cómo: Diseñar elementos atractivos, actualizar la aplicación con nuevas funciones y opciones de compra.
- Medio: Actualizaciones en la aplicación, tienda in-app.
- Quién: Equipo de desarrollo y diseño.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 1.
- KPIs: Ingresos generados a través de elementos in-app, tasa de conversión.

**3. Campañas de Publicidad Pagada:**
- Qué: Aumentar la visibilidad mediante campañas pagadas en diversas plataformas.
- Cómo: Diseñar anuncios creativos, segmentar audiencias, lanzar campañas publicitarias.
- Medio: Publicidad en redes sociales.
- Quién: Equipo de marketing digital.
- Dónde: Plataformas publicitarias clave.
- Cuándo: Durante el trimestre 1.
- KPIs: Aumento en la notoriedad de la marca, clics y conversiones publicitarias.


#### 8.4.2.2. Trimestre 2: Meses 16-18

**1. Colaboraciones Estratégicas:**
- Qué: Colaborar con otros juegos para expandir la visibilidad.
- Cómo: Establecer acuerdos de colaboración, participar en eventos conjuntos.
- Medio: Acuerdos de colaboración, participación en eventos de la industria.
- Quién: Equipo de relaciones públicas y marketing.
- Dónde: Plataformas colaborativas y eventos de la industria.
- Cuándo: Durante el trimestre 2.
- KPIs: Alcance de colaboraciones, aumento de la base de usuarios.

**2. Eventos Especiales Mensuales:**
- Qué: Implementar eventos mensuales en el juego para retener y atraer a nuevos jugadores.
- Cómo: Crear contenido especial, ofrecer recompensas y promociones.
- Medio: Actualizaciones regulares del juego, promociones especiales.
- Quién: Equipo de eventos y desarrollo.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 2.
- KPIs: Participación en eventos mensuales, retención de jugadores.

**3. Programas de Fidelidad:**
- Qué: Establecer programas de fidelidad para recompensar a los jugadores activos.
- Cómo: Crear sistemas de recompensas, lanzar programas de lealtad.
- Medio: Programas integrados en la aplicación, recompensas exclusivas.
- Quién: Equipo de desarrollo y relaciones con el cliente.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 2.
- KPIs: Participación en programas de fidelidad, retención de usuarios leales.
  
#### 8.4.2.3. Trimestre 3: Meses 19-21

**1. Actualizaciones Importantes:**
- Qué: Lanzar actualizaciones significativas con nuevas funciones y contenido.
- Cómo: Evaluar comentarios de usuarios, desarrollar nuevas funciones, lanzar actualizaciones.
- Medio: Actualizaciones en la aplicación, comunicados de prensa.
- Quién: Equipo de desarrollo y marketing.
- Dónde: Plataformas de distribución, redes sociales.
- Cuándo: Durante el trimestre 3.
- KPIs: Evaluación de comentarios de los usuarios, aumento en la retención.

**2. Campañas de Retención:**
- Qué: Implementar estrategias para retener a los jugadores existentes y mantener su interés.
- Cómo: Crear contenido exclusivo, ofrecer recompensas.
- Medio: Mensajes en la aplicación, contenido exclusivo.
- Quién: Equipo de desarrollo.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 3.
- KPIs: Retención mensual de usuarios, participación en contenido exclusivo.

**3. Monetización Justa:**
- Qué: Ajustar estrategias de monetización según los comentarios de la comunidad.
- Cómo: Realizar encuestas de retroalimentación, ajustar configuraciones de compra.
- Medio: Encuestas de retroalimentación, ajustes en la aplicación.
- Quién: Equipo de monetización y desarrollo.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 3.
- KPIs: Mejoras en la satisfacción del usuario, aumento en los ingresos.

#### 8.4.2.4. Trimestre 4: Meses 22-24

**1. Celebración del Segundo Aniversario:**
- Qué: Organizar eventos especiales y recompensas para celebrar el segundo año.
- Cómo: Planificar eventos festivos, regalos atractivos y contenido exclusivo.
- Medio: Plataformas de juego, eventos en el juego.
- Quién: Equipo de eventos y desarrollo.
- Dónde: Dentro de la aplicación.
- Cuándo: Durante el trimestre 4.
- KPIs: Participación y satisfacción en eventos de aniversario.

**2. Encuesta de Satisfacción 2.0:**
- Qué: Obtener comentarios adicionales y ajustar estrategias para el próximo año, si es preciso.
- Cómo: Enviar encuestas detalladas, analizar respuestas y realizar ajustes.
- Medio: Encuestas en línea, análisis de datos.
- Quién: Equipo de desarrollo y análisis.
- Dónde: Fuera de la aplicación (encuestas en línea).
- Cuándo: Durante el trimestre 4.
- KPIs: Respuestas y comentarios recopilados en las encuestas.

**3. Planificación a Largo Plazo:**
- Qué: Iniciar la planificación para el tercer año, considerando nuevas funciones, expansiones y mejoras, si es preciso.
- Cómo: Evaluar el rendimiento del segundo año, identificar áreas de crecimiento, iniciar la planificación estratégica.
- Medio: Revisión de datos, reuniones estratégicas.
- Quién: Equipo de liderazgo y desarrollo.
- Dónde: Oficinas de la empresa.
- Cuándo: Durante el trimestre 4.
- KPIs: Plan estratégico para el tercer año establecido.

### 8.4.3. Planificación semana del lanzamiento
A continuación, se detalla la planificación de publicidad y marketing para las semana post-lanzamiento de Ace Voyage, detallando el plan de publicaciones en las redes sociales de Instagram y X del estudio.

![Planificación semana (post)Lanzamiento](/images/semanaClave_marketing.png)

> *Calendario planificación de marketing semana del 11 al 17*

**Día 1: Anuncio del lanzamiento del juego**

*Instagram:*
1.	Publicar una imagen teaser del juego con el logo y el protagonista Patt.
2.	Acompañar la imagen con una descripción intrigante sobre la historia y la mecánica del juego.
3.	Utilizar hashtags populares relacionados con juegos, puzles y educación.

*X:*
1.	Twittear el mismo teaser con un breve texto descriptivo.
2.	Incluir hashtags relevantes.
   
**Día 2: Arte escenarios y Detrás de Escena**

*Instagram:*
1.	Compartir fotos de los escenarios del juego.
2.	Animar a la participación de los seguidores con preguntas sobre el diseño.

*X:*
1.	Twittear las imágenes de los escenarios del juego con una pregunta para fomentar la participación.
2.	Responder a los comentarios y retuitear menciones positivas.
   
**Día 3: Introducción al Pensamiento Computacional**

*Instagram:*
1.	Realizar una publicación explicando qué es el pensamiento computacional relacionándolo con Ace Voyage.
2.	Compartir varios vídeos breves en las historias del proceso creativo y del desarrollo de los diferentes biomas del videojuego.

*X:*
1.	Compartir un tweet sobre el pensamiento computacional relacionándolo con Ace Voyage.
2.	Utilizar el hashtag #PiensaConPatt para que la comunidad lo utilice.
   
**Día 4: Encuesta Concept Arts de Enemigos**

*Instagram:*
1.	Mostrar concept arts de los enemigos del juego por historias.
2.	Organizar una encuesta en las historias para que los seguidores elijan su enemigo favorito.
3.	Publicar el resultado al final del día.

*X:*
1.	Twittear imágenes de los concept arts de los enemigos.
2.	Utilizar el hashtag #EnemigosDePatt para intentar que la comunidad lo emplee.

**Día 5: Demostración del Juego**

*Instagram:*
1.	Publicar un breve vídeo de gameplay o un gif del juego en acción.
2.	Pedir a los seguidores que comenten lo que piensan.
   
*X:*
1.	Twittear el vídeo o gif, mencionando las características destacadas.
2.	Responder a comentarios y retuitear menciones positivas.

**Día 6: Entrevista con el Equipo de Desarrollo**

*Instagram:*
1.	Realizar una serie de publicaciones con entrevistas al equipo, ya sean escritas o grabadas. También se puede invitar a los seguidores a que hagan preguntas por stories para que los desarrolladores las contesten, y así conectar con el público.
2.	Destacar la pasión del equipo por el proyecto y sus roles.
   
*X:*
1.	Compartir enlaces a las publicaciones de Instagram.
2.	Incluir preguntas abiertas sobre el juego para que los seguidores participen.

**Día 7: Agradecimiento por el apoyo**

*Instagram:*
1.	Compartir una imagen que refleje el éxito del lanzamiento y agradecer a la comunidad por su apoyo. Incluir capturas de pantalla de comentarios positivos y mencionar aspectos destacados del juego.
2.	Publicar historias breves compartiendo mensajes de agradecimiento, capturas de pantalla de jugadores y de los comentarios más divertidos o emotivos.
   
*X:*
1.	Publicar un tweet celebrando el lanzamiento exitoso de Ace Voyage. Compartir estadísticas positivas, logros o menciones notables que se hayan recibido.
2.	Responder a comentarios en Twitter expresando gratitud y continuando las conversaciones con la comunidad.

## 8.5. Análisis
El plan de marketing de Ace Voyage presenta diversas fortalezas que respaldan su enfoque integral. La diversificación de canales, que incluye distintas redes sociales y campañas pagadas en un futuro, revela una comprensión profunda del marketing digital. Además, la creación y distribución de contenido relevante en las redes sociales demuestra una alineación con las tendencias actuales, promoviendo la participación de la audiencia.

No obstante, existen oportunidades para mejorar. Explorar colaboraciones estratégicas con estudios de juegos podría ampliar la visibilidad y llegar a audiencias más amplias. Así mismo, establecer una programación de contenido más estructurada en redes sociales podría aumentar la anticipación y participación de la audiencia.

El análisis identifica desafíos, como la medición precisa de resultados en campañas pagadas, debiéndose incorporar enfoques de análisis más detallados y herramientas específicas para abordar esta limitación. Además, la sostenibilidad a largo plazo es esencial, por lo que se debe evaluar constantemente la efectividad de las estrategias.

Por otro lado, las amenazas consideradas incluyen posibles cambios en los algoritmos de redes sociales y la competencia creciente en publicidad pagada. Diversificar las estrategias más allá de las redes sociales y optimizar constantemente las campañas son medidas clave para mitigar estos riesgos.

Es importante, para evaluar la efectividad de cada canal y ajustar estrategias según los resultados, implementar un análisis continuo de los resultados.

Además, fomentar la interactividad en redes sociales mediante encuestas, preguntas y desafíos puede aumentar la participación de la audiencia, monitoreando constantemente las tendencias de la industria para adaptar las estrategias y mantener la relevancia.

Para la planificación futura, se pueden explorar nuevas formas de contenido, como transmisiones en vivo y eventos en línea, para mantener el interés de la audiencia. Considerar la expansión a nuevos mercados mediante campañas específicas y localización del contenido también podría ser beneficioso.

La adaptabilidad y la respuesta ágil a los cambios del mercado serán esenciales para el éxito continuo del plan.
