# ESTUDIO DE TÉCNICAS DE VIZUALIZACIÓN DE DATOS

Juan Manuel Camacho Lugo

Visualización de Datos

Máster Universitario de Ciencia de Datos (UOC)


## TÉCNICA 1 (Tag cloud / Word cloud):

**Definición:** 

Técnica que muestra las palabras o términos de un texto teniendo en cuenta las que aparecen con mayor frecuencia o son más relevantes. También se pueden asignar datos a las palabras.


**Origen:**

Comenzaron a popularizarse sobre el 2000 en webs que representaban etiquetas asociadas a contenidos. Aunque existen registros más antiguos, Stanley Milgram en 1976 representó los lugares más mencionados por los participantes en los mapas mentales colectivos de París.

**Descripción/funcionamiento:**

Son etiquetas dispuestas en espacios, variando el tamaño, color y la posición según la frecuencia, categoría o significado de las etiquetas. 

**Ejemplo:**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo1.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.anychart.com/products/anychart/gallery/Tag_Cloud/World_Population.php
</p>

**TIPO DE DATOS:**

Datos textuales.

No estructurados o con estructural parcial (líneas, párrafos, capítulos, …).

No existe medidas mínimas o máximas estrictas. Pero, si es necesario contar con textos con suficientes palabras relevantes para una aplicación útil. 
En el caso de textos demasiado grandes es necesario el filtrado de palabras poco significativas. 

**REPRESENTACIÓN CON CONJUNTO DE DATOS ABIERTO:**

**PROGRAMAS ELECTORALES DEL PSOE Y PP PARA LAS ELECCIONES GENERALES DE 2023**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/psoe.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.psoe.es/media-content/2023/07/PROGRAMA_ELECTORAL-GENERALES-2023.pdf
</p>

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/pp.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.pp.es/sites/default/files/documentos/programa_electoral_pp_23j_feijoo_2023.pdf
</p>
    
**Que se representa:**

Representa las propuestas de ambos partidos políticos acorde a sus ideologías y valores.

**Aspectos que muestra / demuestra:**

Presenta las ideas sobre las que se centra el programa.

**Objetivo específico:**

Captar la atención del ciudadano con el fin de obtener su voto.

**Que se pretende  comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Se pretende encontrar cuales son los pilares de la campaña y si respeta la ideología del partido. Como se puede comprobar la nube del programa electoral del PSOE está centrada en la igualdad social. Mientras que la nube del programa electoral del PP, se centra en el nacionalismo.

## TÉCNICA 2 (Stream Graph):

**Definición:** 

Representación gráfica de los cambios en las tendencias a lo largo del tiempo para varias categorías.

**Origen:**

Lee Byron y Martin Wattenberg, introdujeron por primera vez el término "Streamgraph" en 2008.

**Descripción/funcionamiento:**

 Son gráfico de áreas apiladas con formas suaves y fluidas, donde cada área representa una categoría específica. Son ideales para encontrar tendencias y patrones en conjuntos de datos de gran tamaño.

**Ejemplos:**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo2.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.highcharts.com/docs/chart-and-series-types/stream-graph
</p>

**TIPO DE DATOS:**

Se utiliza datos cuantitativos ya que muestran la magnitud a lo largo del tiempo.

Formato de tabla (fecha, categoría, valor, … ), por lo tanto, son datos estructurados.

No se recomienda tener menos de 3 categorías, ya que, no se aprovecharía su rendimiento. 
Tampoco es bueno contar con demasiadas categorías, dificultaría la lectura y se ocultaría información. 

**REPRESENTACIÓN CON CONJUNTO DE DATOS ABIERTO:**

**NÚMERO DE DENUNCIAS TRAMITADAS DESDE EL AÑO 2008 EN ALCOBENDAS**
<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/denuncias.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://datos.gob.es/en/catalogo/l01280066-seguridad-vial-denuncias-tramitadas-excepto-radar-desde-el-ano-2008-historico1
</p>
    
**Que se representa:**

Representa el número de denuncias de tráfico tramitadas desde el año 2008, sin contabilizar las denuncias por radar.

**Aspectos que muestra / demuestra:**

Muestra los patrones de comportamiento de los conductores a lo largo de los años.

**Objetivo específico:**

Ayudar en caso de necesidad a establecer nuevas políticas de gestión del tráfico o si las que están en uso están funcionando.

**Que se pretende comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Se pretende observar como evoluciona el número de denuncias y descubrir posibles tendencias. Esta técnica ayuda a comprobar como las medidas tomadas han ayudado a la disminución de las denuncias a partir de ciertos años.

## TÉCNICA 3 (Isotype & Unit charts):

**Definición:** 

Representación gráfica con (formas, íconos o imágenes) repetidos para ilustrar cantidades o proporciones.

**Origen:**

Isotype fue desarrollado en 1920 por Otto Neurath para un proyecto de comunicación visual (forma accesible de presentar datos complejos).

**Descripción/funcionamiento:**

Representar unidades o cantidades concretas. La diferencia entre ambos es que Isotype utiliza símbolos con un significado visual claro y Unit charts utiliza formas (círculos , cuadrados, …).

**Ejemplos:**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo3.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: http://steveharoz.com/research/isotype/
</p>

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo4.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.storytellingwithdata.com/blog/what-is-a-unit-chart
</p>


**TIPO DE DATOS:**

La representación se refiere a cantidades numéricas, por lo tanto, son datos cuantitativos.

Al asignar una cantidad específica a cada ícono o forma los datos deben estar estructurados.

No es recomendable para pequeñas cantidades (perdida de impacto visual), funcionando mejor con cantidades grandes.
Con cantidades excesivamente grandes puede producir sobrecarga y ser poco práctico.

**REPRESENTACIÓN CON CONJUNTO DE DATOS ABIERTO:**

**POBLACIÓN COMUNIDADES AUTÓNOMAS 2024**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/Isotype.jpg?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://https://datosmacro.expansion.com/demografia/poblacion/espana-comunidades-autonomas
</p>
    
**Que se representa:**

Representa la población actual de cada comunidad autónoma, donde cada ícono corresponde con 300.000 habitantes.

**Aspectos que muestra / demuestra:**

Muestra cómo se distribuye la población del país en sus diferentes comunidades.

**Objetivo específico:**

Facilitar la comprensión de manera rápida sobre que comunidades tienen mayor número de habitantes y cuales menor.

**Que se pretende  comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Permite observar como varia la población en cada comunidad, lo que ayuda a identificar patrones de crecimiento o decrecimiento poblacional.

