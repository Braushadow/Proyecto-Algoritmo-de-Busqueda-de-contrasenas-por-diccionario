## Tecnica fuerza bruta (Algoritmo base)

El algoritmo de busqueda de contraseñas por diccionario en este caso funciona mas como un descifrador de contraseñas, pues una vez ingresada la contraseña a averiguar,
el algoritmo comienza a realizar combinaciones de letras y numeros intentando averiguar la contraseña ingresada. Si bien tiene un apartado para ingresar contraseñas a un diccionario
de ejemplo, este funciona de manera independiente al descifrador y no tiene mucho uso, estos cambios fueron considerados para posteriores avances del proyecto

Este algoritmo que solo utiliza fuerza bruta para averiguar contraseñas tiene una complejidad temporal Big O(Ch^max_len) donde:

Ch es la cantidad de letras y/o numeros posibles para la contraseña
max_len es el tamaño de la contraseña que fue ingresada

Como cualquier algoritmo de fuerza bruta, tiene una complejidad temporal exponencial.

Por otro lado, como el algoritmo no almacena las combinaciones realizadas, solo realiza incrementos por lo que tiene una complejidad espacial Big O(max_len), es decir, complejidad espacial lineal

