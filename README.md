# GUIA 0 (GUIA DE EJERCICIOS INICIAL) - EJ 21
AGUSTIN HUGO GIMENEZ

FACULTAD DE INGENIERIA DEL EJERCITO

ESTRUCTURA DE DATOS Y ALGORITMOS

EJERCICIO 21 : Se pide replicar el comportamiento de la función de asignación dinámica de
memoria (malloc), a través de una función de la siguiente forma: 1. int *
overrideMalloc(int, int[]);
Notas:
a. El primer parámetro que se envía es el tamaño del arreglo que se solicita y
el segundo es un arreglo que representa la memoria del sistema operativo.
Este arreglo contiene unos y ceros, donde un 0 representa un espacio de
memoria disponible, y un 1 indica que dicho espacio está siendo utilizado
por otro proceso.
b. La función deberá devolver la dirección de memoria a partir de la cual se
puede almacenar el bloque de memoria solicitado.
c. En caso de no contar con dicho espacio, la función deberá retornar NULL.

