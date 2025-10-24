# Proyecto: Trainings - Machine Learning

Este repositorio contiene prácticas de aprendizaje automático (Machine Learning) desarrolladas en el contexto de entrenamientos y cursos de DataCamp.

## Prácticas incluidas

### 1. Predicción de Temperatura en Londres

- **Archivo:** `code/Predicting Temperature in London.ipynb`
- **Descripción:** Utiliza técnicas de Machine Learning para predecir la temperatura media mensual en Londres, Inglaterra.
- **Algoritmos utilizados:**
  - Regresión lineal
  - Árboles de decisión
  - Random Forest
- **Métricas:**
  - Error cuadrático medio (RMSE)
- **Herramientas:**
  - MLflow para registro de experimentos, modelos, hiperparámetros y métricas
- **Pasos principales:**
  1. Carga y limpieza de datos meteorológicos
  2. Análisis exploratorio y visualización
  3. Selección de características relevantes
  4. Entrenamiento y evaluación de modelos
  5. Registro y consulta de resultados con MLflow

## Requisitos

- Python 3.7+
- Paquetes: pandas, numpy, scikit-learn, matplotlib, seaborn, mlflow

Instalación recomendada:

```bash
poetry add pandas numpy scikit-learn matplotlib seaborn mlflow
```

## Estructura del repositorio

```
code/
  Predicting Temperature in London.ipynb
pyproject.toml
poetry.lock
README.md
```

## Autoría

Creado por Jiliar Silgado.

---

Este README se genera automáticamente analizando los archivos del proyecto y resalta únicamente las prácticas relacionadas con Machine Learning.
