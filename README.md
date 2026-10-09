# Cuaderno-Robótica 4ºESO
Hola soy Alejandro Esquinas y desde aquí explicare las actividades que iremos haciendo a lo largo del año.

Placa de arduino 1.

<p align="center">
<img src="https://github.com/Elrayoproplayerr/Cuaderno-Robotica/blob/442a97637e30869ebea8ee00c6dd925c190251d7/Pasos%20Previos/Imagenes/arduinounopines.png" />
</p>

Este reto consiste en conseguir que un led se encienda primero mientras el otro permanezca apagado y así sucesivamente.

<p align="center">
<img src="https://github.com/Elrayoproplayerr/Cuaderno-Robotica/blob/b0c452fa2bd8076c0d4a655e676510d10db24bcd/Pasos%20Previos/Imagenes/codigo.png" />
</p>

void setup(): se ejecuta una sola vez al iniciar el programa y configura los pines 13 y 12 como salidas.
void loop(): repite continuamente las instrucciones.
digitalWrite(13, HIGH): enciende el LED del pin 13.
digitalWrite(12, LOW): apaga el LED del pin 12
delay(1000): espera 1 segundo.

Después,el LED del pin 13 se apaga y el del pin 12 se enciende,y vuelve a esperar 1 segundo.

<p align="center">
<img src="https://github.com/Elrayoproplayerr/Cuaderno-Robotica/blob/204bfa3f6ec7c9244772b8a26c6dc0eca53b57f9/Pasos%20Previos/Imagenes/simulacion.png" />
</p>

<p align="center">
<img src="https://github.com/Elrayoproplayerr/Cuaderno-Robotica/blob/49e05701a90dfb24935629585f35197e44cc46b3/Pasos%20Previos/Imagenes/simulacion%202.png" />
</p>



