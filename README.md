![Github header](img/github-repositories.png)

# SAT Electric Power System

## Estado actual

En desarrollo

## Resumen

Este repositorio contiene el circuito electrónico y el diseño de placa de circuito impreso para el sistema de alimentación del satélite.

El actual diseño electrónico se ha llevado a cabo mediante el software **KiCAD**.

## Contenido de la Shield

La PCB cuanta con unas dimensiones de 77 x 77 mm, realizada en base de fibra de vidrio y doble capa de cobre, disponiendo de cuatro orificios de fijación, para el chasis del satélite, ubicados en las esquinas de la placa.

Actualmente, el diseño de este elemento se encuentra desarrollado para que sea capaz de alojar dos baterías recargables del tipo `18650`, con una tensión nominal de **3,7V** y una intensidad de **5.000mAh**.

La placa tiene capacidad para conectar a ella seis unidades de placas solares. Esto nos permite obtener niveles de tensión de entre 8VDC y 11,50VDC, con una intensidad máxima de 50 mA por cada unidad.

Además de lo indicado hasta el momento, la placa cuenta con un interruptor que nos permite encender y apagar el satélite de manera manual. En un futuro, esta funcionalidad será empleada para implementar el sistema **RBF** ( *Remove Before Flight* ) así como los sistemas de conexión en el momento del despliegue del satélite.

### Licencia

[![Creaive Commons 4.0 logo](img/cc40.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)