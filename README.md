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
| https://es.aliexpress.com/item/32477198302.html?spm=a2g0o.productlist.0.0.79fd5942cjP27m&algo_pvid=123ed171-5df1-4053-98f7-100ef661c3b8&algo_expid=123ed171-5df1-4053-98f7-100ef661c3b8-2&btsid=0bb47a1915834369393787902e1401&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_ | $13.69   | Aliexpress  |

## Ejemplo de Arduino


## Datasheet

|  Titulo |Tipo    |  Tamaño(KB) |Fecha   |
|---|---|---|---|
|https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf   | PDF|  78KB | 3 Junio 2018|
|https://angelmicelti.github.io/4ESO/ARD/detector_de_aparcamiento_con_ultrasonidos.html|ejemplo|||




