# ExamenFinal
# Billetera electrónica para una feria

**Como es de su conocimiento al ir a juegos de feria se debe comprar en cada juego el ingreso o en otras se compra un paquete de tickets y se puede accedes a cierto numero de juegos. Pero se tiene un parque que ya no quiere utilizar efectivo, en su lugar quiere utilizar una aplicación que funcione como una billetera electrónica.**

**Grupo de trabajo y roles**

El grupo de trabajo consta de 5 personas las cuales se mencionan a continuación así como sus roles.

Jonathan Cameros - Jefe de proyecto
José Díaz - Desarrollador
Diego Oliva - Líder de documentación
José Chacón - Desarrollador
Brandon Pineda - Diseñador gráfico y UX

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


