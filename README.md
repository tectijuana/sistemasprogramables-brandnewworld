# sistemasprogramables-brandnewworld
sistemasprogramables-brandnewworld created by GitHub Classroom
# 1.4 Proximidad
|  Integrantes  | Parrticipación | Calificación |
|---------------|----------------|--------------|
| a) jose loera |                |              |
| b  José Iñiguez          |                |              |
| c  Rodrigo Reyes            |                |              |
| d) Daniel García             |                |              |

# Sensor ultrasónico HC-SR04
## Descripción

En el creciente mundo de hoy, la atención y búsqueda de las más innovadoras tecnologías, sin duda son los Sensores. El propio sensor define qué esta tecnología se ha desarrollado es decir, la detección de la diana o la señal. La definición formal va como Un dispositivo que detecta la presencia o ausencia de un objeto, o ciertas propiedades de ese objeto, y provee retroalimentación sin entrar en contacto con ellos.

Los sensores miden la magnitud física y la convierten en una señal que puede ser leída fácilmente por el usuario o un instrumento electrónico simple. Hay varios sensores que trabajan en el campo de la ciencia hoy en día. Algunos sensores están hechos para ser utilizados en la vida cotidiana, mientras que hay muchos sensores que han estado facilitando los seres humanos en la investigación y el campo de la ingeniería.

**Sensor de proximidad**

El propósito básico de un sensor de proximidad es percibir lo que sucede con objeto sin estar en contacto con el. Un sensor de proximidad crea un campo alrededor de él mediante la emisión de radiaciones electromagnéticas. El haz de radiaciones electromagnéticas rastrea cualquier objeto u obstáculo en su camino. El término objetivo se utiliza para el objeto que un sensor de proximidad intuye en su camino. El sensor busca cualquier alteración realizada en su campo. El objetivo general sustituye a un determinado haz del campo o los obstáculos de su proyección. Diferentes campos o sensores se utilizan para detectar diferentes objetivos.

La falta de contacto físico con el objetivo por lo general hace un incremento en la vida de un sensor de proximidad. La ausencia de piezas mecánicas lo hace más confiable y le otorga una larga vida.

Rango nominal es el rango máximo del campo en el que un sensor puede detectar la presencia de cualquier objeto. Es la mayor distancia a través de la cual detecta el objetivo. La mayoría de estos sensores tienen un rango nominal ajustable. Su nivel se puede ajustar de acuerdo a la presencia de objeto.

Este sensor tiene un transmisor y un receptor. El transmisor emite rayos infrarrojos que, cuando rebotan después de tocar algún objeto, son captados por el receptor. Sobre la base del tiempo empleado por los rayos de volver al sensor, se puede determinar qué tan lejos o cerca está el objeto del sensor. Estos sensores se utilizan principalmente en aplicaciones donde se requiere la detección de corto alcance.

El sensor ultrasónico HC-SR04 nos permite medir distancias por medio de emisión y rebote de ultrasonidos. Para medir distancias con Arduino podemos hacerlo de diferentes maneras.
Para que no sea molesto al oído humano, utiliza ultrasonido a una frecuencia de 40 kHz. Estas ondas sonoras tienen una frecuencia muy por encima del espectro audible por los seres humanos.
El sensor funciona como un sonar, por rebote de la onda. El emisor del HC-SR04 envía un tren de ondas ultrasónicas cuando se activa la señal de disparo (trigger). Este sonido se refleja contra el objeto y retorna. El receptor detecta el momento en que retorna la onda y lo indica en la salida eco (echo).

**Tipos de Sensores de Proximidad**

Hay varios tipos de sensores de proximidad en el mercado aparte del ultrasónico HC-SR04 , que dependiendo del material a  detectar, las condiciones y el ambiente se utilizará un tipo de sensor de proximidad o otro.

*Sensores de Proximidad magnéticos:
Detectan la proximidad de un campo magnético, normalmente el objeto a detectar tiene un imán acoplado.
*Sensores de Proximidad inductivos:
Detectan la proximidad de objetos compuestos de materiales metálicos.
Sensores de Proximidad Capacitivos:
Detectan la aproximación de cualquier tipo de material.
Sensores de Proximidad Ópticos:
Detectan objetos por medios ópticos y electrónicos. Hay varios tipos de sensores de proximidad ópticos .
Sensores de barrera:
Consta de emisor y receptor enfrentados el uno al otro, detectando la interrupción del rayo de luz al cruzar un objeto entre medio.
Sensores de retroreflexion:
El emisor y el receptor están en el mismo cuerpo, haciendo que el receptor reciba la luz a través de un reflector.
Sensores de reflexión directa:
El emisor y el receptor están en el mismo cuerpo pero en este caso la reflexión la realiza el mismo objeto a detectar activando el receptor a su paso.
Sensores ópticos de proximidad con cables de fibra óptica:
Se puede aplicar como sensor de barrera teniendo emisor y  receptor enfrentados, detectando el objeto al pasar entre los dos. Los sensores de fibra óptica también tienen  modelos con emisor y receptor en el mismo encapsulado y reflexión directa.

## Caracteristicas 
 * Fuente De Poder :+5V DC
 * Corriente de Reposo : <2mA
 * Corriente Funcional : 15mA
 * Angulo Efectivo : <15°
 * Distancia Aproximada : 2cm – 400 cm/1″ – 13ft
 * Resolucion : 0.3 cm
 * Angulos Medibles: 30 Grados
 * Dimensiones : 45mmx20mmx15mm
 
## Conexiones 
 
 |  Sensor Ultrasonico HC-SR04 |  Arduino |
 |---------------|----------------|
|VCC|5V|
|Trig|Pin 11|
|Echo|Pin 12|
|GND| GND|
## Precios 
| Link  |  Precio(MXN)| Fuente  |
|---|---|---|
| https://www.amazon.com.mx/SainSmart-HC-SR04-Ranging-Detector-Distance/dp/B004U8TOE6/ref=sr_1_1?__mk_es_MX=ÅMÅŽÕÑ&keywords=HC-SR04&qid=1583390900&sr=8-1  | $127.92   | Amazon  |
| https://www.ebay.com/itm/1pcs-Ultrasonic-Module-HC-SR04-Distance-Measuring-Transducer-Sensor-for-Arduino/400985326881?epid=26029613210&hash=item5d5c968521:g:kLQAAOxyNyFS-xFw  | $19.80 | Ebay  |
| https://www.alliedelec.com/product/switchcraft/sr04/70931715/?gclid=Cj0KCQiAwP3yBRCkARIsAABGiPpPSaAQBJYqfoqvpv5UcJQ-2t-QMnHTq_X6Von2pmbVcsqOZw83n_kaAgT9EALw_wcB&gclsrc=aw.ds  | $177.85 |  Allied  |
| https://articulo.mercadolibre.com.mx/MLM-552023219-sensor-ultrasonico-hc-sr04-medicion-de-distancia-nivel-hcsr04-_JM?quantity=1#position=1&type=item&tracking_id=3a126476-e422-4175-a266-51c2ce8cf6cf  | $164 |  Mercado Libre  |

## Datasheet

|  Titulo |Tipo    |  Tamaño(KB) |Fecha   |
|---|---|---|---|
|https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf   | PDF|  78KB | 3 Junio 2018|


