# Actividad 3: Aplicación de Técnicas de Optimización en una Red Neuronal

# Objetivo
Evaluar y comparar el impacto de diferentes algoritmos de optimización en el proceso de entrenamiento de una red neuronal profunda, analizando su velocidad de convergencia y estabilidad.


# Técnicas Comparada
Se realizó un análisis comparativo entre el optimizador SGD (Stochastic Gradient Descent) como modelo base y el optimizador Adam (Adaptive Moment Estimation) como técnica de optimización avanzada.

# Configuración Base
Se utilizó una red neuronal densa (SimpleNet) entrenada durante 8 épocas con una tasa de aprendizaje (Learning Rate) de 0.01 y un tamaño de lote (Batch Size) de 64 sobre el dataset MNIST.

# Resultado Principal
Adam demostró una convergencia significativamente más rápida en las primeras épocas, reduciendo la pérdida inicial un 43% más que SGD, aunque ambos optimizadores convergieron a niveles similares de error al finalizar las 8 épocas.

# Cómo ejecutar el notebook
1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden -> Entorno de Ejecución --> Ejecutar todas
3. Las graficas de comparacion se generaran al final del entrenamiento. 
