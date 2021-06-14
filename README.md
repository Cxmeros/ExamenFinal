# ExamenFinal
# Billetera electrónica para una feria

**Como es de su conocimiento al ir a juegos de feria se debe comprar en cada juego el ingreso o en otras se compra un paquete de tickets y se puede accedes a cierto numero de juegos. Pero se tiene un parque que ya no quiere utilizar efectivo, en su lugar quiere utilizar una aplicación que funcione como una billetera electrónica.**

**WIKI**

[Ir a la wiki](https://github.com/Cxmeros/ExamenFinal/wiki)

**Releases**

V1.0
[Ir a la release](https://github.com/Cxmeros/ExamenFinal/releases/tag/v1.0)

**Grupo de trabajo y roles**

El grupo de trabajo consta de 5 personas las cuales se mencionan a continuación así como sus roles.

- Jonathan Cameros - Jefe de proyecto
- José Díaz - Desarrollador
- Diego Oliva - Líder de documentación
- José Chacón - Desarrollador
- Brandon Pineda - Diseñador gráfico y UX

**Requerimientos del sistema**
 
- 	Pagar el uso de los juegos con acercar el teléfono a la máquina, esto ocasiona que se descuente cada juego hasta terminar su saldo en caso se compró un paquete con limite o si es el caso sin restricción permitir el uso de los juegos de forma indefinida de veces.
- 	El usuario por medio de la aplicación deberá comprar un paquete, los paquetes pueden ser:

      -10 juegos
      -20 juegos
      -Sin restricción (sin límite de juegos)
      
- 	Si se quiere comprar otro paquete se puede hacer.
- 	La compra puede hacerse solo de forma electrónica o tarjeta de crédito/debito.
- 	Se debe llevar el control de los ingresos y cortes de caja diarios
- 	Llevar una estadística de los juegos utilizados y cantidad de juegos utilizados por los paquetes sin restricción, esta última estadística es 
        vital para ver la rentabilidad de este tipo de compra.
        
|  Fecha 	    | Actividad |
|---	        |---	     |
|  10 de junio| [Incremento 1 Comunicación](https://github.com/Cxmeros/ExamenFinal/issues/2)	|
|  11 de junio| [Incremento 1 Planeación](https://github.com/Cxmeros/ExamenFinal/issues/3)	|
|  12 de junio| [Incremento 1 Modelado](https://github.com/Cxmeros/ExamenFinal/issues/4)	|
|  13 de junio| [Incremento 1 Construcción](https://github.com/Cxmeros/ExamenFinal/issues/5)	|
|  13 de junio| [Incremento 1 Despliegue](https://github.com/Cxmeros/ExamenFinal/issues/6)	|
|  14 de junio| [Incremento 2 Comunicación](https://github.com/Cxmeros/ExamenFinal/issues/7)	|
|  15 - 17 de junio| [Incremento 2 Planeación](https://github.com/Cxmeros/ExamenFinal/issues/8)	|
|  18 - 24 de junio| [Incremento 2 Modelado](https://github.com/Cxmeros/ExamenFinal/issues/9)	|
|  25 de junio - 24 de julio| [Incremento 2 Construcción](https://github.com/Cxmeros/ExamenFinal/issues/10)	|
|  25 - 26 de julio | [Incremento 2 Despliegue](https://github.com/Cxmeros/ExamenFinal/issues/11)	|
|  27 de julio| [Incremento 3 Comunicación](https://github.com/Cxmeros/ExamenFinal/issues/12)	|
|  28 de julio - 4 de agosto| [Incremento 3 Modelado y planeación](https://github.com/Cxmeros/ExamenFinal/issues/13)	|
|  5 de agosto - 1 de septiembre| [Incremento 3 Construcción](https://github.com/Cxmeros/ExamenFinal/issues/15)	|
|  2 - 3 de septiembre | [Incremento 3 Despliegue](https://github.com/Cxmeros/ExamenFinal/issues/14)	|



**Pagos por NFC**

La tecnología NFC existe desde hace años, pero es en los últimos tiempos cuando nos insisten para hacer pagos con ella

Las siglas NFC corresponden a Near Field Communication, una tecnología de comunicación de corto alcance, como podría ser el bluetooth.

![](https://github.com/Cxmeros/ExamenFinal/blob/main/img/450_1000-63.jpg)

Ofrece una tasa de transferencia de datos muy escasa (unos 424 kbit/s) y está pensada para actuar en labores de identificación de manera rápida y segura.

El NFC está presente en numerosos dispositivos móviles (smartphones, cámaras y tablets) y su uso más generalizado consiste en asociarlos con un altavoz compatible o entre sí para intercambiarse información.

Es la tecnología que se esconde detrás de los pagos que haces con el móvil a distancia (el rango de alcance es de unos veinte centímetros) y, en este caso, sin necesidad de emparejar previamente dos dispositivos.

La principal ventaja de la tecnología NFC es la velocidad de comunicación instantánea. A pesar de eso, uno de sus puntos negativos es que tiene una distancia de transmisión muy reducida. Solo funcionará si el dispositivo móvil está a como mucho 20 centímetros del terminal de pago.

Dos son los modos de funcionar que tiene la tecnología NFC:

**Activo:** Ambos dispositivos se encuentran enchufados y se genera un campo electromagnético gracias al que se intercambian los datos.

**Pasivo:** Solo uno de los dispositivos se encuentra encendido. Es el otro el que aprovecha el campo magnético del primero para intercambiar los datos.

Además del pago por móvil, la tecnología NFC tiene otros dos usos:

**Identificación:** El ejemplo más claro es el de los abonos de autobús. Gracias a la tecnología NFC, se podrá acercar el teléfono móvil al lector y que se descuente el precio del billete sin necesidad de llevar ningún otro tipo de documentación.

**Recogida/intercambio de datos:** En este punto, se combina la tecnología NFC con las etiquetas RFID. Gracias a esta combinación, se puede establecer dónde se encuentra una persona o recibir información de un evento o una tienda.

# Diagrama detallado de la relación de cada módulo con la propuesta inicial
![](https://github.com/Cxmeros/ExamenFinal/releases/download/v1.0/diagrama.png)

# Prototipo de interfaz de usuario

**Menú principal**

![](https://github.com/Cxmeros/ExamenFinal/releases/download/v1.0/Vista.jpeg)


**Escaneo de ticket**

![](https://github.com/Cxmeros/ExamenFinal/releases/download/v1.0/Vista2.jpeg)


