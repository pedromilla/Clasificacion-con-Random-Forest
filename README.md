# Machine Learning, clasificación con Random Forest

Implementación de Random Forest para predecir si el usuario que visita un sitio web usa como sistema operativo Windows, Macintosh o Linux, mediante clasificación.
La información de entrada son 4 características que se extraen de una web que utiliza Google Analytics. Las características son:

-	Duración de la visita en Segundos
-	Cantidad de Páginas Vistas durante la Sesión
-	Cantidad de Acciones del usuario (click, scroll, uso de checkbox, sliders,etc)
-	Suma del Valor de las acciones (cada acción lleva asociada una valoración de importancia)

Como la salida es discreta, asignaremos los siguientes valores a las etiquetas:

-	0  Windows
-	1  Macintosh
-	2  Linux
