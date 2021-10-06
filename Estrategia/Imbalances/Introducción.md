# Imbalances
## Introducción

El método de la escuela de [Jeremy Silman](https://en.wikipedia.org/wiki/Jeremy_Silman) consiste en:

1. Analizar los **desequilibrios** o **imbalances** que existen en una situación dada.
2. Determinar las **responsabilidades** de cada jugador respecto a esa posición. 

```
Hay que evitar empezar a calcular movimientos específicos antes de entender todos los desequilibrios de una posición dada.
```

El término `responsabilidad` no es casual. Los jugadores no son libres de hacer lo que quieran en cada posición. Por ejemplo, un jugador al que le encante atacar dinámicamente no puede ir tras el rey rival en todas las situaciones. Hay que leer el tablero y seguir sus reglas. 

Existen 7 desequilibrios, y los hay de dos tipos: `perdurables` y `temporales`.

Los desequilibrios `perdurables` son aquellos que podemos mantener activamente durante bastante tiempo (incluso toda la partida).

- `Material`: tener piezas de mayor valor que el adversario.

- `Piezas menores`: la lucha entre alfiles y caballos. Aunque en teoría valen lo mismo (3 puntos), unos son mucho más potentes que otros en ciertas situaciones. Hay que forzar situaciones en las que nuestras piezas menores valgan más que las del adversario.

- `Estructura de peones`: un tema amplio que incluye el número de peones en el centro y en las alas, así como el número de `peones dobles`, `peones aislados`, `peones retrasados`, `peones pasados`, etc.

- `Espacio` la anexión de territorio mediante el avance de peones. Más espacio significa más libertad de movimiento, pero también más vulnerabilidad a ataques.

- `Filas y casillas`: las filas y diagonales son los caminos por los que se mueven nuestras piezas, mientras que las casillas hacen las veces de "refugio". Puede haber planes de juego centrados en dominar una fila o crear una casilla débil en campo enemigo.

Los desequilibrios `temporales` son aquellos cuya duración es efímera. Es decir, que aunque no hagamos nada mal, acabaremos perdiendo esa ventaja en poco tiempo.

- `Desarrollo`: cuantas más piezas tengamos activas, más poder tendremos en ese lugar del tablero. Es un desequilibrio `temporal`, ya que eventualmente ambos jugadores acaban desarrollando todas sus piezas.

- `Iniciativa`: dictar hacia dónde se dirige el juego y obligar al rival a jugar de forma reactiva a nuestras acciones. También es un desequlibrio `temporal`.

```
Podemos analizar los desequilibrios de ambos jugadores para cualquier posición. Lo más probable es que cada bando tenga varios desequilibrios a su favor; su misión será demostrar que esos desequilibrios son más fuertes que los de su rival.
```

## Ejemplo

<iframe width=100% height=500 src="https://lichess.org/study/embed/iwNnSYQy/XYCVEyWs?theme=blue&bg=dark" frameborder=0></iframe>

- `Material`: el material está igualado.

- `Piezas menores`: las negras tienen la pareja de alfiles. La posición es relativamente abierta, y es probable que los alfiles sean más poderosos que el dúo de caballos blanco. Las blancas solo disponen de alfil blanco, por lo que tienen debilidad en las casillas negras.

- `Estructura de peones`: las negras no tienen peones débiles. El peón en `e5` de las blancas es vulnerable por estar tan avanzado y por estar en una casilla negra.

- `Espacio` las blancas tienen más espacio gracias a su peón en `e5`.

- `Filas y casillas`: la `fila d` está abierta pero ningún bando la ha ocupado aún con una torre. La casilla `f6` es débil para las negras.

- `Desarrollo`: las blancas lideran el desarrollo. 

- `Iniciativa`: ningún jugador tiene la iniciativa clara.

Una vez determinados los desequilibrios, podemos considerarlos en conjunto y ver las `responsabilidades` de ambos bandos en esta posición. 

- Las blancas tienen más espacio y desarrollo, pero están comprometidas con la defensa de `e5`. Tienen que activar sus caballos colocándolos en `puntos de apoyo`. El mejor punto de apoyo disponible es el punto débil en `f6`, al que no es fácil acceder debido a que `Ne4` bloquea la `fila e` y dificultaría la defensa de `e5`. 

- Las negras están haciendo presión sobre el peón de `e5` y pueden aprovechar que tienen el control de las casillas negras para acabar con él. Deberán privar a los caballos enemigos de puntos de apoyo (regla de `Steinitz`) e intentar bloquear las piezas blancas ligándolas a la defensa de `e5`.
