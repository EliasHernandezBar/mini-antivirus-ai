# AI Security Guard

Proyecto de Data Analytics y Machine Learning orientado a la detección de archivos potencialmente maliciosos mediante el análisis de características extraídas de los propios archivos.

## Descripción

AI Security Guard es un proyecto end-to-end cuyo objetivo es explorar si un modelo de Machine Learning puede diferenciar archivos benignos y potencialmente maliciosos a partir de variables previamente extraídas.

El proyecto está planteado principalmente como un caso práctico de análisis de datos y aprendizaje automático aplicado a un problema técnico de ciberseguridad defensiva.

No pretende sustituir a un antivirus comercial ni analizar malware real durante las primeras fases de desarrollo.

## Pregunta principal

¿Podemos utilizar características de archivos y determinados patrones estructurales para identificar automáticamente archivos potencialmente maliciosos?

## Objetivos

- Realizar un análisis exploratorio de datos (EDA).
- Aplicar técnicas de Data Cleaning.
- Desarrollar procesos de Feature Engineering.
- Entrenar y comparar modelos de clasificación.
- Evaluar resultados mediante métricas adecuadas.
- Analizar falsos positivos y falsos negativos.
- Interpretar las variables más relevantes para el modelo.
- Guardar y reutilizar el modelo entrenado.
- Integrar el modelo en un prototipo funcional para Windows.

## Tecnologías previstas

### Análisis de datos

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn
- Joblib

### Aplicación

- Python
- Pefile
- Psutil
- Watchdog
- Tkinter

## Metodología

El proyecto seguirá las siguientes fases:

1. Planificación y preparación del entorno.
2. Selección del dataset.
3. Exploratory Data Analysis (EDA).
4. Data Cleaning.
5. Feature Engineering.
6. Entrenamiento de modelos.
7. Evaluación y análisis de errores.
8. Interpretabilidad del modelo.
9. Exportación del modelo.
10. Desarrollo de un scanner local para Windows.

## Estado actual

### Completado

- Definición del proyecto.
- Definición de objetivos.
- Diseño de arquitectura.
- Creación del repositorio GitHub.

### Próximos pasos

- Selección del dataset.
- Creación del notebook de EDA.
- Validación de la calidad de los datos.
- Definición de la variable objetivo.

## Estructura inicial

```text
mini-antivirus-ai/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
├── notebooks/
└── src/
```

## Limitaciones
Este proyecto tiene fines educativos y de portfolio. Durante las primeras fases se trabajará con datasets que contienen características extraídas de archivos, evitando la ejecución de malware real.

## Autor
Elías Hernández Barral

Proyecto desarrollado como parte de mi transición profesional hacia Data Analytics y Machine Learning.