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
