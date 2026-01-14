# sprint7-final-project - Análisis ConnectaTel

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.

Este repositorio contiene el análisis exploratorio y ejecutivo realizado sobre los datos de clientes de ConnectaTel, con el objetivo de entender patrones de uso, segmentación de clientes y oportunidades de mejora en la oferta de planes.

🎯 Objetivo del proyecto

El objetivo principal del proyecto es analizar el comportamiento de uso de los clientes (mensajes, llamadas y minutos por llamada) y evaluar cómo estos patrones se relacionan con:

El tipo de plan contratado (Básico vs Premium)

La edad de los clientes

La presencia de outliers y uso extremo

El análisis busca traducir hallazgos técnicos en insights accionables para el negocio, orientados a optimizar la segmentación, la rentabilidad y el diseño de planes.

📊 Datasets utilizados

El proyecto trabaja con datasets que simulan información real de una empresa de telecomunicaciones:

Usuarios: información demográfica (edad, identificador de cliente).

Planes: tipo de plan contratado (Básico / Premium).

Uso: métricas de comportamiento:

Número de mensajes

Número de llamadas

Minutos por llamada

Los datos incluyen valores nulos, dispersión y outliers, diseñados para reflejar escenarios reales de negocio.

🧩 Etapas del análisis

El notebook principal sigue una estructura clara y reproducible:

Carga de datos

Importación de datasets

Revisión inicial de estructura y tipos de variables

Evaluación de calidad de datos

Identificación de valores nulos

Análisis del porcentaje de filas afectadas

Decisiones justificadas de tratamiento (conservación de nulos cuando representan ausencia real de uso)

Análisis exploratorio (EDA)

Distribuciones por variable

Comparación de planes Básico vs Premium

Análisis por edad y nivel de uso

Detección de outliers

Identificación de patrones de uso extremo

Evaluación de implicaciones para el negocio

Insights ejecutivos

Segmentación de clientes

Identificación de segmentos más valiosos

Recomendaciones estratégicas para la oferta de planes

📂 Contenido del repositorio

S7 Version-Estudiante-Project-ConnectaTel.ipynb → Notebook principal con limpieza de datos, EDA, visualizaciones y conclusiones ejecutivas.

README.md → Documento descriptivo del proyecto y guía de reproducción.

▶ Cómo abrir el notebook en Google Colab

Puedes ejecutar el análisis fácilmente en Google Colab:

Abre el archivo .ipynb desde GitHub

Haz clic en Open in Colab

O bien:

Descarga el notebook

Sube el archivo manualmente a https://colab.research.google.com

🔁 Guía de reproducción del análisis

Abrir el notebook S7 Version-Estudiante-Project-ConnectaTel.ipynb

Ejecutar las celdas en orden (de arriba hacia abajo)

Verificar que los datasets estén disponibles en las rutas indicadas en el notebook

Revisar:

Tablas de valores nulos

Gráficos de distribución

Insights y conclusiones finales

El análisis es completamente reproducible siempre que los archivos de datos estén disponibles.

🧠 Resultado esperado

Al finalizar el notebook, el lector podrá:

Comprender cómo usan el servicio los distintos segmentos de clientes

Identificar riesgos y oportunidades asociados a uso extremo

Evaluar si los planes actuales están alineados con el comportamiento real

Contar con recomendaciones claras para decisiones comerciales y de producto

Autor: Enrique Robles Torres – Analista de Datos
