# 🔍 MACHINE LEARNING: CLUSTERING - EXTRACCIÓN DE PATRONES DE DATOS

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)

Este proyecto se centra en el **Aprendizaje Automático No Supervisado** mediante la técnica de **Clustering** (Agrupamiento). El objetivo es realizar un **análisis de patrones** en el comportamiento de clientes de tarjetas de crédito para segmentarlos en grupos homogéneos, extrayendo información de alto valor que no está previamente etiquetada en los datos.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Introducción al Clustering
- **Aprendizaje No Supervisado:** A diferencia de la clasificación, el *clustering* se utiliza cuando **no hay etiquetas** de salida definidas previamente. El modelo debe encontrar patrones y agrupar automáticamente las instancias similares.
- **Concepto:** El *clustering* agrupa los datos de tal forma que los objetos dentro de un *cluster* son más similares entre sí que con respecto a los objetos de otros *clusters*.

### 2️⃣ Dataset y Caso de Estudio
- **Dataset:** Se utiliza el dataset **CC GENERAL.csv**, una base de datos de Kaggle con información sobre el uso general de tarjetas de crédito.
- **Objetivo Práctico:** El análisis busca identificar **segmentos de clientes** basándose en su comportamiento financiero, como hábitos de gasto, frecuencia de compras, límites de crédito y pagos realizados.

### 3️⃣ Metodología de Análisis
- **Preprocesamiento:** Un proyecto de *clustering* típicamente requiere la **estandarización o normalización** de las variables para evitar que las variables con mayores rangos dominen la distancia de agrupamiento.
- **Aplicación de Clustering:** Se aplica un algoritmo de *clustering* (presumiblemente **K-Means**, el más común en estos casos) para asignar a cada cliente a un grupo o *cluster* específico.
- **Extracción de Patrones:** Una vez agrupados, se analizan las características promedio de cada *cluster* para asignarles un **significado empresarial** (ej. *Clientes de Alto Gasto*, *Clientes Morosos*, *Clientes de Uso Infrecuente*, etc.).

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Pandas**     | Carga y manipulación del dataset (`CC GENERAL.csv`)|
| **Scikit-learn**| Implementación del algoritmo de *Clustering*|
| **NumPy**      | Operaciones numéricas y manejo de *arrays* (inferido) |

---

## 🎯 Objetivo del Proyecto
Proporcionar una comprensión sólida del paradigma de **Aprendizaje No Supervisado**. El objetivo es que el usuario pueda aplicar el *clustering* para descubrir estructuras o **patrones ocultos** en datos de clientes, lo cual es fundamental para el **marketing, la gestión de riesgos y la toma de decisiones estratégicas** dentro de una empresa.

---

## 📈 Resultados Clave
- **Segmentación Efectiva:** Se logra la segmentación de la base de clientes de tarjetas de crédito en grupos distintos basados en su comportamiento financiero.
- **Identificación de Patrones:** Se extraen patrones de datos crudos, permitiendo a la empresa **personalizar estrategias** de retención, ofertas y gestión de deuda para cada segmento.
- **Fundamento para Estrategia:** Los *clusters* generados son la base para que los equipos de negocio tomen decisiones, como diseñar promociones específicas para los clientes de bajo uso o estrategias de fidelización para los clientes de alto valor.

