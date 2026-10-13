# Análisis de movilidad urbana y economía (2024)

## 📌 Descripción del proyecto

Este proyecto analiza la relación entre la congestión del tráfico urbano y los indicadores económicos de diferentes ciudades durante el año 2024.

Para ello, se utilizan datos de **TomTom Traffic Index** y **OECD Cities**, con el propósito de explorar posibles relaciones entre las condiciones de movilidad urbana y el desempeño económico de las ciudades, tomando como referencia indicadores como el PIB per cápita.

El proyecto integra técnicas de limpieza, transformación, agregación y análisis exploratorio de datos mediante Python.

## 🎯 Objetivos

- Analizar los niveles de congestión vehicular y los tiempos de desplazamiento en diferentes ciudades.
- Explorar la distribución del PIB per cápita y otros indicadores socioeconómicos.
- Examinar posibles relaciones entre la movilidad urbana y el desempeño económico.
- Identificar diferencias entre ciudades y posibles valores atípicos.
- Construir un conjunto de datos limpio e integrado para facilitar análisis posteriores.

## 📊 Fuentes de datos

El análisis utiliza dos fuentes principales:

- **TomTom Traffic Index:** proporciona indicadores relacionados con la congestión vehicular, los retrasos, la longitud de los atascos y los tiempos de desplazamiento.
- **OECD Cities:** proporciona indicadores económicos, demográficos y ambientales de las ciudades, como el PIB per cápita, el desempleo, la contaminación por PM2.5 y la población.

El análisis se centra en los datos correspondientes al año 2024.

## 🛠️ Herramientas y tecnologías

- **Python:** procesamiento y análisis de datos.
- **Pandas:** limpieza, transformación, agregación e integración de conjuntos de datos.
- **NumPy:** operaciones numéricas.
- **Matplotlib:** visualización de datos.
- **Seaborn:** elaboración de gráficos estadísticos.
- **Jupyter Notebook:** desarrollo y documentación del análisis.

## ⚙️ Metodología

El proyecto se desarrolla a través de las siguientes etapas:

1. **Exploración inicial:** carga de los conjuntos de datos y revisión de su estructura, tipos de variables y valores faltantes.
2. **Limpieza de datos:** estandarización de nombres de columnas, conversión de fechas y tratamiento de variables numéricas.
3. **Preparación de los datos:** extracción del año de los registros de tráfico y selección de las observaciones correspondientes a 2024.
4. **Agregación de indicadores:** cálculo de promedios anuales por ciudad para las variables de tráfico seleccionadas.
5. **Integración de fuentes:** combinación de los datos de movilidad y economía utilizando las variables de ciudad y año como criterios de unión.
6. **Análisis exploratorio:** elaboración de visualizaciones para estudiar distribuciones, diferencias entre ciudades y posibles relaciones entre variables.
7. **Exportación:** generación de un archivo CSV con los datos procesados e integrados.

## 📈 Análisis y resultados

El análisis busca identificar patrones entre los indicadores de movilidad urbana y las características económicas de las ciudades.

Entre los aspectos explorados se encuentran:

- La distribución de los indicadores de congestión y retrasos.
- Las diferencias en el PIB per cápita entre ciudades.
- La presencia de valores atípicos en las variables analizadas.
- Las posibles asociaciones entre la congestión vehicular y el desempeño económico.

Los resultados exploratorios sugieren que el PIB per cápita, por sí solo, no permite explicar claramente las diferencias en los niveles de congestión entre ciudades. Por tanto, sería necesario considerar otros factores, como la infraestructura vial, la densidad poblacional, la planificación urbana y la disponibilidad de transporte público.

Estas observaciones son exploratorias y no permiten establecer relaciones causales.

## 📁 Estructura del proyecto

```text
ladb-mobility-economy/
├── README.md
├── S5_ladb_mobility_economy_project_student.ipynb
└── ladb_mobility_economy_2024_clean.csv
```

*Nota: el archivo CSV se genera durante la ejecución del notebook. Los archivos originales de datos deben estar disponibles para reproducir el análisis.*

## Cómo abrir el archivo en Google Colab

Haz click en el siguiente link:

https://colab.research.google.com/drive/1Qs1gV_Yh10x8Y-y3rf7XjNBXfyZLGWld?usp=sharing

O:
1. Abre el archivo .ipynb en GitHub.
2. Haz click en **Open in Colab**

## 🚀 Cómo ejecutar el proyecto

### 1. Instalar las dependencias

Asegúrate de tener Python instalado y ejecuta:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 2. Preparar los datos

Ubica los archivos CSV originales en las rutas utilizadas por el notebook:

- `tomtom_traffic.csv`
- `oecd_city_economy.csv`

Si los archivos se encuentran en otra ubicación, actualiza las rutas correspondientes.

### 3. Ejecutar el notebook

Abre una terminal en la carpeta del proyecto y ejecuta:

```bash
jupyter notebook
```

Abre el archivo `S5_ladb_mobility_economy_project_student.ipynb` y ejecuta las celdas en orden.

## 📦 Producto final

El principal resultado es el archivo:

`ladb_mobility_economy_2024_clean.csv`

Este archivo contiene los indicadores de movilidad y economía correspondientes a las ciudades que coinciden entre las fuentes de datos y que pueden utilizarse en análisis posteriores.

## ⚠️ Limitaciones

- El análisis depende de la disponibilidad y calidad de los datos originales.
- La integración mediante una unión interna excluye los registros que no tienen coincidencias entre ambas fuentes.
- Los promedios anuales pueden ocultar variaciones diarias o estacionales del tráfico.
- Las asociaciones observadas no implican causalidad.
- Se necesitarían análisis estadísticos adicionales y más variables para evaluar con mayor precisión las relaciones identificadas.

## 👤 Autor

**Juan Pablo Rodriguez Torres**

Proyecto académico de análisis de datos  
Movilidad urbana e indicadores económicos — 2024
</
