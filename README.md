# Distribución de Cúmulos Estelares en la Vía Láctea

Este proyecto analiza la distribución de cúmulos estelares (cúmulos globulares y abiertos) en la galaxia utilizando datos del catálogo Gaia Early Data Release 3 (Gaia EDR3). Se centra en la visualización y el procesamiento de datos astronómicos para comprender mejor la estructura y distribución de estos objetos en el cielo nocturno.

## Contexto
Los cúmulos estelares son grupos de estrellas que se forman a partir de la misma nube molecular y son componentes clave para estudiar la evolución galáctica. Existen dos tipos principales:

- **Cúmulos Globulares (CG):** Grupos densos de estrellas, generalmente antiguos y asociados al halo galáctico.
- **Cúmulos Abiertos (CA):** Grupos menos densos, más jóvenes, y ubicados en el disco galáctico.

Utilizando los datos de Gaia EDR3, este proyecto visualiza la distribución de estos cúmulos en el cielo.

## Datos Utilizados
- **Fuente de datos:** [Gaia EDR3](https://www.cosmos.esa.int/web/gaia/early-data-release-3).
- **Catálogo principal:** [Painting a portrait of the Galactic disc with its stellar clusters](https://vizier.cfa.harvard.edu/viz-bin/VizieR?-source=J/A+A/640/A1).

Los datos incluyen posiciones, magnitudes y características de los cúmulos abiertos y globulares.

## Objetivos
1. Descargar y procesar los datos del catálogo CAN+20 utilizando la biblioteca Vizier.
2. Crear visualizaciones de la distribución de los cúmulos en coordenadas ecuatoriales y galácticas.
3. Analizar patrones y correlaciones entre los cúmulos y la estructura galáctica.

## Tecnologías
- **Python** para el procesamiento y análisis de datos.
- **Bibliotecas utilizadas:**
  - `pandas`: Manipulación de dataframes.
  - `matplotlib` y `seaborn`: Visualización de datos.
  - `astroquery`: Acceso a catálogos astronómicos.
  - `astropy`: Conversión de coordenadas astronómicas.

## Estructura del Proyecto
- `Distribución Cúmulos Vía Láctea.ipynb`: Notebook principal con el análisis y visualizaciones.
- `data/`: Carpeta donde se almacenan los catálogos descargados y datos procesados.

## Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/distribucion-cumulos-via-lactea.git
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abre el notebook y sigue las instrucciones para ejecutar los códigos.

## Resultados Esperados
- Mapas visuales de los cúmulos globulares y abiertos en el cielo nocturno.
- Análisis descriptivo sobre la distribución de los cúmulos en relación con la estructura de la Vía Láctea.

## Referencias
- [Catálogo CAN+20](https://vizier.cfa.harvard.edu/viz-bin/VizieR?-source=J/A+A/640/A1).
- [Gaia Early Data Release 3 (EDR3)](https://www.cosmos.esa.int/web/gaia/early-data-release-3).

## Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request con tus sugerencias.

