# Actividad 4: Métodos de Regularización en una Red Neuronal 

# Objetivo
Implementar técnicas de regularización para reducir el sobreajuste y mejorar la generalización del modelo.

# Métodos de regularización aplicados:

-  Dropout (Abandono) : Se aplicó en las capas ocultas para desactivar aleatoriamente neuronas y evitar la co-adaptación.
- Regularización L2 (Weight Decay): Implementada en el optimizador Adam para evitar que el modelo se volviera demasiado complejo y memorizara los datos de entrenamiento.
  
# Comparación realizada:
Modelo MLP(Multi-Layer perceptron) de 3 capas sin restricciones vs. Modelo MLP con Dropout y Weight Decay.

# Resultado Principal:

- Evidencia de Overfitting: En el modelo base, se observa que el test_loss comienza a estancarse o subir mientras el train_loss sigue bajando, síntoma claro de que el modelo está memorizando el ruido de los datos de entrenamiento.
  
- Efecto de la Regularización: El modelo regularizado muestra curvas de entrenamiento y evaluación mucho más cercanas entre sí. Aunque el error inicial es ligeramente más alto, la brecha (gap) entre entrenamiento y prueba se reduce drásticamente, lo que indica una mejor generalización

- Dificultades: Ajustar la tasa de Dropout; un valor muy alto (0.8) causaba underfitting, por lo que se estabilizó en 0.5 para equilibrar el aprendizaje.

# Cómo ejecutar el notebook

Abrir el archivo terminado en '.ipynb' en Google Colab.
Ejecutar las celdas en orden -> Entorno de Ejecución --> Ejecutar todas

