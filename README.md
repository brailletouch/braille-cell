** About for development of different braille cells / para desarrollo de distintas celdas brailles

![Figura 1. Vista lateral de una celda Braille piezobimorfa típica.](https://github.com/brailletouch/braille-cell/blob/main/images/braillecell.jpg)

Figure 1. Lateral view of a typical piezo bimorph Braille cell. / Figura 1. Vista lateral de una celda Braille piezobimorfa típica.

# English 

For more than 50 years, there have been many attempts to develop paperless Braille displays that provide visually impaired readers with access to digital information. These devices are designed as electronically upgradeable touchscreens that allow users to read Braille text that is dynamically displayed. The displays are designed as arrays of Braille cells, corresponding to the individual characters of the Braille code. The emerging world standard for upgradeable braille displays uses eight dots, arranged in two columns of four dots each. The height of each point relative to the reading surface must be individually controllable, to produce two states: high point and low point. This allows 256 different combinations to be represented, that is, 256 different Braille characters.

The complexity of developing such touch interfaces is related to the need for suitable actuation technologies capable of controlling every point of each cell on the entire screen, while minimizing size, weight, cost, and power consumption (especially for portable devices). To this end, electromagnets, bimetals, shape memory alloys, pneumatic drives, piezoceramic tabs, and many other actuation technologies have been extensively investigated, but efforts have only resulted in display devices at best. complicated and expensive.

Most of the upgradeable Braille displays available on the market have a single line of 20 to 80 Braille characters (cells) and cost several thousand US dollars. The OEM cost of commercially produced Braille piezoelectric cells is approximately US $ 35 per cell, or US $ 4.38 per Braille dot. Almost all Braille modules available today use piezoelectric ceramic bimorphic tabs to activate Braille dots. The piezoelectric tabs are mounted as a staggered stack of cantilevers, each with a Braille pin resting on its free end. Each tab can lift the top of the dome of its 1.5mm diameter Braille pin approximately 0.5mm above the reading surface. As shown in Figure 1, a typical module has four layers of pairs of tabs, side by side, mounted horizontally, below, and parallel to the top reading surface. Figure 1 also shows the associated data latch and required 200V driver circuitry built into each Braille cell module.

These Braille cell modules are mounted horizontally side by side, forming a single arbitrarily long cell line (typically 20, 40, or 80 cells). A maximum of two of these lines can be mounted together, end to end, resulting in a two-line display, although the size and cost of packaging limit most displays to a single line. Therefore, due to the drawback of long overhangs (Figure 1), modern upgradeable braille displays are limited to a single reading line, or at most, two lines. Full page Braille displays cannot be implemented with traditional piezo cantilever technologies because the actuation mechanism footprint for each Braille dot on a full page display must be in the range of 2.5mm 2 or less.

The aforementioned need obviously calls for new Braille display technologies. To facilitate the development of new electronic braille displays, the Center for Braille Innovation (CBI), established by the National Braille Press, Boston, MA, USA, is working to help Braille technology developers by focusing attention and resources financial The CBI also collects technical information related to Braille, such as the following summary of Braille usage requirements.

## Point parameters

Although the technical specifications for upgradeable braille displays are evolving, the values ​​listed in Table 1 are an attempt to present a better fit than current nominal 'standards'.

## Point height uniformity
As indicated in Table 1, the adjacent points should have a height uniformity of ± 0.05 mm. This is because Braille readers generally have a very low tolerance for uneven point heights. While reading Braille, most readers run their fingertips across the tops of the dots, so a raised dot that is much lower than adjacent raised dots may not be felt at all. Therefore, the points must have a uniform height, when in the raised state, and must not show

<p> & nbsp; </p>
<div class = "tableBox">
<table class = "table frame_top"> <caption>
<div class = "paragraph"> <b> <span> Table 1. Braille dot parameter specifications for upgradeable Braille displays. </span> </b> </div>
</caption> <colgroup> <col /> <col /> <col /> <col /> <col /> </colgroup>
<thead>
<tr valign = "top" class = "colsep0">
<th class = "colsep0 rowsep1"> <b> <span> Parameter </span> </b> </th>
<th class = "colsep0 rowsep1"> <b> <span> Minimum (mm) </span> </b> </th>
<th class = "colsep0 rowsep1"> <b> <span> Nominal (mm) </span> </b> </th>
<th class = "colsep0 rowsep1"> <b> <span> Maximum (mm) </span> </b> </th>
<th class = "colsep0 rowsep1 last"> <b> <span> Typical (mm) </span> </b> </th>
</tr>
</thead>
<tbody>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Diameter of point base </span> </td>
<td class = "colsep0 rowsep1"> <span> 1.4 </span> </td>
<td class = "colsep0 rowsep1"> <span> 1,5 </span> </td>
<td class = "colsep0 rowsep1"> <span> 1,6 </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 1,5 </span> </td>
</tr>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Height of point (assuming there is no depressing force from the user's finger) </span> </td>
<td class = "colsep0 rowsep1"> <span> 0.48 </span> </td>
<td class = "colsep0 rowsep1"> <span> 0.5 </span> </td>
<td class = "colsep0 rowsep1"> <span> 0.9 </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 0.7 </span> </td>
</tr>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Point height uniformity for adjacent points </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1 last"> <span> & plusmn; 0.05 </span> </td>
</tr>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Distance between centers of adjacent points perpendicularly in the same cell </span> </td>
<td class = "colsep0 rowsep1"> <span> 2,3 </span> </td>
<td class = "colsep0 rowsep1"> <span> 2,5 </span> </td>
<td class = "colsep0 rowsep1"> <span> 2.6 </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 2.45 </span> </td>
</tr>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Distance between the centers of the corresponding points in horizontally adjacent cells </span> </td>
<td class = "colsep0 rowsep1"> <span> 6.1 </span> </td>
<td class = "colsep0 rowsep1"> <span> 6.35 </span> </td>
<td class = "colsep0 rowsep1"> <span> 6.5 </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 6.42 </span> </td>
</tr>
<tr valign = "top" class = "colsep0">
<td class = "colsep0 rowsep1"> <span> Height of eight dot Braille cell lines </span> </td>
<td class = "colsep0 rowsep1"> <span> 12.25 </span> </td>
<td class = "colsep0 rowsep1"> <span> 13.25 </span> </td>
<td class = "colsep0 rowsep1"> <span> 13.75 </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 13 </span> </td>
</tr>
<tr valign = "top" class = "colsep0 last">
<td class = "colsep0 rowsep1"> <span> Point dome curvature radius </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1"> <span> - </span> </td>
<td class = "colsep0 rowsep1 last"> <span> 0.6-0.8 </span> </td>
</tr>
</tbody>
</table>
</div>
<div class = "tableDownloadOption"> </div>



# Español


Durante más de 50 años, ha habido muchos intentos de desarrollar pantallas Braille sin papel que proporcionarían a los lectores con discapacidad visual acceso a la información digital. Estos dispositivos están concebidos como pantallas táctiles actualizables electrónicamente que permiten a los usuarios leer texto en Braille presentado de forma dinámica. Las pantallas están diseñadas como matrices de celdas Braille, correspondientes a los caracteres individuales del código Braille. El estándar mundial emergente para pantallas braille actualizables utiliza ocho puntos, dispuestos en dos columnas de cuatro puntos cada una. La altura de cada punto con respecto a la superficie de lectura debe ser controlable individualmente, para producir dos estados: punto elevado y punto bajado. Esto permite representar 256 combinaciones diferentes, es decir, 256 caracteres Braille diferentes.

La complejidad de desarrollar tales interfaces táctiles se relaciona con la necesidad de tecnologías de actuación adecuadas capaces de controlar cada punto de cada celda de la pantalla completa, al tiempo que se minimiza el tamaño, el peso, el costo y el consumo de energía (especialmente para dispositivos portátiles). Con este fin, se han investigado extensamente electroimanes, bimetales, aleaciones con memoria de forma, accionamientos neumáticos, lengüetas piezo cerámicas y muchas otras tecnologías de actuación, pero, en el mejor de los casos, los esfuerzos solo han dado como resultado dispositivos de visualización complicados y costosos.

La mayoría de las pantallas Braille actualizables disponibles en el mercado tienen una sola línea de 20 a 80 caracteres Braille (celdas) y cuestan varios miles de dólares estadounidenses. El costo del fabricante del equipo original de las celdas piezoeléctricas Braille producidas comercialmente es de aproximadamente 35 dólares EE.UU. por celda, o 4,38 dólares EE.UU. por punto Braille. Casi todos los módulos Braille disponibles en la actualidad utilizan lengüetas bimorfas cerámicas piezoeléctricas para activar los puntos Braille. Las lengüetas piezoeléctricas están montadas como una pila escalonada de voladizos, cada uno con un pin Braille descansando en su extremo libre. Cada lengüeta puede levantar la parte superior del domo de su pin Braille de 1,5 mm de diámetro aproximadamente 0,5 mm por encima de la superficie de lectura. Como se muestra en la Figura 1 , un módulo típico tiene cuatro capas de pares de lengüetas, una al lado de la otra, montadas horizontalmente, debajo y paralelas a la superficie de lectura superior.La Figura 1 también muestra el pestillo de datos asociado y los circuitos del controlador de 200 V necesarios e integrados en cada módulo de celda Braille.

Estos módulos de celdas Braille están montados horizontalmente uno al lado del otro, formando una línea única de celdas arbitrariamente larga (típicamente 20, 40 u 80 celdas). Es posible montar un máximo de dos de estas líneas juntas, de punta a punta, obteniendo una pantalla de dos líneas, aunque el tamaño y el costo del empaque limitan la mayoría de las pantallas a una sola línea. Por lo tanto, debido al estorbo de los largos voladizos (Figura 1) , las pantallas braille actualizables modernas están limitadas a una sola línea de lectura, o como máximo, a dos líneas. Las pantallas Braille de página completa no se pueden implementar con las tecnologías tradicionales de lengüeta piezoeléctrica en voladizo porque la huella del mecanismo accionador de cada punto Braille en una pantalla de página completa debe estar en el rango de 2,5 mm 2 o menos.

La necesidad antes mencionada, obviamente, exige nuevas tecnologías de actuación Braille. Para facilitar el desarrollo de nuevas pantallas braille electrónicas, el Centro de Innovación Braille (CBI), establecido por National Braille Press, Boston, MA, EE. UU., Está trabajando para ayudar a los desarrolladores de tecnología Braille, centrando la atención y los recursos financieros. El CBI también recopila información técnica relacionada con Braille, como el siguiente resumen de los requisitos de la pantalla Braille.

## Parámetros de puntos

Aunque las especificaciones técnicas para las pantallas braille actualizables están evolucionando, los valores enumerados en la Tabla 1 son un intento de presentar un ajuste mejor a los 'estándares' nominales actuales.

## Uniformidad de la altura del punto
Como se indica en la Tabla 1 , los puntos adyacentes deben tener una uniformidad de altura de ± 0,05 mm. Esto se debe a que los lectores de Braille generalmente tienen una tolerancia muy baja a la falta de uniformidad en la altura de los puntos. Mientras leen en Braille, la mayoría de los lectores pasan la punta de los dedos por la parte superior de los puntos, por lo que es posible que un punto en relieve que esté mucho más abajo que los puntos en relieve adyacentes no se sienta en absoluto. Por lo tanto, los puntos deben tener una altura uniforme, cuando están en el estado elevado, y no deben mostrarse en absoluto, cuando están en el estado bajado.

## Desplazamiento de puntos
En el estado bajado, la parte superior de los puntos debe empotrarse al menos 0,025 mm por debajo de la superficie de lectura. Si la parte superior de un punto rebajado solo está a la altura de la superficie de lectura, la conformidad de la punta del dedo puede hacer que se sienta como si el punto estuviera ligeramente elevado sobre la superficie. Los lectores de Braille se molestan fácilmente con el "ruido" táctil de los puntos "fantasma" que se sienten como si no estuvieran completamente abajo.

## Fuerza de puntos
Debido a que es difícil caracterizar con precisión la fuerza motriz de los puntos Braille de 'buena sensación', hay mucho desacuerdo en los valores publicados para los requisitos óptimos de fuerza de bloqueo y retención. Además, algunos lectores tienen un toque ligero y pueden leer sin aplicar más de 5 g de fuerza en un punto con la punta del dedo. Otros lectores, con 'toque fuerte', pueden aplicar hasta 15 g de fuerza. Generalmente, con una fuerza de lectura de la yema del dedo de 5 g, un punto debe permanecer elevado dentro de 0,1 mm de su altura máxima sin carga. Cuando se aplica una fuerza de lectura de 15 g al punto, debe permanecer elevado al menos 0,25 mm por encima de la superficie de lectura. La altura de 0,25 mm ha sido la altura de referencia de medición de fuerza tradicional para la industria del Braille. Es algo histórico, porque los puntos impulsados ​​por los actuadores bimorfos piezocerámicos típicos normalmente descansan aproximadamente 0.25 mm por encima de la superficie de lectura en el estado sin alimentación: este es un punto a la mitad de la posición completamente elevada (altura máxima del punto) para un punto impulsado positivamente (0.5 mm nominalmente ). En particular, la respuesta de desviación de fuerza puede no ser necesariamente lineal. Por ejemplo, la mayoría de los actuadores piezoeléctricos modernos para pantallas Braille tienen algún tipo de topes rígidos para asegurar una buena uniformidad de la altura del punto elevado.

## Espesor de la celda
El grosor de la celda debe ser inferior a 30 mm, especialmente para aplicaciones portátiles, como tomadores de notas y asistentes digitales personales. Los módulos de pantalla Braille piezoeléctricos típicos tienen ahora aproximadamente 18 mm de grosor.

## Tiempo
Para la mayoría de las aplicaciones se desea un tiempo de configuración de puntos del orden de 100 ms, correspondiente a una velocidad de ciclo de puntos de 10 Hz. Sin embargo, una frecuencia del orden de 1 Hz puede ser tolerable para algunas aplicaciones con interacción limitada, como la lectura continua de páginas largas de texto en pantallas de varias líneas o de página completa.

## Ruido acústico
La mayoría de las aplicaciones requieren que las unidades Braille sean lo suficientemente silenciosas para funcionar en aulas, bibliotecas, reuniones y otros entornos intolerantes al ruido.

## Voltaje y potencia de conducción
La tensión de funcionamiento debe ser inferior a 300 V, tanto por motivos de seguridad como por los requisitos prácticos del circuito del controlador electrónico. Sin embargo, si se necesitan voltajes más altos, será necesario desarrollar un método de accionamiento de alto voltaje seguro que coincida. La mayoría de las aplicaciones requieren energía de batería para admitir la portabilidad, aunque algunas de las aplicaciones de pantalla Braille de página completa pueden tolerar un requisito de funcionamiento solo mientras la unidad está conectada a líneas de alimentación de CA.

## Detección táctil
Es muy deseable incluir la detección de la posición táctil con pantallas táctiles. Esto ya se está utilizando en las pantallas modernas de Braille de una sola línea, para enrutar el cursor y "hacer clic" en las opciones del menú que se muestran. La detección de la posición táctil también es importante para proporcionar atributos o información adicionales sobre una posición, y para combinar las ventajas de usar las salidas táctiles y audibles juntas de manera complementaria.

## Fiabilidad
La vida útil debe ser del orden de 10 7 ciclos para las pantallas de una sola línea y, en consecuencia, menor para las pantallas más grandes, de varias líneas o de página completa que se actualizan con menos frecuencia. Ciertos mecanismos de actuador Braille podrían tener una clasificación más apropiada en términos de decenas de miles (10 4 ) de horas de funcionamiento, en lugar del número de ciclos de puntos.

## Facilidad de servicio / limpieza y reparación de fallas
La limpieza y el mantenimiento de rutina deben ser algo que pueda realizar el usuario. Requerir que un dispositivo personal (por ejemplo, un asistente digital personal o un tomador de notas) sea enviado de regreso a la fábrica crea una dificultad severa para los usuarios que pueden no tener ningún método alternativo para acceder a sus notas e información durante la 'interrupción' del servicio.

## Incompatibilidad entre gráficos táctiles y Braille
Un buen espaciado de puntos de gráficos táctiles produce un espaciado de puntos de texto en Braille incorrecto y viceversa. Idealmente, las pantallas que se utilicen solo para gráficos táctiles y no para texto en Braille deben tener una separación de puntos aún más pequeña que los puntos Braille normales (preferiblemente <2,3 mm) y deben tener un diámetro de base de puntos correspondientemente más pequeño.

## Costo
Idealmente, los precios de las pantallas Braille deberían reducirse a unos pocos cientos de dólares, en lugar de a los miles actuales. Con precios en el rango más bajo, los dispositivos serían lo suficientemente asequibles como para que los miembros de la familia, los grupos religiosos, los sistemas de escuelas primarias y otros los compren para los estudiantes jóvenes.

## Nuestra propuesta de solucion.

La novedad de nuestro proyecto no está en un nuevo invento de celdas, sino en una nueva forma de lectura con 40 u 80 celdas virtuales que son sensores táctiles en lugar de celdas braille, sirven para tener una ubicación donde va cada letra y saber si el texto Está a la derecha centrada a la izquierda o junstificada. Las celdas virtuales nos permiten tener un mapa mental de la posición de las letras o caracteres. Con una mano tocamos las cerdas virtuales para ver la poción donde está la letra con la otra leemos la letra en la única celda física en Braille, de esta forma reducimos gastos en celdas, reducimos el consumo de energía, reducimos el tamaño y peso y se puede fabricar la celda prácticamente con cualquier tecnologías de actuación. pudido ser electroimanes, bimetales, aleaciones con memoria de forma, accionamientos neumáticos, lengüetas piezo cerámicas,  servomotores, solenoide, etc.




<p>&nbsp;</p>
<div class="tableBox">
<table class="table frame_top"><caption>
<div class="paragraph"><b><span>Tabla 1. Especificaciones de los par&aacute;metros de puntos Braille para pantallas Braille actualizables.</span></b></div>
</caption><colgroup><col /><col /><col /><col /><col /></colgroup>
<thead>
<tr valign="top" class="colsep0">
<th class="colsep0 rowsep1"><b><span>Par&aacute;metro</span></b></th>
<th class="colsep0 rowsep1"><b><span>M&iacute;nimo (mm)</span></b></th>
<th class="colsep0 rowsep1"><b><span>Nominal (mm)</span></b></th>
<th class="colsep0 rowsep1"><b><span>M&aacute;ximo (mm)</span></b></th>
<th class="colsep0 rowsep1 last"><b><span>T&iacute;pico (mm)</span></b></th>
</tr>
</thead>
<tbody>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Di&aacute;metro de la base del punto</span></td>
<td class="colsep0 rowsep1"><span>1.4</span></td>
<td class="colsep0 rowsep1"><span>1,5</span></td>
<td class="colsep0 rowsep1"><span>1,6</span></td>
<td class="colsep0 rowsep1 last"><span>1,5</span></td>
</tr>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Altura del punto (asumiendo que no hay fuerza de depresi&oacute;n del dedo del usuario)</span></td>
<td class="colsep0 rowsep1"><span>0,48</span></td>
<td class="colsep0 rowsep1"><span>0,5</span></td>
<td class="colsep0 rowsep1"><span>0,9</span></td>
<td class="colsep0 rowsep1 last"><span>0,7</span></td>
</tr>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Uniformidad de altura de punto para puntos adyacentes</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1 last"><span>&plusmn; 0,05</span></td>
</tr>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Distancia entre centros de puntos adyacentes perpendicularmente en la misma celda</span></td>
<td class="colsep0 rowsep1"><span>2,3</span></td>
<td class="colsep0 rowsep1"><span>2,5</span></td>
<td class="colsep0 rowsep1"><span>2.6</span></td>
<td class="colsep0 rowsep1 last"><span>2,45</span></td>
</tr>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Distancia entre los centros de los puntos correspondientes en celdas adyacentes horizontalmente</span></td>
<td class="colsep0 rowsep1"><span>6.1</span></td>
<td class="colsep0 rowsep1"><span>6,35</span></td>
<td class="colsep0 rowsep1"><span>6.5</span></td>
<td class="colsep0 rowsep1 last"><span>6,42</span></td>
</tr>
<tr valign="top" class="colsep0">
<td class="colsep0 rowsep1"><span>Altura de las l&iacute;neas celulares Braille de ocho puntos</span></td>
<td class="colsep0 rowsep1"><span>12.25</span></td>
<td class="colsep0 rowsep1"><span>13.25</span></td>
<td class="colsep0 rowsep1"><span>13,75</span></td>
<td class="colsep0 rowsep1 last"><span>13</span></td>
</tr>
<tr valign="top" class="colsep0 last">
<td class="colsep0 rowsep1"><span>Radio de curvatura del domo de puntos</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1"><span>-</span></td>
<td class="colsep0 rowsep1 last"><span>0,6-0,8</span></td>
</tr>
</tbody>
</table>
</div>
<div class="tableDownloadOption"></div>
