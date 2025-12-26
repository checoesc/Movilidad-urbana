# Movilidad-urbana
El proyecto analiza la relación entre movilidad urbana y productividad económica en ciudades de América Latina, usando datos del TomTom Traffic Index y OECD Cities. Integra, limpia y analiza indicadores de congestión y variables económicas para identificar ciudades donde invertir en transporte genera mayor impacto.

🚦 Movilidad Urbana y Productividad Económica en Ciudades Latinoamericanas
📌 Descripción del proyecto

Este repositorio analiza la relación entre la movilidad urbana y la productividad económica en ciudades latinoamericanas. El problema central que se aborda es cómo la congestión vehicular, los tiempos de traslado y la saturación vial pueden impactar negativamente en la eficiencia económica de una ciudad, medida principalmente a través del PIB per cápita y otros indicadores socioeconómicos.

A partir de datos reales de movilidad y economía urbana, el proyecto busca identificar patrones, relaciones y niveles críticos que ayuden a priorizar inversiones en infraestructura de transporte, utilizando técnicas de análisis exploratorio, visualización de datos y modelos de árboles de decisión.

🎯 Objetivo

Evaluar cómo los indicadores de tráfico urbano se relacionan con variables de productividad económica, con el fin de:

Identificar ciudades con alto impacto negativo por congestión

Detectar umbrales críticos de movilidad

Apoyar la toma de decisiones basada en datos para inversión en transporte urbano

🗂️ Estructura del repositorio
├── notebooks/
│   └── Proyecto de movilidad urbana.ipynb
├── data/
│   └── (datasets de movilidad y economía)
├── README.md

🔎 Metodología y pasos del análisis
1️⃣ Carga y exploración inicial de datos

Se importan los datasets de movilidad urbana y productividad económica. Se revisa la estructura, tipos de variables y valores faltantes para comprender el alcance del análisis.

2️⃣ Limpieza y preparación de datos

Se eliminan duplicados, se manejan valores nulos y se ajustan formatos numéricos. Además, se estandarizan nombres de ciudades y países para permitir la correcta integración de fuentes.

3️⃣ Integración de datasets

Los datos de tráfico y economía se combinan en una sola tabla analítica, permitiendo relacionar indicadores como congestión, tiempos de viaje y PIB per cápita por ciudad.

4️⃣ Análisis exploratorio (EDA)

Se analizan distribuciones, correlaciones y tendencias mediante estadísticas descriptivas y visualizaciones. Esto permite detectar patrones iniciales entre movilidad y productividad.

5️⃣ Modelado con árboles de decisión

Se implementa un modelo de árbol de decisión para identificar qué variables de movilidad tienen mayor influencia sobre la productividad económica, facilitando la interpretación de resultados.

6️⃣ Interpretación de resultados

Se analizan los nodos del árbol y las reglas generadas para identificar niveles críticos de congestión y su impacto económico.

🛠️ Tecnologías utilizadas

Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

📊 Resultado esperado

Un análisis claro y accionable que muestre cómo la movilidad urbana influye en la productividad económica, proporcionando evidencia para decisiones estratégicas de inversión en infraestructura de transporte.
