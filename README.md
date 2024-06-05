# Análisis de Sentimiento de Tweets sobre el Municipio de Vicente López

## **Objetivo**
El objetivo de este proyecto es analizar las respuestas a los tweets del municipio para identificar y comprender las críticas negativas de la gente. Utilizando técnicas de Procesamiento de Lenguaje Natural (NLP) y modelado de temas, se busca extraer información que permita mejorar la gestión y la respuesta.

## **Alcance**
- **Recopilación de datos:** Recolectar tweets relacionados con el municipio utilizando la extensiòn de google Bardeen AI.
- **Limpieza y preprocesamiento de datos:** Eliminar menciones de usuarios, URLs, y caracteres especiales. Convertir los textos a minúsculas y eliminar stopwords.
- **Análisis de sentimiento:** Utilizar modelos de NLP para clasificar los tweets en categorías de sentimiento (positivo, negativo, neutral).
- **Modelado de temas:** Aplicar LDA (Latent Dirichlet Allocation) para identificar los temas más comunes en los tweets negativos.
- **Visualización:** Crear visualizaciones para mostrar las tendencias de críticas negativas a lo largo del tiempo y las palabras más comunes en los tweets.

## **Conclusiones**
- El análisis de sentimiento y el modelado de temas permitieron identificar los principales problemas y preocupaciones de la gente. Por ejemplo, temas recurrentes como  impuestos, limpieza, iluminaria y limpieza fueron destacados en los tweets negativos.
- Considerando que este anàlisis se hizo con aproximadamente 300 tweets se obtuvo un buen desarrollo y anàlisis pero logicamente cuanto mas datos haya mejor resultado se va a poder obtener.
---

# Análisis de Calidad del Agua del Río de la Plata

## **Objetivo**
El objetivo de este proyecto es analizar los datos de calidad del agua del Río de la Plata para predecir mediante modelos como regresión logistica y árboles de decisiones el Indice de calidad del agua (ICA). El análisis se enfoca en diversos parámetros físicos, químicos y biológicos.

## **Alcance**
- **Recopilación de datos:** Utilizar datos recopilados de la pagina oficial del CIAM (Centro de informaciòn ambiental) para el análisis.
- **Limpieza y preprocesamiento de datos:** Convertir columnas con valores numéricos almacenados como texto a formatos numéricos. Manejar valores especiales como "<0.005" o ">0.5".
- **Análisis descriptivo:** Generar estadísticas descriptivas y visualizaciones.
- **Análisis de correlaciones:** Evaluar las correlaciones entre diferentes variables.
- **Clasificación de calidad del agua:** Utilizar el índice de calidad del agua (ICA) para clasificar las muestras.

## **Conclusiones**
- Se entreno un modelo que predijo resultados que varian del resultado real aproximadante +- 3.69. Lógicamente cuanto mas chico sea mucho mejor pero con la cantidad de datos que tenia, es un buen resultado dentro de todo.
---

### **Recursos**
- Los datos para el análisis del río de la plata son sacados de https://ciam.ambiente.gob.ar/repositorio.php?tid=1&stid=2&did=382# .
- Los datos para el análisis de los tweets fueron recolectados mediante el siguiente scraper: https://www.bardeen.ai/scraper .
- El proyecto fue realizado en la versión de python 3.11.0
