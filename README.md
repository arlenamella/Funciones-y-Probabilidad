# Funciones-y-Probabilidad
Evaluación 2 del Módulo Fundamentos de Data Science


Desafío 1: Generación de funciones

● Genere funciones para calcular la media y varianza de un vector. Debe cumplir con
los siguientes requisitos:
○ Ambas funciones deben ingresar un argumento x correspondiente al vector.
○ Las funciones deben contener docstrings con la documentación asociada a
la variable y retornar un valor utilizando return.
○ La función de la varianza se debe llamar a la función de la media.
● Utilice las funciones para reportar la información sobre goles_favor, goles_contra
y puntos.
(1 punto)

Desafío 2:
Utilizando el método groupby de la clase DataFrame, en conjunto con la función .agg de
pandas, calcule la media, la varianza y desviación estándar de la cantidad de goles a favor,
en contra y de la cantidad de puntos por continente.

● ¿En qué continente se observa una mayor cantidad de goles a favor?
● ¿En qué continente se observa una mayor cantidad de goles en contra?
● ¿En qué continente se observa una mayor cantidad de puntos en promedio?
(2 puntos)

Desafío 3: Simulaciones

● Genere una función generate_pet que devuelva de forma aleatoria un string
'perro' o 'gato' un número n de veces. Ejecútela un par de veces.
Tip: Puede utilizar la función np.random.choice para retornar elementos al azar.
● Aplique la función generate_pet para generar 20 muestras.
● ¿Cuál es la probabilidad de elegir un perro al azar? ¿Y un gato?
● Agregue np.random.seed(2) al inicio del chunk. ¿Qué diferencia hay cuando se
ejecuta la función varias veces luego de fijar la semilla?
(3 puntos)

Desafío 4: Función simuladora

● Genere una función llamada simulate_pets_prob que tome como argumento un
número finito de simulaciones a generar.
● La función debe simular dos situaciones young_pet y old_pet, y contar la
ocurrencia de los siguientes casos:
○ De las dos mascotas simuladas (young y old), contar las ocasiones donde
por lo menos una de las mascotas sea un perro.
○ De las dos mascotas simuladas, contar las ocasiones donde old_pet sea un
perro.
○ De las dos mascotas simuladas, contar las ocasiones donde los dos sean
perros.
● El método debe tener una semilla pseudoaleatoria de 1.
● El output de la función debe entregarse en términos de Probabilidad.
● De los tres escenarios, ¿Cuál es el menos probable? ¿Cuál es el más probable? ¿Por
qué?
(4 puntos)
