

# Objetivo
Implementación de Backpropagation y Funciones de Activación en Redes Neuronales

# Implementación 

* Dataset: Datos sintéticos que simulan perfiles crediticios (Ingresos, Puntaje, Deuda, Historial).

* Arquitecturas: Se evaluaron 4 variantes, desde un Perceptrón simple hasta Redes Multicapa Profundas.

* Proceso: Escalado de datos con StandardScaler, entrenamiento por 100 épocas y evaluación con métricas de Loss (MSE) y Accuracy.
  
# Que Activaciones se compararon

Se realizó una comparación directa bajo la misma arquitectura multicapa entre:

* Sigmoid: Utilizada en las capas ocultas (Experimento C).

* ReLU (Rectified Linear Unit): Utilizada en las capas ocultas (Experimento D).


# Resultados Principales

* La activación ReLU superó a Sigmoid logrando una precisión del 100% y una convergencia mucho más rápida.

* Se evidenció el fenómeno de saturación de gradientes en la red profunda con Sigmoid, la cual mostró un aprendizaje más lento y estancado en comparación con ReLU.
 
# Como se ejecuta 

1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden secuencial para reproducir la grafica y las predicciones.
