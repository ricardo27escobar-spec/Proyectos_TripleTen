# 📊 Marketing Analytics: Análisis de Usuarios, Rentabilidad y Eficiencia de Adquisición

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar el desempeño de marketing de una empresa digital mediante el estudio del comportamiento de sus usuarios, los patrones de conversión, el valor generado por cliente y la rentabilidad de las inversiones publicitarias.

A través de técnicas de análisis exploratorio de datos, análisis de cohortes y métricas de marketing, se evaluó el recorrido completo del usuario desde su primera visita hasta la generación de ingresos, permitiendo identificar oportunidades de optimización en la adquisición, conversión y retención de clientes.

## Objetivo de Negocio
La empresa busca comprender:
* Cómo interactúan los usuarios con la plataforma.
* Cuándo ocurre la primera compra.
* Cuánto valor generan los clientes a lo largo del tiempo.
* Cuánto cuesta adquirir nuevos clientes.
* Qué fuentes de adquisición son más eficientes.
* Si las inversiones en marketing generan retornos positivos.

## Dataset
El análisis se desarrolló utilizando tres conjuntos de datos:

### Visits
Contiene información sobre las visitas realizadas por los usuarios:

* ID de usuario
* Fecha y hora de visita
* Fuente de adquisición

### Orders
Contiene información de compras:
* ID de usuario
* Fecha de compra
* Ingresos generados

### Costs
Contiene los gastos de marketing:
* Fuente de adquisición
* Fecha
* Costos publicitarios

## Metodología

### 1. Análisis de Actividad de Usuarios
Se calcularon métricas de actividad:
* DAU (Daily Active Users)
* WAU (Weekly Active Users)
* MAU (Monthly Active Users)

Además, se evaluó la relación DAU/MAU para medir el nivel de engagement de la plataforma.

### 2. Análisis de Conversión
Se estudió:
* Frecuencia de visitas.
* Tiempo hasta la primera compra.
* Conversión por días desde la adquisición.
* Comportamiento de compra de los usuarios.

El objetivo fue identificar en qué momento ocurre la mayor probabilidad de conversión.

### 3. Análisis de Ventas
Se evaluó:
* Cantidad de pedidos diarios y mensuales.
* Tamaño promedio de compra.
* Ingresos generados por usuario.
* Diferencias entre dispositivos desktop y touch.

### 4. Análisis de Cohortes y LTV
Se construyeron cohortes de usuarios según su fecha de adquisición para calcular:
* LTV por cohorte.
* LTV acumulado.
* Evolución del valor generado por los clientes a lo largo del tiempo.

### 5. Análisis de Marketing
Se analizó:
* Gasto total en marketing.
* Distribución del presupuesto por fuente.
* Evolución temporal de la inversión.
* Participación de cada canal de adquisición.

### 6. Costo de Adquisición de Clientes (CAC)
Se calculó el costo promedio necesario para adquirir un cliente en cada fuente de marketing utilizando la primera visita registrada de cada usuario para evitar duplicidades.

### 7. Retorno sobre la Inversión en Marketing (ROMI)
Finalmente se evaluó la rentabilidad de cada fuente mediante:

ROMI = (Ingresos − Costos) / Costos

Esto permitió identificar qué canales generan valor para la empresa y cuáles consumen presupuesto sin producir retornos suficientes.

## Principales Hallazgos

### Comportamiento de Usuarios
* La plataforma registró aproximadamente 23 mil usuarios activos mensuales.
* El ratio DAU/MAU fue cercano al 4%, indicando un uso ocasional más que diario.
* La mayoría de los usuarios regresa solo una o dos veces.

### Conversión
* La mayor parte de las compras ocurre durante el primer día y la primera semana desde la adquisición.
* La probabilidad de conversión disminuye significativamente con el paso del tiempo.

### Ventas
* Existe una marcada estacionalidad con incrementos importantes hacia fin de año.
* Los usuarios de desktop generan un mayor valor por compra que los usuarios de dispositivos touch.

### LTV
* La mayor parte del valor generado por los clientes se concentra durante los primeros meses posteriores a la adquisición.
* La cohorte de junio de 2017 presentó el mejor desempeño, alcanzando un LTV acumulado cercano a 3 unidades monetarias por usuario.

### Marketing
* La fuente de adquisición 3 concentró aproximadamente el 43% del presupuesto total.
* La inversión mostró un incremento importante durante los últimos meses del año.

### CAC
* La fuente 3 presentó el CAC más alto del análisis.
* Las fuentes 9 y 10 mostraron los costos de adquisición más bajos.
* La fuente 4 logró un equilibrio atractivo entre volumen de clientes y costo de adquisición.

### ROMI
* El ROMI total del negocio fue de -23%.
* La fuente 1 fue la más rentable con un ROMI de 49%.
* Las fuentes 2, 5 y 9 lograron rentabilidad positiva.
* La fuente 3 registró el peor desempeño con un ROMI de -61%.

## Conclusiones
El análisis demuestra que el principal desafío de la empresa no radica en atraer más usuarios, sino en mejorar la calidad y rentabilidad de la adquisición. Aunque la plataforma mantiene una base estable de usuarios y genera ingresos de forma constante, la estrategia global de marketing no logra recuperar completamente la inversión realizada.

Los resultados indican que una redistribución del presupuesto hacia las fuentes más rentables, junto con acciones orientadas a mejorar la conversión temprana y la retención de clientes, podría aumentar significativamente la rentabilidad del negocio.

Este proyecto permitió aplicar técnicas de análisis de comportamiento de usuarios, cohortes, LTV, CAC y ROMI para transformar datos operacionales en recomendaciones estratégicas orientadas a la toma de decisiones.

## Herramientas Utilizadas

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white)&nbsp;
![Datetime](https://img.shields.io/badge/Datetime-3776AB?style=flat&logo=python&logoColor=white)&nbsp;
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)&nbsp;
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)&nbsp;
![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white)&nbsp;
