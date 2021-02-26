Trivial versión 26/02/21
========================================================

NOTAS GENERALES
---------------

Juego de preguntas tipo Trivial con varias respuestas posibles.

· Jugar (las preguntas y respuestas se leerán de una base de datos y serán mostradas al usuario secuencialmente, a las que irá respondiendo). 

· De cada pregunta se almacenarán 3 posibles respuestas (que serán mostradas al usuario) y la respuesta correcta, para que cuando éste elija una, se pueda autocorregir, 
informando al usuario si dicha respuesta es correcta o no.

· Se implementará una clase Pregunta.java (POJO) para ir creando objetos de ese tipo a medida que se va leyendo la base de datos.

· Se implementará un sistema de puntos para contabilizar las preguntas acertadas y las que no. 

· Añadir preguntas (el usuario podrá añadir más preguntas a la base de datos).

· Importar preguntas (el usuario podrá importar preguntas desde un archivo EXCEL con formato prefijado, añadiéndolas a a la base de datos).

· Una vez acabe cada partida, se pedirá al usuario si quiere que se muestre un informe en PDF con el resultado de la misma (la puntuación obtenida, la corrección de las preguntas, etc.: partida.pdf)

· Una vez acabada la partida, se pedirá al usuario que introduzca su nombre, si no existe el registro en la base de datos de récords se creará, registrando así el nombre del usuario y los puntos obtenidos. 
Si el fichero de records existe, se comprobará si existe un registro para el usuario ingresado, si no existe se creará una nueva línea en el fichero y si ya existe, 
se comprobará la puntuación actual obtenida con la registrada, almacenándose la nueva puntuación en el caso de ser mayor que la registrada.

· Permitir ver los récords almacenados ordenados por puntuación, visualizándose de mayor a menor.

· Diseñar un menú para poder elegir las opciones para ejecutar la aplicación.

NOTAS ESPECIFICAS
-----------------

No existen.

OTRAS CONSIDERACIONES
---------------------

No se consideran.