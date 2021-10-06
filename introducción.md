# Introducción

El ajedrez es un juego que enfrenta las ideas de sus oponentes. 

Nadie sabe quién inventó el juego. La idea más aceptada es que es un descendiente de `chataranga`, un juego tradicional de la India occidental, en torno a los siglos 6 y 4 a.C. El juego no llegaría a Europa hasta la Edad Media tardía y a América un par de siglos después. 

El ajedrez comprende varias áreas de pensamiento referentes a distintos aspectos del juego.

*********************************************************************

# Términos

## Estructura

Las partidas de ajedrez suelen durar entre 30 y 50 movimientos y se dividen en 3 fases:

- `Apertura`: primeros 10 - 15 movimientos. Los jugadores reúnen sus fuerzas y las preparan para la acción. El objetivo es desarrollar las piezas y conseguir generar situaciones que se puedan expotar en el medio juego. Suelen ser muy teóricos (hay un repertorio de aperturas estudiadas para blancas y negras que hay que aprender de memoria).

	En partidas amateur, si uno de los bandos se queda muy atrás en desarollo y olvida proteger a su rey, queda expuesto a mates tempranos. 

- `Medio juego`: una extensión de la apertura; el objetivo es expotar al máximo las situaciones generadas. Son más abiertos que las aperturas, no habiendo "tipologías de medio juego" que se puedan estudiar. En cambio, hay directrices posicionales generales.

- `Endgame`: cuando el tablero se queda medio vacío de piezas, anunciando que se acerca el final. Al igual que las aperturas, son muy teóricos y hay tipologías de endgame que se aprenden de memoria.

No hay un límite claro entre el fin de una fase y el inicio de la siguiente. Se trata de una división arbitraria y variable en cada partida. De hecho, una partida no tiene por qué terminar en el endgame. Puede terminar en el opening (ej. mate pastor) o en el middlegame.

## Ventaja

Se puede deducir qué jugador va ganando antes del final de una partida. Existen varios elementos posicionales que indican la ventaja o desventaja de cierto jugador en cada posición de una partida.

Todos estos elementos están relacionados entre sí, y pueden cambiar con cada jugada de una partida. El `material`, el `espacio`, el `color` y la `estructura de peones` son ventajas más duraderas y permantentes, mientras que el resto suelen ser más temporales y efímeras.

Esta lista de elementos no es fija y cada autor tiene su propia versión ligeramente diferente:

#### Tiempo 

Significa dos cosas:

	- El tiempo del reloj de cada jugador en una partida.
	
	- El número de jugadas (o `tempos`) que necesita un jugador para llevar a cabo sus planes. 

Generalmente, si podemos hacer lo que nos plazca, es probable que vayamos ganando en tiempo. Si, por el contrario, tenemos que responder a lo que hace el oponente, no pudiendo hacer lo que queremos, probablemente estemos perdiendo en tiempo. Esto también se denomina `iniciativa`: poder atacar sin vernos obligados a defender.
		
Por ejemplo, si obligamos al rival a mover una de sus piezas a una casilla mala (dejándola inactiva) o de vuelta a la casilla de donde venía, estaremos ganando tiempo, porque el rival necesitará varios turnos para redirigir esa pieza a una casilla mejor. 

Intercambiar piezas puede ganar tiempo o perder tiempo. Si obligamos al rival a responder al intercambio empeorando su posición y ralentizando sus planes, ganamos tiempo. Si el intercambio refuerza la posición del rival, podemos perder tiempo.

```
Una táctica común es intercambiar piezas que están siendo amenazadas y sin defensa; de ese modo, nos quitamos de encima una de las amenazas sin perder tiempo. 

Este tipo de intercambio (y, en general, jugadas puntuales más o menos independientes del discurso del juego) se denomina Zwischenzug.
```

Hay varias normas generales relativas al tiempo y al intercambio:

