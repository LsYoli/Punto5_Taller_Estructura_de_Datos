# Largest Rectangle

## Descripción
Solución al problema [**Largest Rectangle**](https://www.hackerrank.com/challenges/largest-rectangle/problem) de HackerRank utilizando una **pila monótona** para encontrar el área máxima de un rectángulo formado por edificios consecutivos.

## Algoritmo
- Se recorre el arreglo de alturas una sola vez.
- Se mantiene una pila con los índices de las barras en orden creciente de altura.
- Cuando aparece una barra más baja, se calculan las áreas máximas de las barras que ya no pueden extenderse hacia la derecha.
- Al final se agrega una barra ficticia de altura `0` para procesar las barras restantes.

## Complejidad
- **Tiempo:** `O(n)`

## Ejecución
Esta solución está diseñada para ejecutarse directamente en **HackerRank**, utilizando la entrada estándar (`stdin`) y la salida estándar (`stdout`) proporcionadas por la plataforma.

# Linked List Cycle

## Descripción
Solución al problema [**Cycle Detection**](https://www.hackerrank.com/challenges/detect-whether-a-linked-list-contains-a-cycle/problem?isFullScreen=true) de HackerRank utilizando el **algoritmo de Floyd (Tortuga y Liebre)** para determinar si una lista enlazada contiene un ciclo.

## Algoritmo
- Se utilizan dos punteros: `slow` y `fast`.
- `slow` avanza un nodo por iteración, mientras que `fast` avanza dos nodos.
- Si la lista contiene un ciclo, ambos punteros terminarán encontrándose.
- Si `fast` o `fast.next` llegan a `None`, significa que la lista no tiene ciclo.

## Complejidad
- **Tiempo:** `O(n)`

## Ejecución
Esta solución está diseñada para ejecutarse directamente en **HackerRank**, utilizando la entrada estándar (`stdin`) y la salida estándar (`stdout`) proporcionadas por la plataforma.
