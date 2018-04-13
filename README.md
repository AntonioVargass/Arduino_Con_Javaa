PRACTICA ARDUINO CON JAVA DISPLAY  SERIAL

Nombre: Vargas Arevalo Juan Antonio

Fecha 12 de abril de 2018

Material: -Protobot -Arduino genuino -Pantalla LCD Display 16x2 -Cables -Potenciometro -Sensor de temparatura y humedad -Recistencias de 220

OBJETIVO

El objetivo de esta practica es mostrar en el display LCD la temperatura añadiendo un plus que muestre tambien la humedad mediante una comunicacion con Java y Arduino.

DESAROLLO

Un display LCD (Liquid Crystal Display) es un display alfanumérico de matriz de puntos (dot-matrix) que sirve para mostrar mensajes a través de caracteres como letras, números o símbolos. La placa del display viene equipado con un microcontrolador (normalmente el modelo HD44780) que se encarga de generar los caracteres, polarizar la pantalla, desplazar el cursor… Además, también viene equipado con una memoria ROM donde están almacenados los caracteres a través de una matriz de puntos, y una memoria RAM donde se pueden almacenar caracteres creados por nosotros. Estos displays disponen de unos pins para conectar un microcontrolador (en nuestro caso Arduino) para poder dar instrucciones al display.


En esta práctica se mostró la temperatura en la pantalla LCD mediante una conexión Java y Arduino   además se mostró la humedad como un plus en la práctica.
Para realizar la conexión Arduino – Java se utilizó la librería DHT y para la clase en java se utilizaron las siguientes:
PanamaHitek_Arduino-3.0.0-javadoc.
PanamaHitek_Arduino-3.0.0-sources.
PanamaHitek_Arduino-3.0.0.
Más otras 2 utilizadas para las clases que se muestran el programa.
Ya que se realizó la conexión en java se muestra la interfaz que se desarrolló mostrando el puerto donde se conectará.
Comunicar: que es el botón que realiza la conexión.
Temperatura y humedad: donde se muestra la salida de dichos datos.
Texto de comunicación: que es un mensaje inicial de bienvenida.
Enviar y Cerrar: son 2 botones el de enviar como su nombre lo indica envía los datos al display  LCD y cerrar cierra la ventana:
Al dar click en enviar en el display muestra los datos mencionados con la ayuda de nuestro sensor de temperatura y humedad. 

Con el potenciómetro se regula el contraste de la pantalla permitiendo una visibilidad ajustable de los datos.

El proyecto de Arduino tiene como nombre Arduino_con_java_Pantalla.
EL proyecto en Java tiene como nombre comunicación.


Todo esto se realizó con licencias de código abierto tanto como de Java y Arduino.


CONCLUSIÓN

En lo personal esta práctica me gustó mucho ya que   nos permitió conectar dos entornos distintos de programación y además de conocer la funcionalidad del display LCD  y  del sensor de temperatura y humedad que se me hizo muy interesante. 
