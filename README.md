# Proyecto Final - Programación I

## 🎯 Descripción

Este proyecto consiste en una aplicación de predicción de resultados de partidos de fútbol en Copas del Mundo (desde 2002 hasta 2022). El sistema utiliza aprendizaje automático (Machine Learning) con el algoritmo de Random Forest para predecir si el equipo local ganará, perderá o empatará contra el visitante, basado en estadísticas históricas y rankings FIFA.

## 🛠️ Tecnologías utilizadas

- Python
- Google Colab
- Flask (interfaz web)
- scikit-learn (entrenamiento del modelo)
- joblib (guardado del modelo)
- pandas, numpy (procesamiento de datos)

## 📊 Dataset

El conjunto de datos contiene:
- Año y etapa del partido (ej. Octavos, Cuartos, Final)
- Equipos (local y visitante)
- Resultado del partido
- Ranking FIFA de cada equipo
- Etiqueta del resultado (1: gana local, 0: empate, -1: gana visitante)

## 🚀 Ejecución

1. Abre el archivo `ProyectoFinalProgramacion.ipynb` en Google Colab.
2. Ejecuta cada celda en orden:
   - Se instalarán las dependencias.
   - Se entrenará el modelo con los datos históricos.
   - Se iniciará un servidor Flask (vía ngrok) para usar la interfaz de predicción.
3. Accede al enlace generado (ngrok) para predecir nuevos resultados.

## 🔒 Notas de seguridad

Si usas claves o tokens (como en ngrok), **no los incluyas directamente en el código**. Usa variables de entorno o archivos `.env` y no los subas a GitHub.

## 👥 Autores

Grupo 3  
Facultad de Ingeniería y Ciencias Aplicadas  
ISWZ1102 - Programación I  
