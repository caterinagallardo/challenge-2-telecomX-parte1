# challenge-2-telecomX-parte1
<h1 align="center">📊 Proyecto de Análisis de Churn de Clientes - Telecom X</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20progreso-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.10-yellow?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Data%20Science-EDA-green?style=flat-square" />
</p>

---

## 📝 Descripción General  

Este repositorio contiene un proyecto de análisis de datos orientado a comprender las causas que generan la **tasa de abandono de clientes (Churn)** en **Telecom X**, una empresa ficticia del sector de telecomunicaciones.  

El enfoque se centra en el rol de un **Asistente de Análisis de Datos**, llevando a cabo la **recopilación, depuración, transformación y exploración** de la información de clientes, con el fin de identificar patrones relevantes que permitan explicar la pérdida de usuarios.  

A través de un **Análisis Exploratorio de Datos (EDA)**, se identificaron tendencias y relaciones clave que servirán como base para futuros modelos predictivos y el diseño de **estrategias efectivas de retención**.  

---

## 🎯 Objetivo del Análisis  

El principal desafío es la **alta tasa de cancelaciones** que presenta Telecom X. El análisis se planteó los siguientes objetivos:  

✔️ **Detectar patrones y tendencias** entre clientes que abandonan los servicios.  
✔️ **Identificar variables críticas** (demográficas, contractuales, de uso y gasto) relacionadas con el churn.  
✔️ **Extraer insights accionables** para que la empresa pueda implementar acciones de retención basadas en datos.  

---

## 📂 Contenido del Repositorio  

📄 **`README.md`** → Documentación del proyecto.  
📓 **`Challenge Telecom X: análisis de evasión de clientes.ipynb`** → Notebook con el código Python, análisis y visualizaciones.  
📊 **`df_final.csv`** → Dataset final tras limpieza y transformación de datos.  

---

## 🛠️ Herramientas y Librerías Utilizadas  

| Herramienta | Uso principal |
|-------------|--------------|
| **Pandas** 🐼 | Manipulación y análisis de datos |
| **NumPy** 🔢 | Cálculos y operaciones numéricas |
| **Matplotlib** 📉 | Gráficos y visualizaciones estáticas |
| **Seaborn** 📊 | Visualizaciones estadísticas avanzadas |

---

## 🚀 Metodología de Trabajo  

1️⃣ **Obtención y Carga de Datos**  
   - Importación del dataset original en formato JSON.  
   - Preparación del entorno en Python.  

2️⃣ **Limpieza y Preprocesamiento**  
   - Normalización de la estructura JSON.  
   - Tratamiento de valores nulos.  
   - Conversión de tipos de datos.  
   - Codificación de variables categóricas (‘Yes’/’No’ → 1/0).  
   - Consolidación de DataFrames en un único dataset.  

3️⃣ **Análisis Exploratorio de Datos (EDA)**  
   - Cálculo de la tasa de churn general.  
   - Análisis de churn según variables categóricas y numéricas.  
   - Uso de histogramas, boxplots y estadísticas descriptivas para detectar patrones.  

---

<p align="center">
  💡 <em>Este análisis sienta las bases para la implementación de modelos predictivos y estrategias de retención orientadas a reducir la pérdida de clientes.</em>
</p>