- No intercambiar piezas desarrolladas por otras no desarrolladas.
- No hacer intercambios que favorezcan el desarrollo del rival.
- Hacer intercambios que ganen tiempo y evitar intercambios que lo pierdan.
		
Si no sacamos provecho del tiempo cuando lo tenemos (ej. por ir ganando al rival en `desarrollo`) es probable que el rival se recupere y acabemos perdiendo la ventaja.

```
Se denomina desarrollo al número de piezas movilizadas a una casilla activa. Por "casilla activa" se entiende aquella casilla donde la pieza contribuya al plan de ese bando. El desarrollo es deseable porque los planes más potentes son aquellos donde participan más piezas.
```
	
#### Espacio

El avance de los peones en el tablero (especialmente los centrales). Cuanto más avancemos los peones, más libertad de movimiento tendremos y más casillas controlaremos con el resto de piezas. Por el contrario, el jugador con desventaja en espacio estará más constreñido y tendrá menos movilidad. 

No obstante, el espacio tiene un precio: cuanto más se expande un jugador, más área tiene que defender y más vulnerable a ataques se vuelve. Hay que valorar si tenemos capacidad para defender una expansión antes de seguir anexionando territorio.

Las casillas más importantes de todo el tablero son las centrales: `e4`, `d4`, `e5` y `d5`. Se conoce como "centro ampliado" al centro sumado a las casillas que lo rodean (el cuadrado `c6` - `f3`). No es tan importante como el centro, pero también tiene gran relevancia.

El centro es importante porque son casillas que permiten movilizar piezas muy rápidamente de un lado a otro del tablero. Es decir, el jugador que domina el centro tiene más movilidad y más flexibilidad. Muchas aperturas tienen como objetivo controlar el centro lo más rápido posible.

Por el contrario, las piezas colocadas en los extremos del tablero suelen tener menos movilidad e influencia.

La forma más efectiva de obtener el centro es ocuparlo con peones y apoyar esos peones con otras piezas.

#### Material

El número de piezas que nos quedan, teniendo en cuenta su valor relativo. 

Ojo, porque este valor no quiere decir que una pieza sea siempre mejor que otra: hay posiciones en las que un caballo puede ser mucho más activo y letal que una torre rival, a pesar de que sus valores sean 3 y 5 respectivamente.

Por ejemplo: casi siempre un caballo y un alfil valen más que una torre y un peón, a pesar de que el valor de ambos suma 6 (3+3 y 5+1).

Si vamos ganando en material, nos interesa intercambiar piezas, abrir la posición y forzar la llegada al endgame lo antes posible. Cuantas menos piezas en el tablero, más acentuada será nuestra ventaja material.

Si vamos perdiendo en material, hay que evitar intercambios, cerrar la posición e intentar crear oportunidades de contrataque táctico. 

```
Intercambiar piezas del mismo valor no es recomendable si vamos ganando en material, si no mejoramos nuestra posición o empeoramos la del rival.
```

#### Estructura de peones

Una estructura de peones ventajosa es aquella que: 

	- No es fácil de eliminar y está bien defendida.
	- Es flexible y puede moverse conforme lo necesita. 
	- Defiende casillas clave en la posición
	- Defiende satisfactoriamente al rey.

```
Los peones son los mejores defensores gracias a que valen menos que el resto de piezas. 
```

Los peones a veces son denominados "el alma del ajedrez", porque todos los planes de ajedrez giran en torno a la colocación de los peones de ambos bandos. Los peones tienen 4 usos fundamentales:

- Atacar casillas (impidiendo que el enemigo las ocupe).
- Defender piezas.
- Como ariete para abrir la posición.
- Coronarse al final del tablero.

Hay que tener en cuenta que cada vez que un peón avanza, se crea al menos una debilidad, porque nunca más podrán defender las casillas que han dejado atrás. Eso significa que un mal movimiento de peón es una debilidad con lo que tendremos que lidiar toda la partida.

Como norma general es recomendable no mover los peones frente al rey una vez se ha enrocado a no ser que haya un buen motivo, ya que estaremos creando debilidades permanentes frente al rey, lo cual puede ser muy peligroso si no estamos cerca del `endgame`. 

