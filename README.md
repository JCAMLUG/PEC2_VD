# ESTUDIO DE TÉCNICAS DE VIZUALIZACIÓN DE DATOS

Juan Manuel Camacho Lugo

Visualización de Datos

Máster Universitario de Ciencia de Datos (UOC)


## TÉCNICA 1 (Tag cloud / Word cloud):

**Definición:** 

Mayor frecuencia o relevancia de las palabras o términos de un texto.


**Origen:**

Popularizadas sobre el 2000. Aunque existen registros previos de uso (Stanley Milgram en 1976). 

**Descripción/funcionamiento:**

Etiquetas dispuestas en espacios, variando el tamaño, color y la posición, según la frecuencia, categoría o significado de las etiquetas.  

**Ejemplo:**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo1.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes:https://www.anychart.com/products/anychart/gallery/Tag_Cloud/Most_Frequently_Words_on_Wikipedia_Pages.php
</p>

**TIPO DE DATOS:**

Utiliza datos textuales.

Datos no estructurados o estructura parcial.

No existe limitaciones mínimas o máximas estrictas. 

  •	textos pequeños, poco útiles. 
  
  •	Textos grandes, necesario filtrado.
 

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

Representa las propuestas de ambos partidos políticos.

**Aspectos que muestra / demuestra:**

Presenta las ideas sobre las que se centra el programa.

**Objetivo específico:**

Captar la atención del ciudadano con el fin de obtener su voto.

**Que se pretende  comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Se pretende encontrar cuales son los pilares de la campaña.

## TÉCNICA 2 (Stream Graph):

**Definición:** 

Cambios en las tendencias a lo largo del tiempo.

**Origen:**

Lee Byron y Martin Wattenberg, en 2008.

**Descripción/funcionamiento:**

Formas suaves y fluidas, cada área representa una categoría específica.

**Ejemplos:**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/ejemplo2.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://www.highcharts.com/docs/chart-and-series-types/stream-graph
</p>

**TIPO DE DATOS:**

Utiliza datos cuantitativos.

Datos estructurados.

Limitaciones:

  •	No se recomienda tener menos de 3 categorías. 

  •	Tampoco es bueno contar con demasiadas categorías.


**REPRESENTACIÓN CON CONJUNTO DE DATOS ABIERTO:**

**NÚMERO DE DENUNCIAS TRAMITADAS DESDE EL AÑO 2008 EN ALCOBENDAS**
<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/denuncias.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://datos.gob.es/en/catalogo/l01280066-seguridad-vial-denuncias-tramitadas-excepto-radar-desde-el-ano-2008-historico1
</p>
    
**Que se representa:**

Número de denuncias de tráfico tramitadas desde el año 2008 hasta el 2017.

**Aspectos que muestra / demuestra:**

Patrones de comportamiento de los conductores.

**Objetivo específico:**

Establecer / mantener nuevas políticas de gestión del tráfico. 

**Que se pretende comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Evolución del número de denuncias y descubrir posibles tendencias. ciertos años.

## TÉCNICA 3 (Isotype & Unit charts):

**Definición:** 

Representación gráfica con (formas, íconos o imágenes).

**Origen:**

Desarrollado en 1920 por Otto Neurath.

**Descripción/funcionamiento:**

Representar unidades o cantidades concretas.

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

Utiliza datos cuantitativos.

Datos estructurados.

Limitaciones:

  •	No es recomendable para pequeñas cantidades.
  
  •	Cantidades excesivamente grandes puede producir sobrecarga.


**REPRESENTACIÓN CON CONJUNTO DE DATOS ABIERTO:**

**POBLACIÓN COMUNIDADES AUTÓNOMAS 2024**

<p align="center">
  <img src="https://github.com/JCAMLUG/PEC2_VD/blob/main/Isotype.jpg?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  <sub>Fuentes: https://https://datosmacro.expansion.com/demografia/poblacion/espana-comunidades-autonomas
</p>
    
**Que se representa:**

Representa la población actual de cada comunidad autónoma.

**Aspectos que muestra / demuestra:**

Cómo se distribuye la población del país en sus diferentes comunidades.

**Objetivo específico:**

Facilitar la comprensión de manera rápida. 

**Que se pretende  comunicar o descubrir y como la técnica y datos ayudan a ese objetivo:**

Permite observar cómo varia la población en cada comunidad.

## FUENTES:

https://datavizcatalogue.com/methods/wordcloud.html

https://www.anychart.com/products/anychart/gallery/Tag_Cloud/Most_Frequently_Words_on_Wikipedia_Pages.php

https://www.psoe.es/media-content/2023/07/PROGRAMA_ELECTORAL-GENERALES-2023.pdf

https://www.pp.es/sites/default/files/documentos/programa_electoral_pp_23j_feijoo_2023.pdf

https://datavizcatalogue.com/methods/stream_graph.html

https://fastercapital.com/es/contenido/Tecnicas-de-visualizacion--Stream-Graphs--Fluir-con-datos--La-elegancia-de-los-Stream-Graphs.html#La-historia-y-evoluci-n-de-los-gr-ficos-de-flujo

https://www.highcharts.com/docs/chart-and-series-types/stream-graph

https://r-charts.com/es/evolucion/ggstream/

https://datos.gob.es/en/catalogo/l01280066-seguridad-vial-denuncias-tramitadas-excepto-radar-desde-el-ano-2008-historico1

http://steveharoz.com/research/isotype/

https://www.storytellingwithdata.com/blog/what-is-a-unit-chart

https://datosmacro.expansion.com/demografia/poblacion/espana-comunidades-autonomas

