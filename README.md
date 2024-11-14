# clase-24-10-2024-1
# Introduccion a espacios de estados
los espacios de estados son una representacion de los Sistemas dinamicos, a diferencia de otras representaciones, esta tiene en cuanta como relacionan unas variables con otras, lo que nos ofrece una mejor representacion matematica de un sistema. Podemos obtener Espacios de estados a partir de otras representaciones como las ecuaciones en diferencias o funciones de transferencia.

## ¿como se escriben los espacios de estados?

Los espacios de estados originalmete se representan como ecuaciones de estado, pero esto las hace mas tedioso para trabajar, por lo que estos espacios se representan mejor como operaciones entre matrices.
### Espacio de estado como matrices.

$$X(k+1)=AX(k)+Bu(k)$$
$$Y(k)=CX(k)+Du(k)$$

En donde:

A es la matriz de estados

B es la matriz de entrada

C es la matriz de salida

D es la matriz de transmision directa