Cuando se ha enrocado en el flanco de rey, esto es especialmente cierto para los peones de la columna `f`. Hay veces en las que será deseable hacer esto para avanzar con la torre que ha quedado en esa misma columna, pero hay que tener presente que el precio a pagar es el debilitamiento considerable de la seguridad del rey.

Otra norma general es no mover los peones de los extremos (columnas `a` y `h`) durante la apertura a no ser que haya un motivo de peso. Esto suele ser una pérdida de tiempo y un debilitamiento de la posición a largo plazo.

```
Las estructuras de peones suelen tener puntos débiles en la séptima fila,  y por ese motivo suele ser tan efectivo llevar a nuestras torres allí durante el medio juego. 
```

#### Seguridad del rey

Muy vinculada a la estructura de peones. Generalmente, un rey se considera "expuesto" si en la apertura o medio juego no está sólidamente defendido por peones. 

	En el endgame esto no aplica porque quedan pocas piezas en el tablero y el rey no corre peligro de mate incluso aunque no esté defendido por peones. Es más, en muchos endgame el rey sale de su guarida y participa en el ataque como una pieza más.

#### Color

Por último, también se considera que tiene cierta ventaja el jugador que juega con blancas porque decide la línea de aperturas que se va a jugar y tiene una pequeña iniciativa, lo que le da a a las negras una posición inicial momentánea de defensor. Esta ventaja es relativa y no suele considerarse tan relevante como las otras. Muchos jugadores prefieren jugar con negras.

En ajedrez, lo deseable es siempre ser el atacante, nunca el defensor. Los errores como defensor se pagan mucho más caro que los errores como atacante. En muchos casos los atacantes saben de antemano lo que va a ocurrir, mientras que los defensores tienen que esperar a que el rival mueva para empezar a pensar en cómo responder.

Además, para poder salir de la posición de defensa, hay que saber castigar los errores del atacante e iniciar contrataques, que generalmente es más difícil que atacar sin más.

Por ese motivo, es común que los jugadores jueguen varias partidas alternando colores.

## Amenazas

Se denomina `ataque` a la capacidad de una pieza de capturar o explotar una casilla, sea o no deseable. Por el contrario, se denomina `amenaza` a la capacidad de una pieza de capturar o explotar una casilla, dándonos ventaja. Es decir, una `amenaza` es un intento de conseguir ventaja, generalmente inflingiendo cierto daño a la posición rival.

Hay amenazas de todo tipo: las que buscan ganar material, las que dañan la posición rival, las que amenazan al rey, etc. Generalmente nunca hay que ignorar las amenazas del rival, y tenemos que buscar constantemente crear amenazas propias.

Es importante saber distinguir las amenazas reales de las que no lo son (aquellas que no nos pueden hacer daño porque disponemos de una respuesta que haría que el rival saliese perdiendo).

## Aperturas

Todo movimiento en una partida debe tener un propósito claro. Las aperturas son un campo muy teórico y memorístico del ajedrez, aunque todas comparten varias ideas posicionales. Antes de aprenderse varias aperturas de memoria conviene conocer los principios detrás de ellas.

Cada movimiento de apertura suele buscar alguno de los siguientes objetivos: 

1. Desarrollar piezas a casillas activas o mover piezas que posibiliten el desarrollo.
2. Luchar por el centro ocupándolo, atacándolo o apuntándolo.
3. Ganar espacio, consiguiendo movilidad.
4. Poner a salvo al rey (generalmente mediante enroque).

```
El control del centro del tablero mediante peones es fundamental durante la apertura. Si alguno de los bandos descuida ese control, pronto se verá perdiendo tiempos mientras sus piezas menores son atacadas por peones enemigos, que irán ganando espacio y constriñendo el movimiento rival con cada avance.
```

Además, hay 25 cosas que casi siempre hay que evitar durante la apertura:

