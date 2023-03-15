# Algoritmos-Complejos

## Algoritmo de ordenamiento Sort

## Alogoritmo de ordenacion Quick Sort
 Encuentra un punto de corte en el conjunto, en el vector, siempre comparando con el punto de corte hasta que el algoritmo este completamente ordenado.

## Merge Sort
 Divide el algoritmo y sus mitades en 2 y asi sucesivamente, va a ver un punto en el que el agoritmo solo tenga 2 elementos separados, si estan ordenados, se dejan igual si no lo estan, lo giran, 
 una vez girado desacemos las operacion(desjuntar el vector y unirlo de nuevo)/ cuando fusionamos dos grupos que no estan ordenados los giramos nuevamente.

## Busqueda Binaria
Algoritmo para encontrar elementos en un vector ordenado, que este ordenado nos permite encontrar el item de una forma muy rapida, sin tener que recorrer todo el vector.
La busqueda Binaria nos acelera las busquedas.

## Algoritmos de Grafos(vfs dfs)
Son capaces de decir la distancia de cada uno del grafo con respecto al origen.

## Algoritmo de Dijkstra
Sirve para encontrar caminos en grafos, teniedno en cuenta el costo de un nodo a a uno b. encntramos el camino que minimiza el peso.

## Conclucion
 Aveces tenemos que encontrar una forma de solucionar el problema no resolverlo, ya que nos puedes ahorrar tiempo y alamacenamiento.
 De esta forma la solucion del problema se puede ver como un arbol, implemtacion que se realizan por la poda de los 2 caminos(el que tenga el coste menor)
 Estos sistema de poda no son perfectos. Finalmente estos tipos de algoritmos son utilizados para resolver problemas complejos, que requieren de soluciones complejas o dificiles.

# Analisis de Algoritmos
 Los desarrolladores se pasan la vida buscando el algoritmo mas eficiente de todos los demas, el como se guarda, busca, ejecuta la informacion, 
 el algoritmo mas rapido
 Como por ejemplo:
 cuando aplicamos un desenfoque en photshop queremos que tarde segundo no horas, y para eso buscamos la mejor solucion.Los filtros sean isntantaneos, quieremos como usuarios la velocidad de los algoritmos
 La busqueda de la eficienciencia para buscar la velocidad, usando metodos para analisar los algoritmos.

 Definir un concepto que podamos utiulizar para algoritmos y para estrucutras de datos-
## Medicion de eficiencia o Notacion Asintotica
 Sirve para anlisar el coste de un algoritmo en funcion de varios parametros, por ejemplo el tamaño de su entrada

 Si el vector tien un solo elemento solo tiene un coste de 1 pero si tiene 2 elementos estaremos realizando 4 operaciones , con estas gfraficas podemos ver caun rapido empeoran los diversos algoritmos.
 ## queremos ver como evoluciona el coste, realikzando estas simplificaciones podemos agrupar los algoritmos en diferentes conjuintos

Funciones que definen sus costos en conjuntos
Nos permite definir muy facil estas funciones con 5 conjuntos, utilizando 5 simbolos que ajustan las funciones

o grande: son todas aquellas funciones que cumplen una condicion, es decir en una fucnion que apartir de cierto punto concreto siempre es = a alguna funcion de la forma cuando tienden a infinito acaban siendo siempre a alguna funcion que sea linea

omega grande: cota inferior
z grande: combinacion de los dos anteoriores, a partir de cierto valor se mantiende enima de c1 gx o por debajo de la funcion siempre se mantiene en medio, cuota ajustada.
con esto podemos agruapr los costes algoritmos en funcion de las familias a cual pertencen.
la notacion asintortiraca se usa para analisasr el coste cuando n tiende a infinito por eso esta el punto inicial el punbto del que contamos
si este va creciendo hasta el infinito 
o pequeña: esto debe cumplirse para todas las c , funciones por debajo que siguen las funcion g de x

omega pequeña: La funcion tiene que estar por debajo de 

para econtrar datos de vectores o arrays, poder acceder mediante indice, es por eso que el coste del algoritmo es lineal,
el array debe estar ordenado buscar el ´punto medio del vector y comprobar que el valor qu estsas buscando sea 
