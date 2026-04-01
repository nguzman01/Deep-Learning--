# Actividad 3: Técnicas de Optimización en una Red Neuronal

# Objetivo
Implementar y comparar técnicas de optimización (SGD vs. Adam) en una red neuronal.


# Técnicas Comparadas
Se realizó un análisis comparativo entre:

El optimizador SGD (Stochastic Gradient Descent) con un learning_rate=0.01 como modelo base. 

El optimizador Adam (Adaptive Moment Estimation) con un learning_rate=0.001 como técnica de optimización avanzada.

# Configuración Base
Se utilizó una red neuronal densa entrenada durante 50 épocas con un tamaño de lote (Batch Size) de 32 sobre el conjunto de datos Diabetes. La arquitectura consiste en una capa de entrada, una capa oculta de 32 neuronas (ReLU) y una capa de salida (Sigmoid).

# Resultado Principal
El optimizador Adam demostró una convergencia significativamente más rápida y efectiva, alcanzando una precisión final en el set de prueba del 82.02% y una pérdida (loss) de 0.4358.

Por otro lado, SGD mostró un progreso más lento, finalizando con una precisión del 77.52%  y una pérdida de 0.5384. 
Esto confirma que Adam es más eficiente para este conjunto de datos, logrando mejores métricas en el mismo número de épocas.


# Cómo ejecutar el notebook
1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden -> Entorno de Ejecución --> Ejecutar todas
3.Las gráficas de comparación y la matriz de confusión se generarán automáticamente al final. 
