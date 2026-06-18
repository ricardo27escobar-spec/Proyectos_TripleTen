# 📞 Telecomunicaciones: Identificación de Operadores Ineficaces

## 🎯 Problema Detectado

En los centros de atención telefónica, la calidad del servicio depende directamente del desempeño de los operadores. Sin embargo, identificar operadores con bajo rendimiento puede ser complejo cuando se gestionan miles de llamadas diariamente.

CallMeMaybe, una empresa de telefonía virtual, busca implementar un sistema de monitoreo basado en datos que permita detectar operadores ineficaces utilizando métricas operacionales clave como llamadas perdidas, tiempos de espera y actividad saliente.

El objetivo de este proyecto fue desarrollar una metodología analítica que permitiera identificar operadores con señales de ineficiencia y generar recomendaciones para optimizar la experiencia del cliente y la eficiencia operativa.

## 🧩 Desafío de Negocio

La empresa necesitaba responder las siguientes preguntas:

* ¿Existen operadores significativamente menos eficientes que otros?
* ¿Qué métricas permiten identificar comportamientos ineficaces?
* ¿Las diferencias observadas son estadísticamente significativas?
* ¿Qué acciones podrían mejorar la calidad del servicio?

## 📂 Dataset

El análisis se realizó utilizando registros operacionales de CallMeMaybe:

Llamadas entrantes y salientes.
* Duración de llamadas.
* Tiempo de espera.
* Estado de atención.
* Identificación de operadores.

Datos Analizados
* Miles de registros de llamadas.
* Operadores con distintos niveles de actividad.
* Métricas temporales y operacionales.

## 🔍 Metodología
### 1️⃣ Exploración y Limpieza de Datos
* Análisis de estructura del dataset.
* Tratamiento de valores ausentes.
* Validación de tipos de datos.
* Identificación de anomalías y outliers.

### 2️⃣ Análisis Exploratorio (EDA)
* Distribución de llamadas.
* Comportamiento de tiempos de espera.
* Evaluación de actividad por operador.
* Identificación de patrones operacionales.

### 3️⃣ Construcción de Indicadores
Se desarrollaron métricas para evaluar el desempeño de los operadores:

* Tasa de llamadas perdidas.
* Tiempo promedio de espera.
* Volumen de llamadas salientes.
* Nivel de actividad operativa.
### 4️⃣ Identificación de Operadores Ineficaces
Los operadores fueron clasificados según criterios de desempeño operacional utilizando umbrales basados en la distribución de los datos.

### 5️⃣ Validación Estadística
Se realizaron pruebas de hipótesis para validar diferencias entre operadores eficaces e ineficaces.

## 📊 Principales Hallazgos
### 📉 Llamadas Perdidas
* Se observó una tasa global de llamadas perdidas cercana al 44%.
* Algunos operadores alcanzaron tasas extremadamente elevadas.

### ⏳ Tiempo de Espera
* La distribución presentó una fuerte asimetría positiva.
* Existen casos con tiempos de espera significativamente superiores al promedio.

### ☎️ Actividad Operativa
* Se identificaron diferencias importantes en el volumen de llamadas gestionadas por operador.

### 🚨 Operadores Ineficaces
* Fueron identificados más de 600 operadores con señales de ineficiencia operacional.
* Los resultados muestran patrones consistentes de bajo desempeño.

## 📈 Pruebas Estadísticas
Se evaluaron tres hipótesis principales:

### Tiempo de Espera
* H₀: No existen diferencias entre operadores eficaces e ineficaces.
* H₁: Los operadores ineficaces presentan mayores tiempos de espera.

### Llamadas Perdidas
* H₀: La tasa de llamadas perdidas es igual entre grupos.
* H₁: Los operadores ineficaces presentan tasas superiores.

### Actividad Saliente
* H₀: Ambos grupos presentan el mismo nivel de actividad.
* H₁: Los operadores ineficaces realizan menos llamadas salientes.

### Resultado
Las pruebas confirmaron diferencias estadísticamente significativas entre ambos grupos.

## 💡 Recomendaciones
* Implementar monitoreo continuo de KPIs operacionales.
* Priorizar capacitación para operadores con altas tasas de llamadas perdidas.
* Establecer alertas tempranas para tiempos de espera excesivos.
* Redistribuir la carga de trabajo entre operadores.
* Incorporar dashboards de seguimiento para supervisores.

## 🚀 Impacto Esperado
La implementación de estas recomendaciones permitiría:
* Reducir tiempos de espera.
* Disminuir llamadas perdidas.
* Mejorar la experiencia del cliente.
* Optimizar la productividad del centro de atención.
* Facilitar la toma de decisiones basada en datos.

## Tecnologías Utilizadas
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white)&nbsp;
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)&nbsp;
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)&nbsp;
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)&nbsp;
![Datetime](https://img.shields.io/badge/Datetime-3776AB?style=flat&logo=python&logoColor=white)&nbsp;
