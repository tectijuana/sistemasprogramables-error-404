# sistemasprogramables-error-404

_Cierre de bloque 1_
<p align="center">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fthumbs.dreamstime.com%2Ft%2Ferror-isolated-icon-simple-element-illustration-programming-concept-icons-editable-logo-sign-symbol-design-white-142291263.jpg&f=1&nofb=1">
</p>

# ![](https://images.cooltext.com/5387873.png)

<a href="http://cooltext.com" target="_top"><img src="https://cooltext.com/images/ct_pixel.gif" width="80" height="15" alt="Cool Text: Logo and Graphics Generator" border="0" /></a>

## CMOS AR0134 Camera Module 1/3-Inch 1.2MP Color Module
___
### Descripción:

El módulo **AR0134** es un módulo de cámara de color con obturador global de 1/3 de pulgada y 1.2MP que se puede operar en su modo predeterminado o programado para el tamaño del marco, la exposición, la ganancia y otros parámetros. La salida del modo predeterminado es una imagen de resolución completa a 54 cuadros por segundo (fps). Produce datos en bruto de 12 bits, utilizando los puertos de salida paralelos. El dispositivo puede funcionar en modo de video (maestro) o en modo de disparo de cuadro. Las señales **FRAME_VALID** y **LINE_VALID** se emiten en pines dedicados, junto con un reloj de píxeles asincrónico. Se puede programar un pin FLASH dedicado para controlar la iluminación del LED externo o de la exposición del flash. El AR0134 incluye características adicionales para permitir la sintonización específica de la aplicación: ventanas, control de exposición automática ajustable, corrección automática del nivel de negro, sensor de temperatura a bordo y salto de fila y digital binning El AR0134 es un sensor de exploración progresiva que genera un flujo de datos de píxeles a una velocidad de cuadro constante. Utiliza un bucle de fase bloqueada (PLL) en el chip que se puede habilitar opcionalmente para generar todos los relojes internos a partir de un solo reloj de entrada maestro que funciona entre 6 y 50 MHz. La tasa de píxeles de salida máxima es 74.25 Mp / s, correspondiente a una velocidad de reloj de 74.25 MHz.
___
### Ventajas de los sensores CMOS respecto a los sensores CCD  
- Consumo eléctrico muy inferior  
- Son más económicos porque necesitan menos componentes externos  
- Pueden leer un mayor número de píxeles de forma simultánea  
- El conversor digital puede estar integrado en el mismo chip  
- Escaso o inexistente Blooming ("Smear")  
- Mayor flexibilidad en la lectura (Previsualización más rápida, vídeo,...)  
- Permiten la exposición y lectura de los píxeles de forma simultánea  
- Otras topologías posibles (el sensor SuperCCD de Fujifilm emplea una construcción en forma de panel (octogonal) para los píxeles)  
- Distintos tipos de píxeles (según tamaño y sensibilidad) combinables  
- Muy alta frecuencia de imagen en comparación a un CCD del mismo tamaño  
___
### Desventajas de los sensores CMOS respecto a los sensores CCD
- Menor superficie receptora de la luz por píxel  
- Menor uniformidad de los píxeles (mayor ruido de patrón fijo-FPN)  
- Efecto "jelly" o inestabilidad en la imagen con movimientos rápidos (se tuerce el vídeo) o flashes debido al tipo de obturación giratoria que utiliza.  


___
### Catacteristicas:
**Resolución:** 1280 * 960  
**Resolución:** 600TVL  
**Dimensiones:** 12.5mm * 12.5mm * 17mm  
**Iluminación:** 0.5LUX  
**Formato:** PAL / NTSC  
**Fuente de alimentación:** 3.7-5V 100mA  
**Lente de audio:** Gran angular 1.8mm (170 grados)  
**Sensor de imagen:** 1/4 CMOS image sensor  
**Área de sensibilidad:** 3.5964mm x 2.7084mm  
648 pixels **(horizontal)** × 488 **(vertical)**  
**Frecuencia de escaneo horizontal:** 15.625KHz  
**Frecuencia de escaneo vertical:** 50Hz  
**Obturador electrónico** 1 / 50-1 / 80000 (seg) 1 / 60-1 / 80000 (seg)  
**SNR ≥48dB (AGC OFF)**  
**Iluminación mínima:** 0.1 Lux / F1.2  
**Señal de video compuesto:** 1.0Vp-p 75Ω  
**Lente estándar:** 1.8 mm  
**Especificaciones PCB (Circuito impreso):** 20mm*20mm  
**Potencia:** DC5V ± 10% 70mA ± 10%  
**Temperatura de operación :** -10 ℃ ~ 60 ℃ RH95% Max  
___
### Aplicaciones:

