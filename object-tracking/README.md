# Programas de Tracking de Objetos con Huskylens y Micro:bit

En condiciones de baja luminosidad, puede suceder que la cámara permanezca constantemente en "learning" aunque el objeto ya esté identificado. A continuación, se detallan los programas de ejemplo desarrollados para mejorar el seguimiento de objetos con Huskylens y micro:bit.

## Descripción de Programas

1. **microbit-Huskylens---Simple-Object-Tracking.hex**  
   Programa para analizar la posición del objeto entrenado y mostrar su ubicación en la matriz de píxeles de la micro:bit mediante condicionales "if".

2. **microbit-Huskylens_SimpleObjectTracking-sounds.hex**  
   Mismo programa anterior, pero incluye sonidos para facilitar la identificación del objeto cuando está correctamente detectado.

3. **microbit-linear-object-tracking3.hex**  
   Programa con el mismo objetivo, pero ahora utilizando un ajuste lineal. Sin embargo, este enfoque resulta complejo para la micro:bit y su desempeño es subóptimo.

4. **microbit-linear-object-tracking4.hex**  
   Este programa divide la posición de la pantalla en coordenadas que corresponden directamente a los píxeles de la micro:bit, eliminando la dependencia del ajuste lineal.

5. **microbit-linear-object-tracking-5.hex**  
   En esta versión, se eliminaron variables intermedias y se asignan directamente los valores al `plot`, lo cual mejora considerablemente la velocidad de ejecución del programa.

6. **microbit-linear-object-tracking-6.hex**  
   La división se reemplazó por una multiplicación en decimal. No se observaron mejoras significativas en el rendimiento.

7. **microbit-seaShells2-jkd-version.hex**
	Object recognition para girar izq(ID:1), girar der(ID:2), acelerar(ID:3)No contamos con object recognition en nuestra version de software de husky lens, hay que actualizar el firmware
	
8. **microbit-maqueen_tag_orders_music.hex**
	Mismo programa pero enfocado a detctar april_tags 36, cuando esta detectando el tag identificado reproduce una alarma. El id:4 da maxima potencia a los motores, no utilizar.
	

	
## Objetivos e ideas

1. **Perseguir y explotar globos utilizando la plataforma maqueen-plus**
	Lo entrenamos con un determinado globo y en el momento que queda entrenado debe moverse hasta localizar el globo, en ese momento se pone a perseguirlo hasta que lo toque con una aguja y lo explote por lo que volverá al punto de buscar objetivos.
	
	
	
