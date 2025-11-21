# 📊 Análisis Exploratorio de Datos (EDA) — Dataset de Salarios en Ciencia de Datos

Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** realizado sobre un conjunto de datos que contiene información sobre salarios, tipos de trabajo, modalidades de teletrabajo, países de residencia y características laborales en el sector tecnológico/ciencia de datos.

El objetivo principal es **analizar, limpiar, visualizar y extraer conclusiones** a partir del dataset utilizando Python y librerías de análisis de datos.

---

## 📁 Contenido del repositorio
📦 Proyecto-EDA-Salarios
┣ 📜 README.md
┣ 📓 notebook-
|             EDA_codigo.ipynb
┗ 📄 data -
            Dataset salary 2024.csv

---
## 🎯 **Objetivo del proyecto**

El objetivo principal es realizar un **Análisis Exploratorio de Datos (EDA)** sobre un dataset real de salarios en profesiones relacionadas con *Data Science*, *Machine Learning*, *Data Engineering* y áreas afines entre los años 2020 y 2024.

Este trabajo permite:

- Comprender la estructura del dataset.  
- Detectar problemas de calidad de datos.  
- Realizar una limpieza adecuada.  
- Explorar relaciones entre variables.  
- Generar visualizaciones informativas.  
- Extraer conclusiones relevantes sobre el mercado laboral tecnológico.

---

## 📦 **Dataset**

El dataset contiene información de **16 534 empleados** y **11 variables**, incluyendo:

- Año de trabajo (`work_year`)
- Nivel de experiencia (`experience_level`)
- Tipo de contrato (`employment_type`)
- Puesto de trabajo (`job_title`)
- Salario en USD (`salary_in_usd`)
- País de residencia y localización de la empresa
- Ratio de teletrabajo
- Tamaño de la empresa

---

## 🧹 **Limpieza de datos realizada**

Durante el EDA se aplicaron los siguientes pasos de limpieza:

✔️ Eliminación de duplicados  
✔️ Corrección de tipos de datos  
✔️ Normalización de categorías  
✔️ Revisión de incoherencias entre columnas  
✔️ Verificación de valores nulos  
✔️ Comprobación de outliers mediante visualización  

---

## 📊 **Visualizaciones incluidas**

El notebook contiene visualizaciones básicas y extendidas, entre ellas:

### **Visualización básica**
- Distribución del salario (histograma + KDE)
- Boxplot general del salario
- Distribución de experiencia
- Distribución de tipos de trabajo
- Salario por país, por experiencia, por tamaño de empresa, por ratio de teletrabajo y por año

### **Visualización extendida**
- Mapa geográfico del salario medio
- Relación tipo de trabajo y años de experiencia

Todas las visualizaciones están generadas con **Seaborn** y **Matplotlib**.

---


## 📝 **Conclusiones principales**

- Los salarios presentan una distribución sesgada a la derecha con valores muy extremos.
- El sector tiene una fuerte presencia de trabajadores *Senior* (la mayoría del dataset).
- La experiencia laboral es el factor más determinante del salario.
- Estados Unidos es el país dominante tanto en número de empleados como en salarios.
- El teletrabajo completo (0% y 100%) se asocia a mayores salarios que los modelos híbridos.
- Las empresas grandes y medianas pagan más que las pequeñas.
- El salario aumenta progresivamente de 2020 a 2024.
- Existen claras diferencias salariales entre países, incluso para trabajos remotos.

---

## 🛠️ **Tecnologías utilizadas**

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- GeoPandas (para el mapa geográfico)  
- Jupyter Notebook  




