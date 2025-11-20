# 📊 Análisis Exploratorio de Datos (EDA) — Dataset de Salarios en Ciencia de Datos

Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** realizado sobre un conjunto de datos que contiene información sobre salarios, tipos de trabajo, modalidades de teletrabajo, países de residencia y características laborales en el sector tecnológico/ciencia de datos.

El objetivo principal es **analizar, limpiar, visualizar y extraer conclusiones** a partir del dataset utilizando Python y librerías de análisis de datos.

---

## 📁 Contenido del repositorio
📦 Proyecto-EDA-Salarios
┣ 📜 README.md
┣ 📓 notebook.ipynb ← EDA completo paso a paso
┗ 📄 Dataset salary 2024.csv

---

## 🎯 Objetivos del proyecto

- Importar y limpiar el dataset.
- Realizar un análisis exploratorio para entender:
  - Distribuciones de salarios.
  - Diferencias salariales por país, experiencia, tipo de trabajo, tamaño de empresa, modalidad de teletrabajo, etc.
- Detectar valores atípicos.
- Crear visualizaciones profesionales con Seaborn y Matplotlib.
- Elaborar un mapa geográfico con GeoPandas.
- Demostrar dominio en el uso de Pandas, Seaborn, Matplotlib y GeoPandas.

---

## 🧹 Limpieza de datos

Las tareas principales incluyeron:

- Renombrar columnas para mejorar la legibilidad.
- Comprobar valores nulos.
- Crear un dataframe con nulos artificiales para mostrar cómo tratarlos.
- Eliminar columnas redundantes (ej. Salary vs Salary In USD).
- Unificar y preparar datos para análisis categóricos y geográficos.

---

## 📊 Análisis Exploratorio de Datos (EDA)

El notebook incluye visualizaciones como:

### 📌 Distribuciones
- Histograma del salario.
- Boxplot del salario.

### 📌 Variables categóricas
- Salario por nivel de experiencia.
- Salario por país de residencia.
- Salario por tipo de trabajo (Top 10).
- Salario por tamaño de empresa.
- Salario según porcentaje de teletrabajo.
- Frecuencia de países en el dataset.
- Distribución del Remote Ratio.

### 📌 Mapas y heatmaps
- Mapa geográfico del salario medio por país utilizando **GeoPandas**.
- Heatmap Job Title vs Experience Level.
- Heatmap Employee Residence vs Company Location.

---

## 🗺️ Mapa geográfico

Para representar el salario medio por país, se utilizó:

- `GeoPandas`
- Dataset mundial de **Natural Earth** (110m)
- Unión de geometrías por código ISO

Esto permite una visualización clara de las diferencias salariales a nivel global.

---

## ⚠️ Outliers

El EDA incluye una explicación detallada de métodos para detectar y tratar outliers:

- IQR (Interquartile Range)
- Z-Score
- Winsorización
- Eliminación selectiva

Sin modificar el dataset original.

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Pandas**
- **Seaborn**
- **Matplotlib**
- **GeoPandas**
- **NumPy**
- **Jupyter Notebook**

---
