# Análisis de Datos de Acceso a Internet y Tecnologías en Argentina

Este proyecto se centra en el análisis de datos relacionados con el acceso a internet, tecnologías y su penetración en diversas localidades y provincias de Argentina. Utilizando datos del **Ente Nacional de Comunicaciones (ENACOM)**, se busca extraer insights clave y presentar visualizaciones interactivas mediante **Power BI**.

## Objetivo
El objetivo principal del proyecto es consolidar, limpiar y analizar datos provenientes de múltiples archivos para entender el estado de la conectividad tecnológica en Argentina y proporcionar información accionable para la toma de decisiones.

## Metodología
El desarrollo del proyecto se divide en las siguientes etapas:

### Obtención de Datos
- Lectura automatizada de múltiples archivos **Excel** (`.xlsx`) almacenados en un directorio específico.
- Exclusión de archivos duplicados o irrelevantes para garantizar la calidad del conjunto de datos.
- Manejo de excepciones para asegurar un flujo de trabajo robusto y confiable.

### Exploración y Preparación de Datos (EDA)
- **Unificación:** Consolidación de datos de múltiples hojas y archivos en un único DataFrame.
- **Transformación:** Conversión de columnas a formatos numéricos y de fecha para garantizar consistencia y calidad.
- **Filtrado:** Exclusión de datos no relevantes para optimizar el análisis.

### Almacenamiento y Procesamiento
- Los datos procesados se almacenan en un directorio estructurado con nombres que identifican claramente el estado de los archivos (e.g., "procesado").
- Uso de Python y librerías como **Pandas** para automatizar y agilizar el manejo de datos.

### Visualización en Power BI
- Creación de tableros interactivos que permiten explorar las principales métricas relacionadas con la conectividad tecnológica:
  - Regiones con mayor y menor penetración tecnológica.
  - Tendencias en el acceso a internet a lo largo del tiempo.
  - Relación entre conectividad y variables socioeconómicas.

## Herramientas y Tecnologías
- **Python**: Para la preparación, limpieza y procesamiento de datos (librerías como Pandas y NumPy).
- **Power BI**: Para la creación de visualizaciones interactivas.
- **Excel**: Como formato principal de entrada y salida de datos.

## Resultados Esperados
El proyecto busca responder preguntas clave como:
- ¿Qué regiones tienen mayores brechas en conectividad tecnológica?
- ¿Cuáles son las tendencias históricas de acceso a internet en Argentina?
- ¿Cómo se relacionan las métricas de conectividad con otras variables socioeconómicas?

## Contribución
Este proyecto es un ejemplo de cómo integrar análisis de datos y herramientas de visualización para generar valor a partir de información compleja. Puede escalarse y adaptarse a otros contextos o países con necesidades similares.





