# TC1001S.ACT2
DOCUMENTACION ACTIVIDAD 2: MODIFICAR SNAKE

MODIFICACIONES REALIZADAS POR: 
RAMIRO GONZALEZ -A01422501  
EDUARDO MONTES -A00227522

CODIGO ORIGINAL OBTENIDO DE LA LIBRERIA FREEGAMES CON PYTHON DESDE CONSOLA,
COMANDO: PYTHON -M FREEGAMES COPY SNAKE



Para que la comida se moviera al azar un paso a la vez, se utilizaron las misma funciones de la linea 44 y 45
las cuales provocan que se cambie la posición de la comida cada vez que se haga un punto. Por lo tanto se colocaron 
estas funciones en la función de change en las líneas 24 y 25 la cual detecta cambios de posición según se muevan con las flechas del teclado.
Con esto cada vez que se cambie de posición la serpiente, se cambiará la posición de la comida.

Para el cambio de color entre la comida y la serpiente, se utizó la función Colorarrey en la línea 57 donde se eligieron 5 colores, y en la funciones de color para
la serpiente y la comida en las líneas 59 y 60, se llama esta función para que se seleccione un color de manera aleatoria.
