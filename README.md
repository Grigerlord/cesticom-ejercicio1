# Prueba técnica bootcamp-Cesticom
## Ejercicio #1
### Griger Ratia
### grigerratia@gmail.com
### 04161913347

#### *Describir pasos para determinar cómo de un conjunto de números (del 1 al 300) puedo tomar los múltiplos de 2 y 3. Además, cómo calcular la media y el promedio de la lista de números.*

**NOTA: No sé si quisieron decir Promedio y Mediana, o promedio y media, porque promedio y media son lo mismo. Por eso también agregué los pasos para calcular la mediana.**

**Podemos**

+ **Calcular y guardar los múltiplos de 2 y 3 así:**
    1. Multiplicar 2 o 3 * 1
    2. Si el resultado es mayor a 300, Terminar el proceso
    3. Si el resultado es menor o igual a 300, Guardar resultado
    4. Multiplicar 2 o 3 por el número siguiente (2, 3, 4, 5...) (Volver al paso 2)





+ **Calcular la media o promedio, así:**
    1. Sumamos el primer elemento de la lista con el elemento de la siguiente posición
    2. Guardamos el resultado con el nombre SUMA_TOTAL
    3. Si no existe otro elemento en la siguiente posición, saltamos al paso 7
    4. Si existe otro elemento en la siguiente posición, sumamos este número con el valor en SUMA_TOTAL
    5. Actualizamos SUMA_TOTAL igualándolo al valor del resultado obtenido en el paso 4
    6. Volvemos al paso 3
    7. Dividimos el valor guardado en SUMA_TOTAL entre la cantidad de elementos que contiene la lista. Terminar proceso.
  
  
  
  
  
+ **Calcular la Mediana, así:**
    1. Si la lista de elementos está ordenada de forma ascendente, saltar al paso 3
    2. Si la lista de elementos no se encuentra ordenada de forma ascendente, ordenar entonces de forma ascendente.
    3. Si la cantidad de elementos en la lista es un número impar, seleccionar como MEDIANA el número posicionado a la mitad de la lista de elementos. Terminar el proceso.
    4. Si la cantidad de elementos en la lista es un número par, incluir en una NUEVA_LISTA los dos elementos posicionados a la mitad de la lista de elementos.
    5. Calcular el promedio de los elementos incluídos en NUEVA_LISTA. Terminar proceso.


