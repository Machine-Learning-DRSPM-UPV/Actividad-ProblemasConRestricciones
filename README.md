# Actividad Problemas Con Restricciones

De acuerdo a los siguientes problemas, implemente una solución iterativa o recuriva para los siguientes problemas combinatorios:

## Problema 1 - N Reinas

Originalmente conocido como el rompecabezas de las ocho reinas, el clásico problema de N-Queens se originó en el juego del ajedrez, y el tablero de ajedrez 8x8 fue su primer patio de juegos. La tarea consistía en colocar ocho reinas de ajedrez en el tablero sin que ninguna de ellas se amenazara entre sí. En otras palabras, no hay dos reinas que puedan compartir la misma fila, la misma columna o la misma diagonal. El problema de N-Queens es similar, usando un tablero de ajedrez N × N y N reinas de ajedrez.

Se sabe que el problema tiene una solución para cualquier número natural, n, excepto para los casos de n = 2 yn = 3. Para el caso original de ocho reinas, hay 92 soluciones, o 12 soluciones únicas si consideramos que las soluciones simétricas son idénticas.

De acuerdo a lo anterior, realice lo siguiente:
  > 1. Implemente un sistema que dé solución al problema de N-Reinas. Sin utilizar algoritmos genéticos
  > 2. La solución deberá ser mostrada de forma gráfica como se muestra en la siguiente figura
  
![](https://assets.leetcode.com/uploads/2018/10/12/8-queens.png)

## Problema de asignación de horarios de enfermeras

Imagine que es responsable de programar los turnos para las enfermeras en el departamento de su hospital para esta semana. Hay tres turnos en un día, mañana, tarde y noche, y para cada turno, debe asignar una o más de las ocho enfermeras que trabajan en su departamento. Si esto suena como una tarea simple, eche un vistazo a la lista de reglas relevantes del hospital:
  > * Una enfermera no tiene permitido trabajar dos turnos consecutivos.
  > * Una enfermera no puede trabajar más de cinco turnos por semana.
  > * El número de enfermeras por turno en su departamento debe estar dentro de los siguientes límites:
  >    * Turno de mañana: 2–3 enfermeras
  >    * Turno de tarde: 2–4 enfermeras
  >    * Turno de noche: 1–2 enfermeras

Además, cada enfermera puede tener preferencias de turno. Por ejemplo, una enfermera prefiere trabajar solo en turnos de mañana, otra enfermera prefiere no trabajar en turnos de tarde, y así sucesivamente.

Esta tarea es un ejemplo del problema de programación de enfermería (NSP), que puede tener muchas variantes. Las posibles variaciones pueden incluir diferentes especialidades para diferentes enfermeras, la capacidad de trabajar en turnos de cobertura (horas extras) o incluso diferentes tipos de turnos, como turnos de 8 horas y turnos de 12 horas.

De acuerdo a lo anterior, implemente un sistema que de como resultado la asignación de turnos para un conjunto de enfermeras.

## Problema del coloreado de grafos

En la rama matemática de la teoría de grafos, un grafo es una colección estructurada de objetos que representa las relaciones entre pares de estos objetos. Los objetos aparecen como vértices (o nodos) en el gráfico, mientras que la relación entre un par de objetos se representa mediante un borde. Una forma común de ilustrar un gráfico es dibujando los vértices como círculos y los bordes como líneas de conexión, como se muestra en el siguiente diagrama del gráfico de Petersen, llamado así por el matemático danés Julius Petersen:

![Petersen Graph](https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Petersen_graph_3-coloring.svg/480px-Petersen_graph_3-coloring.svg.png)

Los gráficos son objetos notablemente útiles, ya que pueden representar y ayudarnos a investigar una abrumadora variedad de estructuras, patrones y relaciones de la vida real, como redes sociales, diseños de redes eléctricas, estructuras de sitios web, composiciones lingüísticas, redes informáticas, estructuras atómicas, patrones de migración , y más.

La tarea de colorear el gráfico se usa para asignar un color para cada nodo en el gráfico de tal manera que ningún par de nodos conectados (adyacentes) compartan el mismo color. Esto también se conoce como la coloración adecuada del gráfico.

El siguiente diagrama muestra el mismo gráfico de Petersen, pero esta vez coloreado correctamente:

![Petersen Graph](https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Petersen_graph_3-coloring.svg/480px-Petersen_graph_3-coloring.svg.png)

La asignación de color a menudo va acompañada de un requisito de optimización: use la cantidad mínima posible de colores. Por ejemplo, el gráfico de Peterson se puede colorear correctamente con tres colores, como se muestra en el diagrama anterior. Pero sería imposible colorearlo correctamente usando solo dos colores. En términos de teoría de grafos, esto significa que el número cromático de este grafo es tres.

¿Por qué nos importaría colorear los nodos del gráfico? Aparentemente, muchos problemas de la vida real pueden traducirse en una representación gráfica de tal manera que el color del gráfico represente una solución; por ejemplo, la programación de clases para un estudiante o los turnos para un empleado se pueden traducir en un gráfico, donde los nodos adyacentes representan clases o turnos que causan un conflicto. Tal conflicto puede ser clases que caen al mismo tiempo o turnos consecutivos. Debido a este conflicto, la asignación de la misma persona a ambas clases (o ambos turnos) invalidará el horario. Si cada color representa a una persona diferente, la asignación de diferentes colores a los nodos adyacentes resolverá los conflictos. Otros ejemplos relevantes incluyen asignaciones de frecuencia a estaciones de radio, planificación de redundancia de la red eléctrica, sincronización de semáforos e incluso resolución de rompecabezas Sudoku.

De acuerdo a lo anterior, implemente un programa de dé solución al problema del coloreado de grafos.


# Entregables

  > 1. Cada solución deberá estar incluida en su respectiva carpeta
  > 2. Se deberá incluir un reporte PDF con la descripción del problema y la solución implementada
  > 3. El reporte deberá incluir un análisis estadístico de tiempos de ejecución para distintas instancias de cada problema.
 
**Nota: El reporte deberá estar en formato de artículo con la plantilla IEEE Transaction con la siguiente estructura**
  1. Abstract
  2. Intrudución
  3. Estado del arte
  4. Marco teórico
  5. Metodología
  6. Resultados experimentales
  7. Conclusiones
  8. Referencias
