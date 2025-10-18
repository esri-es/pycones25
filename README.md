# PyConES 2025
![Pycones logo](https://2025.es.pycon.org/theme/images/logos/PYCONES_CORTADO.png)

## Análisis de un Accidente Marítimo con Python, Spark y Datos Geoespaciales

El 29 de agosto de 2022 hubo una colisión entre dos barcos en la costa de Gibraltar provocando la rotura del casco del buque OS 35 que transportaba unas 460 toneladas de productos como diésel, fuel-oil pesado y lubricante.
En esta charla queremos analizar esa colisión y para ello analizaremos la posición de los barcos gracias a millones de registros de AIS (Automatic Identification System) y así poder reconstruir los hechos a partir de los datos.
Para ello, utilizamos PySpark y la biblioteca ArcGIS GeoAnalytics Engine para el procesamiento en paralelo de los datos, aplicando transformaciones sobre velocidades y rumbos,  así como para la obtención de las rutas de los barcos: antes, durante y después de la colisión.

Durante la charla veremos:

- Cómo estructuramos un pipeline de análisis geoespacial.
- Manejo de los datos con resolución temporal variable y eventos simultáneos.
- Visualización y validación de las trayectorias en mapas.

El objetivo final de esta charla es ver un ejemplo real donde la variable espacial es clave para un análisis completo de los datos.

Autores: [Libertad Chapinal Cervantes](https://github.com/libertadcc) y [Álvaro Gutiérrez Climent](https://github.com/alvarogtrzcliment)
