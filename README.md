# Proyecto-Tercer-Parcial

OBJETIVO PRINCIPAL:

OBJETIVOS SECUNDARIOS:

MARCO TEORICO:
![image](https://user-images.githubusercontent.com/116833736/221909864-8366940c-f872-4f41-b9c6-a9ec85b014f0.png)
![image](https://user-images.githubusercontent.com/116833736/221909888-9ec94399-e548-4021-a57a-d1d62634d1a3.png)
![image](https://user-images.githubusercontent.com/116833736/221909899-cf6ac250-4fd4-4f19-9101-d681a1c2b8ef.png)

MATERIALES:

* Protoboard
* Un censor integrado LM35
* Un amplificador operacional LM358
* Un potenciómetro de 100k
* LED rojO 
* LED verde
* 2 resistencias de 470 ohm
* 1 resistencia de 10k Ohm
* Multimetro

CIRCUITO:
![image](https://user-images.githubusercontent.com/116833736/221910409-28735889-7765-412b-aba7-f94dcaaae64e.png)

PROCEDIMIENTO:

Conectamos el sensor LM35 al protoboard al positivo y negativo respectivamente, asi mismo conectamos el Op-Amp al protoboard al positivo y negativo respectivamente, conectamos el Op-Amp al sensor LM35 y realizamos un puente a la salida para conectar las resistencias y a los leds para que se prendan con el amplificador, y por ultimo conectamos el potenciometro al positivo y negativo respectivamente en el protoboard y lo comunicamos con el Op-Amp para que este transmita la señal que necesitamos. A continuacion se comprueba el circuito.

PARA COMPROBAR EL CORRECTO FUNCIONAMIENTO DEL CIRCUITO:

Realizamos las conexiones que se necesitan para que el circuito funcione correctamente, una vez realizado todo esto conectamos un multimetro al potenciometro para establecer el voltaje pico que debe alcanzar el sensor de temperatura para prender el led color rojo, una vez estableecido esto conectamos el multimetro al sensor de temperatura y medimos el valor inicial.
Empezamos a calentar el sensor lo suficiente como para comprobar que los leds se prenden correctamente; en el multimetro debe notarse la diferencia de voltaje cada que el sensor se vaya calentando poco a poco hasta que alcance la temperatura deseaada. El led verde debe estar prendido desde un principio hasta que el sensor alcance el voltaje estabelcido por el potenciometro, una vez llegado a este valor se debe apagar y prender el de color rojo indicando que la temperatura igualó o sobrepaso el establecido.

COMO FUNCIONA EL PROYECTO:

Se conecta el sensor integrado LM35 para medir la temperatura, pero este necesita un amplificar la señal que envia este sensor mas una condicion logica de trabajo para poder activar Los LEDS, en esta ocasion utilizaremos el amplificador operacional (Op-Amp) LM358, este Op-Amp realiza operaciones basicas como la suma, resta, multiplicacion o division, asi como otras como la comparacion o logaritmico, pero en este caso se utilizará solo la de comparación. En el pin 3 entra lo que es la señal que envia el sensor, en el pin 2 iria el potenciometro que vamos a utilizar funcionando como un divisor de voltaje entre positivo y negativo, y en el primer pin se conecta cada LED para que estos funcionen como indicadores del correcto funcionamiento del circuito.
Este circuito funciona ya que el sensor mide 10mV por cada grado centigrado que detecta, este se va a comparar con el voltaje del potenciometro gracias al Op-Amp que utilizamos, y el resultado se observara con cada led.

IMAGENES DEL CIRCUITO ARMADO:

![image](https://user-images.githubusercontent.com/116833736/221911453-3bfbad23-91d7-4783-bee8-940faa90cbef.png)
![image](https://user-images.githubusercontent.com/116833736/221911666-f3c26a63-0d49-45aa-82ab-6852e68b02a6.png)
![image](https://user-images.githubusercontent.com/116833736/221913722-01fedc8f-d3c9-47a4-a1c5-748acf3cb508.png)

VIDEO:

https://youtube.com/shorts/X4FtWjnT7wc

CONCLUSIONES:


BIBLIOGRAFIA:

_Floyd, T. L. (2007). Principios de circuitos electricos (8.a ed.). Pearson**
