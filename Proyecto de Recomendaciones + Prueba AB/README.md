# 🧪 Sistema de Recomendaciones y Prueba A/B

## 🎯 Problema de Negocio
Las plataformas digitales dependen de la capacidad de convertir usuarios en clientes. Con el objetivo de mejorar la experiencia de navegación y aumentar las conversiones, la empresa desarrolló un nuevo sistema de recomendaciones de productos.

Sin embargo, antes de implementar esta funcionalidad a gran escala, era necesario validar si realmente generaba mejoras en el comportamiento de los usuarios o si los cambios observados podían explicarse por variaciones aleatorias.

## 📌 Objetivo
Evaluar el impacto de un nuevo sistema de recomendaciones mediante una prueba A/B, comparando el comportamiento de un grupo de control (A) y un grupo experimental (B) a lo largo del embudo de conversión.

## 📂 Datos Utilizados
El análisis se realizó utilizando cuatro conjuntos de datos:
* Eventos de usuarios.
* Participantes del experimento.
* Nuevos usuarios registrados.
* Información de campañas de marketing.

## 🔍 Metodología

### 1. Exploración y Validación de Datos
* Identificación de valores nulos.
* Búsqueda de registros duplicados.
* Conversión de variables temporales.
* Validación de integridad de los datos experimentales.

### 2. Análisis del Embudo de Conversión
Se evaluó el recorrido de los usuarios entre las distintas etapas:

Login → Product Page → Product Cart → Purchase

### 3. Evaluación de la Calidad del Experimento
* Comparación de eventos por usuario.
* Identificación de usuarios presentes en ambos grupos.
* Análisis de distribución temporal de eventos.
* Validación de equilibrio entre muestras.

### 4. Pruebas Estadísticas
Se aplicó una prueba Z para comparar las tasas de conversión entre grupos independientes en cada etapa del embudo.

## 📊 Principales Hallazgos
* Los grupos presentaron distribuciones de actividad similares.
* Se identificaron usuarios asignados simultáneamente a ambos grupos, los cuales fueron eliminados para evitar sesgos.
* El volumen de eventos aumentó progresivamente durante el período experimental.
* Se detectaron diferencias estadísticamente significativas en algunas etapas del embudo de conversión.

## 🧪 Hipótesis Evaluadas
* **H₀:** No existen diferencias significativas entre las tasas de conversión de los grupos A y B.
* **H₁:** Existen diferencias significativas entre las tasas de conversión de los grupos A y B.

## 📈 Resultados
La prueba Z identificó diferencias estadísticamente significativas en:
* Login → Product Page
* Product Page → Cart
* Login → Purchase

Estos resultados sugieren que la modificación introducida tuvo impacto sobre determinadas etapas del recorrido del usuario.

## 💡 Recomendaciones
* Implementar monitoreo continuo del sistema de recomendaciones.
* Analizar el comportamiento por segmentos de usuarios.
* Realizar experimentos complementarios para validar la estabilidad de los resultados.
* Monitorear métricas posteriores a la implementación para confirmar el impacto observado.

## 🚀 Impacto de Negocio
El proyecto permitió evaluar objetivamente la efectividad de una nueva funcionalidad de producto mediante experimentación controlada, proporcionando evidencia estadística para respaldar decisiones de implementación y optimización de la experiencia de usuario.

## 🛠️ Tecnologías Utilizadas
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)&nbsp;
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)&nbsp;
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white)&nbsp;
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)&nbsp;
![Datetime](https://img.shields.io/badge/Datetime-3776AB?style=flat&logo=python&logoColor=white)&nbsp;
![Math](https://img.shields.io/badge/Math-3776AB?style=flat&logo=python&logoColor=white)
