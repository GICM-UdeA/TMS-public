# Sistema de medición de temperatura (TMS)
A continuación, se describe de forma resumida las caracteristicas del sistema de medición de temperatura dos dimensional para caracterizar las condiciones de secado de celdas solares flexibles fabricadas con un sistema Roll to Roll (R2R) (Más detalles pueden encontrarse en el [manual de usuario](https://github.com/GICM-UdeA/TMS-project/tree/main/TMS/docs/TMS-User-Manual.pdf)).

El hardware consiste en un DAQ (data acquisition system) basado en Arduino y Python, este se encarga de monitorear las temperaturas medidas por el conjunto de 6 termocuplas tipo K, y reporta los registros al usuario a través de una interfaz gráfica de usuario (software). En esta última, se pueden ver en tiempo real los datos tomados de forma gráfica, con posibilidad de extraerlos en un archivo Excel para su posterior análisis.

Los detalles sobre el diseño del circuito y la programación del Hardware pueden consultarse en la carpeta del [`hardware`](https://github.com/GICM-UdeA/TMS-project/tree/main/TMS/hardware).

Los detalles sobre la programación del software pueden consultarse en la carpeta del [`software`](https://github.com/GICM-UdeA/TMS-project/tree/main/TMS/software).