1. Movimientos innecesarios de peón.
2. Sacar la reina demasiado pronto.
3. Mover la misma pieza dos veces.
4. Cambiar una pieza desarrollada por otra no desarrollada.
5. Cambiar piezas sin motivo.
6. Desarrollar una pieza porque sí, sin un plan general.
7. Bloquear los peones centrales.
8. Impedir el desarrollo de otras piezas.
9. Debilitar el flanco de rey o mover el rey sin enrocar.
10. Mover caballos a los extremos del tablero.
11. Desperdiciar tempos o movimientos.
12. Restar importancia a ganarle peones al adversario.
13. Sacrificar sin un buen motivo.
14. Rechazar un sacrificio si no vemos lo que el oponente quiere hacer. Prestar atención a la posición, porque puede que se haya equivocado.
15. Jugar sin un plan general.
16. Desarrollar de forma descoordinada.
17. Cambiar de plan en cada movimiento.
18. Permanecer sin enrocar demasiado tiempo.
19. Avanzar peones demasiado muy pronto.
20. Ignorar los movimientos del adversario.
21. Dar jaques que no llevan a nada.
22. Evitar intercambios naturales de forma caprichosa.
23. No tomarse al rival demasiado a broma ni demasiado en serio; jugar contra el tablero, no contra la persona que tenemos delante.
24. Jugar una secuencia de movimientos pre-pensada sin hacer caso de lo que hace el rival.
25. Abrir el centro si aún no hemos enrocado.

```
Es crucial no perder tempos durante la apertura. Una forma común de perder tempos es mover peones a casillas donde bloqueen el desarrollo de otras piezas (ej. alfiles). Ganar territorio a costa de perder tempos es un lastre en el que es fácil caer y cuyo precio se paga en el medio juego. Activar muchas piezas muy pronto es fundamental en cualquier apertura.
```

En casi todas las aperturas las piezas juegan papeles parecidos: 

- Generalmente las aperturas usan sobre todo alfiles y caballos. Suele ser buena idea desarrollarlos pronto, sencillamente porque son las piezas más flexibles al inicio de la partida y pueden conseguir objetivos a corto plazo de forma efectiva.

- En muchos casos, las torres están más o menos inactivas incluso después del enroque. Eso solo cambia cuando se abre una fila (los peones desaparecen de una fila) y una torre la ocupa. 

- Durante las aperturas los peones juegan un papel principalmente defensivo.

- Como norma general, no conviene sacar la reina a campo abierto durante la apertura, porque queda expuesta a ataques por piezas rivales que se desarrollan, haciéndonos perder tiempos para poner a salvo a la reina.

Dos movimientos iniciales muy comunes en aperturas son `1.e4` y `1.d4`; en ambos casos, las negras liberan diagonales para desarrollar sus piezas, ganan todo el espacio posible y se abalanzan sobre el centro.

```
Aunque las blancas deciden el primer movimiento, las negras pueden alterar el curso de la apertura con el segundo movimiento. Es decir, que aunque las blancas decidan que la línea de aperturas a jugar es 1.e4, las negras pueden decidir que esa partida va a ir por la rama de la defensa eslava.
```

Para los principiantes suele ser preferible `1.e4` a `1.d4` porque comenzar con el peón de reina suele acabar en posiciones más complejas y sofisticadas que requieren más experiencia para ser jugadas correctamente. Por el contrario, `1.e4` lleva a posiciones más abiertas que son más asequibles para jugadores de menos nivel.

Como el peón blanco de `e` no tiene apoyo al desarrollarse, suele ser mucho más difícil jugar `e4` más tarde en el juego, mientras que `d4` tiene el apoyo de la reina y puede jugarse más adelante.  Esto significa que con `1.d4` es más probable que no se intercambien peones en el centro, llevando a posiciones más lentas y cerradas.

El objetivo principal de las blancas en muchas aperturas `1.e4` es impedir que las negras muevan `1.d6`, ya que esto dificulta su desarrollo y da a las blancas cierta ventaja. 

