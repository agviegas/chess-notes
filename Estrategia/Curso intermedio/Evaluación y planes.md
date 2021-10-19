# Cómo evaluar posiciones

Durante el [[Aperturas#Análisis post-partida|análisis post-partida]], el ordenador asigna a cada posición una valoración numérica positiva si la ventaja es para blancas y negativa si la ventaja es para negras en función de las perspectivas de victoria de cada color.

La evaluación de posiciones de ajedrez consiste justo en eso: medir cómo de buenas son las espectativas de cada jugador de cara a los siguientes movimientos antes de jugarlos. La diferencia de puntos de material es un factor a considerar, pero una posición con un desequilibrio de puntos puede estar equilibrada, indeterminada o incluso resultar favorable para el jugador en desventaja de material. 

La evaluación del estado de la posición se basa en 4 factores:
- Material.
- Seguridad de cada rey, no en cuanto a cómo de "expuesto" esté, sino cómo de fácil lo tienen las piezas enemigas para alcanzarlo.
- Actividad de piezas: cuántas piezas están activas, cuántas casillas controlan en el lado enemigo del tablero.
- Estructura de peones y espacio

En cierto sentido, la táctica consiste en reconocer los desequilibrios presentes en esos 4 factores y saber **convertirlos** en una victoria.

> Si un árbol cae en el bosque y nadie lo oye, ¿hace ruido?
> Si tienes una ventaja de +2 pero no la **conviertes**, ¿tenías ventaja?

# ¿Cómo planear esas conversiones?

## Planes

Este vídeo da algunas ideas sobre cómo hacer planes en sus primeros 2 tips:

<iframe width="450" height="253" src="https://www.youtube.com/embed/fGFl4GjVvrA" title="10 Chess Tips To CRUSH Everyone" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Pero en general, una buena forma de reconocer la presencia o ausencia de planes durante una partida es: ¿puedo explicar con palabras qué pretendo conseguir con esta apertura / este movimiento / esta táctica? Al no poder formular planes claros estamos jugando de forma instintiva, reinventando la rueda y probablemente haciendo movimientos sub-óptimos (para eso existen las [[Aperturas#Bases de datos|bases de datos]] de aperturas y partidas enteras). Así, parte del estudio de aperturas es el estudio de la "filosofía" de la apertura, sus intenciones y planes implícitos. 

Desde el momento en que la partida se desvía de la teoría de la apertura, o a la hora de evaluar la posición del mid o late game, Levy recomienda usar **la checklist**.

## La checklist

Todos los buenos jugadores siguen este proceso, ya sea mecánicamente o, en el caso de jugadores de élite, intuitivamente. 

Cuando tu oponente hace un movimiento:
1. ¿La pieza que se ha movido amenaza a algo? Ya sea de captura, jaque o de naturaleza posicional (amenazar una casilla, bloquear una de mis piezas).
2. ¿Alguna de las otras piezas de mi rival amenazan a algo? Por ejemplo, ataques descubiertos. 
3. Si es que no a todo, hago la misma lista para mí:
	1. ¿Puedo dar jaque?
	2. ¿Puedo comerme una pieza?
	3. ¿Puedo atacar? 

Las respuestas a estas preguntas generarán una serie de ideas sobre qué puede querer hacer cada jugador, pero cada una de esas ideas requiere calcular los siguientes movimientos de cada jugador y evaluar la posición resultante en caso de seguir esa vía. 

Al calcular variaciones de una jugada es fácil caer en el "hopeful thinking" de que el rival jugará mal y la jugada tendrá éxito. Para evitar esto, al evaluar jugadas debemos intentar demostrar que la jugada *no* funciona, y solo al fallar en ese intento podemos pensar que la jugada es buena. 

A estas amenazas que obligan al rival a mover como nos conviene Levy las llama "forcing move". 