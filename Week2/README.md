

# Objetivo
Implementar y validar una red neuronal basica 

# Implementacion 

**Dataset:** Se utilizó load_diabetes, transformándolo en un problema de clasificación binaria (0: bajo riesgo, 1: riesgo alto) basado en la mediana.

**Preprocesamiento:** Los datos fueron normalizados con StandardScaler y divididos en 80% para entrenamiento y 20% para prueba.

**Modelos:** Se entrenó una Regresión Logística como Baseline y un MLPClassifier (1 capa de 32 neuronas, activación ReLU).

# Pruebas Realizadas
Para validar la lógica de la neurona, se realizó una prueba controlada utilizando los pesos reales aprendidos por el modelo base:

**Puntaje Z calculado:** 1.7055

**Salida de clasificación (Umbral):** 1

**Resultado:** Se verificó que la lógica manual coincide con la predicción del modelo entrenado, validando la comprensión del funcionamiento interno de la neurona.


# Resultados Principales 
**Modelo MLP:** Alcanzó un **74% de precisión (Accuracy)**.
**Métricas:** El modelo presenta un desempeño balanceado entre precisión y sensibilidad (recall) para ambas clases.
**Conclusión:** El puntaje Z actúa como el motor de decisión; valores positivos activan la neurona hacia la clase de riesgo, demostrando la importancia de la configuración de pesos y bias en la frontera de decisión.


# Cómo Ejecutar

1. abrir el archivo terninado en '.ipynb' en Google Colad.
2. Ejecutar ( Entorno de ejecución > Ejecutar Todas) 
