# 📊 Proyecto de Machine Learning: Análisis de Rendimiento Estudiantil

## 📝 Descripción del Proyecto
Este proyecto tiene como objetivo analizar un conjunto de datos basado en características de estudiantes para resolver dos problemas de negocio distintos utilizando técnicas de Machine Learning: uno predictivo continuo (Regresión) y uno de segmentación binaria (Clasificación). 

El análisis se divide en dos notebooks principales que abordan diferentes preguntas clave sobre el desempeño académico y las necesidades de los alumnos.

##  Modelos Desarrollados

### 1. Modelo de Regresión (Predicción de Puntaje)
* **Objetivo:** Predecir el puntaje exacto que obtendrá un alumno en su examen final basándose en sus variables históricas y de comportamiento.
* **Algoritmos evaluados:** Se probaron múltiples modelos (Lineales, Ridge, Lasso, ElasticNet) y se optimizaron sus hiperparámetros.
* **Valor de Negocio:** Permite estimar el desempeño general de una generación y establecer métricas de éxito antes de que concluya el ciclo escolar.

### 2. Modelo de Clasificación (Necesidad de Tutoría)
* **Objetivo:** Identificar proactivamente si un alumno requerirá la asignación de un tutor para mejorar su desempeño académico (Sí/No).
* **Algoritmos evaluados:** Se implementaron técnicas de clasificación (incluyendo Support Vector Machines - SVM) evaluando su precisión y capacidad de generalización.
* **Valor de Negocio:** Ayuda a optimizar los recursos de la institución, asignando tutores de manera preventiva a los estudiantes que tienen mayor probabilidad de necesitarlos, reduciendo así la tasa de reprobación.

##  Tecnologías y Librerías Utilizadas
El proyecto fue desarrollado en Python utilizando las siguientes herramientas:
* **Manipulación de datos:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Modelos de regresión, clasificación, métricas y validación cruzada)
* **Preprocesamiento:** `MinMaxScaler`, `StandardScaler`