Algunas de las primeras aperturas que aprender derivadas de `1.e4` son:

- `Apertura italiana`, también conocida como `Giuoco Piano`.
- `Apertura española`, también conocida como `Ruy López`.
- `Apertura escocesa`.

Aperturas comunes que empiezan con `1.d4` son:

- `Gambito de dama`, que tiene dos variantes: aceptado y declinado. El declinado se considera más sólido para las negras.

Hay otras aperturas menos comunes para el blanco:

- `Apertura inglesa`: flexible para ambos bandos.
- `Gambito danés`: peligroso si las negras no conocen la apertura. Si lo conocen, se acaba en una posición abierta sin damas.
- `Bird`: arriesgada para las blancas.
- `Gambito de rey`: arriesgado para las blancas.
- `Ataque grob`: arriesgado para las blancas.

Cuando nos enfrentamos como negras a ataques de blancas que desconocemos y que no atacan directamente el centro, la buena idea es seguir los principios generales de las aperturas, tomar el centro nosotros con peones y desarrollar piezas.

Las negras también tienen varias líneas de aperturas que pueden empezar a estudiar:

- `Defensa eslava`: alternativa interesante al `gambito de dama declinado`. Hay dos alternativas: `defensa eslava` y `defensa semieslava`.
- `Defensa Philidor`: defensa sólida pero pasiva para las negras, que no podrán jugar su alfil negro al comienzo.
- `Defensa siciliana`: muy popular, lleva a posiciones tácticamente complejas.
- `Defensa rusa` o `defensa Petrov`. 
- `Defensa escandinava`: arriesgada para las negras. 
- `Defensa francesa`: las negras ceden una ventaja inicial de espacio central y luego contratacan el centro blanco y destruirlo. El mayor reto para las negras es activar su alfil blanco, que ha quedado bloqueado por la estructura de peones.
- `Defensa Caro-Kann`: apertura sólida pero lenta para las negras.
- `Defensa Nimzo-india`.
- `Defensa india de rey`.
- `Defensa Grunfeld`: muy táctica, un paso en falso puede acabar en desastre si el rival conoce bien la apertura y sus trampas.
- `Gambito budapest`: una línea con trampas interesantes que pueden terminar con las blancas si no concen 
- `Defensa holandesa`: arriesgada para las negras.

Existen otras primeras jugadas interesantes, como `1.a3`, `1.b4`, `1.f4` y `1.Nc3`, pero suelen ser  jugadas solo por jugadores avanzados.

Se denomina `centro clásico` a la colocación de los peones `d` y `e` blancos en las casillas `d4` y `e4`, respectivamente. Es la posición ideal para las blancas en una apertura, aunque las negras rara vez lo permiten. Gana mucho territorio y le da a las negras la iniciativa, ralentizando mucho el desarrollo negro.

### Enroque
Se denomina `enroque` al movimiento que cruza a una de las torres con el rey. Para que sea legal, ni la torre ni el rey deben haberse movido hasta ese momento.

El rey puede enrocar hacia el flanco de rey o hacia el flanco de reina. Aunque esto no siempre es así y depende de la posición, suele ser preferible lo primero por varios motivos.

1. Puede ocurrir antes, porque hay que mover menos piezas para liberar esa fila.

2. En el enroque en el flanco de reina el peón de `a2` está desprotegido, dejando al rey más expuesto a ataques enemigos a no ser que debilitemos esa estructura de peones (moviendo alguno de ellos) o perdiendo un tiempo en mover el rey a `b1`.

## Endgames

Los finales o endgames son las fases del juego en las que no quedan muchas piezas en el tablero; generalmente rey, peones y alguna pieza menor o torre de cada bando. En este punto es común que las reinas se hayan intercambiado.

En muchas partidas  este es el momento de sacar a los reyes de sus refugios y llevarlos al centro del tablero para conseguir que los peones restantes puedan llegar al final.

