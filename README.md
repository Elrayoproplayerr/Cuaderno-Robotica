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

PULSADOR.

Este resto consiste en hacer que se encienda el led cuando presionemos el pulsador.

<p align="center">
<img src="https://github.com/Elrayoproplayerr/Cuaderno-Robotica/blob/0291b826f5191cd84c1765f1a1b627cdd6490158/Pasos%20Previos/Imagenes/codigo%20pulsador.png" />
</p>

El código hace que un LED conectado al pin 13 de Arduino se encienda durante 1 segundo y se apague durante otro segundo, repitiendo este proceso continuamente.
- setup(): configura el pin 13 como salida.
- loop(): enciende y apaga el LED continuamente.







Potenciómetro. Monitor serie.

__int P2 = A2;__

__float valor = 0;__

__float deceroauno;
void setup() {
   Serial.begin(9600);
}__

__void loop() {
   valor = analogRead(P2);
   Serial.println(valor);
   delay(20);
}__















































