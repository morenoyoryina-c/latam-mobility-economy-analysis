# Análisis de Movilidad Urbana y Economía en Latinoamérica

**Proyecto de Análisis de Datos | Tripleten – Sprint 5**

## 📌 Descripción del proyecto

Este proyecto analiza la relación entre la congestión vehicular y los indicadores económicos en diferentes ciudades de Latinoamérica.

A través de herramientas de análisis de datos en Python, se estudian patrones de tráfico, tiempos de retraso e indicadores económicos, como el PIB per cápita.

El objetivo es comprender cómo se relacionan la movilidad urbana y las condiciones económicas, así como identificar oportunidades para futuras investigaciones y mejoras en infraestructura de transporte.

## 🎯 Objetivos del análisis

- Identificar y corregir problemas de calidad de datos.
- Limpiar y preparar los conjuntos de datos para su análisis.
- Combinar información de movilidad y economía.
- Analizar los niveles de congestión vehicular entre ciudades.
- Explorar la relación entre congestión vehicular y PIB per cápita.
- Generar visualizaciones y conclusiones basadas en los datos.

## 🛠️ Herramientas utilizadas

Plataforma educativa de TripleTen: entorno web donde desarrollé y ejecuté el proyecto.

## 📂 Fuentes de datos

Se utilizaron dos conjuntos de datos:

**1. TomTom Traffic Data**

Contiene información relacionada con la congestión vehicular, los retrasos y los tiempos de desplazamiento.

**2. OECD City Economy Data**

Incluye indicadores económicos de diferentes ciudades, entre ellos el PIB per cápita.

El análisis se centra en información correspondiente a 2024.

## 🔎 Metodología

### 1. Exploración inicial

Se revisaron los conjuntos de datos para identificar su estructura, tipos de variables, valores faltantes y posibles inconsistencias.

### 2. Limpieza de datos

Se realizaron transformaciones para mejorar la calidad de la información, incluyendo la estandarización de nombres de columnas y la conversión de tipos de datos.

### 3. Preparación de los datos

Se filtró la información correspondiente a 2024 y se calcularon indicadores promedio de congestión vehicular por ciudad.

### 4. Integración de datos

Se combinaron los conjuntos de datos de movilidad y economía para facilitar el análisis conjunto de sus indicadores.

### 5. Análisis exploratorio

Se utilizaron estadísticas descriptivas y visualizaciones, como histogramas, diagramas de caja y gráficos de barras, para identificar patrones y diferencias entre ciudades.

## 📊 Principales resultados

El análisis permitió identificar los siguientes hallazgos:

- Se analizaron **15 ciudades de 7 países latinoamericanos**.
- Ciudad de México presentó el mayor indicador promedio de retraso vehicular (`jams_delay`), con aproximadamente **2.833,06**.
- El promedio del indicador `jams_delay` en el conjunto de datos combinado fue de aproximadamente **629,52**.
- No se identificó una relación claramente proporcional entre el PIB per cápita y la congestión vehicular.
- Montevideo presentó niveles relativamente bajos de congestión, a pesar de registrar uno de los valores más altos de PIB per cápita entre las ciudades analizadas.

Estos resultados muestran que la congestión vehicular puede estar relacionada con múltiples factores y no únicamente con el nivel económico de una ciudad.

## 💡 Conclusiones y recomendaciones

El análisis sugiere que el desarrollo económico de una ciudad no determina por sí solo sus niveles de congestión vehicular.

Bogotá se identificó como una ciudad de interés para futuras investigaciones debido a sus niveles relativamente altos de congestión y su menor PIB per cápita en comparación con otras ciudades analizadas.

Se recomienda profundizar en factores como la infraestructura vial, la disponibilidad de transporte público y la planificación urbana antes de tomar decisiones de inversión.

## 📁 Estructura del repositorio

```text
Repositorio/
├── README.md
└── cuadernos/
    └── latam_mobility_analysis.ipynb
```

## ▶️ Cómo ejecutar el proyecto

1. Abrir la carpeta `cuadernos`.
2. Seleccionar el archivo `latam_mobility_analysis.ipynb`.
3. Abrir el notebook en Jupyter Notebook o Google Colab.
4. Cargar los archivos CSV originales.
5. Actualizar las rutas de los archivos si es necesario.
6. Ejecutar las celdas en orden.

**Nota:** El notebook original utiliza rutas del entorno de TripleTen, por lo que puede ser necesario modificarlas para ejecutar el proyecto en Google Colab.

## 👩‍💻 Autora

**Yoryina Moreno**

Profesional en Administración de Empresas  
Estudiante de Análisis de Datos – TripleTen

*Proyecto desarrollado como parte de mi formación en análisis de datos y construcción de mi portafolio profesional.*
