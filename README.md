# RTC-DS3221

Módulo RTC I2C basado en el chip de precisión DS3231.
La temperatura es el parámetro que más afacta a la precisión de un RTC por lo que este módulo está especialmente indicado para entornos con cambios de temperatura muy pronunciados, por ejemplo, en cuadros eléctricos expuestos al sol. La precisión que alcanza el DS3231 es de +/-0.432 segundos/día o lo que es lo mismo, +/-2 minutos por año dentro del rango de temperatura desde -45ºC hasta +85ºC.
 
Características:
- Alimentación a 5V.
- Pila de respaldo CR1220 incluida (duración, 8 años).
- Precisión: +/-2 minutos/año
- Rango de temperatura de funcionamiento: -45ºC hasta +85ºC
- Bus I2C.
- Señal de interrupción por alarma.
- Librería para Arduino recomendada: https://github.com/adafruit/RTClib
