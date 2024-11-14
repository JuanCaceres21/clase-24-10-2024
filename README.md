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

### Espacios de estado a partir de una ecuacion en diferencias
Las ecuaciones en diferencias son una forma de representar los sistemas de forma discreta, a partir de estas ecuaciones se pueden obtener las matrices A, B, C, D las cuales le daran forma a el espacio de estados que representara el comportamiento de este sistema dinamico.

Se deben seguir los siguientes pasos:

1. Se debe despejar el adelanto mas alto en la ecuacion en diferencias.
2. Igualas la salida de la ecuacion a la variable de estado X1(k).
3. Se aplican adelantos para obtener los adelantos de la variable de estado.

💡**Ejemplo 1:** 

Tenemos la ecuacion en diferencias de la forma:

$$22.5Y(K+2)+391Y(K+1)+45Y(K)=1734U(k)$$

Siguiendo el procedimiento decimos que:

1. Se debe despejar el adelanto mas alto en la ecuacion en diferencias.

$$22.5Y(K+2)=-391Y(K+1)-45Y(K)+1734U(k)$$

2. Igualas la salida de la ecuacion a la variable de estado X1(k).

$$Y(K)=X1(K)$$

3. Se aplican adelantos para obtener los adelantos de la variable de estado.

$$Y(K+1)=X1(k+1)$$

$$X1(K+1)=X2(k)$$ Ecuacion de estado 1

$$X2(K+1)=Y(K+2)$$ Ecuacion de estado 2

Procedemos a ordenar la matriz con las ecuaciones de estado encontradas:
