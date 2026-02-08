# Laboratorio 3 - IA

## 📌 Descripción general

Este laboratorio tiene como objetivo reforzar el criterio de diseño de modelos de Inteligencia Artificial, más allá del uso de librerías. Se aborda la implementación y análisis de modelos probabilísticos, geométricos y basados en reglas, evaluando no solo su desempeño numérico, sino también su interpretabilidad y aplicabilidad en un contexto real de e-sports.

El laboratorio se divide en tres tareas principales:

Análisis teórico de decisiones de diseño en modelos de IA.

Implementación desde cero de un clasificador Bayesiano para detección de spam.

Aplicación y comparación de modelos SVM y Árboles de Decisión sobre un dataset real de League of Legends.

## Estructura del repositorio
```bash
├── README.md
├── Task2.ipynb
├── Task3.ipynb
├── entrenamiento.txt
└── high_diamond_ranked_10min.csv
```

## 📄 Descripción de archivos

README.md
Documento descriptivo del laboratorio, objetivos y estructura.

Task2.ipynb
Implementación completa del Filtro de Spam Bayesiano, incluyendo:

Pre-procesamiento de texto

Cálculo de probabilidades a priori

Likelihoods con Laplace Smoothing

Inferencia y evaluación del modelo

Task3.ipynb
Implementación de SVM y Árboles de Decisión sobre el dataset de League of Legends, incluyendo:

Limpieza y pre-procesamiento

Entrenamiento de SVM (Kernel Lineal y RBF)

Entrenamiento y visualización de Árboles de Decisión

Feature Importance y análisis

Comparación final de modelos

entrenamiento.txt
Archivo de texto utilizado como dataset para el entrenamiento del clasificador Bayesiano de spam (formato: ETIQUETA \t MENSAJE).

high_diamond_ranked_10min.csv
Dataset de partidas ranked de League of Legends (Diamond), con estadísticas al minuto 10.
Variable objetivo: blueWins.

## 📊 Resultados principales

Los modelos SVM obtienen el mejor desempeño numérico.

El Árbol de Decisión, aunque menos preciso, ofrece mayor interpretabilidad.

Variables como diferencia de oro, experiencia y control del mapa resultan clave para explicar el resultado de una partida al minuto 10

📎 Laboratorio realizado como parte del curso CC3045 – Inteligencia Artificial.
