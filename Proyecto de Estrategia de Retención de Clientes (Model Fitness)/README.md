# 🏋️ Estrategia de Retención de Clientes (Model Fitness)

## 📌 Descripción del Proyecto

La retención de clientes es uno de los principales desafíos para los gimnasios, ya que la cancelación de membresías impacta directamente en los ingresos y la estabilidad del negocio.

En este proyecto se analizaron los datos de la cadena de gimnasios **Model Fitness** con el objetivo de identificar los factores asociados al abandono de clientes (*churn*), construir modelos predictivos capaces de anticipar futuras cancelaciones y segmentar a los usuarios según sus patrones de comportamiento.

A través de técnicas de **Análisis Exploratorio de Datos (EDA)**, **Machine Learning Supervisado** y **Clustering**, se desarrolló una estrategia basada en datos para apoyar la toma de decisiones orientadas a mejorar la fidelización de clientes.

## 🎯 Objetivos

* Identificar los factores que influyen en la cancelación de clientes.
* Detectar perfiles con mayor riesgo de abandono.
* Construir modelos predictivos para anticipar cancelaciones.
* Segmentar clientes mediante técnicas de clustering.
* Proponer recomendaciones de negocio para mejorar la retención.

## 🔎 Metodología

### 1. Análisis Exploratorio de Datos (EDA)

* Limpieza y validación de datos.
* Análisis de variables relacionadas con cancelación.
* Matriz de correlación.
* Identificación de patrones de comportamiento.

### 2. Modelos Predictivos

Se desarrollaron dos modelos de clasificación:

* Regresión Logística
* Bosque Aleatorio (Random Forest)

Métricas evaluadas:

* Exactitud (Accuracy)
* Precisión (Precision)
* Recall
* F1 Score
* ROC AUC

### 3. Segmentación de Clientes

* Estandarización de variables.
* Dendrograma para estimar el número de grupos.
* Aplicación de K-Means.
* Identificación de 5 segmentos de clientes con comportamientos diferenciados.

## 📊 Principales Hallazgos

* Los clientes con mayor riesgo de cancelación presentan contratos cortos, menor antigüedad y baja frecuencia de asistencia.
* La frecuencia de visitas al gimnasio es uno de los factores más relevantes para explicar la permanencia de los usuarios.
* Los modelos predictivos alcanzaron aproximadamente un **92% de exactitud** y un **ROC AUC cercano a 0.97**, demostrando una alta capacidad para identificar clientes en riesgo.
* El análisis de clustering permitió identificar segmentos con distintos niveles de compromiso y probabilidad de abandono.

## 💡 Recomendaciones

* Implementar alertas tempranas para clientes con disminución de asistencia.
* Diseñar campañas de renovación antes del vencimiento de contratos.
* Fortalecer programas de bienvenida para nuevos usuarios.
* Incentivar la participación mediante actividades grupales y beneficios de fidelización.
* Aplicar estrategias diferenciadas según el segmento de clientes identificado.

## 🚀 Resultado

El proyecto demuestra cómo el análisis de datos puede utilizarse para anticipar la cancelación de clientes, optimizar estrategias de retención y apoyar la toma de decisiones mediante modelos predictivos y técnicas de segmentación.

## 🛠️ Herramientas Utilizadas
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white)&nbsp;
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)&nbsp;
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=flat&logo=tensorflow&logoColor=white)&nbsp;
![K-Means Clustering](https://img.shields.io/badge/K--Means%20Clustering-4CAF50?style=flat&logo=scikitlearn&logoColor=white)&nbsp;
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)&nbsp;
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)&nbsp;
![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white)&nbsp;
