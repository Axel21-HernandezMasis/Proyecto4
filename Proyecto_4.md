# Proyecto4
Este proyecto fue dividido en 3 secciones
La primera realizar una simulación del sistema de comunicaciones como el daod en el ejemplo 3.2 con la diferencia de utilizar la
modulación QPSK en lugar de una modulación BPSK. 
Para esto se toma primeramente la imagen y se pasa por un modulador para esto se toman los siguientes pasos:
Se crea un periodo.
Se inicializala señal.
Se asigna la forma de la onda.
Se crean dos portadoras y se les da un funcionamiento para el paso de datos.
Se calcula  la potencia promedio de la señal modulada.
Para la sección del demodulador se toman los siguientes pasos:
Se toman la cantidad de muestras de la señal
Se calcula la cantidad de bits.
Se crea un vector para esos bits.
Se crea un vector para la demodulasión de la señal.
Se crea una señal de bit para la energía de la demodulación 
Se le da un funcionamiento lógico a la demodulasión.
Seguidamente se crea un graficador el cual muestra los datos de la gráfica, se importa la imagen y se codifican los pixeles
Se desmodula la señal y se genera la imagen.
Así mismo, se modelan las ondas para verificar sus daros.
Se gráfica el cambio entre señales observando que tiene pulsos anchos y cortos hasta estibilizarse.
Se gráfica la señal módulada BPKS, la modulada al salir del canal y la desmodulada.

Para la sección 2 se busca gráficar una función de estacionaridad y ergodicidad
Primero se crea un vector de tiempo, luego se toman las formas de onda posibles, se toma el promedio de las cuatro realizaciones por cada instante, se 
grafica el resultado teórico, practico y las realizaciones.

Para la última sección para medir la densidad de la potencia se toma en consideración las siguientes cosas, se crea primeramente
una señal de furier y se toman la cnatidad de muestras igual que en la sección anterior. Se creó un periodo de onda el cuaL media el tiempo de esta
y se gráifca el resultado el cual muestra una gráfica de la densidad de energía.
