** About for development of different braille cells / para desarrollo de distintas celdas brailles

![Figura 1. Vista lateral de una celda Braille piezobimorfa típica.](https://github.com/brailletouch/braille-cell/blob/main/images/braillecell.jpg)

Figure 1. Lateral view of a typical piezo bimorph Braille cell. / Figura 1. Vista lateral de una celda Braille piezobimorfa típica.


Durante más de 50 años, ha habido muchos intentos de desarrollar pantallas Braille sin papel que proporcionarían a los lectores con discapacidad visual acceso a la información digital. Estos dispositivos están concebidos como pantallas táctiles actualizables electrónicamente que permiten a los usuarios leer texto en Braille presentado de forma dinámica. Las pantallas están diseñadas como matrices de celdas Braille, correspondientes a los caracteres individuales del código Braille. El estándar mundial emergente para pantallas braille actualizables utiliza ocho puntos, dispuestos en dos columnas de cuatro puntos cada una. La altura de cada punto con respecto a la superficie de lectura debe ser controlable individualmente, para producir dos estados: punto elevado y punto bajado. Esto permite representar 256 combinaciones diferentes, es decir, 256 caracteres Braille diferentes.

La complejidad de desarrollar tales interfaces táctiles se relaciona con la necesidad de tecnologías de actuación adecuadas capaces de controlar cada punto de cada celda de la pantalla completa, al tiempo que se minimiza el tamaño, el peso, el costo y el consumo de energía (especialmente para dispositivos portátiles). Con este fin, se han investigado extensamente electroimanes, bimetales, aleaciones con memoria de forma, accionamientos neumáticos, lengüetas piezo cerámicas y muchas otras tecnologías de actuación, pero, en el mejor de los casos, los esfuerzos solo han dado como resultado dispositivos de visualización complicados y costosos.

La mayoría de las pantallas Braille actualizables disponibles en el mercado tienen una sola línea de 20 a 80 caracteres Braille (celdas) y cuestan varios miles de dólares estadounidenses. El costo del fabricante del equipo original de las celdas piezoeléctricas Braille producidas comercialmente es de aproximadamente 35 dólares EE.UU. por celda, o 4,38 dólares EE.UU. por punto Braille. Casi todos los módulos Braille disponibles en la actualidad utilizan lengüetas bimorfas cerámicas piezoeléctricas para activar los puntos Braille. Las lengüetas piezoeléctricas están montadas como una pila escalonada de voladizos, cada uno con un pin Braille descansando en su extremo libre. Cada lengüeta puede levantar la parte superior del domo de su pin Braille de 1,5 mm de diámetro aproximadamente 0,5 mm por encima de la superficie de lectura. Como se muestra en la Figura 1 , un módulo típico tiene cuatro capas de pares de lengüetas, una al lado de la otra, montadas horizontalmente, debajo y paralelas a la superficie de lectura superior.La Figura 1 también muestra el pestillo de datos asociado y los circuitos del controlador de 200 V necesarios e integrados en cada módulo de celda Braille.

Estos módulos de celdas Braille están montados horizontalmente uno al lado del otro, formando una línea única de celdas arbitrariamente larga (típicamente 20, 40 u 80 celdas). Es posible montar un máximo de dos de estas líneas juntas, de punta a punta, obteniendo una pantalla de dos líneas, aunque el tamaño y el costo del empaque limitan la mayoría de las pantallas a una sola línea. Por lo tanto, debido al estorbo de los largos voladizos (Figura 1) , las pantallas braille actualizables modernas están limitadas a una sola línea de lectura, o como máximo, a dos líneas. Las pantallas Braille de página completa no se pueden implementar con las tecnologías tradicionales de lengüeta piezoeléctrica en voladizo porque la huella del mecanismo accionador de cada punto Braille en una pantalla de página completa debe estar en el rango de 2,5 mm 2 o menos.

Por lo tanto, con respecto a las pantallas braille estándar de una línea, de varios miles de dólares y basadas en piezo, existe una clara necesidad de un Braille de orden de magnitud menos costoso, compacto y especialmente de varias líneas o incluso de página completa. muestra. Esto se considera un tema clave para mejorar la tasa de alfabetización extremadamente baja (∼12%) de los estudiantes ciegos y para permitir que las personas con discapacidad visual en general accedan a la información digital de manera amplia.

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

## Momento
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

## El potencial de los polímeros electromecánicamente activos.
Para abordar la necesidad de nuevas tecnologías para la activación de puntos Braille, capaces de cumplir con los requisitos presentados anteriormente, en la actualidad, se están centrando cada vez más esfuerzos en los transductores emergentes basados ​​en polímeros electromecánicamente activos (EAP) [1–6]. Son materiales "inteligentes" intrínsecamente capaces de cambiar las dimensiones y / o la forma en respuesta a estímulos eléctricos adecuados, para convertir la energía eléctrica en trabajo mecánico para su actuación. También pueden operar en modo inverso, convirtiendo la energía mecánica en forma eléctrica para la detección mecánica. Estas propiedades funcionales se combinan con características generales atractivas, como conformidad mecánica, resistencia a los golpes, peso ligero, baja densidad de masa, ausencia de ruido acústico, facilidad de procesamiento, alta escalabilidad y bajo costo. Los materiales de EAP se clasifican comúnmente en dos familias principales:

• EAP iónicos (activados por un transporte inducido eléctricamente de iones y / o solvente), que incluyen geles poliméricos, compuestos iónicos polímero-metal, polímeros conjugados y nanotubos de carbono;

• EAP electrónicos (activados por fuerzas electrostáticas), que incluyen polímeros piezoeléctricos, polímeros electroestrictivos, elastómeros dieléctricos, elastómeros de cristal líquido y aerogeles de nanotubos de carbono.

Cada familia consta de tipos de materiales que operan de acuerdo con diferentes principios físicos y tienen propiedades y rendimiento significativamente diferentes [1–6] . Incluso hace 30 años, se investigó un material EAP temprano, el polímero piezoeléctrico de fluoruro de polivinilideno Kynar, para su uso en actuadores de pantalla Braille, aunque se descubrió que no cumplía con los exigentes requisitos de las pantallas Braille [7,101] . Hoy, tras los tremendos avances de la última década en ciencia y tecnología EAP, el campo ha madurado hasta el punto de que se están diseñando y desarrollando seriamente soluciones prácticas potencialmente adecuadas para nuevas pantallas Braille actualizables. La Tabla 2 proporciona una descripción general de los enfoques clave.

Hasta ahora, ninguna de esas estrategias parece estar lista para su aplicabilidad a corto plazo, al menos en su implementación actual. Esto se debe a una serie de desafíos (específicos para cada enfoque), cuya discusión requeriría conocimientos técnicos que inevitablemente van más allá de las posibilidades de este artículo. En resumen, los desafíos incluyen fuerzas bajas o baja confiabilidad o vida útil corta o complejidad de fabricación excesiva o alto espesor de celda o velocidad de respuesta lenta o voltajes de activación altos o incluso combinaciones de tales inconvenientes. Sin embargo, los resultados específicos de esas investigaciones (ver referencias en la Tabla 2) son muy prometedores y muestran espacio para mejoras sustanciales. Esto revela el potencial de las tecnologías EAP para superar las limitaciones típicas de los actuadores tradicionales para esta aplicación específica. La pregunta es si alguna de estas o las soluciones futuras que todavía se basan en los EAP permitirán alguna vez una pantalla braille debajo costo 



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
