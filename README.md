#ACTIVIDAD3
---
---

En el presente repositorio se ha agregado el código fuente de "memory" 
Recuperado de: http://www.grantjenks.com/docs/freegames/pacman.html . En el código original, vemos como pac man se enfrenta a fantasmas (aunque no tan inteligentes) hasta recolectar cada pellet, donde nuestro puntaje se muestra en el lado superior derecho. El juego terminará al tocar un fantasma o al conseguir cada pellet.

Se nos ha pedido realizar lo siguiente:

1)Los fantasmas sean más listos
-
2)Cambiar el tablero
-
3)Hacer que los fantasmas vayan mas rápido
-

Explicaciones
***

*Primer Caso:* 

*Segundo Caso:* El tablero de pacman está basado en una lista de 0 y 1, 1 representa dónde puede avanzar pacman, los fantasmas y donde aparecen los *"pellets"*, mientras que los 0 representan los bordes del tablero. Al tener conocimiento de esto, extendimos el tablero en tamaño y modificamos los bordes interiores para satisfacer con la condición de que los fantasmas puedan recorrer sin problema. 

*Tercer Caso:* Este fue logrado a través de los vectores designados para los 4 fantasmas, siendo originalmente: (5,0),(-5,0),(0,5),(0,-5). Se duplicaron los valores de todos para aumentar su velocidad. Identificamos que la velocidad solo puede ser con múltiplos de 5, debido a limitaciones dentro del código, optamos por doble velocidad para ser una mayor desafió al usuario junto con la ventaja de que las partidas pueden ser más rápidas.





