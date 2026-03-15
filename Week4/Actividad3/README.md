# Actividad 3: Aplicación de Técnicas de Optimización en una Red Neuronal

# Objetivo
Evaluar y comparar el impacto de diferentes algoritmos de optimización en el proceso de entrenamiento de una red neuronal profunda, analizando su velocidad de convergencia y estabilidad.


# Técnicas Comparada
Se realizó un análisis comparativo entre el optimizador SGD (Stochastic Gradient Descent) como modelo base y el optimizador Adam (Adaptive Moment Estimation) como técnica de optimización avanzada.

# Configuración Base
Se utilizó una red neuronal densa (SimpleNet) entrenada durante 8 épocas con una tasa de aprendizaje (Learning Rate) de 0.01 y un tamaño de lote (Batch Size) de 64 sobre el dataset MNIST.

# Resultado Principal
Adam demostró una convergencia significativamente más rápida en las primeras épocas, reduciendo la pérdida inicial un 48.4% respecto a SGD (pasando de 0.7498 a 0.3869 en la Época 1). 
Sin embargo, se observó que mientras SGD mantuvo un descenso constante hasta el final (0.2213), Adam presentó una ligera inestabilidad en la última época, subiendo a 0.2316, lo que sugiere que para esta configuración específica, SGD logró una mayor estabilidad final

# Cómo ejecutar el notebook
1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden -> Entorno de Ejecución --> Ejecutar todas
3. Las graficas de comparacion se generaran al final del entrenamiento. 
