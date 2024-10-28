En situaciones de luminosidad baja puede pasar que la cámara aparezca todo el tiempo en "learning" aunque el objeto ya está identificado.

1. microbit-Huskylens---Simple-Object-Tracking.hex
	-Programa para analizar la posición del objeto entrenado y mostrar su posición en la matriz de píxeles de la microbit utilizando condicionales "if".
2. microbit-Huskylens_SimpleObjectTracking-sounds.hex
	-Mismo programa con sonidos para saber si estamos identificando el objeto o no más fácilmente.
3. microbit-linear-object-tracking3.hex
	-Programa con el mismo objetivo pero ahora realizamos un ajuste lineal, esto parece algo demasiado complejo para la microbit y funciona bastante mal.
4. microbit-linear-object-tracking4.hex
	-Ahora dividimos la posicion de la pantalla para pasarla a una coordenada de los pixeles de la microbit y no depender de la función del ajuste lineal.
5. microbit-linear-object-tracking-5.hex
	-Hemos quitado las variables para asignar al plot la lectura directamente, se nota que ahora el programa funciona mucho más rápido.
6. microbit-linear-object-tracking-6.hex
	-Hemos cambiado la division por una multiplicacion en decimal. No apreciamos mejoras importantes.