```
En muchos casos querremos calcular si a un peón le da tiempo llegar al final antes de que el rey enemigo lo capture. Para averiguarlo sin calcular podemos usar la regla del cuadrado, que consiste en dibujar en el tablero un cuadrado imaginario cuyo lado es igual a la distancia del peón al final, y el peón está en una de sus esquinas. Si el rey enemigo puede entrar en ese cuadrado, al peón no le da tiempo llegar al final. 
```


## Estrategia

Mientras que la `táctica` se centra en oportunidades puntuales y jugadas concretas, la `estrategia` es la línea de pensamiento que trata la globalidad del juego o planes a largo plazo. La estrategia es la directriz general, la táctica son los medios concretos para llevar a cabo ese plan. 

Tres principios básicos de estrategia son:
1. Determinar cuál es nuestra pieza menos activa y colocarla en un lugar mejor.
2. Impdeidr que el rival mejore sus piezas malas (ej. impidiendo el avance de peones enemigos que constriñen a piezas de su mismo bando).
3. Inercambiar piezas activas del enemigo por piezas inactivas nuestras.

```
La estrategia dicta qué hacer, y la táctica nos muestra cómo hacerlo de forma efectiva.
```

*********************************************************************
## Táctica

Se denomina táctica al uso de oportunidades puntuales para conseguir una ventaja sobre el adversario. Para entender correctamente la teoría táctica hay que saber el valor asignado a las piezas:
	
		- Peón: 1
		- Alfil y caballo: 3
		- Torres: 5
		- Reina: 9
		
Mucho ojo, porque este valor es relativo. Es posible que haya partidas donde un alfil sea mucho más activo e importante que una reina. Se trata de valores orientativos iniciales, no hay que tomárselos al pie de la letra en todas las posiciones.

Se suelen distinguir dos tipos de táctica: 

- Tácticas de mate: ganan la partida. 
- Tácticas de no mate: consiguen otras cosas, como material.

*********************************************************************

### Tácticas de mate

Análogamente a las tácticas de no mate, existen múltiples tácticas de mate o `mating patterns`, cuyo fin es hacer jaque mate al rey rival. No obstante, en este caso existen cientos de tipos con sus variantes. No es necesario conocerlas todas para poder hacer un mate, pero si es recomendable estar familiarizado con las más comunes (hay libros llenos solamente de ejercicios de mate para entrenar esa visión táctica).

Una estrategia común en táticas de mate es hacer jaque al rival como opción preferente, ya que esto limita el número de respuestas del rival, y permite hacer un plan más sólido donde es más difícil que el rival nos sorprenda con una respuesta inesperada.

### Tácticas de no mate

Existen 13 tipos de tácticas de no mate:
	
#### Piezas colgadas / En prise

Atacar a una pieza desprotegida, de manera que nos la podemos comer "gratis".
	
<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/LhhVyeZA?theme=blue&bg=dark" frameborder=0></iframe>

#### Ataque múltiple / forks

Atacar a varias piezas al mismo tiempo, de modo que el rival solo puede salvar una de ellas. 

La pieza más efectiva para hacer ataques dobles es la reina porque es la que más rayos lanza, mientras que la más peligrosa es el peón, ya que es la que menos valor tiene, de modo que saldremos ganando casi siempre.

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/Knev2NHg?theme=blue&bg=dark" frameborder=0></iframe>

#### Clavadas / Pins

Consiste en atacar a dos piezas rivales que están alineadas con una pieza de ataque lineal (alfil, torre o reina), de modo que una de ellas (generalmente la menos valiosa) queda inmovilizada.

Una clavada es absoluta cuando la pieza no se puede mover legalmente (ya que el rey quedaría en jaque) y es relativa si la pieza detrás de la clavada no es el rey, de modo que el jugador puede elegir mover la pieza incluso a pesar de la clavada.

Cuando una pieza rival está clavada podemos ganar material aumentando la presión sobre ella. Si conseguimos acumular más presión que el rival, ganaremos esa pieza. 

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/0ZJnGOhM?theme=blue&bg=dark" frameborder=0></iframe>


