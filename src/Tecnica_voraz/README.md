## Tecnica voraz en busqueda de contraseñas (Algoritmo de Huffman)

Principalmente, el algoritmo fue modificado para que esta vez cumpliera su objetivo de buscar contraseñas por medio de un diccionario. Desde distintas 
fuentes, obtuvimos grandes diccionarios de contraseñas comunes y/o faciles de averiguar almacenados en formato .txt, estos diccionarios los encontramos en 
distintas paginas web y repositorios orientados principalmente a la ciberseguridad.

Con los cambios realizados, el algoritmo ahora permite elegir entre distintos diccionarios para intentar averiguar las contraseñas ingresadas. 
Una vez que el algoritmo termina, muestra las contraseñas que fueron encontradas en la tabla de texto. 

Usamos el algoritmo de Huffman para la compresion de los archivos de texto que tienen las contraseñas. De modo que una vez que el programa es cargado, 
los archivos son comprimidos para ocupar menor cantidad de almacenamiento y una vez que el algoritmo termina y el programa acaba, los textos regresan a su 
estado original. 
