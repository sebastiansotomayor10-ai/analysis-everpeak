# analysis-everpeak
# 🚦 Movilidad Urbana y Economía en Latinoamérica

## 📌 Descripción del proyecto

Este proyecto analiza la relación entre la movilidad urbana y los indicadores económicos de distintas ciudades de Latinoamérica.

El objetivo principal es evaluar si existe una relación entre los niveles de congestión vehicular y la productividad económica de las ciudades, utilizando información de tráfico y economía correspondiente al año 2024.

A partir del análisis, se busca identificar ciudades donde una inversión en infraestructura de transporte podría generar un impacto significativo en movilidad, productividad y calidad de vida.

---

## 🎯 Objetivos

- Explorar y limpiar datos de movilidad y economía.
- Estandarizar formatos y tipos de datos.
- Analizar información correspondiente al año 2024.
- Calcular indicadores promedio de tráfico por ciudad.
- Integrar información de movilidad y economía en un mismo dataset.
- Comparar los niveles de congestión con el PIB per cápita.
- Identificar ciudades con posibles necesidades de inversión en infraestructura.
- Generar recomendaciones basadas en los resultados obtenidos.

---

## 📂 Fuentes de datos

Para el análisis se utilizaron dos datasets principales:

### TomTom Traffic Index

Contiene información relacionada con movilidad y tráfico urbano, incluyendo variables como:

- Congestión y retrasos.
- Longitud de embotellamientos.
- Cantidad de embotellamientos.
- Minutos de retraso.
- Tiempos de viaje.

### OECD Cities

Contiene indicadores económicos y demográficos de las ciudades analizadas, incluyendo:

- PIB per cápita.
- Tasa de desempleo.
- Población.

---

## 🛠️ Tecnologías utilizadas

El proyecto fue desarrollado utilizando:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Metodología

El análisis se desarrolló mediante las siguientes etapas:

### 1. Exploración de datos

Se realizó una revisión inicial de ambos datasets para conocer:

- Dimensiones de los datos.
- Tipos de variables.
- Valores faltantes.
- Formatos incorrectos.
- Posibles inconsistencias.

### 2. Limpieza y transformación

Se realizaron diferentes procesos de preparación, incluyendo:

- Estandarización de nombres de columnas utilizando `snake_case`.
- Conversión de fechas a formato `datetime`.
- Conversión de variables económicas a valores numéricos.
- Limpieza de símbolos y separadores.
- Transformación de la población a valores absolutos.

### 3. Filtrado temporal

El análisis se concentró en los registros correspondientes al año **2024**, permitiendo comparar información de movilidad y economía dentro del mismo periodo.

### 4. Agregación de datos de movilidad

Debido a que el dataset de tráfico contiene múltiples observaciones por ciudad, se calcularon promedios anuales para obtener una representación consolidada del comportamiento de cada ciudad.

### 5. Integración de datasets

Los datos de movilidad y economía fueron combinados utilizando como referencia la ciudad y el año.

Esto permitió construir un dataset final con indicadores de tráfico, economía y población.

### 6. Análisis y visualización

Se utilizaron diferentes visualizaciones para estudiar:

- Distribución de los niveles de congestión.
- Distribución del PIB per cápita.
- Diferencias entre ciudades.
- Posibles relaciones entre movilidad urbana y productividad económica.

---

## 📊 Principales hallazgos

El análisis no mostró una relación lineal clara entre el PIB per cápita y los niveles de congestión.

Algunas ciudades con un PIB per cápita elevado presentan altos niveles de congestión, mientras que otras con niveles económicos similares muestran un mejor comportamiento en términos de movilidad.

Esto sugiere que la productividad económica por sí sola no es suficiente para explicar los problemas de movilidad urbana.

Entre las ciudades analizadas, **Bogotá destacó por presentar una combinación relevante de factores**:

- Un nivel elevado de congestión.
- Un PIB per cápita relativamente bajo dentro del conjunto analizado.
- Una población aproximada de 11.3 millones de habitantes.

Debido a esta combinación, Bogotá podría representar una ciudad prioritaria para evaluar inversiones en infraestructura de transporte.

---

## 💡 Recomendaciones

A partir de los resultados obtenidos, se recomienda:

- Evaluar a Bogotá como una posible prioridad para inversiones relacionadas con movilidad.
- No utilizar únicamente el PIB per cápita como criterio para determinar necesidades de infraestructura.
- Incorporar información histórica para estudiar la evolución de la congestión.
- Analizar variables adicionales como crecimiento poblacional y parque vehicular.
- Incorporar información sobre uso y cobertura del transporte público.
- Analizar los tiempos promedio de viaje.
- Considerar la inversión histórica en infraestructura de cada ciudad.

---

## ⚠️ Limitaciones del análisis

Una de las principales limitaciones es que el análisis se concentra únicamente en información correspondiente al año **2024**.

Los resultados podrían estar afectados por situaciones particulares de ese año, como:

- Obras de infraestructura.
- Eventos masivos.
- Cambios en políticas de movilidad.
- Cambios en los patrones de transporte.

Por esta razón, sería recomendable realizar posteriormente un análisis longitudinal utilizando información de varios años.

Esto permitiría determinar si los patrones encontrados son permanentes o corresponden a situaciones temporales.

---

## 🌎 Alcance del análisis

El dataset final utilizado para el análisis de 2024 incluye:

- **15 ciudades**
- **7 países latinoamericanos**

El proyecto integra indicadores económicos, demográficos y de movilidad para generar una visión conjunta del desempeño de las ciudades.

---

## 📁 Archivos del proyecto

```text
├── S5_ladb_mobility_economy_project_student.ipynb
├── ladb_mobility_economy_2024_clean.csv
└── README.md
