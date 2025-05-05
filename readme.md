# 📰 Clasificador de Noticias con Análisis de Sentimiento

Este proyecto utiliza técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático para clasificar titulares de noticias como **reales** o **falsas**, e incluye un análisis de sentimiento para evaluar el tono emocional de cada titular.

---

## 📌 Funcionalidades

- Limpieza y preprocesamiento de texto
- Vectorización de texto con TF-IDF (Unigramas y Bigramas)
- Entrenamiento y evaluación de modelos:
  - Regresión Logística
  - Naive Bayes
  - Bosques Aleatorios
- Selección automática del mejor modelo según la precisión en validación
- Análisis de sentimiento con VADER (NLTK)
- Clasificación automática de datos de prueba
- Clasificación manual de un nuevo titular ingresado por el usuario
- Exportación de predicciones, modelo y vectorizador

---

## 🛠️ Requisitos

**Python** 3.8 o superior.

Instala las librerías necesarias 
