# Curso práctico de visualización de datos

## Objetivo

Este repositorio contiene un curso diseñado *ex profeso* para Alejandro Cuauhtémoc sobre visualización de datos. La idea es que el alumno pueda, al final de las n sesiones, visualizar grandes cantidades de datos en múltiples formas.

El curso irá desde un breve repaso de las funciones de `R`, principalmente funciones disponibles gracias al `tidyverse`, hasta el uso de módulos de `D3.js` para hacer visualizaciones interactivas y exportables a la web en `HTML`. 

Asimismo, el curso también tendrá un módulo de geocomputación. Primero en `sf` y luego en `QGIS`, con el propósito de responder a las necesidades de cada proyecto.

## Software

El curso se llevará a cabo en `R`, pero habrá algunos módulos de uso de información geográfica en `QGIS`.

## Módulos

1. El `tidyverse` para el procesamiento de datos.
    1. Unir, filtrar, seleccionar y procesar datos en formato `tibble`.
    2. Comparación de posibilidades y limitaciones de bases *wide* vis à vis *long*.
    3. Uso de datos de series de tiempo con `lubridate` y `POSIXtc`.
    4. Uso de *pipes* `%>%` para la abreviación de procesos.
    5. Introducción a `ggplot2` como herramienta de visualización del `tidyverse`.

2. Introducción a `ggplot2`
    1. Introducción a al gramática de `ggplot2` y al uso de `aes()`.
    2. Introducción a la lógica de capas.
    3. Elementos estructurales de las visualizaciones.
    4. Modificación de elementos guía: títulos, subtítulos, títulos de ejes, thiks, escalas, límites, grids y guías.
    5. Introducción a la lógica de coordenadas.
    6. "Primitivos" gráficos
        1. `geom_polygon`
        2. `geom_path`
        3. `geom_segment`
        4. `geom_segment`
        5. `geom_rect`
    7. `qplot`, esa salida fácil

3. Tipos de visualizaciones con respecto a al naturaleza de los datos
    1. `geom_hist`
    2. `geom_density`
    3. `geom_freqpoly`
    4. `geom_bar`
        1. `geom_crossbar`
        2. `geom_errorbar`
    5. `geom_point`
        1. `geom_pointrange`
    6. `geom_violin`
    7. `geom_hex`
    8. `geom_area`
    9. `geom_boxplot`
    10. Heatmaps con `geom_tile`

4. Extensiones de `ggplot2`
    1. `ggridges`
    2. `gg_joy`
    3. `gg_tern`
    4. `gg_mosaic`

5. Embellecer a voluntad una gráfica
    1. Uso de elementos en *Themes* incluidos en el paquete.
    2. Uso de *brewer* y paletas de colores.
        1. `wesanderson`
        2. `ochRe`
        3. `viridis`
        4. `scico`
    3. `ggthemes`
    4. `hbrthemes`

6. Más allá de `ggplot2`: Otros tipos de visualización
    1. `treemap()`
    2. `plot3D`

7. Análisis de redes
    1. `igraph`
    2. `networkD3`
        1. Redes
        2. Diagramas de Sankey
    3. `alluvial`
    4. `circlize`

8. Geografías
    1. `ggmap`
    2. `sf`
    3. Una brevísima introducción a *QGIS*
        1. *QuickMap* plug-in
        2. *Styles para hacer choropleths.
