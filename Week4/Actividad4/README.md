# Actividad 4: Métodos de Regularización en una Red Neuronal
# Objetivo
Implementar técnicas de regularización para reducir el sobreajuste y mejorar la generalización del modelo.

# Métodos de regularización aplicados:
Dropout (Abandono) :Se implementó la técnica de Dropout con una tasa de 0.2 (20%), aplicada tras la capa oculta densa de 64 neuronas.
Comparación realizada:
Se comparó el desempeño de una arquitectura base (sin regularización) frente a una arquitectura regularizada bajo las mismas condiciones de entrenamiento (80 épocas, optimizador Adam).

# Resultado Principal:
El modelo con Dropout logró eliminar la tendencia alcista de la pérdida de validación observada en el modelo base, logrando una curva de aprendizaje más estable y un mejor desempeño final en los datos de prueba.

# Cómo ejecutar el notebook
Abrir el archivo terminado en `.ipynb` en Google Colab. Ejecutar las celdas en orden -> Entorno de Ejecución --> Ejecutar todasy si es coherente con el ejemplo y lo que pide la actividad