- Seguridad  
- Imagenes de alto rango
- Vigilancia
- Visión de dron 
- Automatización
___
### Contenido del paquete:  
1 x Arducam CMOS AR0134 1/3-Pulgadas 1.2MP Modulo de camara a color
___
### Imagenes producto:

![](http://imgfz.com/i/X3xFv1J.png)
___
### Diagrama de bloque

![](http://imgfz.com/i/lz40gtD.png)
___
### Dimensiones del sensor
![](http://imgfz.com/i/0nQhxvX.png)
___
### Pines del sensor
![](http://imgfz.com/i/dpaFWCi.png)
| No.pin | Nombre de pin | Tipo    | Descripción                      |
|--------|---------------|---------|----------------------------------|
| 1      | GND           | Tierra  | Entrada a tierra                 |
| 2      | Flash         | Salida  | Control de salida de flash       |
| 3      | Trigger       | Entrada | Entrada de exposicion de color   |
| 4      | VSYNC         | Salida  | Indica si la ventana esta activa |
| 5      | HREF          | Salida  | Indica los pixeles activos       |
| 6      | DOUT11        | Salida  | Datos de salida 11               |
| 7      | DOUT10        | Salida  | Datos de salida 10               |
| 8      | DOUT11        | Salida  | Datos de salida 9                |
| 9      | DOUT11        | Salida  | Datos de salida 8                |
| 10     | DOUT11        | Salida  | Datos de salida 7                |
| 11     | DOUT11        | Salida  | Datos de salida 6                |
| 12     | DOUT11        | Salida  | Datos de salida 5                |
| 13     | DOUT11        | Salida  | Datos de salida                  |
| 14     | GND           | Tierra  | Tierra                           |
| 27     | VCC           | Voltaje | Entrada de voltaje               |
| 28     | VCC           | Voltaje | Entrada de voltaje               |
| 29     | VCC           | Voltaje | Entrada de voltaje               |
| 30     | VCC           | Voltaje | Entrada de voltaje               |
___

### Link de compra
[![](http://files.softicons.com/download/toolbar-icons/black-wireframe-toolbar-icons-by-gentleface/png/32/shop_cart.png)](https://www.uctronics.com/arducam-cmos-ar0134-1-3-inch-1-2mp-color-camera-module.html)
[CMOS AR0134](https://www.uctronics.com/arducam-cmos-ar0134-1-3-inch-1-2mp-color-camera-module.html) 
### PDF Datasheet
[![](http://files.softicons.com/download/toolbar-icons/plastic-mini-icons-by-deleket/png/32x32/File%20PDF-01.png)](http://www.arducam.com/downloads/modules/industrial/1Inch3_1.2_Megapixel_AR0134_CMOS_Camera_Module_DS.pdf)
[CMOS AR0134 Datasheet](http://www.arducam.com/downloads/modules/industrial/1Inch3_1.2_Megapixel_AR0134_CMOS_Camera_Module_DS.pdf)  
[![](http://files.softicons.com/download/toolbar-icons/plastic-mini-icons-by-deleket/png/32x32/File%20PDF-01.png)](http://www.arducam.com/downloads/modules/industrial/1Inch3_1.2_Megapixel_AR0134_CMOS_Camera_Module_DS.pdf)
[CMOS AR0134 Manual](http://www.arducam.com/downloads/modules/industrial/AR0134_DS.pdf)

___
### Integrantes team error 404

| Nombre                          | Participación | Calificación |
|:-------------------------------:|:-------------:|:------------:|
| Aulis Sanchez Victor Jair       |               |              |
| Hernández Gambino Kevin Josafat |               |              |
| Jiménez Ramírez Gonzalo David   |               |              |
| Ornelas López Karina Karla      |               |              |