#### Pincho o Enfilada / Skewer

Es igual que una clavada, pero a la inversa. Consiste en atacar a dos piezas rivales alineadas, obligando a la primera a moverse y dejando a la segunda al descubierto. 

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/M4DNzDLM?theme=blue&bg=dark" frameborder=0></iframe>

#### Ataque descubierto

consiste en mover una pieza, de modo que otra pieza del mismo bando que estaba detrás de ella queda descubierta y ataca a una pieza rival. Por ejemplo: mover un caballo que cubría una torre, de ésta quede descubierta y haga jaque al rey rival. 
		
Por definición, la reina nunca puede iniciar un ataque descubierto, ya que la pieza que se mueve debe tener un rango distinto que la pieza descubierta (de lo contrario, ya estaría atacando antes de mover).

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/VEx1xnE5?theme=blue&bg=dark" frameborder=0></iframe>

#### Doble jaque

Consiste en atacar al rey rival con dos piezas. Esto se puede conseguir haciendo un ataque descubierto, de modo que tanto la pieza que se mueve como la que ha sido descubierta ataquen al rey. 

Este ataque es realmente letal porque la única jugada posible del rival es mover al rey.

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/o8Pi8TY0?theme=blue&bg=dark" frameborder=0></iframe>
	

#### Minado o desviación / Undermining

Consiste en capturar o obligar el desplazamiento de la pieza que protegía a otra pieza rival, de modo que ésta queda expuesta. Esta táctica funciona bien cuando una pieza tiene un único defensor.

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/TSuxgF1I?theme=blue&bg=dark" frameborder=0></iframe>

#### Sobrecarga 

Una pieza se considera sobrecargada si no puede dar respuesta a todos sus deberes defensivos. 

Por ejemplo, si un peón rival defiende dos piezas y nos comemos una de ellas, la segunda pieza que defendía quedará desprotegida cuando el peón se mueva de su sitio para comerse a nuestra pieza.

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/cK9tftNz?theme=blue&bg=dark" frameborder=0></iframe>

#### Ataque de rayos X / Hurdle

Consiste en atacar piezas o casillas a través de piezas o casillas rivales. Es parecido a un `pincho`, aunque más genérico, porque también sirve para atacar casillas y para defender piezas. 

Por ejemplo, si en la misma fila hay una torre blanca, una torre negra y una torre blanca, ambas torres se están defendiendo entre sí por rayos X, aunque no se vean entre sí directamente.

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/yBAel5AC?theme=blue&bg=dark" frameborder=0></iframe>

#### Atracción

Se denomina atracción a la técnica de obligar al rival a mover una pieza a una casilla que no desea, de modo que podemos asestarle un golpe táctico (ganando material o la partida).

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/1MQV5JKz?theme=blue&bg=dark" frameborder=0></iframe>

#### Trampa

Una pieza se considera atrapada si no puede moverse a ninguna casilla sin ser comida por una pieza rival, perdiendo en el intercambio de material. En estos casos lo común es ganar material atacando directamente a la pieza atrapada. El jaque mate no es otra cosa que una `trampa` al rey. 

<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/A20LEY2c?theme=blue&bg=dark" frameborder=0></iframe>

#### Táctica a la desesperada

Cuando una de nuestras piezas queda atrapada (por ejemplo por una trampa), en lugar de darla por perdida y empezar a hacer otra cosa, podemos intentar sacarle el máximo partido (por ejemplo, haciendo que capture otra pieza, aunque sea de menos valor, o debilitando la posición del rival antes de perderla).

#### Promoción

Consiste en conseguir que un peón llegue al final del tablero, de modo que podemos convertirlo en la pieza que queramos (casi siempre reina). 


<iframe width=100% height=500 src="https://lichess.org/study/embed/9FlApgud/b9xlLnfs?theme=blue&bg=dark" frameborder=0></iframe>

*********************************************************************



