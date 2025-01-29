# Análisis de Datos de Acceso a Internet y Tecnologías en Argentina

Este proyecto se centra en el análisis de datos relacionados con el acceso a internet, tecnologías y su penetración en diversas localidades y provincias de Argentina. Utilizando datos del **Ente Nacional de Comunicaciones (ENACOM)**, se busca extraer insights clave y presentar visualizaciones interactivas mediante **Power BI**.

## Objetivo
El objetivo principal del proyecto es consolidar, limpiar y analizar datos provenientes de múltiples archivos para entender el estado de la conectividad tecnológica en Argentina y proporcionar información accionable para la toma de decisiones.

## Metodología
El desarrollo del proyecto se divide en las siguientes etapas:

### Obtención de Datos
Para obtener los datos se requirió lectura automatizada de múltiples archivos Excel (.xlsx) almacenados en un directorio específico. Tambien era necesaria la exclusión de archivos duplicados o irrelevantes para garantizar la calidad del conjunto de datos y el manejo de excepciones para asegurar un flujo de trabajo robusto y confiable.

### Exploración y Preparación de Datos (EDA)
- **Unificación:** Consolidación de datos de múltiples hojas y archivos en un único DataFrame.
- **Transformación:** Conversión de columnas a formatos numéricos y de fecha para garantizar consistencia y calidad.
- **Filtrado:** Exclusión de datos no relevantes para optimizar el análisis.

### Almacenamiento y Procesamiento
Los datos procesados se almacenan en un directorio estructurado con nombres que identifican claramente el estado de los archivos (e.g., "procesado"). Fuè necesario el uso Python y librerías como **Pandas** para automatizar y agilizar el manejo de datos.

### Visualización en Power BI
En la visualizaciòn ede Power BI tenia que crear tableros interactivos que permiten explorar las principales métricas relacionadas con la conectividad tecnológica, como regiones con mayor y menor penetración tecnológica, tendencias en el acceso a internet a lo largo del tiempo y tambien la relación entre conectividad y variables socioeconómicas.

## Herramientas y Tecnologías
- **Python**: Para la preparación, limpieza y procesamiento de datos (librerías como Pandas y NumPy).
- **Power BI**: Para la creación de visualizaciones interactivas.
- **Excel**: Como formato principal de entrada y salida de datos.

